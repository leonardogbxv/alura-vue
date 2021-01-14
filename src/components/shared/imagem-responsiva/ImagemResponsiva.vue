<template>
  <img 
    class="imagem-responsiva" 
    :src="url" 
    :alt="titulo"
  >
</template>

<script>
export default {
  name: 'ImagemResponsiva',
  props: ['url', 'titulo']
}
</script>

<style scoped>
  .imagem-responsiva {
    width: 100%;
  }
</style>