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
This page will hold my publicly available visualizations and critiques for the class.
<br>
<br>
<p>Check below for the collapsible menu of each week's assignments!</p>
<button type="button" class="collapsible">Open Week 1</button>
<div class="content">
<p>
<h2>Week 1: Controlling for Color</h2>
  <button type="button" class="collapsible">Visualization Critique #1</button>
  <div class="content">
  <p>
    <h3>Visualization Critique #1: The Economist</h3>
    <br>
    Original Image from The Economist vs. Personal Critiques
    <br>
    <img src="economist_chart.png" width="300" height="300"> <img src="economist_chart_critique.png" width="300" height="300"> <img src="economist_chart_critique2.png"           width="300" height="300">
    <br>
    <a href="https://github.com/jcboyle2/Boyle-Portfolio/blob/master/JohnBoyle_Critique%20%231_Economist_bar_chart.xlsx?raw=true">Download a written copy of the critique     (.xlsx), which explains the decisions in the image above.</a>
  </p>
  </div>

<button type="button" class="collapsible">Other Critiques and Redesigns from the Good Charts Workbook</button>
  <div class="content">
  <p>
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
</p>
</div>

<button type="button" class="collapsible">Open Week 2</button>
<div class="content">
<p>
  <h2>Week 2:Chart Elements, Hierarchy, Ordering, and More</h2>
  <br>
  <button type="button" class="collapsible">Data Visualization: OECD Country Government Debt</button>
  <div class="content">
  <p>
  <h3>DataViz 2: Working with Web-Based Visualization Tools and Data</h3>
  <b>General Government Debt (Total, % of GDP) - OECD Countries, 2017</b>
  <iframe src="https://data.oecd.org/chart/61Cj" width="640" height="480" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a  href="https://data.oecd.org/chart/61Cj" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</a></iframe>
  <br>
  <br>
  <b>General Government Debt (Total, % of GDP) - OECD Countries, 1995-2019</b>
  <br>
  <b>Version 1: Tufte's Sparklines Re-Creation</b>
  <div class="flourish-embed flourish-chart" data-src="visualisation/3148409" data-url="https://flo.uri.sh/visualisation/3148409/embed"><script     src="https://public.flourish.studio/resources/embed.js"></script></div>
  <br>
In the chart above, we are examining the Debt-to-GDP ratio of each OECD Country from 1995 to 2019. The Debt-to-GDP ratio ranges from as low as 6.6% in Estonia (2001) to a high of 238.7% in Japan (2018). As you may notice, not every country has data available for each year reported. By looking at this chart you can see which countries were most impacted by the 2008 Financial Crisis (like Greece, Spain, and the United States), which were relatively unaffected (like Norway, Poland, and Sweden).
  <br>
  <br>
  <b>Version 2: Animated Rank Chart, using Flourish Templates</b>
  <div class="flourish-embed flourish-scatter" data-src="visualisation/3150106" data-url="https://flo.uri.sh/visualisation/3150106/embed"><script   src="https://public.flourish.studio/resources/embed.js"></script></div>
  <br>
    This chart, similar to the first, examines each country individually by animating through each country's available data. My original plan was to make the color gray on the "All Countries" slide, and highlightable with mouse hovering. However, I was not able to achieve this without using CSS (which is not available to a free account holder).

I tried to focus on making this chart as simple as possible. The two colors, light blue and gray, are picked from the OECD logo. They seem to fit together well. The animation plays through in alphabetical order to show how each country differs from the last. A linear trendline is added to each chart to show how the Debt-to-GDP ratio has changed throughout the course of the 25 year period.

If I were to take this a step further, I would add to the data an average debt-to-GDP ratio for each country to sort the data. Currently sorting by debt-to-GDP will mess with the make the line tracing the dots go by the years of highest ratios, not by year (so the lines for Japan would connect from 2018 -> 2014 -> 2015 -> ... -> 1995 instead of sequentially). Secondly, I would add a region specific tag in order to add another area of potential color. An example would be to compare European countries to South American countries to examine the effect of the 2008 Financial Crisis.
</p>
</div>

<button type="button" class="collapsible">Redoing Week 1's Critique in Datawrapper</button>
  <div class="content">
  <p>
  Below is the data critique from The Economist in week 1, re-visualized using Datawrapper!
  <br>
  <iframe title="Brazil's Growing Pension Problem" aria-label="chart" id="datawrapper-chart-wsU57" src="https://datawrapper.dwcdn.net/wsU57/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
  </script>
  </p>
  </div>
</p>
</div>

<button type="button" class="collapsible">Open Week 3</button>
<div class="content">
<p>
  <h2>Week 3</h2>
  Check back soon for Week 3's assignments!
</p>
</div>

<button type="button" class="collapsible">Open Week 4</button>
<div class="content">
<p>
  <h2>Week 4</h2>
  Check back soon for Week 4's assignments!
</p>
</div>

<button type="button" class="collapsible">Open Week 5</button>
<div class="content">
<p>
  <h2>Week 5</h2>
  Check back soon for Week 5's assignments!
</p>
</div>

<button type="button" class="collapsible">Open Mini Project</button>
<div class="content">
<p>
  <h2>Mini Project</h2>
  Check back soon for the Mini Project's benchmark assignments!
</p>
</div>

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
