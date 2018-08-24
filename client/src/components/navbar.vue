<template>
    <div class=jkj-navbar>
    <nav class="navbar navbar-expand-lg navbar-light">
    <a class="navbar-brand" href="#" style="color: #fff;">JKJ</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
        <li class="nav-item active">
            <a class="nav-link jkj-home-btn" href="#" style="color: #fff;" @click="selectedComponent='home'">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
            <a class="nav-link abtme-link" href="#" style="color: #fff;" @click="selectedComponent='aboutme'">About Me</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#" style="color: #fff;" @click="selectedComponent='accomp'">Accomplishments</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#" style="color: #fff;" @click="selectedComponent='projects'">Projects</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#" style="color: #fff;">Contact</a>
        </li>
        
    </ul>
  </div>
</nav>
    <keep-alive>
        <component :is="selectedComponent">

        </component>
        </keep-alive>
    </div>
</template>

<script>
    import home from './home.vue'
    import aboutme from './aboutme.vue'
    import accomp from './accomp.vue'
    import projects from './projects.vue'
    export default{
      data: function () {
        return {
          selectedComponent: 'home'
        }
      },
      components: {
        home: home,
        aboutme: aboutme,
        accomp: accomp,
        projects: projects
      }
    }
</script>
<style>
.jkj-home-btn{
    margin-left: 55vw;
}
.navbar{
    background-color: #251e3e;
    color: #fff;
}
.nav-item{
    margin-right: 1vw;
    font-family: 'Sunflower', sans-serif;
    color: #fff;
}
.nav-link{
    color: #fff;
}
.navbar-brand{
    font-family: 'Monoton', cursive;
    font-size: 1.8em;
}
.abtme-link{
    width: 85px;
}
@media screen and (max-width: 992px){
    .jkj-home-btn{
        margin-left: 0vw;
    }
}
</style>
