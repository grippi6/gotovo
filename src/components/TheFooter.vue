<script setup>

</script>

<template>
  <div class="footer-start">
    <router-link class="ah" :to="{name:'main'}"><img src="../assets/image/лого.png" alt="" width="200px"></router-link>
    <div class="nav-footer">
    <p href="" >Мы в соцсетях</p>
      <div class="images">
      <img src="../assets/image/vk.png" width="40px" >
      <img src="../assets/image/inst.jpg" width="40px">
      <img src="../assets/image/telega_2.png" width="40px">
      </div>
    </div>
  </div>
</template>

<style scoped>
.footer-start{
  align-items: center;
  width: 100%;
  background-color: brown;
  display: flex;
  justify-content: space-evenly;
}
.footer-start p{
  color:gold;
  font-size:1.5em;
}
.images{
  display: flex;
  justify-content: space-evenly;border-radius: 50%;
  padding: 3px;
}
.images img{
  display: flex;
  justify-content: space-evenly;border-radius: 50%;
  padding: 3px;
}
.ah{
  margin-top:10px ;
  text-decoration: none;
  margin-bottom: 10px;
}
.ah p {
  font-family: nyashasans;
}
</style>