---
layout: single
permalink: /clubroom/
---
Welcome to the clubroom page HeNTAi.
<html>
<body>

<img id="image" src="/assets/images/kancolle_office_dark.gif">

<p id="status">If you see this line, the status is not fetched. Try refreshing the page or contact the club authorities.</p>
<p> Refresh the page to update the status.</p>
<script>
	fetch("https://nkante.site:8080")
		.then(function(response) {
			if (response.ok) {
		        response.text().then(function(contents) {
					document.getElementById("status").innerHTML = contents;
					if (contents.includes("<b>ON</b>")) {
    		    	document.getElementById("image").src = "/assets/images/kancolle_office_bright.gif";
					}
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

Raw version of this page is also available [here](/status/raw).
