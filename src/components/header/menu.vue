<template>
  <div id="menu_tab">
    <ul class="menu">
      <li>
        <router-link to="/" class="nav">Home</router-link>
      </li>
      <li class="divider"></li>
      <li>
        <router-link to="/product" class="nav">Product</router-link>
      </li>
      <li class="divider"></li>
      <li>
        <router-link to="/about" class="nav">About</router-link>
      </li>
      <li class="divider"></li>
      <li>
        <router-link to="/contact" class="nav">Contact</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
/* eslint-disable*/
export default {
  name: "menu",
  data() {
    return {};
  }
};
</script>

<style lang="scss" scoped>
</style>