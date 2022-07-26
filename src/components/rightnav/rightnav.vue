<template>
  <div>
    <div class="right_content">
      <div class="title_box">Buscar</div>
      <div class="border_box">
        <input type="text" name="newsletter" class="newsletter_input" value="Samsung Galaxy" />
        <a href="#" class="join">buscar</a>
      </div>
      <div class="shopping_cart">
        <div class="title_box">Carrito</div>
        <div class="cart_details">
          3 articulos
          <br />
          <span class="border_cart"></span> Total:
          <span class="price">350$</span>
        </div>
        <div class="cart_icon">
          <a href="#">
            <img src="@/assets/images/shoppingcart.png" alt width="35" height="35" border="0" />
          </a>
        </div>
      </div>
      <div class="title_box">Lo nuevo</div>
      <div class="border_box">
        <div class="product_title">
          <a href="#">OPPO A15</a>
        </div>
        <div class="product_img">
          <a href="#">
            <img src="@/assets/images/105669-300x300.jpg" width="100" alt border="0" />
          </a>
        </div>
        <div class="prod_price">
          <span class="reduce">350$</span>
          <span class="price">270$</span>
        </div>
      </div>
      <div class="title_box">Sucursales</div>
      <ul class="left_menu">
        <li class="odd">
          <a href="#">Mérida</a>
        </li>
        <li class="even">
          <a href="#">Valladolid</a>
        </li>
        <li class="odd">
          <a href="#">Oaxaca</a>
        </li>
        <li class="even">
          <a href="#">Juchitán</a>
        </li>
        <li class="odd">
          <a href="#">San Maria de Huatulco</a>
        </li>
        <li class="even">
          <a href="#">Salinas Cruz</a>
        </li>
        <li class="odd">
          <a href="#">Tehuantepec</a>
        </li>
      </ul>
      <div class="banner_adds">
        <a href="#">
          <h3>Xiaomi Poco X4</h3>
          <img src="@/assets/images/Xiaomi-Poco-X4-pro-Front.jpg" alt width="100" border="0" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
/* eslint-disable*/
export default {
  name: "RightMenu",
  data() {
    return {};
  }
};
</script>