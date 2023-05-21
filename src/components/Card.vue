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
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  img {
    width: 100%;
    object-fit: contain;
  }
}
</style>
