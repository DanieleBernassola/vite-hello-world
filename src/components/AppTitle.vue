<!-- Nuovo componente per il titolo -->
<script>
export default {
  name: 'Title',
  data() {
    return {
      title: 'La mia prima app con Vite!'
    }
  }
};
</script>
<template>
  <h1>{{ title }}</h1>
</template>
<style></style>