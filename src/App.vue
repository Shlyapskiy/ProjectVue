<template>
  <div id="app">
    <Header />
    <router-view />
    <Sidebar />
    <Footer />
  </div>
</template>
<script>
import Header from './components/AppHeader.vue'
import Sidebar from './components/SidebarMenu.vue'
import Footer from './components/AppFooter.vue'

export default {
  components: {
    Header,
    Sidebar,
    Footer
  }
}
</script>

<style>
#app {

  text-align: center;
  color: #000000;
  margin-top: 1px
}
#app img {
  max-width: 300%;
  margin: 1px;
}
</style>
