<script setup></script>

<template>
  <header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
      </ul>
      <div class="logo">
        <img src="./images/Logo.svg" alt="" />
      </div>
      <ul>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </nav>

    <!-- End of desktop Navigation menu -->

    <div class="hero-section">
      <div class="left">
        <img src="./images/herosection.png" />
      </div>
      <div class="right">
        <h1>
          PREMIUM HANDMADE <br />
          JEWELLERY ON EVERY <br />
          OCCASION
        </h1>

        <p>
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
          sint. Velit officia consequat duis enim velit mollit. Exercitation
          veniam consequat sunt nostrud amet.
        </p>
        <button class="btn">
          <a href="#">Learn More...</a>
        </button>
      </div>
      <div class="icon">
        <img src="./images/Icon.svg" />
      </div>
    </div>
  </header>

  <!-- End of the header section -->
  <section>
    <div class="service-section">
      <div class="products">
        <div class="ex-products">
          <h1>3000</h1>
          <h3>exclusive products</h3>
        </div>
        <div class="icon">
          <div class="earrings">
            <img src="./images/earrings.svg" />
            <h4>Earrings</h4>
          </div>
          <div class="Rings">
            <img src="./images/rings.svg" />
            <h4>Rings</h4>
          </div>
          <div class="Necklace">
            <img src="./images/necklace.svg" />
            <h4>Necklace</h4>
          </div>
          <div class="Watch">
            <img src="./images/watches.svg" />
            <h4>Watch</h4>
          </div>
          <div class="brecelet">
            <img src="./images/bracelets.svg" />
            <h4>Bracelet</h4>
          </div>
        </div>
      </div>
      <!-- products ended here -->
      <div class="banner">
        <div class="left">
          <h1>
            NEW <br />
            SPRING <br />
            COLLECTIONS
          </h1>
        </div>
        <div class="right">
          <div>
            <h1>
              20% <br />
              OFF
            </h1>
            <p>
              Amet ipsum, enim massaenum mattis pulvinar. Pretium sem a , sed
              lacus ac.
            </p>
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
      <div class="product">
        <div class="order">
          <img src="./images/order 1.png" />
          <p>Dark earrings</p>
          <p>$10.00 - $23.00</p>
        </div>
        <div class="order">
          <img src="./images/order 2.png" />
          <p>Fancy earrings</p>
          <p>$1.90 - $37.90</p>
        </div>
        <div class="order">
          <img src="./images/order 3.png" />
          <p>Gold necklace</p>
          <p>$100.00 - $300.00</p>
        </div>
        <div class="order">
          <img src="./images/order 4.png" />
          <p>Gold ring</p>
          <p>$35.00 - $45.00</p>
        </div>
        <div class="order">
          <img src="./images/order 5.png" />
          <p>Head crown</p>
          <p>$1,480.00- $2,000.00</p>
        </div>
        <div class="order">
          <img src="./images/order 6.png" />
          <p>Light earrings</p>
          <p>$12.00 - $33.00</p>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,400;1,500;1,600;1,700;1,800;1,900&family=Poppins:wght@100&display=swap");

:root {
  --bg-color: #010101;
  --herosection: #181314;
  --product-color: #f9f2ec;
  --btn-color: #d9d9d9;
  --banner-color: #048c91;
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  font-family: "Poppins", sans-serif;
  margin: 0;
}

ul,
li,
a {
  text-decoration: none;
  list-style-type: none;
}
/* buttons */

.btn {
  background-color: var(--btn-color);
  border-radius: 24px;
  width: 134.51px;
  height: 39px;
  margin-top: 31px;
}

.btn a {
  font-family: "Heebo";
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 0%;
  /* identical to box height, or 0px */
  color: var(--bg-color);
}

/* Header */

header {
  width: 100%;
}

nav {
  padding: 0 172px 0 166px;
  display: flex;
  justify-content: space-between;
  background-color: var(--bg-color);
  height: 74px;
  align-items: center;
}

nav.logo {
  width: 123px;
  height: 36px;
  cursor: pointer;
}

nav ul {
  display: flex;
  align-items: center;
  gap: 51px;
}

nav li a {
  font-family: "Heebo";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 24px;
  /* identical to box height */
  letter-spacing: 0.13em;
  color: #ffffff;
}

nav li a:hover {
  color: #b5d42c;
}

/* Hero Section */

.hero-section {
  background-color: var(--herosection);
  height: 564px;
  display: flex;
  justify-content: space-between;
  position: relative;
}

.hero-section .right h1 {
  font-family: "Heebo";
  font-style: normal;
  font-weight: 400;
  font-size: 31px;
  line-height: 134.4%;
  /* or 42px */
  letter-spacing: 0.13em;
  color: #ab9d90;
}

.hero-section .right p {
  font-family: "Heebo";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 134.4%;
  /* or 19px */
  letter-spacing: 0.13em;
  color: #ffffff;
  margin-top: 9px;
}

.hero-section .right {
  width: 451px;
  height: 281px;
  margin-right: 181px;
  align-self: center;
}

.hero-section .icon {
  position: absolute;
  bottom: -42px;
  left: 50%;
  transform: translateX(-50%);
}

/* header end here  */

/* exclusive products */

.service-section {
  background-color: var(--bg-color);
  height: 991px;
}

.ex-products {
  padding-top: 139px;
  text-align: center;
}

.ex-products h1 {
  font-family: "Gudea";
  font-style: normal;
  font-weight: 400;
  font-size: 64px;
  line-height: 38px;
  /* identical to box height, or 59% */
  letter-spacing: 0.04em;
  color: #ffffff;
}

.ex-products h3 {
  padding-top: 34px;
  font-family: "Gudea";
  font-style: normal;
  font-weight: 400;
  font-size: 32px;
  line-height: 0px;
  /* identical to box height, or 0% */
  letter-spacing: 0.02em;
  color: #ffffff;
}

.icon {
  padding-top: 98px;
  color: #fff;
  align-items: center;
  text-align: center;
  line-height: 40px;
  display: flex;
  justify-content: center;
  gap: 100px;
}

/* banner */

.banner {
  display: flex;
  background-color: var(--banner-color);
  width: 1025px;
  height: 680px;
  margin: 40px auto;
}

.banner .left {
  width: 512px;
  height: 680px;
  display: flex;
  justify-content: center;
  align-items: center;
  background: url(./images/leftbanner.png);
}

.banner .left h1 {
  width: 408px;
  height: 171px;
  font-family: "Hahmlet";
  font-style: normal;
  font-weight: 700;
  font-size: 46px;
  line-height: 124.4%;
  /* or 57px */
  letter-spacing: 0.13em;
  color: #ffffff;
}

.banner .right {
  width: 512px;
  height: 680px;
  display: flex;
  align-items: center;
  background: url(./images/rightbanner.png);
}

.banner .right h1 {
  font-family: "Hanuman";
  font-style: normal;
  font-weight: 400;
  font-size: 64px;
  line-height: 107.9%;
  /* or 69px */
  letter-spacing: 0.13em;
  color: #4e4540;
}

.banner .right p {
  width: 165px;
  height: 86px;
  font-family: "Hannari";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 141.4%;
  /* or 20px */
  letter-spacing: 0.13em;
  color: #000000;
}

.banner .right h4 {
  font-family: "Hannari";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 141.4%;
  /* identical to box height, or 20px */
  letter-spacing: 0.13em;
  color: #ff4560;
}

.banner .right div {
  width: 135px;
  height: 275px;
  margin-left: 40px;
}
/* order product  */

section .order-product {
  padding: 230px 155px 0px;
}

.order-product h1 {
  margin-bottom: 86px;
}

.product {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
}

.order {
  background: #f9f2ec;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem 0;
}

.order p {
  font-family: "Heebo";
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 21px;
  /* identical to box height */
  align-self: flex-start;
  color: #636363;
  padding-left: 8px;
}


</style>
