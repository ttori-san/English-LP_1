<template>
  <div class="introduction">
    <div class="flex">
      <img class="intro-person" src="../assets/5e5350e2d87131d9ff0acac5_peep-6.png" />
      <div class="today's phrase">
        <p class="phrase-template">Today's phrase is...</p>
        <p class="variable-input-area" :todaysPhrase="sendText">{{sendText}}</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.flex{
  display: flex;
}
.intro-person{
  width: 100px;
}
.phrase-template{
  color:white;
  font-size:25px;
}
.variable-input-area{
  color:lightblue;
  display:inline-block;
  font-size:30px;
  height:50px;
  border-style: none;
  border-bottom: white solid 3px;
  border-radius: 0%;
}
</style>

<script>
export default {
  data(){
    return{
      sendText:"nebulous"
    }
  }
}
</script>