<template>
  <div class="home">
      <div v-for="(category,index) in menuData" :key="index"> 
        <menu-card 
          :category='category.category'
          :imgUrl='categoryImg'
        />
      </div>
  </div>
</template>

<script>
import MenuCard from '@/components/MenuCard.vue'
import { menu } from '@/services/menu.js'

export default {
  name: 'Home',
  components: {
    MenuCard 
  },
  data(){
    return {
      categoryImg:require('@/assets/img/image_browser.jpg'),
      menuData: menu
    }
  }
}
</script>
