<template>
  <div :class="{ dark: darkMode }">
    <h1 class="text-red-500 dark:text-dim-600">Hello World!</h1>
  </div>
</template>
<script setup>
const darkMode = ref(false)
</script>
