# Module18
HTML
<!DOCTYPE html>
<html>
<head>
  <link href="css/style.css" type="text/css" rel="stylesheet">
  <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Open+Sans" />
</head>
<body>
  <nav>
    <label class="logo">Hussain Alyousif</label>
    <ul>
        <li><a href="#" class="active">Home</a></li>
        <li><a href="#">Portfolio</a></li>
        <li><a href="#">Resume</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">About</a></li>
    </ul>
</nav>
  <div class="container">
    <div id="toggle">Project<img src="images/downArrow.png"></div>
    <ul id="dropDown">
      <li>Project 1</li>
      <li>Project 2</li>
    </ul>
  </div>
  <script src="https://code.jquery.com/jquery-3.4.1.js"></script>
  <script src="js/index.js"></script>
</body>
<ul>
  <img src="images/Hussain1.png" alt="Hussain" style="width: 25%" class="two">
  <img src="images/5fbbc83b5d18c0a5a2e4753ea9b1ea83.jpg" alt="Pro1" style="width:25%" class="three">
  <img src="images/Watering-App-600x453.png" alt="Pro2" style="width:25%" class="four">
</ul>
</html>
____________________

.container {
  width: 500px;
  margin: 0 auto;
  text-align:center;
  font-size: 22px;
  font-family: "Open Sans", helvetica, sans-serif;
  font-weight: bold;
}
#dropDown {
  display: none;
}
#toggle {
  background-color: #4682b4;
  padding: 15px;
  color: white;
  font-weight: bold;
  cursor: pointer;
  width: 100%;
}
ul {
  margin:0;
  padding: 0;
  list-style-type:none;
}
/*li {
  margin:0;
  padding: 15px;
  border: 1px solid #4682b4;
}*/
img {
  width: 18px;
}
nav{
  background-color: #4682b4;
  height: 80px;
  width: 100%;
}
label.logo{
  color: white;
  font-size: 36px;
  line-height: 80px;
  padding: 0 100px;
  font-weight: bold;
}
nav ul {
  float: right;
  margin-right: 20px;
}
nav ul li{
  display: inline-block;
  line-height: 80px;
  margin: 0;
}
nav ul li a{
  color: white;
  font-size: 1rem;
  border-radius: 3px;
}
a.active,a:hover{
  color: rgb(7, 23, 95);
  transition: 0.5s;
}
.two {
  display:block;
  margin-left: auto;
  width: 100%;
}
@media(max-width:768px){
  label.logo{
      font-size: 31px;
      padding-left: 50px;
  }
}
ul {
  width: 30em;
}
li {
  display: inline;
  list-style: none;
}
