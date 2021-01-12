<template>
  <div id="app">
    <div id="nav">
      <Header />
      <div class="flex">
        <Sidemenu />
        <div class="right">
          <Introductioin />
          <VocabularyInput />      
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style>
.flex{
  display:flex;
}
#app {
  color:white ;
  background-color:black;
}

#nav {
  padding: 30px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

<script>
import Header from './components/Header'
import Sidemenu from './components/Sidemenu'
import Introductioin from './components/Introductioin'
import VocabularyInput from './components/VocabularyInput'
export default {
  components:{
    Header,
    Sidemenu,
    Introductioin,
    VocabularyInput,
  }
}
</script>
