<template>
  <div class="UserInput">
    <div class="input-area">
      <div class="flex">
        <input class="apply input"/>
        <p class="apply">{{textExample}}</p>
      </div>
    </div>
    <div class="answer-response">
      <p class="response">
        <span class="responseVariable">{{responseJa}}</span>
        <span>スペルが間違っています</span>
        <!-- v-else ↑-->
        {{template}}
      </p>
    </div>
  </div>
</template>
<script>
export default {
  data(){
    return{
      props:["todaysPhrase"],
      textExample:"answer",
      //if else{
        template:"答え",
        // }
        responseJa:"漠然とした",
    }
  }
}
</script>
<style scoped>
.flex{
  display: flex;
}
.apply{
  color:white;
}
.input{
  width: 50%;
  font-size:30px;
  border-bottom:white solid 3px;
  background-color:black;
}
.answer-response{
  color:white;
}
.responseVariable{
  font-size: 25px;
  border-bottom: white solid 3px;
}
</style>