<script setup>
import MeuCarrinho from '@/components/MeuCarrinho.vue';
import ListagemLivros from '@/components/ListagemLivros.vue'

</script>

<template>
  <h1>Minha livraria</h1>
  <div class="container-geral">

    <ListagemLivros/>

    <MeuCarrinho/>
  
  </div>
</template>

<style scoped>

.container-geral {
  /* display: flex;
  justify-content: space-between; */
  display: grid;
  grid-template-columns: 3fr 1fr;
}

.carrinho {
  /* min-width: 20%; */
}

</style>
