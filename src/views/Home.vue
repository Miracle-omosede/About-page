<template>
  <div class="home">
    <AboutUs />
  </div>
</template>

<style scoped>

</style>

<script>
// @ is an alias to /src
import AboutUs from '@/components/AboutUs.vue'

export default {
  name: 'Home',
  components: {
    AboutUs
  }
}
</script>
