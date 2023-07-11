<template>
  <div>Show page! hehe</div>
    
  <div>
    The message is {{ showPageMessage }}
  </div>
</template>

<script setup>
defineProps({
    showPageMessage: String,
})
</script>