<!DOCTYPE html>
<title>Tutoring 4U</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif}
.w3-bar,h1,button {font-family: "Montserrat", sans-serif}
.fa-anchor,.fa-coffee {font-size:200px}
</style>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-black w3-card w3-left-align w3-large">
    <a class="w3-bar-item w3-button w3-hide-medium w3-hide-large w3-right w3-padding-large w3-hover-gre w3-large w3-white" href="javascript:void(0);" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large w3-white">Home</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Subjects</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Scheduling</a>
    <a href="#" class="w3-bar-item w3-button w3-hide-small w3-padding-large w3-hover-white">Pricing</a>
  </div>

  <!-- Navbar on small screens -->
  <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium w3-large">
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Subjects</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Scheduling</a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Pricing</a>
  </div>
</div>

<!-- Header -->
<header class="w3-container w3-light-grey w3-center" style="padding:128px 16px">
  <h1 class="w3-margin w3-jumbo">Welcome to Tutoring 4U</h1>
  <p class="w3-xlarge">Founded in 2021</p>
  <button class="w3-button w3-black w3-padding-large w3-large w3-margin-top"><a href="#">Get Started</a></button>
</header>

<!-- First Grid -->
<div class="w3-row-padding w3-padding-64 w3-container">
  <div class="w3-content">
    <div class="w3-twothird">
      <h1>About</h1>
      <h5 class="w3-padding-32">Who Are We?</h5>

      <p class="w3-text-grey" style="text-align:center;">We are a tutoring service that's sole goal is to improve the quality of education your child receives. Kids of all ages experience difficulty in school either because they are not attended to individually by their teachers or can't learn effectively through the school methods. Our tutoring program solves most if not all of these problems. We have developed a method of teaching that can be applied to any student. It combines Chinese, Finnish, and American teaching styles into one that has seen great success amongst those who have previously struggled in school. Our team comprises high school students, college students, and teachers all over the United States who have been trained on how to use our developed teaching strategy. So far, we have seen great results. Students who were C Students coming into High School were enrolled in our program, and by the time they applied to college, they had GPAs ranging from 3.5-4.0. We have any course you can imagine that can help your child succeed. We only want the best for our students as they will be the future; therefore, we must develop them in the best way possible to ensure that they bring positive values to the world in the future. </p>
    </div>

    <div class="w3-third w3-center">
      <img src="https://www.careeraddict.com/uploads/article/58346/illustration-man-tutoring-woman-computer.jpg" width="300" height="200">
    </div>
  </div>
</div>

<!-- Second Grid -->
<div class="w3-row-padding w3-light-grey w3-padding-64 w3-container">
  <div class="w3-content">
    <div class="w3-third w3-left w3-padding-64">
      <img src="https://mlqmtwka8c9g.i.optimole.com/gOh5_1g.Ga1T~1cfa5/w:764/h:321/q:75/https://www.competethemes.com/wp-content/uploads/2016/01/add-contact-form.png" width="400" height="200">
    </div>
    <br>

    <div class="w3-twothird">
      <h1 style="text-align:center; ">Contact Us</h1>

      <p style="text-align:center; ">
                    <button class="btn btn-sm btn-info disabled btn-block">
                        <span class="glyphicon glyphicon-envelope"></span>
                        Email Us: 
                    </button>
                    tutoring4u@gmail.com</p>
                <p style="text-align:center; "> 
                    <button class="btn btn-sm btn-info disabled btn-block">
                        <span class="glyphicon glyphicon-home"></span>
                        Mail Us: 
                    </button>
                    7714 Poor House Lane
                    <br>
                             Bakersfield, CA 93306
                </p>
                <p style="text-align:center; ">
                    <button class="btn btn-sm btn-info disabled btn-block">
                        <span class="glyphicon glyphicon-thumbs-up"></span>
                        Find Us:
                    </button>
                    
                    @tutoring4U
                </p>
                <p style="text-align:center; ">
                    <button class="btn btn-sm btn-info disabled btn-block">
                        <span class="glyphicon glyphicon-earphone"></span>
                        Call Ue:
                    </button>
                     +1 (800) - tutor4u
                </p>
    </div>
  </div>
</div>

<div class="w3-container w3-black w3-center w3-opacity w3-padding-64">
    <h1 class="w3-margin w3-xlarge">Tutoring 4U</h1>
</div>



<script>
// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}
</script>

</body>
</html>
