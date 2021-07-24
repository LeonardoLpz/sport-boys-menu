<template>
  <div class="home">
      <div v-for="(category,index) in menuData"> 
        <menu-card 
          :category='category.category'
          :imgUrl='categoryImg'
        />
      </div>
  </div>
</template>

<script>
import MenuCard from '@/components/MenuCard.vue'
import { platillosEconomicos, combinaPlatos} from '@/services/menu.js'

export default {
  name: 'Home',
  components: {
    MenuCard 
  },
  data(){
    return {
      categoryImg:require('@/assets/img/image_browser.jpg'),
      categoryTitle:'Aperitivos',
      menuData:[],
    }
  },
   beforeMount: function () {
    
    this.menuData.push(platillosEconomicos)
    this.menuData.push(combinaPlatos)
    console.log(this.menuData)
  }
}
</script>
