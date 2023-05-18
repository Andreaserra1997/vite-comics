<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  components: { AppHeader, AppMain, AppFooter }
}
</script>

<template>
  <app-header></app-header>
  <app-main></app-main>
  <app-footer></app-footer>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
