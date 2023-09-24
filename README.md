# PORTFOLIO
MIT X-PRO FIRST WEBSITE
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->

  
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
  
<link href ="C:\Users\nbant\OneDrive\Desktop\index.html\WEBSITE MIT\BOOTSTRAP FOLDER\popper\popper.min.js"/>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

<style>
  .color-css {
    background-color: rgb(5, 71, 5);
  }
  .header1 {
    width: 100%;
    height: auto;
    background-image:  linear-gradient(to right, rgb(57, 135, 204), rgba(16, 16, 17, 0));
    background-repeat: no-repeat, no-repeat, no-repeat;
    background-position:
    bottom right,
    left,
    right;

  }
  .project {
    border-radius: 50%;
  }
  .dropdown-submenu {
    position: relative;
  }
  
  .dropdown-submenu .dropdown-menu {
    top: 0;
    left: 100%;
    margin-top: -1px;
  }
  .navbar-css {
    background: url ("./images/NY city.jpg")
  }
  .ul-css {
    padding: 10px;
    background: rgb(12, 1, 1);
    border: 8px solid rgb(83, 81, 81)
  }
  .ul-css1 {
    padding: 10px;
    background: rgb(95, 200, 8);
    border: 8px solid rgb(83, 81, 81)
  }
  
  .navbtn-css {
    background: rgb(109, 10, 86);
    border: 2px solid rgb(158, 154, 154);
    color: rgb(181, 246, 248);
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: medium;
  }
  .aboutbtn {
    background: rgb(59, 105, 41);
    border: 2px solid rgb(125, 177, 91);
    color: rgb(241, 241, 192);
    font-family: sans-serif;
  }
  .aboutbtn:hover{
    color: white;
  }
  .aboutcont {
    background:rgb(227, 165, 233);
    border-radius: 0 50px 0 50px;
  }
  .aboutbody {
    background:rgb(78, 67, 2);
    border-radius: 0 50px 0 50px;
    color:  rgb(245, 220, 220);
  }

  .heading1 {
    font-size: 50px;
    text-align: right;
    text-shadow: 1px 1px 3px black, 2px 2px 5px darkblue;
    color: rgb(7, 7, 151);
  }
  .heading2 { 
    font-size: 30px;
    text-align: right;
    color:rgb(236, 74, 201);
  }
  .contactbody {
    background: rgb(238, 176, 176);
    border: 2px solid rgb(12, 1, 1);
    border-radius: 50px 25px;
    color: rgb(7, 7, 151);

  }

  
/*css animation -css*/
 
.ball1 {
  background-color: rebeccapurple;
  border-radius: 50%;
  width: 100px;
  height: 100px;
  font-size: 30px;
  color: white;
  text-align: center;
  position: relative;
  animation: move1;
  animation-duration: 2s;
  animation-direction: alternate;
  animation-iteration-count:infinite;
}
 
.ball2 {
  background-color: rgb(153, 51, 110);
  border-radius: 50%;
  width: 100px;
  height: 100px;
  position: relative;
  animation: move2;
  animation-duration: 2s;
  animation-direction: alternate;
  animation-iteration-count:infinite;
}
.ball3 {
  background-color: rgb(92, 114, 45);
  border-radius: 50%;
  width: 100px;
  height: 100px;
  position: relative;
  animation: move3;
  animation-duration: 2s;
  animation-direction: alternate;
  animation-iteration-count:infinite;
  transform: rotate(-45deg);
}

.ball4 {
   
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-color:rgb(6, 20, 91);
  position: relative;
  animation-name: test;
  animation-duration: 4s;
  animation-iteration-count:infinite;
}

@keyframes test {
  0%   {background-color:rgb(6, 20, 91); left:0px; top:0px;}
  12.5%  {background-color:rgb(6, 20, 91); left:800px; top:0px;}
  25%  {background-color:rgb(6, 20, 91); left:800px; top:250px;}
  37.5%  {background-color:rgb(6, 20, 91); left:0px; top:250px;}
  50%  {background-color:rgb(6, 20, 91); left:0px; top:500px;}
  62.5% {background-color:rgb(6, 20, 91); left:800px; top:500px;}
  75%   {background-color:rgb(6, 20, 91); left:800px; top:250px;}
  87.5%  {background-color:rgb(6, 20, 91); left:0px; top: 250px;}
  100%  {background-color:rgb(6, 20, 91); left:0px; top:0px;}
  
}

#add {
    animation-composition: add;
}

@keyframes move1 {
  0% {
    transform: translateY(0px);left:0px; top: 0px;
  }
  50% {
    transform: translateY(500px);
    background-color:rgb(14, 137, 123);
  }
  100% {
    transform: translateY(0px);left:0px; top: 0px;
    background-color:rgb(151, 144, 7);
  }
  }

@keyframes move2 {
  0% {
    transform: translateX(0px);left:0px; top: 50px;
    background-color:rgb(196, 91, 214);
  }
 
  100% {
    transform: translateX(750px);
    background-color:rgb(132, 234, 129);
  }
}
@keyframes move3 {
  0% {
    transform: translateX(0px);left:0px; top: 0px;
    background-color:rgb(230, 31, 107);
  }
  
  100% {
  transform: translateY(640px) ;
  background-color:rgb(24, 174, 215);
  }
}
.ball_css {
  text-align : center;
  font-size: 50px;
  font-family:Verdana, Geneva, Tahoma, sans-serif;
  margin: 200px;
  
}


/*css animation -css end*/
</style>
 
    <title>Nageshwer  Blog</title>
  </head>
  <body>
    <div class = "col-11">
      <h1 class="heading1">Github Portfolio</h1>
        <h2 class = "heading2">Nageshwer Rao Bantu</h2>
    </div>
      <div class="text-bg-info p-1"></div>
        <div class="text-bg-primary p-3"></div>
          <div class="text-bg-info p-1"></div>

<!--Navbar-->
  <div class= "container-fluid">
    <nav class="navbar navbar-expand-lg bg-cover header1 ">
      <a class="navbar-brand-centered" href="#"><img src ="/nageshimg7.png" alt= "nagesh" width = "400"/></a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

      <div class="collapse navbar-collapse " id="navbarNavDropdown">
        <ul class="navbar-nav">

          <li class="nav-item">
            <a class="nav-link active  " aria-current="page" href="#Home">
              <button type="button" class="btn  btn-lg navbtn-css">Home</button>
            </a>            
          </li>

          <li class="nav-item">
            <a class="nav-link active" href="#Bootstrapcss">
              <button type="button" class="btn  btn-lg navbtn-css">Bootstrapcss</button>
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#YOUTUBE VIDEO">
              <button type="button" class="btn  btn-lg navbtn-css">YOUTUBE</button>
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#CSS ANIMATIONS">
              <button type="button" class="btn  btn-lg navbtn-css">CSS Animations</button>
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#About Me">
            <button type="button" class="btn  btn-lg navbtn-css">About Me</button></a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#Contact Me">
              <button type="button" class="btn btn-lg navbtn-css">Contact Me</button>
            </a>
          </li>
         
        </ul>
      </div>
    
<!-- navbar  end -->
<!-- multiple dropdown -->
<div class="container">
    <div class="dropdown">
      <button class="btn bg-danger project rounded-circle w-40 h-20  p-5 mt-5 mb-5 fs-1 dropdown-toggle" type="button" data-toggle="dropdown">Projects
      </button>
      <ul class="dropdown-menu">

        <li class = "dropdown-submenu"><a class = "test" tabindex="-1" href="#">EYE EXERCISE<span class="caret"></span></a>
            <ul class="dropdown-menu">
                <li><a tabindex="-1" href="https://github.com/miryalguda/EYE-EXERCISE/blob/main/eye.css">Eye Exercise CSS</a></li>
                <li><a tabindex="-1" href="https://github.com/miryalguda/EYE-EXERCISE/blob/main/eye.html">Eye Exercise HTML</a></li>
                <li><a tabindex="-1" href="https://github.com/miryalguda/EYE-EXERCISE/blob/main/eye1.js">Eye Exercise JS</a></li>            
            </ul>         
        </li>

        <li class = "dropdown-submenu"><a class = "test" tabindex="-1" href="#" >PAC MEN<span class="caret"></span></a>
            <ul class="dropdown-menu">
                <li><a tabindex="-1" href="https://github.com/miryalguda/PACMEN">PAC MEN CSS</a></li>
                <li><a tabindex="-1" href="https://github.com/miryalguda/PACMEN/blob/main/pacmen.html">PAC MEN HTML</a></li>
                <li><a tabindex="-1" href="https://github.com/miryalguda/PACMEN/blob/main/pacmen.js">PAC MEN JS</a></li>            
            </ul>       
        </li>

        <li class = "dropdown-submenu"><a class = "test" tabindex="-1" href="#" >MAP DIRECTION<span class="caret"></span></a>
            <ul class="dropdown-menu">
                <li><a tabindex="-1" href="https://github.com/miryalguda/MAP-DIRECTION/blob/main/mapdirection2.css">MAP DIRECTION CSS</a></li>
                <li><a tabindex="-1" href="https://github.com/miryalguda/MAP-DIRECTION/blob/main/mapdirection2.html">MAP DIRECTION HTML</a></li>
                <li><a tabindex="-1" href="https://github.com/miryalguda/MAP-DIRECTION/blob/main/mapdirection2.js">MAP DIRECTION JS</a></li>            
            </ul>       
        </li>

        <li class="dropdown-submenu"><a class="test" tabindex="-1" href="#">MAP ANIMATION<span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a tabindex="-1" href="https://github.com/miryalguda/REALTIME-BUS-TRACKER/blob/main/mapboxstyle.css">MAP ANIMATION CSS</a></li>
            <li><a tabindex="-1" href="https://github.com/miryalguda/REALTIME-BUS-TRACKER/blob/main/mapboxstyle.html">MAP ANIMATION HTML</a></li>
            <li><a tabindex="-1" href="https://github.com/miryalguda/REALTIME-BUS-TRACKER/blob/main/mapboxstyle.js">MAP ANIMATION JS</a></li>            
          </ul>
        </li>

      </ul>
    </div>
</div>
  
<!-- multiple dropdown -->
</nav>
<!--Navbar  closed-->

<!--colorband-->

<div>
  <div class="text-bg-info p-1"></div>
  <div class="text-bg-primary p-3"></div>
  <div class="text-bg-info p-1"></div>
</div>
  <!-- colorbank end -->
<div>
    <ul class ="ul-css"></ul>
</div>
  <div class="text-bg p-3"></div>

  <!-- carousel -->  

<div class =   "container">
<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">

    <div class="carousel-item active">
      <img src="/eye-sm.jpg" class="d-block w-80 h-60" alt="eye">
    </div>
    
    <div class="carousel-item">
      <img src="/pacmen-sm.jpg" class="d-block w-80 h-60" alt="pac men">
    </div>

    <div class="carousel-item">
      <img src="/mapdirection-sm.jpg" class="d-block w-80 h-60" alt="mapdirection">
    </div>
  </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
</div>
</div>
<!-- carouse  closed -->
<!-- color band -->
<div>
  <div class = "p-5 mt-5 mb-5"></div>
  <div class ="ul-css  "></div><p id="YOUTUBE VIDEO"></p>
  <div class = "p-5 mt-5 mb-5"></div>
</div>
<!-- color band end-->

<!-- youtube video -->
<div class="container p-5 mt-5 mb-5 text-center">
  <h1 >YOUTUBE VIDEO</h1>
    <div>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/bNSaTvrHSZI?si=mV2vAGeJhUuwqzt8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
</div>

<!-- youtueb video -->
<!-- color band -->
<div>
  <div class = "p-5 mt-5 mb-5"></div>
  <div class ="ul-css  "></div><p id="CSS ANIMATIONS"></p>
  <div class = "p-5 mt-5 mb-5"></div>
</div>
<!-- color band end-->


<!-- css animations -->
<div class="container p-5 mt-5 mb-5" style= "background-color: rgb(152, 152, 243);border: 2px solid rgb(232, 150, 150); width: 900px; height: 600px; position:relative;">
 
  <div class="ball4" style= "position: absolute"></div>
    <div class="ball3"  id = "add" style=" position: absolute;"></div>
      <div class="ball1" style="position: absolute;"></div>
        <div class="ball2" style= "position: absolute"></div>
          <div class="ball_css">CSS ANIMATIONS</div>
</div>

<!-- css  animations end -->
<!-- color band -->
<div>
  <div class = "p-5 mt-5 mb-5"></div>
  <div class ="ul-css  "></div><p id="About Me"></p>
  <div class = "p-5 mt-5 mb-5"></div>
  
</div>
<!-- color band end-->

<!-- About me -->


<div class="container aboutcont">
  <h1  class = "text-center p-5 mt-5 mb-5 fs-1">About Me</h1>
<div class = "w-100 aboutbody p-5 mb-5 mt-5 text-center fs-1">
  <p>  Hi, I am Nageshwer Rao Bantu, living in Massachusetts.</p>

  <p>  Started  my career with chemistry and obtained Ph.D in organi chemistryin 1986.  Did a post doctoral  fellowship at columbia University (1987-89).  puiblished  several publications in internationals chemistry journals.  worked  for IBM and Olin Microelectronic Materials.   After  9 years, explored  my own business and ran for 20+  years.  slowly got interested  in programming and joined in software  engineering course  offered  by MIT X-pro.   Currently enjoying the course and hereby presented some of the coding work during this course.  Hope You like it.</p>

  <p>  My linkedin : https://www.linkedin.com/in/nageshwer-bantu-b34a0825b/</p>
  <p>  Github : https://github.com/miryalguda/nagesh.github.io</p>
    
   
  <p>Thanks for watching my webpage. </p>
 <a href="mailto: nbantu2011@gmail.com">
  <button type="button" class="btn aboutbtn  btn-lg ">Contact me</button>
 </a>
</div>
</div>
<!-- About me end -->

<!-- color band -->
<div>
  <div class = "p-5 mt-5 mb-5"></div>
  <div class ="ul-css  "></div>
  <div class = "p-5 mt-5 mb-5"></div>
</div>
<!-- color band end-->


<!-- contact me-->
<div class="container">
  <p id = "Contact Me"></p>

  <div class = "has-bg-img">
    <div class=" bg-img bg-cover p-5 mt-5 mb-5" style="background-image: url('/forest960.jpg'); height : auto; width : 100%; color: white; border-radius: 20px;">
      <div class = " p-5 mb-5 mt-5 text-center ">
        <h1 >Contact Me</h1>
        <div class= "contactbody p-5 mt-5 mb-5">
          <p>If  you need  any assistance in web devement project, please  contact  me</p>
        </div>
            <button type="button" class="btn navbtn-css btn-lg">Email </button>
      </div>
    </div>
  </div>
</div>
<!-- contact me end-->



<!-- Main container end -->


<footer class ="bg-dark mt-5 mb-5 p-5 text-white text-center">
  <p>&copy; New web site</p>
  <p><a href="mailto: nbantu2011@gmail.com" class="text-white">Email Us </a></p>
</footer>


</div>
<!-- Main container end -->


  
    <!-- multiple dropdown js -->
    <script>
        $(document).ready(function(){
          $('.dropdown-submenu a.test').on("click", function(e){
            $(this).next('ul').toggle();
            e.stopPropagation();
            e.preventDefault();
          });
        });
    </script>
    <!-- multiple dropdown js end -->
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
  
  

  </body>
</html>
