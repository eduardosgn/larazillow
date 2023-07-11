<template>
    <MainLayout>
        <div>Show page! hehe</div>
        
        <div>
            The message is {{ showPageMessage }}
        </div>
    </MainLayout>
</template>

<script setup>
import MainLayout from '../../Layouts/MainLayout.vue';

defineProps({
    showPageMessage: String
});
</script>