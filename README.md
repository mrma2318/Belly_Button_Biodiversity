# Belly_Button_Biodiversity

## Overview of Project: Belly Button Biodiversity investigates the microbes that are inhabiting our navals. 

### The purpose of this analysis is to identify the top 10 bacterial species in volunteers belly buttons. If we idenify a species as potential candidate to manufacturing synthetic beef, then the volunteers will be able to identify whether that species is found in their naval. 

## Analysis
- Before I could run my analysis, I needed to familiarize myself with the data. First, I needed to import the data as a JSON file. When examining the data, there were 153 arrays with three key objects: metadata, names, and samples. Then I examined each object in more detail to get a better understanding of what information was in each array.

- When assisting in the creation of the Belly Button Biodiversity webpage, I wanted to have it set up so that you could select an individual ID from a dropdown menu, Image 1. To do this I needed to access both the keys and values inside the object so that it would display the metadata with the appropriate ID. Then when an ID is selected, it will also display the demographic information about that person, Image 2.

### Image 1: Dropdown Menu

### Image 2: Demographic Information

- Then using my knowledge of JavaScript, Plotly, and D3.js, I created a bar chart, blubble chart, and guage chart of the belly button biodiversity data. For the bar chart, I wanted the species name for each bacterial ID number (samples_values) as the values in the chart, the ID numbers of all the bacterial found in that person's navel (otu_ids) as the labels, and then the label of bacteria (otu_lables) as the hover text for the bars on the chart, Image 3. 

### Image 3: Bar Chart

## Results

## Summary