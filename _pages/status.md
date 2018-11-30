---
layout: none
permalink: /status
---
<html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HNTA Clubroom Status</title>
</head>

<body>

<p>Welcome to the status page of HNTA.</p>
<p id="status">If you see this line, the status is not fetched. Try refreshing the page or contact the club authorities.</p>

<script>
	fetch("https://nkante.ml:8080")
		.then(function(response) {
			if (response.ok) {
		        response.text().then(function(contents) {
    		    	document.getElementById("status").innerHTML = contents;
		        });
			} else {
				throw new Error("Status could not be retrieved. Please contact the club authorities.");
			}
		}).catch(function(error) {
			document.getElementById("status").innerText = error.message;
		});
</script>

</body>

</html>
