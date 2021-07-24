<template>
  <div class="home">
      <menu-card 
      :category='categoryTitle'
      :imgUrl='categoryImg'
    />
    <menu-card 
      :category='categoryTitle'
      :imgUrl='categoryImg'
    />
    <menu-card 
      :category='categoryTitle'
      :imgUrl='categoryImg'
    />
     <menu-card 
      :category='categoryTitle'
      :imgUrl='categoryImg'
    />
     <menu-card 
      :category='categoryTitle'
      :imgUrl='categoryImg'
    />
  </div>
</template>

<script>
import MenuCard from '@/components/MenuCard.vue'

export default {
  name: 'Home',
  components: {
    MenuCard 
  },
  data(){
    return {
      categoryImg:require('@/assets/img/image_browser.jpg'),
      categoryTitle:'Aperitivos'
    }
  }
}
</script>
