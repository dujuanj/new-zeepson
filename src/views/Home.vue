<template>
  <div class="home">
    <Header/> 
    <index msg="Welcome to Your Vue.js App"/>
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import index from '@/components/index.vue'
import Header from '@/components/header.vue'
import Footer from '@/components/footer.vue'

export default {
  name: 'home',
  components: {
    index,
    Header,
    Footer
   
  }
}
</script>
