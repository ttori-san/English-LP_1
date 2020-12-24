<template>
  <div class="sidemenu">
    <ul class="archive">
      <li class="archive-label">archive</li>
      <li class="month"><a href="#">Dec.</a></li>
      <li class="month"><a href="#">Nov.</a></li>
      <li class="month"><a href="#">Oct.</a></li>
      <li class="month"><a href="#">Sep.</a></li>
      <li class="month bottom"><a href="#">Aug.</a></li>
    </ul>
  </div>
</template>
<style scoped>
.sidemenu{
  width:20%;
  border-right:white solid 2px;
  background-color:black;
}
.archive{
  list-style: none;
  margin:0;
}
.archive-label{
  font-size:120%;
  margin-right:10px;
}
.month{
  padding-top: 3px;
  border-bottom:white solid 100%;
  list-style: none;
}
.bottom{
  padding-bottom:3px;
}
.sidemenu a{
  text-decoration: none;
  color:white;
  cursor: pointer;
}
.sidemenu a:hover{
  border-bottom: rgba(255, 190, 71, 0.986) solid;
  color:rgba(255, 190, 71, 0.986);
  transition:0.3s;
}

</style>