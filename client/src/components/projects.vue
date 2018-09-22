<template>
    <div class="projects-section">
        <h1 class="projects-title animated fadeInLeft">Project Contributions: </h1>
        <h2 class="proj-quote animated fadeInRight"><i>Practical Knowledge is better than bookish knowledge....</i></h2>
        <h1 class="projects-title proj-title animated fadeIn">Course Projects: </h1>
        <div class="card-group">
            <div class="card">
                <div class="card-body text-center jkjcard-one hvr-grow">
                    <img src="../assets/C.png" alt="C++ Symbol" class="proj-icon" href="https://github.com/jamesjose03/Traffic-Fines-System">
                    <a href="https://github.com/jamesjose03/Traffic-Fines-System"><h2 class="proj-name">Traffic Fines Management</h2></a>
                    <p class="card-text">Project done in C++ to Add, Remove & Edit Fines.<br>This was done in Class 12 as part of Course Project.</p>
                </div>
            </div>
            <div class="card">
                <div class="card-body text-center jkjcard-two hvr-grow">
                    <img src="../assets/python.png" alt="Python Symbol" class="proj-icon">
                    <a href="https://github.com/jamesjose03/Maze-Runner-Game-in-Python-Using-the-Pygame-module-"><h2 class="proj-name">Maze Runner- The Game</h2></a>
                    <p class="card-text">Project done in Python using the pygame module.<br> Clone of the Dino Game in Chrome Browser.<br> Done as part of Microproject.</p>
                </div>
            </div>
            <div class="card">
                <div class="card-body text-center jkjcard-three hvr-grow">
                    <img src="../assets/CP.png" alt="C Symbol" class="proj-icon">
                    <a href="https://github.com/jamesjose03/robo-chat"><h2 class="proj-name">RoboChat -<br>  A Chat-Bot Application</h2></a>
                    <p class="card-text">RoboChat is a Chat-Bot which is a personal assistant.<br> It helps store reminders, tell facts, plays music, etc.<br> Done using C programming language as part of Microproject.</p>
                </div>
            </div>
        </div>
        <div class="personal-projects">
            <h1 class="projects-title proj-title">Personal Projects:</h1>
            <div class="card-group">
                <div class="card">
                    <div class="card-body text-center jkjcard-one hvr-grow">
                        <img src="../assets/logo.png" alt="VueJS Symbol" class="proj-icon">
                        <a href="https://github.com/jamesjose03/vue-first-app"><h2 class="proj-name">User Skills App</h2></a>
                        <p class="card-text">A simple webapp to add or remove skills of a user.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body text-center jkjcard-two hvr-grow">
                        <img src="../assets/python.png" alt="Python Symbol" class="proj-icon">
                        <a href="https://github.com/jamesjose03/calculatorGUI"><h2 class="proj-name">Calculator GUI Model</h2></a>
                        <p class="card-text">A Basic Calculator built using tkinter module of Python.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body text-center jkjcard-three hvr-grow">
                        <img src="../assets/logo.png" alt="VueJS Symbol" class="proj-icon">
                        <a href="https://github.com/jamesjose03/monster-slayer-game"><h2 class="proj-name">Monster Slayer Game</h2></a>
                        <p class="card-text">A game developed using VueJS as a part of Online Course Project on Udemy</p>
                    </div>
                </div>
                <div class="card">
                    <div class="card-body text-center jkjcard-one hvr-grow">
                        <img src="../assets/phpmysql.png" alt="PHP-SQL Symbol" class="proj-icon">
                        <a href="https://github.com/jamesjose03/login_system"><h2 class="proj-name">Login System</h2></a>
                        <p class="card-text">Basic Login System using PHP & MySQL.</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="emptysect">
            <p></p>
        </div>
    </div>
</template>

<style>
.projects-section{
    background-color: #251e3e;
    overflow-x: hidden;
    height: 146vh;
}
.emptysect{
    background-color: #251e3e;
}
.proj-quote{
    color: #fff;
    font-family: 'Enriqueta', sans-serif;
    text-align: center;
}
.projects-title{
    text-align: center;
    color: #fff;
    font-family: 'Amaranth', sans-serif;
}
.proj-icon{
    height: 200px;
}
.proj-name{
    color: #fff;
    font-family: 'Amaranth', sans-serif;
}
.proj-title{
    margin-top: 3vw;
    margin-bottom: 2vw;
}
.card{
    border: none;
}
.card-text{
    color: #fff;
    font-family: 'Enriqueta', sans-serif;
}
.jkjcard-one{
    background-color: #451e3e;
}
.jkjcard-two{
    background-color: #651e3e;
}
.jkjcard-three{
    background-color: #851e3e;
}
.hvr-grow {
    display: inline-block;
    vertical-align: middle;
    transform: translateZ(0);
    box-shadow: 0 0 1px rgba(0, 0, 0, 0);
    backface-visibility: hidden;
    -moz-osx-font-smoothing: grayscale;
    transition-duration: 0.3s;
    transition-property: transform;
}

.hvr-grow:hover,
.hvr-grow:focus,
.hvr-grow:active {
    transform: scale(1.1);
    z-index: 1;
    background-color: #051e3e;
}
</style>
