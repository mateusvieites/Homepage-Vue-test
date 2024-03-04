<template>
  <PrimeiroComponente /> {{ casa }}
</template>
<script>
import PrimeiroComponente from "./components/PrimeiroComponente.vue";

export default {
  name: 'App',
  components: {
    PrimeiroComponente
  },data(){
    return{
      casa: "mateus"
    }
  }
}
</script>