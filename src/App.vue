<script>
import AppHeader from './components/AppHeader.vue'
export default {
  name: 'Second app .Vue',
  components: {
    AppHeader
  }
}
</script>

<template>
  <AppHeader />
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
</style>
