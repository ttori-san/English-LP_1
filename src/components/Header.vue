<template>
  <header class="header">
    <p class="header-logo">Englsih LP</p>
    <ul class="header-list">
      <li ><a class="header-list-link" href="#">home</a></li>
    </ul>
  </header>
</template>

<style scoped>
.header{
  height:100px;
  width:auto;
  color: white;
  background: #20b974;

  padding-left:40%;
  align-items:center;
  justify-content: space-between;
  display:flex;
}
.header-logo{
  font-size: 40px;
  font-style: bold;
  font-family:-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

  text-align: center;
  margin:0;
  cursor: pointer;
  /* padding-top:30px; */
}
.header-list{
  list-style: none;
  padding-right:10%;
}
 .header-list-link{
   text-decoration: none;
   color:white;
   cursor: pointer;
 }
 .header-list-link:hover{
   border-bottom: rgba(255, 190, 71, 0.986) solid;
   color:rgba(255, 190, 71, 0.986);
   transition:0.3s;
 }
</style>