<script>
export default {
  props: {
    thumb: String,
    price: String,
    series: String,
    type: String,
  },
};
</script>

<template>
  <div class="card">
    <img :src="thumb" />
    <h3>{{ series }}</h3>
  </div>
</template>

<style lang="scss" scoped>
.card {
  img {
    width: 100%;
    object-fit: cover;
  }
}
</style>
