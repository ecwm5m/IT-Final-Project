##Some Code For Fun

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


[Previous Page](Page3.md)  
[Next Page](Page5.md)  

