<script>
import HeaderLink from "./HeaderLink.vue";

export default {
  components: { HeaderLink },
};
</script>

<template>
  <header>
    <div class="content-header">
      <div><img src="../assets/img/dc-logo.png" /></div>
      <HeaderLink />
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
</style>
