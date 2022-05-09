<script>
import PerfilBook from "@/components/PerfilBook.vue";
import ListaFavoritos from "@/components/ListaFavoritos.vue";
import ConteudoBook from "@/components/ConteudoBook.vue";
// import FooterRodape from "@/components/FooterRodape.vue";
export default {
  components: { PerfilBook, ListaFavoritos, ConteudoBook },
};
</script>

<template>
  <PerfilBook />
  <ListaFavoritos />
  <ConteudoBook />
  <!-- <FooterRodape /> -->
</template>
