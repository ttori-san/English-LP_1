<template>
  <div id="app">
    <Header />
      <!-- main "FLEX"内に記述-->
    <div class="flex">
      <Sidemenu />
      <Introduction />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Sidemenu from './components/Sidemenu.vue'
import Introduction from './components/Introductioin.vue'
export default {
  name: 'App',
  components: {
    Header,
    Sidemenu,
    Introduction
  }
}
</script>

<style>
#app{
  background-color:#000000;
  color:white;
}
.flex{
  display: flex;
}
</style>
https://github.com/ttori-san/English-LP_1.git
