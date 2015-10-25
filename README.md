# websiteproject
it contain image slider
<html>
<head>
<style>
@import url(http://fonts.googleapis.com/css?family=Varela+Round);

html
body { 
background-image : url("bg.jpg");
background-size:100%;
background-attachment: fixed;
}

.slides {
    padding: 0;
    width: 90%;
    height: 100%;
    display: block;
    margin: 0 auto;
    position: relative;
    top:30%;
}

.slides * {
    user-select: none;
    -ms-user-select: none;
    -moz-user-select: none;
    -khtml-user-select: none;
    -webkit-user-select: none;
    -webkit-touch-callout: none;
}

.slides input { display: none; }

.slide-container { display: block; }

.slide {
    top: 0;
    opacity: 0;
    width: 100%;
    height: 100%;
    display: block;
    position: absolute;

    transform: scale(0);

    transition: all .7s ease-in-out;
}

.slide img {
    width: 100%;
    height: 100%;
}

.nav label {
    width: 200px;
    height: 100%;
    display: none;
    position: absolute;

	  opacity: 0;
    z-index: 9;
    cursor: pointer;

    transition: opacity .2s;

    color: #FFF;
    font-size: 156pt;
    text-align: center;
    line-height: 380px;
    font-family: "Varela Round", sans-serif;
    background-color: rgba(255, 255, 255, .3);
    text-shadow: 0px 0px 15px rgb(119, 119, 119);
}

.slide:hover + .nav label { opacity: 0.5; }

.nav label:hover { opacity: 1; }

.nav .next { right: 0; }

input:checked + .slide-container  .slide {
    opacity: 1;

    transform: scale(1);

    transition: opacity 1s ease-in-out;
}

input:checked + .slide-container .nav label { display: block; }

.nav-dots {
	width: 100%;
	bottom: 9px;
	height: 11px;
	display: block;
	position: absolute;
	text-align: center;
}

.nav-dots .nav-dot {
	top: -5px;
	width: 11px;
	height: 11px;
	margin: 0 4px;
	position: relative;
	border-radius: 100%;
	display: inline-block;
	background-color: rgba(0, 0, 0, 0.6);
}

.nav-dots .nav-dot:hover {
	cursor: pointer;
	background-color: rgba(0, 0, 0, 0.8);
}

input#img-1:checked ~ .nav-dots label#img-dot-1,
input#img-2:checked ~ .nav-dots label#img-dot-2,
input#img-3:checked ~ .nav-dots label#img-dot-3,
input#img-4:checked ~ .nav-dots label#img-dot-4,
input#img-5:checked ~ .nav-dots label#img-dot-5,
input#img-6:checked ~ .nav-dots label#img-dot-6 {
	background: rgba(0, 0, 0, 0.8);
}
.k1
{
   color :white;
font-family: "CORPORATE A BQ";
font-weight: lighter;
POSITION:ABSOLUTE;
LEFT : 50%;
TOP:15%;
font-size:200%;
opacity:0.4;
}
.k2
{
   color :white;
font-family: "CORPORATE A BQ";
font-weight: lighter;
POSITION:ABSOLUTE;
LEFT : 58%;
TOP:15%;
font-size:200%;
text-decoration:none;
}
.k3
{
   color :white;
font-family: "CORPORATE A BQ";
font-weight: lighter;
POSITION:ABSOLUTE;
LEFT : 69%;
TOP:15%;
font-size:200%;
}
.k4
{
   color :white;
font-family: "CORPORATE A BQ";
font-weight: lighter;
POSITION:ABSOLUTE;
LEFT : 79%;
TOP:15%;
font-size:200%;
}
.k5 img
{
  position : absolute;
  width:10%;
height:20%;
top:50px;
left :80px;
}
.a1 img
{
  position : absolute;
  width:28%;
height:37%;
top:132%;
left :5.5%;
}
.b1 img
{
  position : absolute;
  width:28%;
height:37%;
top:132%;
left :36%;
}
.c1 img
{
  position : absolute;
  width:28%;
height:37%;
top:132%;
left :66.5%;
}
.t1
{
position:absolute;
color:white; 
font-family:"COPPERPLATE GOTHIC";
top :170%;
left:5.5%;
font-size:120%;
}
.t2
{
position:absolute;
color:white; 
font-family:"COPPERPLATE GOTHIC";
top :170%;
left:36%;
font-size:110%;
}
.t3
{
position:absolute;
color:white; 
font-family:"COPPERPLATE GOTHIC";
top :170%;
left:66.5%;
font-size:120%;
}
a
{
  color:white;
  text-decoration:none;
} 
a:hover
{
  opacity:0.4;
}
</style>
</head>
<body>
<ul class="slides">
    <input type="radio" name="radio-btn" id="img-1" checked />
    <li class="slide-container">
		<div class="slide">
			<img src="8.jpg" />
			
        </div>
		<div class="nav">
			<label for="img-6" class="prev">&#x2039;</label>
			<label for="img-2" class="next">&#x203a;</label>
		</div>
    </li>

    <input type="radio" name="radio-btn" id="img-2" />
    <li class="slide-container">
        <div class="slide">
          <img src="9.jpg" />
        </div>
		<div class="nav">
			<label for="img-1" class="prev">&#x2039;</label>
			<label for="img-3" class="next">&#x203a;</label>
		</div>
    </li>

    <input type="radio" name="radio-btn" id="img-3" />
    <li class="slide-container">
        <div class="slide">
          <img src="10.jpeg" />
        </div>
		<div class="nav">
			<label for="img-2" class="prev">&#x2039;</label>
			<label for="img-4" class="next">&#x203a;</label>
		</div>
    </li>

    <input type="radio" name="radio-btn" id="img-4" />
    <li class="slide-container">
        <div class="slide">
          <img src="11.jpg" />
        </div>
		<div class="nav">
			<label for="img-3" class="prev">&#x2039;</label>
			<label for="img-5" class="next">&#x203a;</label>
		</div>
    </li>

    <input type="radio" name="radio-btn" id="img-5" />
    <li class="slide-container">
        <div class="slide">
          <img src="2.jpg" />
        </div>
		<div class="nav">
			<label for="img-4" class="prev">&#x2039;</label>
			<label for="img-6" class="next">&#x203a;</label>
		</div>
    </li>

    <input type="radio" name="radio-btn" id="img-6" />
    <li class="slide-container">
        <div class="slide">
          <img src="3.jpg" />
        </div>
		<div class="nav">
			<label for="img-5" class="prev">&#x2039;</label>
			<label for="img-1" class="next">&#x203a;</label>
		</div>
    </li>

    <li class="nav-dots">
      <label for="img-1" class="nav-dot" id="img-dot-1"></label>
      <label for="img-2" class="nav-dot" id="img-dot-2"></label>
      <label for="img-3" class="nav-dot" id="img-dot-3"></label>
      <label for="img-4" class="nav-dot" id="img-dot-4"></label>
      <label for="img-5" class="nav-dot" id="img-dot-5"></label>
      <label for="img-6" class="nav-dot" id="img-dot-6"></label>
    </li>
</ul>
<k class = "k1">
Home
</k>
<k class = "k2">
<a href = "over.HTML">Overview</a>
</k>
<k class = "k3">
<a href = "about.HTML">About us </a>
</k>
<k class = "k4">
<a href = "contact.HTML">Contact us</a>
</k>
<k class = "k5">
<img src  = "mrw.png">
</k>
<a class ="a1" href= "over.html">
<img src = "glc.jpg">

</a>
<a class ="b1" href = "over.html">
<img src = "d.jpg">
</a>
<a class ="c1" href = "over.html">
<img src = "b.jpg">

</a>
<T class = "t1">
The new model of GLC-Class
</T>
<T class = "t2">
NEWS ABOUT MERCEDES-BENZ <BR>S-CLASS
</T>
<T class = "t3">
THE NEW GENERATION B-CLASS
</T>






</body>
</html>
