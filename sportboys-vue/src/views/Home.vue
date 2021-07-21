<template>
  <div class="home">
    <category/>
  </div>
</template>

<script>
import Category from '@/views/Category.vue'
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    Category
  }
}
</script>
