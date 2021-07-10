# plotlydiploy

## Overview of Project 

### Purpose

The purpose of this exercise is to create a dashboard which will provide dynamic and interactive visualizations of the biodiversity found in a test subjects's belly button, when their id number is chosen from a dropdown menu.

## Summary

Samples were obtained from belly buttons of volunteers identified by their ID numbers. Any test subjects' ID number may be selected from a dropdown menu in the dashboard. The webpage then automatically reloads to display information about the bacterial types observed in cultures, grown from samples, obtained from the volunteer with that particular ID number.\

The horizontal bar chart displays the top ten most abundant bacterial types found in the sample. \
The bubble chart displays all the bacterial types in the sample. The size of the bubble direcly correlates to the relative abundance of the bacterial species, represented by the OTU IDs. The OTU or Operational Taxonomic Unit IDs represent bacterial species.\
Hovering over a bar or a bubble in the charts will give the species name corresponding to the OTU ID.\
A gauge chart is also displayed, which shows the number of times the test subjects' navel is washed weekly. This information may be used to find, if the are any, correlation between the numbers, and types of bacterial species and washing frequency of the belly button.\ 

Research participants for this study are able to see the information about the biodiversity in their navels, if they know their id numbers. They may then be able to determine if their belly buttons contain bacteria that are able to synthesize proteins that may have useful applications, in this case enhance beef flavor for synthetic beef.

The dashboard was built using javascript, and HTML. Plotly was used to create the different interactive visualizations. Furthermore Bootstrap, and CSS were used to style the page.


### Resources used
- Data Source: 'samples.json' 
- Software: ECMAScript2015, d3.js 4.11.0, Bootstrap v4.0.0, Plotly
The image inserted in the dashboard, and over here was obtained from the webpage of robdunnlab, from the NC State, The Public Science Lab.

