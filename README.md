# Plotly_Biodiversity

Deliverable 1: Create a Horizontal Bar Chart
For this deliverable, you’ve already done the following in this module:

Lesson 12.1.3: Create a bar chart
Lesson 12.2.1: Use JavaScript functions and methods: map(), filter(), reverse(), and slice().
Lesson 12.2.2: Create a bar chart with filtered arrays
Lesson 12.3.2: Load a JSON file with d3.json()
Lesson 12.4.3: Create a function that reads in json data
Lesson 12.4.3: Write code to use the ID number to create the sample’s information on a panel or chart
Lesson 12.5.1: Deploy your project to GitHub Pages

#################################

Deliverable 2: Create a Bubble Chart
For this deliverable, you’ve already done the following in this module:

Lesson 12.2.2 Create a trace object and layout for a chart
Lesson 12.5.1: Deploy your project to GitHub Pages

################################

Deliverable3: Create a Gauge Chart
For this deliverable, you’ve already done the following in this module:

Lesson 12.2.2: Create a trace object and layout for a chart
Lesson 12.5.1: Deploy your project to GitHub Pages

################################

Delivreable 4: Customize the Dashboard

README.md
In this project, we're:
- Using plotly.js to create basic plots
- Using D3.json() to fetch external data sources (CSV, API)
- Parsing data in JSON format
- Transforming data with JavaScript
- Using JavaSript's Math library to manipulate numbers
- Using event handlers in JavaScript for interactive features (buttons, drop down menus)

Our tools:
VS code: to create and edit HTML and JavaScript files
Web browser: such as Chrome, to view, inspect and debug visualizations.
Terminal interface: to run local server
GitHub: to deploy final data visualization

in our basic index.html, we will add: <script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
which will be our CDN (Content Delivery Network) to our latest plotly library version
in our <body> section, we wanna create a simple plot that extract the data from plots.js
  We accomplish that by create a </div> with an ID "plotArea" and used </script> to refer to the file  plots.js which contains the JavaScript code and data:
   
  index.html:
  <!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <meta http-equiv="X-UA-Compatible" content="ie=edge">
   <title>Basic Charts</title>
   <script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
</head>
<body>
   <div id="plotArea"></div>
   <script src="plots.js"></script>.    //plots.js file contains this code: Plotly.newPlot("plotArea", [{x: [1,2,3], y:[10,20,30]}]);
</body>
</html>



