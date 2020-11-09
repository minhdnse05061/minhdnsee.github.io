<!DOCTYPE html>
<html lang="en">    <!-- Engligh language, en stands for engligh--> 
<head>
  
<title>webpage 1</title></time>
<meta charset="utf-8">


<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Popper JS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</head>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>

.body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}
  /* Make the image fully responsive */
  .carousel-inner img {
    width: 100%;
    height: 100%;
  }

  #more {display: none;}

  html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}

  </style>

  <!-- iNSERT THE JAVASCRIPT CODE HERE -->
  <script>
    function myFunction() {
  var dots = document.getElementById("dots");
  var moreText = document.getElementById("more");
  var btnText = document.getElementById("myBtn");

  if (dots.style.display === "none") {
    dots.style.display = "inline";
    btnText.innerHTML = "Read more";
    moreText.style.display = "none";
  } else {
    dots.style.display = "none";
    btnText.innerHTML = "Read less";
    moreText.style.display = "inline";
  }
}
  </script>
</head>


<body style="height:1500px">

<nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top">
  <a class="navbar-brand" href="#">Ferroli</a>
  <ul class="navbar-nav ml-auto">
    <li class="nav-item">
      <a class="nav-link" href="code2.html">Home</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="About us.html">About us</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="gallery.html">Gallery</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="contact.html">Contact</a>
    </li>
    </ul>
    <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <form class="form-inline" action="/action_page.php">
    <input class="form-control mr-sm-2" type="text" placeholder="Search">
    <button class="btn btn-success" type="submit">Search</button>
  </form>
</nav>
</nav>
<div class="container-fluid" style="margin-top:80px">
 </div>

<div id="demo" class="carousel slide" data-ride="carousel">
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
  </ul>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="C:/Users/Admin/Desktop/ass/Images/bg.jpg" alt="Los Angeles" width="1550" height="650">
      <div class="carousel-caption">
        <h2>LUXURY</h2>
        <h3>Elegant and Luxurious!</h3>
      </div>   
    </div>
    <div class="carousel-item">
      <img src="C:/Users/Admin/Desktop/ass/Images/bg2.jpg" alt="Los Angeles" width="1550" height="650">
      <div class="carousel-caption">
        <h2>COMFORTABLE</h2>
        <h3>Happy Movement!</h3>
      </div>   
    </div>
    <div class="carousel-item">
     <img src="C:/Users/Admin/Desktop/ass/Images/bg3.jpg" alt="Los Angeles" width="1550" height="650">
      <div class="carousel-caption">
        <h2>LUCKY</h2>
        <h3>Make you Lucky</h3>
      </div>   
    </div>
  </div>
  <a class="carousel-control-prev" href="#demo" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#demo" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div>


<section>
  <div class="container">
    <h1 class="text-center pt-5">ABOUT US</h1>
		<hr class="w-100 pt-5">
		<div class="row">
			<div class="col">
        <img src="C:/Users/Admin/Desktop/ass/Images/h1.jpg" width="500" height="500">
			</div>
			<div class="col">
			  <h2>FERROLI VIETNAM</h2>
				<br>
				<p>FERROLI VIETNAM Ferroli Asean Co., Ltd., part of the Ferroli Group, is an 100-percent foreign-owned Italian enterprise which specializes in thermal equipment including electric water heaters, solar water heaters, heatpumps etc.</p>
				<p>Ferroli Asean began with its first 2,300m2 assembling and manufacturing factory in Tu Liem, Hanoi in 2005. In 2008, due to Ferroli group investment restructuring strategies for the China and South East Asia markets, Ferroli Indochina Co., Ltd. was officially established. Ferroli located its factory in Thach That industrial park, Quoc Oai, Hanoi with an area of 10,000m2
				<p>Ferroli Indochina has always been given great support in the areas of technology, product development, and staff training by the Group.</p>
				<p><span id="dots">...</span><span id="more"> Ferroli is very proud to be partner to numerous large construction projects, including luxurious and high quality hotels, resorts in Vietnam such as Crowne Plaza, The manor, and The Garden mall in Hanoi; Hoa Binh Skyscraper, Saigon Pearl in Ho Chi Minh City; Son Tra Resort and the Spa in Da Nang. </span></p> <br>
				
				<button onclick="myFunction()" id="myBtn">Read more</button>			
			</div>	
		</div>	
</section>
<style>

.footer {
  position: fixed;    
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: black;
  color: white;
  text-align: center;
}


.fa {
  padding: 5px;
  font-size: 10px;
  width: 30px;
  text-align: center;
  text-decoration: none;
  margin: 1px 1px;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}

.fa-google {
  background: #dd4b39;
  color: white;
}


.fa-youtube {
  background: #bb0000;
  color: white;
}

.fa-instagram {
  background: #125688;
  color: white;
}

</style>
<div class="footer">
  <br>
<!-- Add font awesome icons -->
<a href="https://www.facebook.com" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="https://www.google.com" class="fa fa-google"></a>
<a href="https://www.youtube.com" class="fa fa-youtube"></a>
<a href="https://www.instagram.com" class="fa fa-instagram"></a>

  
  <p class="pt-2"> copyright 2020 </p>

</div>

</body>



</html>
