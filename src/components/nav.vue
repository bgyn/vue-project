<script setup></script>

<template>
    <navbar class="nav_navbar" id="navbar">
    <nav class="navbar_links">
      <div class="nav_left">
        <li class="nav_links"><a href="/">HOME</a></li>
        <li class="nav_links"><a href="/about">PRODUCTS</a></li>
      </div>
      <div class="nav_logo">
        <a href="#">JEWELERY</a>
        <img src="/diamond.png" alt="img_logo" class="img_logo" />
      </div>
      <div class="nav_right">
        <li class="nav_links"><a href="#services">SERVICES</a></li>
        <li class="nav_links"><a href="#footer">CONTACT</a></li>
      </div>
    </nav>
  </navbar>
</template>
<style>
.nav_navbar {
  width: 100%;
}
.nav_navbar .navbar_links {
  background-color: var(--nav_bg);
  display: flex;
  padding: 1.5rem 8rem;
  justify-content: space-between;
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
.nav_left,
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
.hamburger{
  
}
.hamburger .line{
  width: 60px;
  height: 5px;
  background-color: aliceblue;
  margin: 5px 0;
}

@media (max-width: 480px){
  .nav_navbar .navbar_links{
    padding:  1.5rem 1rem;
  }
  .nav_left{
    display: none;
  }
  .nav_right{
    display: none;
  }
}

</style>