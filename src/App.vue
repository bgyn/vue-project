<script setup></script>

<template>
  <!-- navbar -->
  <navbar class="nav_navbar" id="navbar">
    <nav class="navbar_links">
      <div class="nav_left">
        <li class="nav_links"><a href="#navbar">HOME</a></li>
        <li class="nav_links"><a href="#product">PRODUCTS</a></li>
      </div>
      <div class="nav_logo">
        <a href="#">JEWELERY</a>
        <img src="/public/diamond.png" alt="img_logo" class="img_logo" />
      </div>
      <div class="nav_right">
        <li class="nav_links"><a href="#services">SERVICES</a></li>
        <li class="nav_links"><a href="#footer">CONTACT</a></li>
      </div>
    </nav>
  </navbar>
  <!-- navbar -->

  <!-- slider -->
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
  <!-- slider -->

  <!-- exclusive product -->
  <div class="exclusive_product">
    <div class="product_container">
      <div class="product_text">
        <h1>3000</h1>
        <p>exclusive product</p>
      </div>
      <div class="product_items">
        <div class="product">
          <img src="diamond-ring.png" alt="diamond_ring" />
          <p>Neckless</p>
        </div>
        <div class="product">
          <img src="diamond-ring.png" alt="diamond_ring" />
          <p>Neckless</p>
        </div>
        <div class="product">
          <img src="diamond-ring.png" alt="diamond_ring" />
          <p>Neckless</p>
        </div>
        <div class="product">
          <img src="diamond-ring.png" alt="diamond_ring" />
          <p>Neckless</p>
        </div>
        <div class="product">
          <img src="diamond-ring.png" alt="diamond_ring" />
          <p>Neckless</p>
        </div>
        <div class="product">
          <img src="diamond-ring.png" alt="diamond_ring" />
          <p>Neckless</p>
        </div>
      </div>
      <div class="product_collection">
        <div class="contianer_1 collection">
          <img src="model (3).jpg" alt="" />
          <div class="text">
            <p>NEW<br />SPRING<br />COLLECTION</p>
          </div>
        </div>
        <div class="contianer_2 collection">
          <img src="model (2).jpg" alt="" />
          <div class="text">
            <h1>20%<br />OFF</h1>
            <p>
              In publishing and<br />
              graphics design<br />
              Lorem ipsum is a <br />placeholder
            </p>
            <p class="red_text">Products</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- exclusive product -->

  <!-- product gallery -->
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
    </div>
  </div>
  <!-- product gallery -->

  <!-- footer -->
  <footer id="footer">
    <div class="footer_container">
      <div class="about_container">
        <div class="jeweler">
          <div class="logo">
            <h3>JEWELERY</h3>
            <img src="diamond.png" alt="" class="img"/>
          </div>
          <p>
            Lorem ipsum dolor sit amet consectetur<br />
            adipisicing elit. Neque, minus.
          </p>
        </div>
        <div class="payment">
          <h3 class="title">Payment Option</h3>
          <div class="payment_option">
            <div class="card">
              <img src="master-card.png" alt="" />
            </div>
            <div class="card">
              <img src="american-express.png" alt="" />
            </div>
            <div class="card">
              <img src="paypal.png" alt="" />
            </div>
            <div class="card">
              <img src="visa.png" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="links_container">
        <div class="useful_links">
          <h3>Useful Links</h3>
          <ul>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Help & About us</a></li>
            <li><a href="#">Shipping & Returns</a></li>
            <li><a href="#">Refund Policy</a></li>
          </ul>
        </div>
        <div class="delivery_link">
          <h3>Delivery</h3>
          <ul>
            <li><a href="#">How it works</a></li>
            <li><a href="#">Free Delivery</a></li>
            <li><a href="#">FAQ</a></li>
          </ul>
        </div>
      </div>
      <div class="customer_service">
        <h3>Customer Service</h3>
        <ul>
          <li><a href="#">Orders</a></li>
          <li><a href="#">Downloads</a></li>
          <li><a href="#">Addresss</a></li>
          <li><a href="#">Acount Details</a></li>
          <li><a href="#">Lost password</a></li>
        </ul>
      </div>
      <div class="need_help">
        <h3>Need help?</h3>
        <ul>
          <li><a href="#">+61 (0) 383 766 284</a></li>
          <li><a href="#">+61 (1) 383 766 284</a></li>
          <li>
            <a href="#">Monday - Friday<br />8am - 5pm</a>
          </li>
          <li>
            <a href="#">Saturday<br />9am - 4pm</a>
          </li>
        </ul>
      </div>
    </div>
    <div class="copyright">
      <p>&copy 2023 - Jewelery Management System - Vue.js project</p>
    </div>
  </footer>
  <!-- footer -->
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Hahmlet&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Heebo&display=swap');
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
.nav_navbar {
  width: 100%;
}
.nav_navbar .navbar_links {
  background-color: var(--nav_bg);
  display: flex;
  padding: 1.5rem;
  justify-content: space-around;
  align-items: center;
}
.nav_navbar .navbar_links .nav_logo {
  position: relative;
  cursor: pointer;
}
.nav_links {
  margin: 0 1rem;
}
.nav_navbar .navbar_links .nav_logo a {
  color: white;
  font-size: 1.1rem;
}
.nav_navbar .navbar_links .nav_left,
.nav_right {
  display: flex;
}
.nav_navbar .navbar_links .nav_logo .img_logo {
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
  position: relative;
}
.slider .slider_container {
  width: 100%;
  background-color: black;
  display: flex;
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
  letter-spacing: 2px;
  font-size: 2rem;
  margin-bottom: 1rem;
  cursor: pointer;
}
.slider .slider_container .slider_content .content {
  color: white;
  font-size: 1rem;
  letter-spacing: 1px;
  line-height: 19px;
  cursor: pointer;
  padding-right: 2rem;
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
  left: 48%;
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

.exclusive_product {
  width: 100%;
  padding: 0 8rem;
  background-color: var(--product_bg);
  height: 120vh;
  display: flex;
}
.exclusive_product .product_container .product_text {
  margin-top: 5rem;
  text-align: center;
}
.exclusive_product .product_container .product_text h1 {
  font-size: 3rem;
  color: white;
  font-weight: 300;
}
.exclusive_product .product_container .product_text p {
  color: white;
}
.exclusive_product .product_container .product_items {
  text-align: center;
  display: flex;
  justify-content: space-between;
  margin: 5rem 0;
}
.exclusive_product .product_container .product_items p {
  color: white;
}
.exclusive_product .product_container .product_items img {
  border: 2px solid white;
  padding: 30%;
  border-radius: 50%;
}
.exclusive_product .product_container .product_collection {
  display: flex;
}
.exclusive_product .product_container .product_collection .collection {
  width: 50%;
  position: relative;
}
.exclusive_product .product_container .product_collection .collection img {
  width: 100%;
  height: 80%;
  object-fit: cover;
}

.exclusive_product .product_container .product_collection .contianer_1 p {
  font-size: 2.5rem;
  color: white;
  line-height: 3rem;
  font-family: 'Hahmlet', serif;
  letter-spacing: 0.5rem;
}
.exclusive_product
  .product_container
  .product_collection
  .contianer_2
  .text
  h1 {
  font-family: 'Hahmlet', serif;
  color: #4e4540;
}
.exclusive_product .product_container .product_collection .contianer_2 .text p {
  font-family: 'Hahmlet', serif;
  margin: 0.5rem 0;
  color: black;
  font-size: 1.1rem;
}
.exclusive_product
  .product_container
  .product_collection
  .contianer_2
  .text
  .red_text {
  color: red;
  font-size: 1.1rem;
}
.exclusive_product .product_container .product_collection .collection .text {
  position: absolute;
  top: 0;
  color: white;
  left: 15%;
  top: 30%;
}
.our_product {
  width: 100%;
  background: #ececec;
  display: flex;
  align-items: center;
  justify-content: center;
}
.our_product .products_container {
  margin: 20rem 0 0 0;
  padding: 0 8rem;
}
.our_product .products_container .order_container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
}
.our_product .products_container .order_container .products {
  padding: 3rem 2rem;
  background-color: #f9f2ec;
  display: flex;
  flex-direction: column;
}
.our_product .products_container .order_container .products .text {
  color: #636363;
}
.our_product .products_container .order_container .products .img img {
  width: 100%;
}
.our_product .products_container .container_title {
  text-transform: uppercase;
  margin: 2rem 0 5rem 0;
}
.our_product .products_container .gallery .gallery_container {
  margin: 10rem 0;
  width: 100%;
  display: grid;
  grid-template-columns: repeat(6, 1fr);
}
.our_product .products_container .gallery .gallery_container .img img {
  width: 100%;
}
#footer {
  background-color: #ececec;
  width: 100%;
  display: flex;
  flex-direction: column;
}

.footer_container {
  width: 100%;
  padding: 0 8rem;
  display: flex;
  justify-content: space-between;
}
.footer_container .about_container .payment .payment_option {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
}
.footer_container .about_container .jeweler p{
  margin: 1rem 0;
  color: #535353;
}
.footer_container .about_container .jeweler .logo{
  display: inline;
  position: relative; 
}
.footer_container .about_container .jeweler .logo h3{
  position: relative;
  display: inline;
  z-index: 2;
  color: #535353;
  font-size: 16px;
}
.footer_container .about_container .jeweler .logo .img{
  position: absolute;
  top: -15px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 0;
  width: 40px;
}
.footer_container .about_container .payment .payment_option .card img {
  width: 70%;
  padding-right: 1rem;
}
.footer_container .about_container .payment .title{
  color: #535353;
  margin-bottom: 1rem;
  font-size: 14px;
}
.links_container .useful_links h3{  color: #535353;
  margin-bottom: 1rem;
  font-size: 14px;
}
.links_container ul li a{
  color: #535353;
  font-size: 12px;
}
.links_container .delivery_link h3{
  color: #535353;
  margin: 1rem 0;
  font-size: 14px;
}
.customer_service h3{
  margin-bottom: 1rem;
  color: #535353;
  font-size: 14px;
}
.customer_service ul li a{
  color: #535353;
  font-size: 12px;
}
.need_help h3{
  margin-bottom: 1rem;
  font-size: 14px;
  color: #535353;

}
.need_help ul li a{
  color: #535353;
  font-size: 12px;
}
.copyright{
  margin: 1rem 0;
  text-align: center;
  font-size: 14px;
}
</style>
