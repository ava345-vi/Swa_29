<!DOCTYPE html>
<html>
<head>
	<title>Page Title</title>
	<style>
		body {
			background-color: #f2f2f2;
		}
		h1 {
			color: #00698f;
		}
		p {
			color: #666;
			font-size: 18px;
		}
		button {
			background-color: #4CAF50;
			color: #fff;
			padding: 12px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
		}
	</style>
</head>
<body>
	<h1 id="header">Heading</h1>
	<p>Paragraph</p>
	<button onclick="changeText()">Click Me</button>

	<script>
		function changeText() {
			document.getElementById("header").innerHTML = "New Heading!";
		}
	</script>
</body>
</html>
