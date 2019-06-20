<h1>employ.im</h1>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
* {
  box-sizing: border-box;
}
body {
  margin: 0;
}
.navbar {
  overflow: hidden;
  background-color: #333;
  font-family: Arial, Helvetica, sans-serif;
}
.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}
.dropdown {
  float: left;
  overflow: hidden;
}
.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font: inherit;
  margin: 0;
}
.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  width: 100%;
  left: 0;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.dropdown-content .header {
  background: red;
  padding: 16px;
  color: white;
}
.dropdown:hover .dropdown-content {
  display: block;
}
/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 10px;
  background-color: #ccc;
  height: 250px;
}
.column a {
  float: none;
  color: black;
  padding: 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}
.column a:hover {
  background-color: #ddd;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    height: auto;
  }
}
</style>
<body>

<div class="navbar">
  <a href="#home">get a job</a>
  <a href="#news">employees</a>
  <div class="dropdown">
    <button class="dropbtn">candidates 
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
      <div class="header">
      </div>   
      <div class="row">
        <div class="column">
          <h3>candidates</h3>
          <a href="#">start applying instantly</a>
          
        </div>
        <div class="column">
          <h3>getstarted</h3>
          <a href="#">job search</a>
          <a href="#">company search</a>
          <a href="#">create your cv</a>
          <a href="#">how it works</a>
         
        </div>
        <div class="column">
          <h3>find a job today</h3>
          <a href="#"><button type="button" class="btn btn-primary">log in</button><br>
  <button type="button" class="btn btn-primary">register</button>
  </a>
         
        </div>
      </div>
    </div>
  </div> 
</div>


 <style>
body, html {
  height: 100%;
  font-family: Arial, Helvetica, sans-serif;
}
* {
  box-sizing: border-box;
}
.bg-img {
  /* The image used */
  background-image: url("globe.jpg");
  min-height: 380px;
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
/* Add styles to the form container */
.container {
  position: absolute;
  right: 0;
  margin: 20px;
  max-width: 300px;
  padding: 16px;
  background-color: white;
}
/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  border: none;
  background: #f1f1f1;
}
input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}
/* Set a style for the submit button */
.btn {
  background-color: #4CAF50;
  color: white;
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}
.btn:hover {
  opacity: 1;
}
</style>

<body>

<h2>Find the career you deserve</h2>
<div class="bg-img">
  <form action="/action_page.php" class="container">
    <h1>Login</h1>

    <label for="email"><b>keywords</b></label>
    <input type="text" placeholder="Enter keywords" name="email" required>

    <label for="psw"><b>company</b></label>
    <input type="password" placeholder="Enter company" name="psw" required>
     
    <label for="email"><b>job type</b></label>
    <input type="text" placeholder="Enter job type" name="email" required>


    <button type="submit" class="btn">find the job now</button>
  </form>
</div>

</body>


  
