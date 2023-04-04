<script setup>
</script>
<template>
<div class="our_product" id="product">
    <div class="products_container">
      <h1 class="container_title">Products</h1>
      <div class="order_container">
        <div class="products">
          <div class="img">
            <img src="earing.png" alt="" />
          </div>
          <div class="text">
            <h5 class="earing_type">Dark Earing</h5>
            <p class="price">$10.00 - $23.00</p>
          </div>
        </div>
        <div class="products">
          <div class="img">
            <img src="earing.png" alt="" />
          </div>
          <div class="text">
            <h5 class="earing_type">Dark Earing</h5>
            <p class="price">$10.00 - $23.00</p>
          </div>
        </div>
        <div class="products">
          <div class="img">
            <img src="earing.png" alt="" />
          </div>
          <div class="text">
            <h5 class="earing_type">Dark Earing</h5>
            <p class="price">$10.00 - $23.00</p>
          </div>
        </div>
        <div class="products">
          <div class="img">
            <img src="earing.png" alt="" />
          </div>
          <div class="text">
            <h5 class="earing_type">Dark Earing</h5>
            <p class="price">$10.00 - $23.00</p>
          </div>
        </div>
        <div class="products">
          <div class="img">
            <img src="earing.png" alt="" />
          </div>
          <div class="text">
            <h5 class="earing_type">Dark Earing</h5>
            <p class="price">$10.00 - $23.00</p>
          </div>
        </div>
        <div class="products">
          <div class="img">
            <img src="earing.png" alt="" />
          </div>
          <div class="text">
            <h5 class="earing_type">Dark Earing</h5>
            <p class="price">$10.00 - $23.00</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.our_product {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 290px;
}
.our_product .products_container {
  padding: 0 8rem;
}
.our_product .products_container .order_container {
  display: grid;
  grid-template-columns: repeat(3, auto);
  gap: 2rem;
}
.our_product .products_container .order_container .products {
  padding: 2rem 1rem;
  background-color: #f9f2ec;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.our_product .products_container .order_container .products .text {
  color: #636363;
  align-self: flex-start;
  margin-top: 2rem;
  margin-left: 2em;
}
.our_product .products_container .order_container .products .img img {
  width: 90%;
}
.our_product .products_container .container_title {
  text-transform: uppercase;
  margin: 5rem 0 5rem 0;
}
</style>