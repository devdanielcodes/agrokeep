<template>
    <div class="tteam">
        <logo />
            <div class="main">
                <h1>The Team</h1>
                <div class="team">
                    <div class="person">
                        <h2>Chinazo</h2>
                        <h4>Backend Devloper</h4>
                        <ul>
                            <li><a href="">Tw.</a></li>
                            <li><a href="">Ig.</a></li>
                            <li><a href="">Ln.</a></li>
                        </ul>
                    </div>
                    <div class="person">
                        <h2>Adekoya Daniel</h2>
                        <h4>Frontend Developer /<br> UI Designer</h4>
                        <ul>
                            <li><a href="">Tw.</a></li>
                            <li><a href="">Ig.</a></li>
                            <li><a href="">Ln.</a></li>
                        </ul>
                    </div>
                </div>
                <div class="team cc">
                    <div class="person">
                        <h2>Afeez Wojuade</h2>
                        <h4>Mobile Developer</h4>
                        <ul>
                            <li><a href="">Tw.</a></li>
                            <li><a href="">Ig.</a></li>
                            <li><a href="">Ln.</a></li>
                        </ul>
                    </div>
                    <div class="person">
                        <h2>John Afolabi</h2>
                        <h4>Data Analyst</h4>
                        <ul>
                            <li><a href="">Tw.</a></li>
                            <li><a href="">Ig.</a></li>
                            <li><a href="">Ln.</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        <Misc />
    </div>
</template>

<script>
    export default {
        head: {
            title: 'Agrokeep | Team',
            meta: [
                { charset: 'utf-8' },
                { name: 'viewport', content: 'width=device-width, initial-scale=1' },
                { hid: 'description', name: 'description', content: 'The Team of Agrokeep (Team Futur)' }
            ],
        }
    }
</script>

<style scoped>
.main h1{
    text-align: center;
    color: white;
    position: relative;
    width: 70%;
    margin: 0 auto;
    font-size: 40px
}
.main h1::after{
    content: '';
    position: absolute;
    top: 50%;
    left: 0;
    transform: translateY(-50%);
    width: 30%;
    height: 4px;
    background: white
}
.main h1::before{
    content: '';
    position: absolute;
    top: 50%;
    right: 0;
    transform: translateY(-50%);
    width: 30%;
    height: 4px;
    background: white
}
.team{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    font-size: 20px;
    color: #FFF;
    text-align: center;
    flex-wrap: wrap;
}
.person{
    width: 250px;
    margin-top: 50px;

}
.cc, .person:nth-child(2){
    margin-bottom: 30px;
}
.person h2, .person h4{
    margin-bottom: 10px
}
.person h4{
    font-weight: 200
}
ul{
    display: flex;
    justify-content: space-between;
    list-style: none;
    width: 60%;
    margin: auto
}
ul li a{
    color: white;
    text-decoration: none;
}
@media screen and (max-width: 760px){
    .main h1::before, .main h1::after{
        display: none;
    }
}
</style>