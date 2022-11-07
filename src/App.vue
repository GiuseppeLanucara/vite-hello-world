<script>

import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
import AppBackground from "./components/AppBackground.vue";

export default {
  data() {
    return {


    }
  },
  components: {
    AppTitle,
    AppHero,
    AppBackground

  },

  methods: {


  }
}
</script>


<template>
  <AppTitle />
  <p>Questa è una dimostrazione sulla prima app fatta utilizzando Vite</p>
  <AppHero />

</template>



<style>
p {
  color: mistyrose;
  font-size: xx-large;
  font-style: oblique;
  text-align: center;
  margin-top: 50px;

}
</style>