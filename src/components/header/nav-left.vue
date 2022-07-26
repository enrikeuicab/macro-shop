<template>
  <div>
    <div class="crumb_navigation">
      Navigation:
      <span class="current">Home</span>
    </div>
    <div class="left_content">
      <div class="title_box">CATEGORÍAS</div>
      <ul class="left_menu" v-for="(item, index) in leftMenu" :key="index">
        <li :class="item.className">
          <a href="#">{{item.name}}</a>
        </li>
      </ul>
      <div class="title_box">Ofertas</div>
      <div class="border_box">
        <div class="product_title">
          <a href="#">Samsung Galaxy</a>
        </div>
        <div class="product_img">
          <a href="#">
            <img src="@/assets/images/bann1-verano.png" alt border="0" />
          </a>
        </div>
        <div class="prod_price">
          <span class="reduce">350$</span>
          <span class="price">161$</span>
        </div>
      </div>
      <div class="title_box">Nuestro Catalogo</div>
      <div class="border_box">
        <input type="text" name="newsletter" class="newsletter_input" value="Ingresa tu email" />
        <a href="#" class="join">Suscribete</a>
      </div>
      <div class="banner_adds">
        <video width="180" height="140" controls>
          <source src="https://macropay.mx/wp-content/uploads/2021/07/Video_Macro.mp4" type="video/mp4">
        </video>
      </div>
    </div>
  </div>
</template>

<script>
/* eslint-disable*/
export default {
  name: "MenuLeft",
  data() {
    return {
      leftMenu: [
        {
          id: 1,
          name: "ALCATEL",
          className: "odd"
        },
        {
          id: 2,
          name: "HUAWEI",
          className: "even"
        },
        {
          id: 3,
          name: "LANIX",
          className: "odd"
        },
        {
          id: 4,
          name: "LG",
          className: "even"
        },
        {
          id: 5,
          name: "MOTOROLA",
          className: "odd"
        },
        {
          id: 6,
          name: "NOKIA",
          className: "even"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
</style>