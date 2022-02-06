<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Avatar :url="'http://img.duoziwang.com/2021/06/q101801413228587.jpg'"
            :size="100"/>
    <Icon type="home" />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Avatar from './components/Avatar'
import Icon from './components/Icon'

export default {
  name: 'App',
  components: {
    Avatar,
    Icon
  },
}
</script>

<style scoped>
.iconfont{
  color: red;
}
</style>



