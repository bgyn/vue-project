<script setup></script>

<template>
  <!-- navbar -->
  <section id="navbar">
    <navbar class="nav_navbar">
      <ul class="navbar_links">
        <li class="nav_links"><a href="#">HOME</a></li>
        <li class="nav_links"><a href="#">PRODUCTS</a></li>
        <div class="nav_logo">
          <a href="#">JEWELERY</a>
          <img src="diamond.png" alt="img_logo" class="img_logo" />
        </div>
        <li class="nav_links"><a href="#">SERVICES</a></li>
        <li class="nav_links"><a href="#">CONTACT</a></li>
      </ul>
    </navbar>
  </section>
  <!-- navbar -->
  
  <!-- slider -->
  <div class="slider">
    <div class="slider_container">
      <div class="slider_img">
        <img src="model.png" alt="model_img" />
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
    </div>
  </div>
<!-- slider -->
</template>
<style>
:root {
  --nav_bg: #272727;
  --logo_color: #beb698;
  --slider_title: #ab9d90;
  --product_bg: #403732;
  --dawn_pink: #ececec;
}

@import url('https://fonts.googleapis.com/css2?family=Heebo&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
}

body {
  font-family: 'Heebo', sans-serif;
}
.nav_navbar {
  width: 100%;
}
.nav_navbar .navbar_links {
  background-color: var(--nav_bg);
  display: flex;
  padding: 1.5rem;
  justify-content: center;
  align-items: center;
}
.nav_navbar .navbar_links .nav_links {
  margin: 0 1.5rem;
}
.nav_navbar .navbar_links .nav_logo {
  margin: 0 18rem;
  position: relative;
  cursor: pointer;
}
.nav_navbar .navbar_links .nav_logo a {
  color: white;
  font-size: 1.2rem;
}
.nav_navbar .navbar_links .nav_logo .img_logo {
  color: var(--logo_color);
  position: absolute;
  top: -50%;
  right: 50%;
  transform: translateX(50%);
  z-index: 0;
  width: 40px;
}
.nav_navbar .navbar_links .nav_links a {
  color: white;
  font-size: 1rem;
}

.slider {
  width: 100%;
  height: 75vh;
  background-color: black;
  overflow-y: hidden;
}
.slider .slider_container {
  display: flex;
  padding-right: 2rem;
  justify-content: space-between;
}
.slider .slider_container .slider_img img {
  position: relative;
  top: -10%;
}
.slider .slider_container .slider_content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  transform: translateY(-20%);
}
.slider .slider_container .slider_content .title {
  color: var(--slider_title);
  font-weight: 200;
  letter-spacing: 2px;
  font-size: 2rem;
  margin-bottom: 1.5rem;
  cursor: pointer;
}
.slider .slider_container .slider_content .content {
  color: white;
  padding-right: 6rem;
  font-size: 1rem;
  letter-spacing: 1px;
  line-height: 19px;
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
</style>
