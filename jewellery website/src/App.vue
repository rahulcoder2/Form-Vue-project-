<script setup>
  
</script>

<template>
  <header>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Products</a></li>
        </ul>
        <div class="logo">
          <img src="./images/Logo.svg" alt="">
        </div>
        <ul>
          <li><a href="#">Services</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </nav>
  
      <!-- End of desktop Navigation menu -->

      <div class="hero-section">
        <div class="left">
          <img src="./images/herosection.png">
        </div>
        <div class="right">
          <h1>
            PREMIUM HANDMADE <br>
            JEWELLERY ON EVERY <br>
            OCCASION
          </h1>
  
          <p>
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud amet.
          </p>
  
          <a href="#" class="btn">Learn More...</a>
        </div>
        <div class="icon">
          <img src="./images/Icon.svg">
        </div>
      </div>
  </header>

  <!-- End of the header section -->
  <section>
    <div class="service-section">
      <div class="products">
        <div class="ex-products">
          <h1>
            3000 <br>
            exclusive Products
          </h1>
        </div>
        <div class="icon">
          <div class="earrings">
            <img src="./images/earrings 1.svg">
            <h4>Earrings</h4>
          </div>
          <div class="Rings">
            <img src="./images/diamond-ring 1.svg">
            <h4>Rings</h4>
          </div>
          <div class="Necklace">
            <img src="./images/necklace 1.svg">
            <h4>Necklace</h4>
          </div>
          <div class="Watch">
            <img src="./images/smartwatch 1.svg">
            <h4>Watch</h4>
          </div>
          <div class="brecelet">
            <img src="./images/bracelet 1.svg">
            <h4>Bracelet</h4>
          </div>
        </div>
      </div>
      <!-- products ended here -->
      <div class="banner">
        <div class="left">
          <h1>NEW <br> SPRING <br> COLLECTIONS</h1>
        </div>
        <div class="right">
          <div>
            <h1>20% <br> OFF</h1>
            <p>Amet ipsum, enim massaenum mattis pulvinar. Pretium sem a , sed lacus ac.</p>
            <h4>Product</h4>
          </div>
        </div>
      </div>
    </div>
    <!-- Banner ended from here -->
  </section>
  <!--  End of the Exclusive Products  -->
  <section>
    <div class="order-product">
      <h1>PRODUCTS</h1>
    </div>
  </section>
  
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:wght@100&display=swap');

:root{
  --bg-color: #010101;
  --herosection: #181314;
  --product-color: #F9F2EC;
  --btn-color: #D9D9D9;
  --banner-color:#048C91;
}

*,
*::before,
*::after{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body{
  font-family: 'Poppins', sans-serif;
  margin: 0;
  overflow-x: hidden;
}

ul,
li,
a{
  text-decoration: none;
  list-style-type: none;
}
/* buttons */

.btn{
  background-color: var(--btn-color);
  border-radius: 24px;
  font-family: "Poppins",sans-serif;
  font-weight: bold;
  font-size: 18px;
  display: inline-block;
  padding: 16px 32px;
  color: black;
}



/* Header */

header{
  width: 100vw;
}

nav{
  padding: 0 181px;
  display: flex;
  justify-content: space-between;
  background-color: var(--bg-color);
  height: 65px;
  align-items: center;
}

nav.logo{
  width: 123px;
  height: 36px;
  cursor: pointer;
}

nav ul{
  display: flex;
  align-items: center;
  gap: 103px ;
}

nav li a{
  font-family: "poppins", sans-serif;
  color: #fff;
  font-size: 18px;
  font-weight: bold;
}

nav li a:hover{
  color: #b5d42c;
}

/* Hero Section */

.hero-section{
  background-color: var(--herosection);
  height: 530px;
  display: flex;
  justify-content: space-between;
}

.hero-section .right h1{
  font-family: 'Poppins';
  font-weight: bold;
  font-size: 36px;
  color: #FFFFFF;
  margin-bottom: 0px;
}

.hero-section .right p{
  font-family: "Poppins",sans-serif;
  font-weight: normal;
  font-size: 16px;
  color: #FFFFFF;
  margin-bottom: 30px;
}

.hero-section .right{
  width: 458px;
  margin-right: 181px;
  align-self: center;
}

.hero-section .icon{
  position: absolute;
  top:83% ;
  left: 47%;
  z-index: 1;
}

/* header end here  */


/* exclusive products */

.service-section{
  background-color: var(--bg-color);
  height: 560px;
  
}

.ex-products h1{
  color: #fff;
  text-align: center;
  padding: 45px 0;
}
.icon div{
  width: 20px;
}
.icon{
  color: #fff;
  align-items: center;
  display: flex;
  justify-content: center;
  gap: 125px ;
}

/* banner */

.banner{
  display: flex;
  background-color: var(--banner-color);
  width: 1025px;
  height: 680px;
  margin: 30px auto;
}

.banner .left{
  width: 512px;
  height: 680px;
  display: flex;
  align-items: center;
  background: url(./images/leftbanner.png);
}

.banner .left h1{
  width: 440px;
  height: 255px;
  font-family: 'Playfair Display',serif;
  font-weight: 400;
  font-size: 64px;
  color: #FFFFFF;
  margin-left: 15px;
}

.banner .right{
  width: 512px;
  height: 680px;
  display: flex;
  align-items: center;
  background: url(./images/rightbanner.png);
}

.banner .right div{
  width: 135px;
  height: 275px;
  margin-left: 40px;
}

/* order product  */

.order-product{
  margin-top: 450px;
  padding: 0 150px;
}



 </style>