<template>
  <div>
    <platillo-card/>
  </div>
</template>

<script>
import Category from '@/views/Category.vue'
import PlatilloCard from '@/components/PlatilloCard.vue'
// @ is an alias to /src

export default {
  name: 'Platillos',
  components: {
    Category,
    PlatilloCard
  }
}
</script>
