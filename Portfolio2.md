<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  display: none;
  overflow: hidden;
  background-color: #f1f1f1;
}
</style>
</head>
<body>
  
<h1>Portfolio</h1>
<br>
This page will hold my publicly available visualizations and critiques for the class.
See each week below to check out my visualizations!
<br>
<p>Collapsible Set of Weeks:</p>
<button type="button" class="collapsible">Open Week 1</button>
<div class="content">
<p>
<br>
<h2>Week 1</h2>
<br>
<h3>Visualization Critique #1: The Economist</h3>
<br>
Original Image from The Economist vs. Personal Critiques
<br>
<img src="economist_chart.png" width="300" height="300"> <img src="economist_chart_critique.png" width="300" height="300"> <img src="economist_chart_critique2.png" width="300" height="300">
<br>
<a href="https://github.com/jcboyle2/Boyle-Portfolio/blob/master/JohnBoyle_Critique%20%231_Economist_bar_chart.xlsx?raw=true">Download a written copy of the critique (.xlsx), which explains the decisions in the image above.</a>
<br>
  <h3> Other Critiques from The Good Charts Workbook</h3>
<br>
<b>Comparing How We Spend Our Time</b>
<br>
<img src="how_we_spend_time.png" width="600" height="300">
<br>
<b>Interest In Buying A Drone, Total</b>
<br>
<img src="drone_interest1.png">
<br>
<b>Interest In Buying A Drone, Under 30</b>
<br>
<img src="drone_interest2.png">
</p>
</div>

<button type="button" class="collapsible">Open Week 2</button>
<div class="content">
<p>
## Week 2

Below is the data critique from The Economist in week 1, re-visualized using Datawrapper!

<iframe title="Brazil's Growing Pension Problem" aria-label="chart" id="datawrapper-chart-wsU57" src="https://datawrapper.dwcdn.net/wsU57/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>

### DataViz 2: Working with Web-Based Visualization Tools and Data

<b>General Government Debt (Total, % of GDP) - OECD Countries, 2017</b>
<iframe src="https://data.oecd.org/chart/61Cj" width="640" height="480" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/61Cj" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>

<b>General Government Debt (Total, % of GDP) - OECD Countries, 1995-2019</b>

<b>Version 1: Tufte's Sparklines Re-Creation</b>
<div class="flourish-embed flourish-chart" data-src="visualisation/3148409" data-url="https://flo.uri.sh/visualisation/3148409/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<b>Version 2: Animated Rank Chart, using Flourish Templates</b>
<div class="flourish-embed flourish-scatter" data-src="visualisation/3150106" data-url="https://flo.uri.sh/visualisation/3150106/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
</p>
</div>
## Week 3

## Week 4

## Week 5

## Mini Project

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>

</body>
</html>