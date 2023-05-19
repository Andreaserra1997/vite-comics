<script>
import Card from "./Card.vue";

export default {
  components: { Card },
  data() {
    return {
      arrCard: [
        {
          thumb: "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb: "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<template>
  <main>
    <div class="jumbo"></div>
    <div class="content-top">
      <ul>
        <li v-for="(card, index) in arrCard" :key="index">
          <Card :thumb="card.thumb" :series="card.series" />
        </li>
      </ul>
    </div>
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
  background-color: #1c1c1c;
  color: white;
  padding: 2rem;
  ul {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    max-width: 1000px;
    margin: auto;
    li {
      width: calc(100% / 6);
      list-style: none;
      text-align: center;
    }
  }
}
.content-down {
  background-color: #0282f9;
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
}
</style>
