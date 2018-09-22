<template>
    <div class="jkj-homepg">
        <div class="container">
            <div class="row">
                <div class="col-sm">
                    <img src="../assets/james_photo.jpg" alt="James' Photo" class="jkj_pic">
                </div>
                <div class="col-xl">
                    <img src="../assets/home.svg" alt="Landing Page Vector" class="landing_pg_vector">
                </div>
                <div class="col-sm">
                    <h2 class="jkj-top-heading animated fadeInRight">James Kaviyil Jose</h2>
                </div>
                <div class="col-sm">
                    <h4 class="jkj-tagline animated fadeInUp">Front-End Web Developer & <br>Passionate Coding Enthusiast</h4>
                </div>
            </div>    
        </div>
    </div>
</template>

<style>
.jkj-homepg{
    background-color: #251e3e;
    height: 100vh;
}
.landing_pg_vector{
    height: 501px;
    width: 520px;
    margin-left: 44vw;
    margin-top: -15vw;
}
.jkj-top-heading{
    margin-top: -16vw;
    margin-left: -1vw;
    font-family: 'Bangers',cursive;
    font-size: 4vw;
    color: #fff;
}
.jkj-tagline{
    margin-left: -37vw;
    margin-top: -10vw;
    font-family: 'Changa', sans-serif;
    color: #fff;
}
.jkj_pic{
    border-radius: 75px;
    margin-top: 8vw;
    margin-left: 5vw;
}

/*Media Queries*/
/*For Large Screens(above 1500px)*/
@media screen and (min-width: 1920px){
    .landing_pg_vector{
        height: 525px;
        width: 658px;
        margin-left: 39vw;
        margin-top: -9vw;
    }
    .jkj-tagline{
        margin-left: -29vw;
    }
    .jkj_pic{
        margin-top: 15vw;
    }
}

@media screen and (min-width: 1680px){
    .jkj-tagline{
        margin-left: -32vw;
    }
    .jkj_pic{
        margin-top: 15vw;
    }
    .landing_pg_vector{
        margin-top: -12vw;
    }
}

@media screen and (min-width: 1600px){
    .jkj-tagline{
        margin-left: -34vw;
    }
    .landing_pg_vector{
        margin-top: -14vw;
    }
    .jkj_pic{
        margin-top: 14vw;
    }
}
</style>

