<script></script>

<template>
  <header>
    <div class="content-header">
      <div><img src="../assets/img/dc-logo.png" /></div>
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  background-color: #fff;
  .content-header {
    display: flex;
    align-items: center;
    justify-content: space-around;
    height: 6rem;
    max-width: 1000px;
    margin: auto;
    img {
      width: 60%;
    }
  }
}
ul {
  display: flex;
  li {
    list-style: none;
    padding-inline: 0.6rem;
    a {
      text-decoration: none;
      color: black;
    }
  }
}
</style>
