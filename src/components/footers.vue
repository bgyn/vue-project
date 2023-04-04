<script setup></script>

<template>
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
          <li><a href="#">Account Details</a></li>
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
</template>

<style>
#footer {
  /* background-color: #ececec; */
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