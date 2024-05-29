<!-- SCRIPT = JS -->
<script>
import TitleComponent from "./components/AppTitle.vue";
import JumboComponent from "./components/AppHero.vue";
export default {
  name: 'myApp',
  data() {
    return {

    };
  },
  // COMPONENTI CHE IMPORTO
  components: {
    TitleComponent,
    JumboComponent
  },
};
</script>
<!-- TEMPLATE = HTML -->
<template>
  <!-- POSSO UTILIZZARE I COMPONENTI IMPORTATI COME TAG HTML -->
  <TitleComponent></TitleComponent>
  <JumboComponent></JumboComponent>
</template>
<!-- STYLE = CSS -->
<style></style>
