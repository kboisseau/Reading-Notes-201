# Class 12: Third Party Libraries and Chart JS

Charts are a better way for displaying data more visually than tables, mainly becasue they're easier to look at and convey data quickly.
When working with charts we need to download Chart.js as a beginning step afterwards we can copy the chart.min.js out of the unzipped folder then right into the directory we are working on.
Drawing a line chart, our first goal is to create a canvas elemtn in our HTML in which chart.js can draw our chart.
We add this portion to the body of our HTML page
<canvas id="buyers" width="600" height="400"></canvas>

In the process of creating a pie chart we use the follwing element:
<canvas id="buyers" width="600" height="400"></canvas>
Then proceed to add context and instantiate the chart

var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions);

Bar Charts are similar to line charts and it begins with adding a canvas element

<canvas id="income" width="600" height="400"></canvas>
