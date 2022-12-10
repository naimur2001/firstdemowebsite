body{
  background: linear-gradient(
    #c6ffdd
    ,
    #fbd786
    ,
    #f7797d);
    height: 1500px;
}

.navbar{
margin-top: -8px;
height: 70px;

display: block;
z-index: 1;
}


.nav1{
  margin-top: -5px;
  margin-right: 8px;
  margin-left: 8px;
  background-color: rgb(3, 90, 90);
  color: white;
  border-radius: 8px;
  z-index: 1;
}

.d-flex {
margin-top: 12px;
display: block;
z-index: 1;

}
.form {
    display: block;
    width: 100%;
    padding: 0.375rem 0.75rem;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border-radius: 0.375rem;
    transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
    outline-style:double;
    z-index: 1;
}
.dropdown-menu{
  background: linear-gradient(to bottom, #33ccff 0%, #ffcc00 100%);
z-index: 1;
}
.row{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  margin-top: 20px;
  margin-right: 10px;
  margin-left: 25px;
}
.card{
transition: transform 0.5s;
background: rgba(255, 255, 255, 0.1);
}
.card:hover{
  box-shadow: 0 0 5px 6px rgba(0,0,0,0.15);
  transform: scale(1.005);
}
.ct{
  font-weight: bold;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  cursor: pointer;
  color: black;
}
.card-img-top{
  height: 150px;
  cursor: pointer;
}
.bl{
  font-size: 20px;
  font-family: Arial;
  font-weight: bold;
}

.dt{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  position: relative;
  top: -8;
  font-size: 100px;

}
.dt .dot{
  margin-right: 40px;
  margin-left: 40px;
  opacity: 0.40;
  cursor: pointer;
  transition: transform .5s;
}
.dot:hover{
  transform: scale(1.5);
  color: #f7797d;
}
.box{
  display: flex;
  justify-content: center;
  align-items: center;
}
.box2{
  height: 6rem;
  width: 9rem;
  background-color: rgba(218, 229, 239, 0.3);
  border-radius: 8px;
  display: flex;
  position: relative;
  bottom: 170;
  right: -930;
  border:1px solid rgba(0, 0, 0,0.1);
  cursor: pointer;
}
.box2 p{
  display: flex;
  justify-content: center;
  align-items: center;
  color: #000000;
  z-index: 1;
  position: relative;
  left: 50;
  top: 10;
  opacity:0;
  cursor: pointer;
  transition: opacity .5s;
}
.box2 p:hover{
opacity: 1;
}
.feature{
  height: 22rem;
  width: 55rem;
  background-color: rgba(218, 229, 239, 0.3);
  border:1px solid rgba(0, 0, 0,0.1);
  color: #000000;
  position: relative;
  border-radius: 8px;

}
.feature-content{
 display: inline-block;
  position: relative;
  top: 15;
  left: 50;
  z-index: 1;
  font-size: 16px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
@media screen and (max-width:500px) {

  .dt{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    position: relative;
    top: -8;
    left: 30;
    font-size: 50px;

  }
  .dt .dot{
    margin-right: 40px;
    margin-left: 40px;
    opacity: 0.40;
    cursor: pointer;
    transition: transform .5s;
  }



  .feature{
    height: 20rem;
  width: 100rem;
    background-color: rgba(218, 229, 239, 0.3);
    border:1px solid rgba(0, 0, 0,0.1);
    color: #000000;
    position: relative;
    border-radius: 8px;
    left: -40;
  }
  .feature-content{
   display: inline-block;
    position: relative;
    top: 25;
    left: 10;
    z-index: 1;
    height: -10rem;
    width: 20rem;
    font-size: 8px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    overflow: hidden;
    padding: 2px;
  }
  .box2{
    height: 3rem;
    width: 150rem;
    background-color: rgba(218, 229, 239, 0.3);
    border-radius: 8px;
    display: flex;
    position: relative;
    top: -155;
    right: -310;
    border:1px solid rgba(0, 0, 0,0.1);
    cursor: pointer;
  }
  .box2 p{
    display: flex;
    justify-content: center;
    align-items: center;
    color: #000000;
    z-index: 1;
    position: relative;
    left: 20;
    top: 10;
    font-size: 10px;
    opacity:0;
    cursor: pointer;
    transition: opacity .5s;
  }
  .box2 p:hover{
  opacity: 1;
  }
}

.s-l-form{
  position: absolute;
  max-width: 55rem;
  height: 28rem;
  /* background-color: #000000; */
  top: 58rem;
  left: 16.5rem;
  border-radius: 0.5rem;

}
.myRightCtn{
  position: relative;
  right: 25;
  background-image: linear-gradient(45deg,#f046ff,#9b00e8);
  border-radius: 1rem;
  height: 26rem;
  width: 26rem;
 color: white;
 font-size: 12px;
 display: flex;
 justify-content: center;
 align-items: center;
}
.myleftCtn{
  position: relative;
  right: 25;
  background-image: linear-gradient(45deg,#ffffff,#ff1673);
  border-radius: 1rem;
  height: 26rem;
  width: 26rem;
 color: white;
 font-size: 12px;
 display: flex;
 justify-content: center;
 align-items: center;
}
.myForm header{
  font-family: Arial;
  font-weight: bold;
  font-size: 18px;
  color: #000000;
  position: relative;
  bottom: 70;

}
.myForm2 header{
  font-family: Arial;
  font-weight: bold;
  font-size: 18px;
  color: #ffffff;
  position: relative;
  bottom: 70;

}

.myForm2 a{
  color: #000000;
  font-size: 15px;
}
 198  
indeximage.html
@@ -0,0 +1,198 @@
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>educative</title>
  <link 
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" 
  rel="stylesheet" 
  integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" 
  crossorigin="anonymous">
  <link rel="stylesheet" href="indeximage.css">
</head>
<body>
  <!-- <div class="container">
    <div style="width: 40%; border: 5px red solid;"> 
    <img src="https://mdbootstrap.com/img/logo/mdb192x192.webp" class="img-fluid" alt="">
  </div>
  <h1 class="my-5">
    Thumbnail
  </h1>
  <img src="https://i.picsum.photos/id/0/5000/3333.jpg?hmac=_j6ghY5fCfSD6tvtcV74zXivkJSPIfR9B8w34XeQmvU" 
  alt="" class="img-thumbnail w-25">
  </div> -->
  <nav class="navbar  navbar-expand-lg  bg-dark">
    <div class="container-fluid nav10 ">
      <!-- <a class="navbar-brand" href="#">Navbar</a> -->
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse nav100" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link  nav1" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link nav1" href="#">Career</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle nav1" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Courses
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">English</a></li>
              <li><a class="dropdown-item" href="#">Mathmetics</a></li>
              <li><a class="dropdown-item" href="#">Bangla</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Physics</a></li>
              <li><a class="dropdown-item" href="#">Chemistry</a></li>
              <li><a class="dropdown-item" href="#">Biology</a></li>
              <li><a class="dropdown-item" href="#">Higher Math</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <!-- <a class="nav-link disabled">Disabled</a> -->
          </li>
          <li class="nav-item">
            <a class="nav-link  nav1" aria-current="page" href="#">Contact</a>
          </li>
        </ul>
        <form class="d-flex " role="search">
          <input class="form me-3 " type="search" placeholder="Search" aria-label="Search" >
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
<div class="row">
  <div class="card" style="width: 18rem;">
    <img src="cardpic.avif" class="card-img-top" alt="...">
    <div class="card-body">
      <p class="card-text ct">Recenet post</p>
      <p class="card-text">Tap in find new<span class="bl">............</span></p>  

        </div>
  </div>
  <div class="card" style="width: 18rem;">
    <img src="annie-spratt-nrzFZ3UBJ9o-unsplash.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <p class="card-text ct">Life Hacks</p>
      <p class="card-text">Explore for your betterness<span class="bl">............</span></p>
    </div>
  </div>
  <div class="card" style="width: 18rem;">
    <img src="andre-benz-lIa03ti94ec-unsplash.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <p class="card-text ct">Volnteer</p>
      <p class="card-text">Join now and go far<span class="bl">............</span></p>   
     </div>
  </div>
  <div class="card" style="width: 18rem;">
    <img src="aditya-chinchure-ZhQCZjr9fHo-unsplash.jpg" class="card-img-top" alt="...">
    <div class="card-body">
      <p class="card-text ct">Entertaintment</p>
      <p class="card-text">Enjoy your life with full of joy <span class="bl">............</span></p>
    </div>
  </div>
</div>
<div class="dt">
  <p class="dot">.</p>
  <p class="dot">.</p>
  <p class="dot">.</p>
</div>
<div class="box">
<div class="box2">
  <p>Feature</p>
</div>

<div class="feature">
  <p class="feature-content">
Lorem Ipsum is simply dummy text of the printing and typesetting industry.<br>
Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,<br>when an unknown printer took a galley of type and scrambled it to make a type specimen book.<br>It has survived not only five centuries,<br> but also the leap into electronic typesetting,<br> remaining essentially unchanged.<br> It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages,<br>
and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
  </p>
</div>
</div>

<div class="formbox">
<div class="s-l-form">
<div class="mycard">
  <div class="row">
    <div class="col-md-6">
      <div class="myLeftCtn">
        <form action="" class="myForm text-center">
          <header>Create New Account</header>
          <div class="form-group">


            <div class="input-group mt-2">
              <span class="input-group-text" id="inputGroupPrepend2">@</span>
              <input type="text" class="form-control" id="validationDefaultUsername" placeholder="Username"  aria-describedby="inputGroupPrepend2" required>
            </div>
          </div>
          <div class="form-group mt-2">
         <i class="fa fa-envelope" ></i>
         <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Email">          </div>
          <div class="form-group mt-2">
            <input type="password" class="form-control" id="inputPassword2" placeholder="Password">
          </div>
          <div class="form-group mt-2">
            <input class="form-check-input " type="checkbox" value="" id="invalidCheck" required>
      <label class="form-check-label" for="invalidCheck">
        Agree to terms and conditions
      </label>
      <div class="invalid-feedback">
        You must agree before submitting.
      </div>
          </div>
            <button class="btn btn-primary mt-2" type="submit">Submit form</button>

        </form>
      </div>
    </div>



    <div class="col-md-6">
      <div class="myRightCtn">
        <form action="" class="myForm2 text-center">
          <header>Log In</header>
          <div class="form-group mt-2">
            <input type="email" id="form2Example1" class="form-control" placeholder="Email" />
          </div>

          <div class="form-group mt-2">
            <input type="password" id="form2Example2" class="form-control" placeholder="Password"/>
          </div>
         <div class="form-group mt-2">
          <input class="form-check-input" type="checkbox" value="" id="form2Example31" checked />
                <label class="form-check-label" for="form2Example31"> Remember me </label>
                <a href="#!">Forgot password?</a>
              </div>

              <button type="button" class="btn btn-primary btn-block mt-2 mb-2">Sign in</button>
              <div class="form-group">
                <div class="text-center">
                  <p>Not a member? <a href="#!">Sign Up</a></p>
                </div>
               </div>

        </form> 
      </div>
    </div>
  </div>
</div>
</div>
</div>

  <script
   src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" 
  integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" 
  crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" 
  integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3" 
  crossorigin="anonymous"></script>

</body>
</html>
