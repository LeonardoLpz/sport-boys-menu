<template>
  <div id="app">
    <menu-header/>
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/platillos">Platillos</router-link> |
    </div>
    <router-view/>
    <menu-footer/>
  </div>
</template>
<script>
import MenuFooter from '@/components/MenuFooter.vue'
import MenuHeader from '@/components/MenuHeader.vue'
export default {
  components: { MenuHeader, MenuFooter },
  
}
</script>
<style lang="scss">
@import url("./assets/css/styles.css");
</style>
