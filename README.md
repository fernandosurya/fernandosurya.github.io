<!Doctype html>
<Html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#grad1 {
	height: 60px;
	background-color: #748eff; /* for browsers that do not support gradients */
	background-image: linear-gradient(#b9ffff,#5dcff);
	}

p.small {
	line-height: 0.3;
	}
p.big {
	line-height: 1.8
	}

.navbar {
  overflow: hidden;
  background-color: #333;
}

.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 10px 12px;
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
  padding: 10px 12px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
</head>

<body style= "background-color: #b9ffff">
	<h4 style= "font-size: 18px"> Welcome to </h4>
	<p style= "text-align: center; font-family: arial; font-size: 150%"> <b> MY PRIVATE WEBSITE </b> </p>

<div class="navbar">
  	<a href="fernandosurya.github.io">Home</a>

  	<a href="fernandosurya.github.io/study.html">Study</a>
	
	<div class="dropdown">
   		<button class="dropbtn">Favorite
      		<i class="fa fa-caret-down"></i>
    		</button>
	<div class="dropdown-content">
      		<a href="#">Songs</a>
      		<a href="#">Places</a>
	</div>
	</div>

	  	<div class="dropdown">
    			<button class="dropbtn">Contact Me
      			<i class="fa fa-caret-down"></i>
    			</button>
    		<div class="dropdown-content">
      			<a href = "mailto:fernandosurya021@gmail.com">Gmail</a>
      			<a href="https://instargam.com/fernandosurya01">Instagram</a>
      			<a href="https://wa.me/082280822345">Whatsapp</a>
		</div>
		</div>
</div>
<p style= "font-family: arial; font-size: 100%"> Hello, Welcome to my Private Website. In this website you can know me more deep and you can take a look for what i already done.</p>
</body>
</html>
