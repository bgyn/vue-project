<script setup>
import nav_bar from './../components/nav.vue';
import product from './../components/product.vue';
import slider from './../components/slider.vue';
import exclusive from './../components/exclusive_product.vue';
import gallery from './../components/gallery.vue';
import footers from './../components/footers.vue';

</script>

<template>
  <!-- navbar -->
  <nav_bar></nav_bar>
  <!-- navbar -->

  <!-- slider -->
  <slider></slider>
  <!-- slider -->

  <!-- exclusive product -->
  <exclusive></exclusive>
  <!-- exclusive product -->

  <!-- products -->
  <product></product>
  <!-- products -->

  <!-- product gallery -->
 <gallery></gallery>
  <!-- product gallery -->

  <!-- footer -->
  <footers></footers>
  <!-- footer -->
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Hahmlet&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Heebo&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Hanuman&display=swap');
:root {
  --nav_bg: #272727;
  --logo_color: #beb698;
  --slider_title: #ab9d90;
  --product_bg: #403732;
  --dawn_pink: #ececec;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
  font-family: 'Heebo', sans-serif;
}
html{
  scroll-behavior: smooth;
}

</style>
