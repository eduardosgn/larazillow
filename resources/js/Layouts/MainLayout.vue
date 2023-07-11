<template>
    <Link href="/" style="margin-right: 1rem;">Homepage</Link>
    <Link href="/show" style="margin-right: 1rem;">Show page</Link>
    <div>The time in seconds that you are connected to this webapp: {{ timer }}</div>
    <slot></slot>
</template>

<script setup>
import { Link } from '@inertiajs/vue3';
import { ref } from 'vue';

const timer = ref(0);
setInterval(() => {
    timer.value++
}, 1000);
</script>