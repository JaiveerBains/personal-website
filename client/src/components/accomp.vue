<template>
    <div class="accomp-section">
        <h1 class="accomp-title animated fadeInRight">Accomplishments across the years....</h1>
        <h3 class="accomp-quote animated fadeInLeft"><i>Every Accomplishment starts with the decision to try....</i></h3>
        <div class="main-timeline animated fadeIn">
    <div class="timeline">
        <a href="#" class="timeline-content">
            <span class="year">August 2018</span>
            <h3 class="title">CEO - Mad.Hacks</h3>
            <p class="description">
                Became the CEO of Mad.Hacks, a Student Developer Community, which is a branch of MadLabs Inc.
            </p>
        </a>
    </div>
    <div class="timeline">
        <a href="#" class="timeline-content">
            <span class="year">June 2018</span>
            <h3 class="title">VueJS Front-End Developer</h3>
            <p class="description">
                Trained for Front-End Web Development using VueJS.
            </p>
        </a>
    </div>
    <div class="timeline">
        <a href="#" class="timeline-content">
            <span class="year">March 2018 - Present</span>
            <h3 class="title">Intern @ MadLabs Inc.</h3>
            <p class="description">
                Started Internship as <b>Front-End Web Developer</b> at MadLabs Inc., a Startup Company at TBI AJCE.
            </p>
        </a>
    </div>
    <div class="timeline">
        <a href="#" class="timeline-content">
            <span class="year">July - December 2017</span>
            <h3 class="title">Workshops Attended</h3>
            <p class="description">
                Attended the following Workshops conducted at AJCE: 
                <ul>
                    <li>Intro. to MS Office</li>
                    <li>IEEE Workshop on Android Development</li>
                    <li>IEEE Workshop on Java</li>
                    <li>Intro. to Linux</li>
                </ul>
            </p>
        </a>
    </div>
    <div class="timeline">
        <a href="#" class="timeline-content">
            <span class="year">June 2017</span>
            <h3 class="title">Joined for B.Tech CSE at AJCE</h3>
            <p class="description">
                Joined Amal Jyothi College of Engg. for B.Tech in Computer Sc. & Engg.
            </p>
        </a>
    </div>
    <div class="timeline">
        <a href="#" class="timeline-content">
            <span class="year">May 2017</span>
            <h3 class="title">Computer Science Topper in Class XII</h3>
            <p class="description">
                I was the Computer Science Topper of my School in the 2017 CBSE Class XII Board Exams.
            </p>
        </a>
    </div>
    <div class="timeline">
        <a href="#" class="timeline-content">
            <span class="year">2016</span>
            <h3 class="title">Red House Boy Captain</h3>
            <p class="description">
                I was given the responsibility of leading the Red House of Indian School Salalah as the Boy Captain for the year 2016-17.
            </p>
        </a>
    </div>
</div>
    </div>
</template>

<style>
.accomp-section{
    background-color: #251e3e;
}
.accomp-title{
    font-family: 'Amaranth', sans-serif;
    text-align: center;
    color: #fff;
    text-decoration-style: dashed;
}
.accomp-quote{
    text-align: center;
    color: #fff;
    font-family: 'Enriqueta', sans-serif;
}
.main-timeline{
    overflow: hidden;
    position: relative;
}
.main-timeline:before{
    content: "";
    width: 10px;
    height: 100%;
    border: 3px solid #959595;
    position: absolute;
    top: 40px;
    left: 50%;
    transform: translateX(-50%);
}
.main-timeline .timeline{
    width: 50%;
    padding: 10px 60px 10px 100px;
    float: right;
    position: relative;
}
.main-timeline .timeline:before{
    content: "";
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: #c47c48;
    border: 5px solid #fff;
    box-shadow: 0 0 1px 5px #c47c48;
    position: absolute;
    top: 42px;
    left: -20px;
}
.main-timeline .timeline-content{
    display: block;
    background: #e9e9e7;
    padding: 70px 30px 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.2) inset;
    position: relative;
}
.main-timeline .timeline-content:hover{ text-decoration: none; }
.main-timeline .year{
    display: block;
    width: 80%;
    height: 50px;
    background: #c47c48;
    padding: 0 0 0 50px;
    font-size: 30px;
    font-weight: 800;
    color: #fff;
    line-height: 50px;
    box-shadow: 0 0 20px rgba(0,0,0,0.4) inset;
    border-radius: 10px 10px 10px 0;
    position: absolute;
    top: 20px;
    left: -20px;
}
.main-timeline .year:before{
    content: "";
    border-top: 40px solid #c47c48;
    border-left: 20px solid transparent;
    border-bottom: 20px solid transparent;
    position: absolute;
    bottom: -60px;
    left: 0;
}
.main-timeline .title{
    font-size: 18px;
    font-weight: 600;
    text-transform: uppercase;
    color: #4a4a4a;
    margin-top: 0.5vw;
}
.main-timeline .description{
    font-size: 14px;
    color: #6f6f6f;
    margin: 0 0 5px 0;
}
.main-timeline .timeline:nth-child(2n){
    padding: 10px 100px 10px 60px;
    text-align: right;
}
.main-timeline .timeline:nth-child(2n):before{
    left: auto;
    right: -20px;
}
.main-timeline .timeline:nth-child(2n) .year{
    padding-right: 50px;
    border-radius: 10px 10px 0 10px;
    left: auto;
    right: -20px;
}
.main-timeline .timeline:nth-child(2n) .year:before{
    border-left: none;
    border-right: 20px solid transparent;
    left: auto;
    right: 0;
}
.main-timeline .timeline:nth-child(2){ margin-top: 140px; }
.main-timeline .timeline:nth-child(odd){ margin: -140px 0 0 0; }
.main-timeline .timeline:nth-child(even){ margin-bottom: 60px; }
.main-timeline .timeline:first-child,
.main-timeline .timeline:last-child:nth-child(even){ margin: 0; }
.main-timeline .timeline:nth-child(2n):before{
    background: #bf3fc8;
    box-shadow: 0 0 1px 5px #bf3fc8;
}
.main-timeline .timeline:nth-child(2n) .year{ background: #bf3fc8; }
.main-timeline .timeline:nth-child(2n) .year:before{ border-top-color: #bf3fc8; }
.main-timeline .timeline:nth-child(3n):before{
    background: #ce3c41;
    box-shadow: 0 0 1px 5px #ce3c41;
}
.main-timeline .timeline:nth-child(3n) .year{ background: #ce3c41; }
.main-timeline .timeline:nth-child(3n) .year:before{ border-top-color: #ce3c41; }
.main-timeline .timeline:nth-child(4n):before{
    background: #8cc43d;
    box-shadow: 0 0 1px 5px #8cc43d;
}
.main-timeline .timeline:nth-child(4n) .year{ background: #8cc43d; }
.main-timeline .timeline:nth-child(4n) .year:before{ border-top-color: #8cc43d; }
@media only screen and (max-width: 990px){
    .main-timeline:before{ top: 8%; }
    .main-timeline .timeline{ padding: 10px 10px 10px 100px; }
    .main-timeline .timeline:nth-child(2n){ padding: 10px 100px 10px 10px; }
}
@media only screen and (max-width: 767px){
    .main-timeline:before{
        width: 8px;
        top: 0;
        left: 12px;
        transform: translateX(0);
    }
    .main-timeline .timeline,
    .main-timeline .timeline:nth-child(even),
    .main-timeline .timeline:nth-child(odd){
        width: 100%;
        float: none;
        text-align: left;
        padding: 0 0 0 60px;
        margin: 0 0 30px 0;
    }
    .main-timeline .timeline:before,
    .main-timeline .timeline:nth-child(2n):before{
        width: 20px;
        height: 20px;
        border: 3px solid #fff;
        top: 38px;
        left: 6px;
    }
    .main-timeline .timeline:nth-child(2n) .year{
        right: auto;
        left: -20px;
        border-radius: 10px 10px 10px 0;
    }
    .main-timeline .timeline:nth-child(2n) .year:before{
        border-left: 20px solid transparent;
        border-bottom: 20px solid transparent;
        border-right: none;
        right: auto;
        left: 0;
    }
}
</style>

