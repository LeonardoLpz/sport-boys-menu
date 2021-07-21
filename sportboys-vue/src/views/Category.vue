<template>
  <div>
    <menu-card 
      :category='categoryTitle'
      :imgUrl='categoryImg'
    />
  </div>
</template>

<script>
import MenuCard from '@/components/MenuCard.vue'
export default {
  name:'Category',
  components: { MenuCard },
  data(){
    return {
      categoryImg:require('@/assets/img/image_browser.jpg'),
      categoryTitle:'Aperitivos'
    }
  }
}
</script>