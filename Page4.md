## Some Code For Fun  
**FizzBuzz Solution:**

	<!DOCTYPE html>
	<html>
	<head>
	<meta charset="UTF-8">
	<title>Fizz Buzz</title>
	<script>

	function fizzbuzz() {
		var display = document.getElementById('display');
		var displayHTML = "";
		for (i = 1; i <= 100; i++) {
			if (i % 3 === 0 && i % 5 === 0) {
      			display.innerHTML += "<div>fizzbuzz</div>";
    			} else if (i % 3 === 0) {
      			display.innerHTML += "<div>fizz</div>";
    			} else if (i % 5 === 0) {
      			display.innerHTML += "<div>buzz</div>";
    			} else {
      			display.innerHTML += "<div>" + i + "</div>";
   			 }
			}
	
		}
	</script>

	</head>

	<body onload="fizzbuzz()">
	<div id="display">

	</div>
	</body>

	</html>
	
**SVG Images:**

	<!DOCTYPE html>
	<html>
	<body>

	<h1>SVG Challenge</h1>

	<svg width="100" height="100">
   		<circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
	</svg> 

	<svg width="400" height="110">
  		<rect width="300" height="100" style="fill:rgb(100,0,255);stroke-width:3;stroke:rgb(0,0,0)" />
	</svg>

	<svg height="210" width="500">
  		<polygon points="200,10 250,190 160,210" style="fill:lime;stroke:purple;stroke-width:1" />
	</svg>
 
	</body>
	</html>
	
	


[Previous Page](Page3.md)  
[Home Page](README.md)  

