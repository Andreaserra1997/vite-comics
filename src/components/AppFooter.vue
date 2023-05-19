<script></script>

<template>
  <footer>
    <div class="content-footer">
      <div class="big-list">
        <div class="first-list">
          <ul>
            <li><h3>DC COMICS</h3></li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <div class="list-down">
            <ul>
              <li><h3>SHOP</h3></li>
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>
          </div>
        </div>

        <ul>
          <li><h3>DC</h3></li>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>

        <ul>
          <li><h3>SITES</h3></li>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
    </div>
  </footer>
  <div class="footer-down">
    <div class="content-footer-down">
      <div class="btn-sign">
        <button>SIGN-UP NOW!</button>
      </div>
      <div class="icon-social">
        <h3>FOLLOW US</h3>
        <img src="../assets/img/footer-facebook.png" />
        <img src="../assets/img/footer-twitter.png" />
        <img src="../assets/img/footer-youtube.png" />
        <img src="../assets/img/footer-pinterest.png" />
        <img src="../assets/img/footer-periscope.png" />
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
footer {
  background-image: url(../assets/img/footer-bg.jpg);
  padding: 3rem;
  .content-footer {
    max-width: 1000px;
    margin: auto;
  }
  .big-list {
    display: flex;
    h3 {
      color: white;
      padding-bottom: 0.8rem;
    }
    li {
      list-style: none;
      padding-inline: 0.8rem;
      color: #959595;
      line-height: 1.3rem;
    }
  }
  .list-down {
    padding-top: 0.5rem;
  }
}
.footer-down {
  background-color: #303030;
  .content-footer-down {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 6rem;
    max-width: 1000px;
    margin: auto;
    button {
      border: 3px solid #0282f9;
      background-color: #303030;
      color: #fff;
      padding: 0.8rem;
      cursor: pointer;
    }
    .icon-social {
      display: flex;
      align-items: center;
      img {
        padding-inline: 0.5rem;
      }
      h3 {
        color: #0282f9;
        padding-right: 1rem;
      }
    }
  }
}
</style>
