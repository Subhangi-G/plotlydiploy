# plotlydiploy

## Overview of Project 

### Purpose

The purpose of this exercise is to create a dashboard which will provide dynamic and interactive visualizations of the biodiversity found in a test subjects's belly button, when their id number is chosen from a dropdown menu.

## Summary

Samples were obtained from belly buttons of volunteers identified by their ID numbers. Any test subjects' ID number may be selected from a dropdown menu in the dashboard. The webpage then automatically reloads, and the demographic information about the test subject is displayed. 

![demographic_info](https://user-images.githubusercontent.com/71800628/125146567-05d9de00-e0ec-11eb-898b-a447267de0fe.png)

An interactive visualization is provided about the bacterial types observed in cultures, grown from samples, obtained from the test subject.

The horizontal bar chart displays the top ten most abundant bacterial types found in the sample. \
The bubble chart displays all the bacterial types in the sample. The size of the bubble direcly correlates to the relative abundance of the bacterial species, represented by the OTU IDs. The OTU or Operational Taxonomic Unit IDs represent bacterial species. Hovering over a bar or a bubble in the charts will give the species name corresponding to the OTU ID.

![bubble_chart](https://user-images.githubusercontent.com/71800628/125146578-1ee28f00-e0ec-11eb-95b0-934b1ae4ec9c.png)

A gauge chart is also displayed, which shows the number of times the test subjects' navel is washed weekly. This information may be used to find, if the are any, correlation between the numbers, and types of bacterial species and washing frequency of the belly button. 

Research participants for this study are able to see the information about the biodiversity in their navels, if they know their id numbers. They may then be able to determine if their belly buttons contain bacteria that are able to synthesize proteins that may have useful applications, in this case enhance beef flavor for synthetic beef.

The dashboard was built using javascript, and HTML. Plotly was used to create the different interactive visualizations. Furthermore Bootstrap, and CSS were used to style the page.\
The dashboard is also responsive. Below is a picture of how it would appear on an Ipad.

![ipad_view](https://user-images.githubusercontent.com/71800628/125149630-b4d3e500-e0ff-11eb-963c-1543c956b7a1.png)


### Resources used
- Data Source: 'samples.json' 
- Software: ECMAScript2015, d3.js 4.11.0, Bootstrap v4.0.0, Plotly
The image inserted in the dashboard, and the one below, were obtained from the webpage of robdunnlab, from the NC State, The Public Science Lab.
http://robdunnlab.com/projects/belly-button-biodiversity/


![most-common-taxa](https://user-images.githubusercontent.com/71800628/125146585-2b66e780-e0ec-11eb-8f37-8bbb26360642.jpg)


