<template>
    <div>Hello World!! hehe</div>

    <div>
        The message is {{ message }}
    </div>
</template>

<script setup>
defineProps({
    message: String,
})
</script>