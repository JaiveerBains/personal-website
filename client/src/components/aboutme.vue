<template>
    <div class="jkj-abtme-section">
        <div class="container">
            <div class="row">
                <h2 class="jkj-abtme-header animated rotateInDownRight">Welcome to My Page!</h2>
            </div>
            <div class="row">
                <p class="jkj-abtme-desc animated fadeInUp">
                    Hey, I am James Kaviyil Jose, currently a student pursuing B.Tech in CSE. <br> 
                    I am very passionate coder who likes to code all day long. <br>
                    Right now, I specialize in Front-End Web Development using VueJS. <br>
                    Other Programming Languages known are: <br>
                    <ul class="jkj-skillset">
                        <li>Python</li>
                        <li>C++</li>
                        <li>C</li>
                        <li>Javascript</li>
                        <li>HTML, CSS, JS</li>
                    </ul>
                    I am currently looking for Web Development Projects (FrontEnd). <br>
                    If any, please do contact me by clicking the button below.
                </p>
            </div>
            <div class="row contact-me-btn animated fadeInUp">
                <a class="jkj-contact-link" href="#"> &nbsp Contact Me </a>
            </div>
            <div class="abtme-img">
                <img src="../assets/aboutus.svg" alt="About Me SVG" class="abtme-svg">
            </div>
        </div>
    </div>
</template>

<style>
.jkj-abtme-header{
    font-family: 'Amaranth', sans-serif;
    margin-top: 10vw;
    color: #fff;
}
.jkj-abtme-desc{
    font-family: 'Enriqueta', sans-serif;
    color: #fff;
}
.contact-me-btn{
    height: 50px;
}
.jkj-abtme-section{
    background-color: #251e3e;
    height: 700px;
}
.jkj-contact-link{
    background-color: #651e3e;
    width: 104px;
    height: 30px;
    border-radius: 21px;
    color: #fff;
}
.jkj-contact-link:hover{
    cursor: pointer;
    background-color: #851e3e;
    color: #fff;
    text-decoration: none;
}
.abtme-svg{
    height: 500px;
    width: 500px;
    margin-left: 40vw;
    margin-top: -30vw;
}
</style>

