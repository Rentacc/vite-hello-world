<template>
  <div>
    <AppTitle />
    <AppHero />
  </div>
</template>

<script>
import AppTitle from "./components/apptitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    AppTitle,
    AppHero
  }
};
</script>
