<template>
  <div class="home">
    <img class="hero" src="../assets/hero.png" alt="">
    <logo />
    <div class="main">
      <h1>Reduce wastage of food <br>with <span>Agrokeep</span></h1>
      <div class="misc">
        <p>coming soon</p>
        <div class="btns">
          <button><img src="../assets/playstore.svg" alt="" srcset=""> PLAYSTORE</button>
          <button><img src="../assets/apple.svg" alt="" srcset=""> APPLESTORE</button>
        </div>
      </div>
    </div>
    <Misc />
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.home{
  height: 100vh;
}
.hero{
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  pointer-events: none;
  z-index: -1;
}
.main{
  color: white;
  width: 90%;
  margin: auto;
  margin-top: 50px;
}
.main h1{
  font-weight: 300;
  font-size: 60px;
}
.main h1 span{
  border-bottom: 2px solid #F2C94C;
  padding-bottom: 5px;
}
.misc{
  margin-top: 70px;
}
.misc p{
  font-size: 30px;
  margin-bottom: 10px;
}
.misc .btns{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 450px;
  flex-wrap: wrap;
  margin-top: 30px;
}
button{
  color: #27AE60;
  padding: 15px 25px;
  font-size: 20px;
  display: flex; 
  justify-content: space-between;
  align-items: center;
  background: white;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  margin-right: 10px;
  margin-bottom: 10px;
}
button img{
  margin-right: 10px;
}
@media screen and (max-width: 760px){
  .hero{
    width: 100%;
    object-fit: cover;
  }
  .main {
    margin-top: 10px;
  }
  .misc{
    margin-top: 30px;
  }
  .main h1{
    font-size: 35px;
  }
  .misc p{
    font-size: 20px;
  }
  .misc .btns{
    width: 35%
  }
  button{
    font-size: 17px;
    padding: 15px 18px;
  }
}
</style>