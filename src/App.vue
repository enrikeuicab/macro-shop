<template>
  <div id="main_container">
    <Header />
    <Menu />
    <MenuLeft />
    <div class="center_content">
        <router-view></router-view>
    </div>
    <RightMenu />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/header/header.vue'
import Menu from '@/components/header/menu.vue'
import MenuLeft from "@/components/header/nav-left.vue";
import RightMenu from '@/components/rightnav/rightnav.vue';
import Footer from '@/components/footer/footer.vue'


export default {
  name: 'HomeView',
  components: {
    Header,
    Menu,
    MenuLeft,
    RightMenu,
    Footer
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
