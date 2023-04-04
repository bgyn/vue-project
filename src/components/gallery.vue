<script setup></script>
<template>
     <div class="gallery" id="services">
    <div class="gallery_container">
      <div class="img">
        <img src="img (1).jpg" />
      </div>
      <div class="img">
        <img src="img (2).jpg" />
      </div>
      <div class="img">
        <img src="img (3).jpg" />
      </div>
      <div class="img">
        <img src="img (4).jpg" />
      </div>
      <div class="img">
        <img src="img (5).jpg" />
      </div>
      <div class="img">
        <img src="img (6).jpg" />
      </div>
    </div>
  </div>
</template>
<style>
.gallery{
  width: 100%;
}
 .gallery .gallery_container {
  margin: 10rem 0;
  padding: 0 8rem;
  width: 100%;
  display: grid;
  grid-template-columns: repeat(6, 1fr);
}
.gallery .gallery_container .img img {
  width: 100%;
}
</style>