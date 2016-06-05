<head>
<title>Vaishaal Shankar</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
<link rel="stylesheet" type="text/css" href="mou.css">
</head>

Vaishaal Shankar
========
[cv](/cv.pdf)
[blog](/blog)
[github](http://github.com/vaishaal)

![image](http://s17.postimg.org/rxv2qg1v3/image.jpg)


I am a <span id="years" ></span> year graduate student working with Ben Recht.

My research interests lie in the intersection of machine learning and distributed systems.
More specifically I am interested in the design, analysis and implementation of *practical* machine learning algorithms
suitable for massive datasets.








You can contact me at vaishaal at eecs dot berkeley dot edu    

This page is currently under (perpetual) construction




Publications
-------------
Shankar, V., Zhang, J., Chen, J., Dinh, C., Clements, M., & Zakhor, A. (2016, February). Approximate Subgraph Isomorphism for Image Localization. *International Symposium on Electronic Imaging*

Shankar, V., & Culler, D. (2015, March). A Modern Student Experience in Systems Programming. In Proceedings of the Second (2015) ACM Conference on Learning@ Scale (pp. 233-236). ACM.

Kantchelian, A., Tschantz, M. C., Afroz, S., Miller, B., Shankar, V., Bachwani, V., Bachwani, R., Joseph, A.D. & Tygar, J. D. (2015, October). Better malware ground truth: Techniques for weighting anti-virus vendor labels. *In Proceedings of the Eigth ACM Workshop on Artificial Intelligence and Security (pp. 45-56). ACM.*


Miller, B., Kantchelian, A., Tschantz, M.C., Afroz, S., Bahwani, R., Faizullabhoy, R., Huang, L., Shankar, V., Wu, T., Yiu, G., Joseph, A.D.  & Tygar, J. D (2016 July).  Reviewer Integration and Performance Measurement for Malware Detection. *13th Conference on Detection of Intrusions and Malware & Vulnerability Assessment*

Tech Reports
-------------
Iliopoulos, F., Moulous, V., Shankar, V., & Simchowitz, M. [Gradients for the Loss!.](http://people.eecs.berkeley.edu/~msimchow/GradientsForLoss.pdf)




Other Useful Stuff
------------------
[Git for advanced beginners](https://docs.google.com/presentation/d/1FOOA4Tn9evpPHas0z-o2AM6wrUI_bXXcnepYnQ9TrZ4/pub?start=false&loop=false&delayms=3000)


On the side
-------------
I am an officer in the [Cal Running Club](http://crc.berkeley.edu), a low stress social running club that meets at Kroeber 5:30 pm every week day (during the
school year). Come say hi!



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

