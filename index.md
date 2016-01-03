<head>
<title>Vaishaal Shankar</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
<link rel="stylesheet" type="text/css" href="mou.css">
</head>

Vaishaal Shankar
========

![image](http://s17.postimg.org/rxv2qg1v3/image.jpg)


I am a <span id="years" ></span> year graduate student working with Ben Recht.
My research interests lie in the intersection of machine learning and distributed systems.  
You can contact me at vaishaal at eecs dot berkeley dot edu    
I've worked on a few projects which you can find [here](http://github.com/vaishaal).  
My cv is [here](/cv.pdf)

This page is currently under (perpetual) construction


Other Useful Stuff
------------------
[Git for advanced beginners](https://docs.google.com/presentation/d/1FOOA4Tn9evpPHas0z-o2AM6wrUI_bXXcnepYnQ9TrZ4/pub?start=false&loop=false&delayms=3000)



<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-47546603-1', 'berkeley.edu');
  ga('send', 'pageview');

</script>
<script>
var d = new Date();
var n = d.getFullYear();
var m = d.getMonth();
if (m < 8) {
  n = n - 1
}

var k = n - 2015 + 1
var endings = ["st","nd", "rd","th"]

if (k <= 3) {
	var year = k + endings[k-1]
} else {
	var year = k + endings[3]
}
document.getElementById("years").innerHTML = year
</script>

