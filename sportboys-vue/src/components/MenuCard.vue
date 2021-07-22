<template>
  <!-- COMPONENT: CARD CATEGORÍA -->
  <div 
    v-on:click="toPlatillos"
    class="card">
    <img
      :src="imgUrl"
      alt="Imagen que representa una categoría"
      class="card__image"
    />
    <p class="card__title">{{ category }}</p>
  </div>
</template>

<script>
export default {
  name: 'MenuCard',
  props: [
     'imgUrl',
    'category'
  ],
  methods: {
  toPlatillos() {
    this.$router.push('/platillos')
  }
}
  
}
</script>