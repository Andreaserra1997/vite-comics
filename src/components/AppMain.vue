<script></script>

<template>
  <main>
    <div class="jumbo"></div>
    <div class="content-top"></div>
    <div class="content-down">
      <ul>
        <li>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" /><a
            href="#"
            >DIGITAL COMICS</a
          >
        </li>
        <li>
          <img src="../assets/img/buy-comics-merchandise.png" alt="" /><a
            href="#"
            >DC MERCHANDISE</a
          >
        </li>
        <li>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" /><a
            href="#"
            >SUBSCRIPTION</a
          >
        </li>
        <li>
          <img
            class="location"
            src="../assets/img/buy-comics-shop-locator.png"
            alt=""
          /><a href="#">COMIC SHOP LOCATOR</a>
        </li>
        <li>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" /><a href="#"
            >DC POWER VISA</a
          >
        </li>
      </ul>
    </div>
  </main>
</template>

<style lang="scss" scoped>
.jumbo {
  background-image: url(../assets/img/jumbotron.jpg);
  background-size: cover;
  height: 300px;
}
.content-top {
  height: 100px;
  background-color: #1c1c1c;
  color: white;
}
.content-down {
  background-color: #0282f9;
}
ul {
  display: flex;
  justify-content: center;
  max-width: 1000px;
  margin: auto;
  li {
    display: flex;
    align-items: center;
    list-style: none;
    height: 5rem;
    padding-inline: 3rem;
    img {
      width: 50%;
      padding-right: 0.5rem;
    }
    .location {
      width: 30%;
    }
    a {
      text-decoration: none;
      font-size: 0.8rem;
      white-space: nowrap;
      color: #fff;
    }
  }
}
</style>
