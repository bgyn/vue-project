<script setup>

</script>

<template>
<div class="slider" id="slider">
    <div class="slider_container">
      <div class="slider_img">
        <img src="model.jpg" alt="model_img" />
      </div>
      <div class="slider_content">
        <h2 class="title">
          PREMIUM HANDMADE<br />
          JEWELLERY ON EVERY<br />
          OCCASSION
        </h2>
        <p class="content">
          In publishing and graphic design, Lorem ipsum is a placeholder text
          commonly used to demonstrate the visual form of a document or a
          typeface without relying.
        </p>
        <button class="btn">FIND OUT MORE</button>
      </div>
      <div class="rectangle">
        <img src="diamond.png" alt="diamond" class="diamond_img" />
      </div>
    </div>
  </div>
</template>

<style>
.slider {
  position: relative;
}
.slider .slider_container {
  width: 100%;
  background-color: black;
  display: flex;
  padding-right: 8rem;
}
.slider .slider_container .slider_img {
  overflow-y: hidden;
}
.slider .slider_container .slider_img img {
  width: 100%;
  height: 100%;
}
.slider .slider_container .slider_content {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.slider .slider_container .slider_content .title {
  color: var(--slider_title);
  font-weight: 200;
  letter-spacing: 3px;
  font-size: 2rem;
  margin-bottom: 1rem;
  cursor: pointer;
}
.slider .slider_container .slider_content .content {
  color: white;
  font-size: 14px;
  letter-spacing: 2px;
  line-height: 20px;
  cursor: pointer;
}
.slider .slider_container .slider_content .btn {
  color: var(--slider_title);
  border: 1px solid var(--slider_title);
  background-color: transparent;
  padding: 10px;
  margin-top: 1.5rem;
  width: 8rem;
  cursor: pointer;
}
.slider .rectangle {
  position: absolute;
  bottom: -25px;
  left: calc(50% - 25px);
  width: 50px;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: white;
  transform: rotate(45deg);
  z-index: 3;
}
.slider .rectangle .diamond_img {
  transform: rotate(-45deg);
}
</style>