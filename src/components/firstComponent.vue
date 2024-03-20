<template>
  <div>
    <h1>{{ titulo }}</h1>
    <p>Meu nome é {{ nome }} e trabnalho com {{ profissao }}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      titulo: "Frameword Front end",
      nome: "pedro",
      profissao: "programador",
    };
  },
};
</script>