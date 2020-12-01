<template>
    <div class="misc">
        <ul class="socials">
            <li>Tw.</li>
            <li>Ig.</li>
            <li>Ln.</li>
        </ul>
        <p>&copy; copyrights 2020. Agrokeep Ent.</p>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

*{
    font-size: 20px;
    color: white;
}
.misc{
    height: 10vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  padding:  0 5%;
  margin: auto; 
  z-index: 10;
  position: absolute;
  bottom: 0;
}
.socials{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.socials li{
    margin-right: 30px;
    list-style-type: none;
}
@media screen and (max-width: 760px){
    .misc{
        padding: 0 2%;
        height: 10vh;
    }
    .misc p, li{
        font-size: 13px;
    }
    .socials li{
        margin-right: 10px;
    }
}
</style>