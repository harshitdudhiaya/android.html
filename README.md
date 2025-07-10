
<!DOCTYPE html>
<html>
	<head>
		<title>Android</title>
		<style>
			body {
  margin: 0;
  font-family: Arial, sans-serif;
}

.menu-icon {
  font-size: 30px;
  padding: 15px;
  cursor: pointer;
  display: inline-block;
  background-color: #333;
  color: white;
  position: fixed;
  z-index: 2;
}

#menu-toggle {
  display: none;
}

.slide-menu {
  position: fixed;
  left: -250px;
  top: 0;
  width: 250px;
  height: 100%;
  background-color: #333;
  overflow-y: auto;
  transition: left 0.3s ease;
  padding-top: 60px;
  z-index: 1;
}

.slide-menu ul {
  list-style: none;
  padding: 0;
}

.slide-menu ul li {
  padding: 15px;
  border-bottom: 1px solid #444;
}

.slide-menu ul li a {
  color: white;
  text-decoration: none;
  display: block;
}

#menu-toggle:checked + .menu-icon + .slide-menu {
  left: 0;
}

.content {
  padding: 20px;
  margin-left: 0;
  transition: margin-left 0.3s ease;
}

#menu-toggle:checked ~ .content {
  margin-left: 250px;
}
.h1{color:white;}
		</style>
	</head>
	<body bgcolor=#333>
		 <input type="checkbox" id="menu-toggle" />
  <label for="menu-toggle" class="menu-icon">&#9776;</label>

  <nav class="slide-menu">
    <ul>
	<li>Introduce Android Evolution</li>
      <li><a href="#">Android 1.0</a></li>
      <li><a href="#">Android 1.1</a></li>
      <li><a href="#">Android Cupcake</a></li>
      <li><a href="#">Android Donut</a></li>
       <li><a href="#">Android Eclair</a></li>
	  <li><a href="#">Android Froyo</a></li>
      <li><a href="#">Android Gingerbread</a></li>
	<li><a href="#">Android Honeycomb</a></li>
	<li><a href="#">Android Ice Cream Sandwich</a></li>
	<li><a href="#">Android Jelly Bean</a></li>
	<li><a href="#">Android KitKat</a></li>
	<li><a href="#">Android Lollipop</a></li>
	<li><a href="#">Android Marshmallow</a></li>
	<li><a href="#">Android Nougat</a></li>
	<li><a href="#">Android Oreo</a></li>
	<li><a href="#">Android Pie</a></li>
	<li><a href="#">Android 10</a></li>
	<li><a href="#">Android 11</a></li>
	<li><a href="#">Android 12</a></li>
	<li><a href="#">Android 13</a></li>
	<li><a href="#">Android 14</a></li>
	<li><a href="#">Android 15</a></li>
	<li><a href="#">Android 16</a></li>
    </ul>
  </nav>

  <div align=right>
   <a href="android.html"><img src="and.png" hieght=20% width=10%></a>
  </div>
		<div align=center>
		<marquee scrollamount=20><h1 class=h1>Introduce Android Evolution</h1></marquee>
		</div>
		<div align=center>
		<img src="an.png">
		</div>
		<div align=center>
		<h1 class=h1>Click on Three lines in left side to show Android Evolution</h1>
		</div>
	</body>
</html>
