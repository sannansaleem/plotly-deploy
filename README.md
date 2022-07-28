# plotly-deploy

https://sannansaleem.github.io/plotly-deploy/

#### Table of Contents

[Project Overview](#project-overview)  
[Challenge Overview](#challenge-overview)  
[Challenge Objectives](#challenge-objectives)  
[Challenge Summary](#challenge-summary)  

## Project Overview
In this module, we will use Plotly.js, a data visualization library within JavaScript, to create an interactive data visualization for the web. The completed work will be displayed in a portfolio we created using github pages to deploy the project.  


## Challenge Overview
In this challenge, we have a partially completed dashboard, but need to finish it. A completed panel for demographic information has alreaddy been provided but bacterial data for each volunteer needs to be visualised nad displayed in a user friendly interface. Specifically, the volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, our volunteers will be able to identify whether that species is found in quantity in their navel.  

## Challenge Objectives  
The goals of this challenge are for us to:

  -Deliverable 1: Create a Horizontal Bar Chart
  
  -Deliverable 2: Create a Bubble Chart
  
  -Deliverable 3: Create a Gauge Chart
  

## Challenge Summary  
### <ins> Deliverable 1 </ins>
<p align="center">
<img src="/images/del_1.png" width="40%" height="40%"> 
</p>

- Code is written to create the arrays when a sample is selected from the dropdown menu 

- Code is written to create the trace object in the buildCharts() function, and it contains the following: 

  - The y values are the otu_ids in descending order

  - The x values are the sample_values in descending order

  - The hover text is the otu_labels in descending order.

- Code is written to create the layout array in the buildCharts() function that creates a title for the chart 

- When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following: 

  - The top 10 sample_values are sorted in descending order

  - The top 10 sample_values as values

  - The otu_ids as the labels
 
 ### <ins> Deliverable 2 </ins>
 <p align="center">
<img src="/images/del_2.png" width="60%" height="60%"> 
</p>

- The code for the trace object in the buildCharts(); function does the following:
  - Sets the otu_ids as the x-axis values
  - Sets the sample_values as the y-axis values
  - Sets the otu_labels as the hover-text values
  - Sets the sample_values as the marker size
  - Sets the otu_ids as the marker colors
- The code for the layout in the buildCharts(); function does the following:
  - Creates a title
  - Creates a label for the x-axis
  - The text for a bubble is shown when hovered over
- When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu

### <ins> Deliverable 3 </ins>
<p align="center">
<img src="/images/del_3.png" width="40%" height="40%"> 
</p>

- The code to build the gauge chart does the following: 
  - Creates a title for the chart.
  - Creates the ranges for the gauge in increments of two, with a different color for each increment.
  - Adds the washing frequency value on the gauge chart.
  - The indicator shows the level for the washing frequency on the gauge.
  - The gauge is added to the dashboard.
  - The gauge fits in the margin of the <div> element.
- When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable 


