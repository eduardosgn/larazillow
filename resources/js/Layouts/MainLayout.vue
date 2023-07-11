<template>
    <Link href="/" style="margin-right: 1rem;">Homepage</Link>
    <Link href="/show" style="margin-right: 1rem;">Show page</Link>
    <slot></slot>
</template>

<script setup>
import { Link } from '@inertiajs/vue3';
</script>