<template>
  <div>
    <img src="../assets/complement.svg" alt="" class="comp">
    <nuxt-link to="/"><img src="../assets/logo.svg" alt="" class="logo"></nuxt-link>
    <nuxt-link to="/team">Team</nuxt-link>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
div{
  height: 16vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 90%;
  margin: auto; 
  z-index: 10;
  position: relative;
}
a{
  text-decoration: none;
  color: white;
  font-size: 25px;
}
.comp{
  position: absolute;
  left: 0;
  top: 40px;
  pointer-events: none;
}
@media screen and (max-width: 760px){
  div{
    min-height: 10vh;
    padding: 20px 0;
  }
  div .logo{
    width: 50px;
  }
}
</style>