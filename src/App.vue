<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue';
export default {
  name: 'Second app .Vue',
  components: {
    AppHeader, AppMain, AppFooter
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  width: 1200px;
  margin: 0 auto;
}

body {
  height: 100vh;
  font-family: 'Times New Roman', Times, sans-serif;
}
</style>
