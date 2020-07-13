<h1>Data Visualization: Government Debt</h1>

<b> Visualization #0: General Government Debt, OECD Countries in 2017</b>
<iframe src="https://data.oecd.org/chart/61Cj" width="640" height="480" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true">OECD Chart: General government debt, Total, % of GDP, Annual, 2017</iframe>


<b> Visualization #1: Government Debt Created in Tufte's Sparkline Style </b>
<div class="flourish-embed flourish-chart" data-src="visualisation/3148409" data-url="https://flo.uri.sh/visualisation/3148409/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


In the chart above, we are examining the Debt-to-GDP ratio of each OECD Country from 1995 to 2019. The Debt-to-GDP ratio ranges from as low as 6.6% in Estonia (2001) to a high of 238.7% in Japan (2018). As you may notice, not every country has data available for each year reported. By looking at this chart you can see which countries were most impacted by the 2008 Financial Crisis (like Greece, Spain, and the United States), which were relatively unaffected (like Norway, Poland, and Sweden).


<b> Visualization #2: Government Debt Animated</b>
<div class="flourish-embed flourish-scatter" data-src="visualisation/3150106" data-url="https://flo.uri.sh/visualisation/3150106/embed"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


This chart, similar to the previous, examines each country individually by animating through each country's available data. My original plan was to make the color gray on the "All Countries" slide, and highlightable with mouse hovering. However, I was not able to achieve this without using CSS (which is not available to a free account holder). Where I think this is more helpful than the second is that the charts are bigger and therefore the trends are little more clear. When you look at the grid of lines chart, it is cool to see all the ratios close, but it can be hard to judge what is happening in each individual country.

I tried to focus on making this chart as simple as possible. The two colors, light blue and gray, are picked from the OECD logo. They seem to fit together well. The animation plays through in alphabetical order to show how each country differs from the last. A linear trendline is added to each chart to show how the Debt-to-GDP ratio has changed throughout the course of the 25 year period. This was my third attempt at getting a clear visualization from Flourish. Originally I wanted to use the world map graph, but I struggled to get the available data to fit their model. My second attempt was to make a box plot for each country, to see if there were any outliers in the data, but this proved to not fit as well. This final attempt began as a connected dot-plot that turned into this animated dot-plot, connecting each country by year.

If I were to take this a step further, I would add to the data an average debt-to-GDP ratio for each country to sort the data. Currently sorting by debt-to-GDP will mess with the make the line tracing the dots go by the years of highest ratios, not by year (so the lines for Japan would connect from 2018 -> 2014 -> 2015 -> ... -> 1995 instead of sequentially). Secondly, I would add a region specific tag in order to add another area of potential color. An example would be to compare European countries to South American countries to examine the effect of the 2008 Financial Crisis.
