<!-- Nuovo componente per Jumbotron -->
<script>
export default {
  name: 'Jumbo',
  data() {
    return {
      jumbotron: 'Sono il Jumbotron'
    }
  }
};
</script>
<template>
  <h2>{{ jumbotron }}</h2>
</template>
<style>
h2 {
  background-color: blue;
}
</style>