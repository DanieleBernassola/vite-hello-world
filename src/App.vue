<!-- SCRIPT = JS -->
<script>
import TitleComponent from "./components/AppTitle.vue";
export default {
  name: 'myApp',
  data() {
    return {

    };
  },
  // COMPONENTI CHE IMPORTO
  components: {
    TitleComponent,
  },
};
</script>
<!-- TEMPLATE = HTML -->
<template>
  <!-- POSSO UTILIZZARE IL COMPONENTE IMPORTATO COME TAG HTML -->
  <TitleComponent></TitleComponent>
</template>
<!-- STYLE = CSS -->
<style></style>
