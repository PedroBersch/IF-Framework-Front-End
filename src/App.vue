<template>
  <div>
    <PrimeiroComponente />
    <Imagens />
  </div>
</template>

<script>
import PrimeiroComponente from "./components/firstComponent.vue";
import Imagens from "./components/rederizarImagens.vue";
export default {
  name: "App",
  components: {
    PrimeiroComponente,
    Imagens,
  },
};
</script>