<template>
  <div class="home">
    <div class="landing">
        <img class="hero" src="https://res.cloudinary.com/devdaniel/image/upload/v1606785486/hero_f44yb1.png" alt="">
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
    <!-- Section -->
    <div class="side s1">
      <h1>Manage more than one<br> project at a time.</h1>
      <img src="https://res.cloudinary.com/devdaniel/image/upload/v1606785449/manage_pxkwza.png" alt="" srcset="">
    </div>
    <!-- Section -->
    <div class="side s2">
      <img src="https://res.cloudinary.com/devdaniel/image/upload/v1606785448/fill-form_xwho3z.png" alt="" srcset="">
      <h1>Fill in forms for your<br> perfect prediction.</h1>
    </div>
    <!-- Section -->
    <div class="side2">
      <img class="comp" src="../assets/complement.svg" alt="" srcset="">
      <h2>Get accurate data of how much <br>harvest you would make.</h2>
      <img src="https://res.cloudinary.com/devdaniel/image/upload/v1606785448/accurate_ximuzk.png" alt="" srcset="">
    </div>
    <!-- Section -->
    <div class="footer">
      <h4>coming soon...</h4>
      <p>&copy; copyrights 2020. Agrokeep Ent.</p>
    </div>
  </div>
  
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.home{
  color: white;
}
.landing{
  position: relative;
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
  width: 90%;
  margin: auto;
  margin-top: 50px;
}
.main h1, .side h1{
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
.side{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 90%;
  margin: 100px auto;
  height: 100vh;

}
.side2{
  width: 90%;
  margin: 100px auto;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background: #298A53;
  border: 10px solid #F2C94C;
  border-radius: 40px;
  padding-top: 20px;
  position: relative;
  flex-wrap: wrap;
  z-index: -4;
  overflow: hidden;

}
.side2 h2{
  font-weight: 100;
  font-size: 35px;
}
.side2 img{
  margin-top: 20px;
}
.side2 .comp{
  position: absolute;
  top: 0;
  left: 0;
  width: 150px;
  z-index: -1;
}
.footer{
  background: #F2C94C;
  width: 100%;
  padding: 20px 40px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap
}
@media screen and (max-width: 1119px){
    .side{
      flex-direction: column;
      margin: 100px auto;
      text-align: center;
      height: auto;
    }
    .side h1{
      font-size: 35px;
    }
    .s1 img{
      margin-top: 40px
    }
    .s2 img{
      margin-bottom: 40px
    }
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
  .side{
    height: auto;
  }
  .side img{
    width: 400px;
  }
  .side2{
    text-align: center;
    padding: 0 40px;
    padding-top: 40px;
  }
  .side2 h2{
    font-size: 25px
  }
}
@media screen and (max-width: 460px){
  .side2 h2{
    font-size: 18px
  }
  .side img{
    width: 200px;
  }
}
</style>