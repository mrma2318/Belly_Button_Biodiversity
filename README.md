# Belly_Button_Biodiversity

## Overview of Project: Belly Button Biodiversity investigates the microbes that are inhabiting our navals. 

### The purpose of this analysis is to identify the top 10 bacterial species in volunteers belly buttons. If we idenify a species as potential candidate to manufacturing synthetic beef, then the volunteers will be able to identify whether that species is found in their naval. 

## Analysis
- Before I could run my analysis, I needed to familiarize myself with the data. First, I needed to import the data as a JSON file. When examining the data, there were 153 arrays with three key objects: metadata, names, and samples. Then I examined each object in more detail to get a better understanding of what information was in each array.

- When assisting in the creation of the Belly Button Biodiversity webpage, I wanted to have it set up so that you could select an individual ID from a dropdown menu, Image 1. To do this I needed to access both the keys and values inside the object so that it would display the metadata with the appropriate ID. Then when an ID is selected, it will also display the demographic information about that person, Image 2.

### Image 1: Dropdown Menu
![Dropdown Menu](https://github.com/mrma2318/Belly_Button_Biodiversity/blob/dcef81368e9f8e36a2ce85b150aae151c308ccf6/images/Screen%20Shot%202022-11-22%20at%202.52.15%20PM.png)

### Image 2: Demographic Information
![Demographic Information](https://github.com/mrma2318/Belly_Button_Biodiversity/blob/dcef81368e9f8e36a2ce85b150aae151c308ccf6/images/Screen%20Shot%202022-11-22%20at%202.52.29%20PM.png)

- Then using my knowledge of JavaScript, Plotly, and D3.js, I created a bar chart, blubble chart, and guage chart of the belly button biodiversity data. For the bar chart, I wanted the species name for each bacterial ID number (samples_values) as the values in the chart, the ID numbers of all the bacterial found in that person's navel (otu_ids) as the labels, and then the label of bacteria (otu_lables) as the hover text for the bars on the chart, Image 3. 

### Image 3: Bar Chart
![Bar Chart](https://github.com/mrma2318/Belly_Button_Biodiversity/blob/dcef81368e9f8e36a2ce85b150aae151c308ccf6/images/bar_chart.png)

- Next, for the bubble chart I used the otu_ids as the x-axis and the  sample_values as the y-axis. Then I adjusted the bubbles on the graph to where the sample_value was the marker size and the color was based off the otu_ids, Image 4.

### Image 4: Bubble Chart
![Bubble Chart](https://github.com/mrma2318/Belly_Button_Biodiversity/blob/dcef81368e9f8e36a2ce85b150aae151c308ccf6/images/bubble_chart.png)

- Lastly, I made a gauge chart that displays the weekly washing frequency's values, where the values were measured on a scale from 0-10, Image 5. Then I customized the [webpage](http://127.0.0.1:5501/js/index.html) by changing the background, font color, adding a description of the project, and adding spaces between the charts and the top and bottom of the page. 

### Image 5: Gauge Chart
![Gauge Chart](https://github.com/mrma2318/Belly_Button_Biodiversity/blob/dcef81368e9f8e36a2ce85b150aae151c308ccf6/images/guage.png)