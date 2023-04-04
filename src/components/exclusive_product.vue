<script setup></script>

<template>
  <div class="exclusive_products">
    <div class="exclusive_container">
      <div class="product_text">
        <h1>3000</h1>
        <p>exclusive product</p>
      </div>
      <div class="exclusive_item">
        <div class="item">
          <div class="img">
            <img src="diamond-ring.png" alt="" />
          </div>
          <p>Earing</p>
        </div>
        <div class="item">
          <div class="img">
            <img src="diamond-ring.png" alt="" />
          </div>
          <p>Earing</p>
        </div>
        <div class="item">
          <div class="img">
            <img src="diamond-ring.png" alt="" />
          </div>
          <p>Earing</p>
        </div>
        <div class="item">
          <div class="img">
            <img src="diamond-ring.png" alt="" />
          </div>
          <p>Earing</p>
        </div>
        <div class="item">
          <div class="img">
            <img src="diamond-ring.png" alt="" />
          </div>
          <p>Earing</p>
        </div>
        <div class="item">
          <div class="img">
            <img src="diamond-ring.png" alt="" />
          </div>
          <p>Earing</p>
        </div>
      </div>
      <div class="exclusive_collection">
        <div class="collection collection_1">
          <div class="text">
            <h1> new<br />
            spring<br />
            collection</h1>
           
          </div>
        </div>
        <div class="collection collection_2">
          <div class="text">
            <h1>20%<br />off</h1>
            <p>
              In publishing and graphic design, Lorem ipsum is a placeholder
            </p>
            <p class="red_text">product</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.exclusive_products {
  width: 100%;
  padding: 0 8rem;
  background-color: var(--product_bg);
  height: 100vh;
  display: flex;
  flex-direction: column;
}

.exclusive_products .exclusive_container .product_text {
  display: flex;
  align-items: center;
  flex-direction: column;
  color: white;
  margin: 80px 0;
}
.exclusive_item {
  display: flex;
  justify-content: space-between;
  margin-bottom: 4rem;
}
.exclusive_item .item .img {
  border: 2px solid white;
  border-radius: 50%;
  width: 80px;
  height: 80px;
  display: flex;
  padding: 1.3rem;
}
.exclusive_item .item p {
  text-align: center;
  margin: 5px 0;
  color: white;
}
.exclusive_collection {
  display: flex;
  width: 100%;
}
.exclusive_collection .collection {
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  height: 590px;
  max-height: 590px;
  width: 50%;
  position: relative;
}
.exclusive_collection .collection .text{
  height: 100%;
  position: absolute;
  top: calc(50% - 110px);
  left: 100px;
  color: white;
  display: inline;
}
.exclusive_collection .collection_1 .text h1{
  text-transform: uppercase;
  font-family: 'Hamlet';
  letter-spacing: 3px;
  line-height: 50px;
  font-size: 32px;
}
.exclusive_collection .collection_2 .text h1{
  font-size: 50px;
  font-family: 'Hanuman', serif;
  text-transform: uppercase;
  color: #4E4540;
  line-height: 65px;
}
.exclusive_collection .collection_2 .text p{
  font-size: 14px;
  color: #4E4540;
  margin-bottom: 20px;
  font-weight: bold;
  letter-spacing: 2px;
  width: 150px;
}
.exclusive_collection .collection_2 .text .red_text{
  color: rgb(204, 0, 0);
  text-transform: uppercase;
  font-size: 14px;
}
.collection_1 {
  background-image: url('model(1).jpg');
}
.collection_2 {
  background-image: url('model(2).jpg');
}
</style>
