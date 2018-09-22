<template>
    <div class=jkj-navbar>
        <!-- Modal -->
<div id="myModal" class="modal fade" role="dialog">
  <div class="modal-dialog">

<!-- Modal content-->
<div class="modal-content">
<div class="modal-header">
<button type="button" class="close" data-dismiss="modal">×</button>
<h4 class="modal-title">Contact Me</h4>
</div>
<div class="modal-body">

        <form role="form" method="post" id="reused_form" >
        <p>
            For projects & further enquiries, kindly fill this form to contact me.
        </p>

        <div class="form-group">
            <label for="name">
                Name:</label>
            <input type="text" class="form-control"
            id="name" name="name"   required maxlength="50">

        </div>
        <div class="form-group">
            <label for="email">
                Email:</label>
            <input type="email" class="form-control"
            id="email" name="email" required maxlength="50">
        </div>
        <div class="form-group">
            <label for="name">
                Message:</label>
            <textarea class="form-control" type="textarea" name="message"
            id="message" placeholder="Your Message Here"
            maxlength="6000" rows="7"></textarea>
        </div>





        <button type="submit" class="btn btn-lg btn-success btn-block" id="btnContactUs">Send <i class="fas fa-paper-plane"></i></button>

    </form>
    <div id="success_message" style="width:100%; height:100%; display:none; ">
        <h3>Sent your message successfully!</h3>
    </div>
    <div id="error_message"
    style="width:100%; height:100%; display:none; ">
        <h3>Error</h3>
        Sorry there was an error sending your form.

    </div>
</div>

</div>

 </div>
</div>
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
            <a class="nav-link" href="#" style="color: #fff;" data-toggle="modal" data-target="#myModal">Contact</a>
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
.jkj-navbar{
    height: 100vh;
}
@media screen and (max-width: 992px){
    .jkj-home-btn{
        margin-left: 0vw;
    }
}
</style>
