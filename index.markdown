---
layout: post
title: "CS 448B: Data Visualizations Final Project"
---
Welcome to our project!

The dataset we chose to use was the Newspaper Navigator. The dataset includes different types of visual content such as images and maps from historical newspapers from 1850 to 1963. The object detection model used to compile the dataset recognizes data of the following types: Photograph, Illustration, Map, Comics/Cartoon, Editorial Cartoon, Headline, Advertisement. The dataset also includes textual information about the visual content itself, such as text content of a headline. There is also metadata regarding geographical location, newspaper information, dates, etc.

 <iframe width="100%" height="503" frameborder="0"
  src="https://observablehq.com/embed/0ce55ef5b9385dcd@1009?cells=chart&api_key=6235b37a985552792ee5a971af6e2fa007c5dd45"></iframe>
  This visualization shows the most common words/phrases from the photos datasets from each year from 1900 - 1946. We can use this visualization to see the most common words during the world wars and compare this to before and after the wars. The Top 30 topics from each year are listed in alphabetical order on the x-axis and the counts of the number of times these words appear is on the y-axis. It is interesting to see how the topic counts were so much higher in the 1910s and 1920s than in the 1930s and 1940s. This means there were many more photos from these decades than the decades after. The Great Depression was from 1929-1939. During this time, since the economy took a great downturn, it was likely there was less news printed and what could be considered unnecessary such as photos were removed from the newspapers. For example, the highest topic counts from 1915 were almost 6,000 and the highest topic counts from 1940 were around 500. Some interesting trends we noticed were that in years during the war, there were many mentions of other countries. For example in 1916, the words british, french, german, and mexico are all are displayed on the visualization. Other war related terms such as army are also only mentioned in war years. 
  
<iframe width="100%" height="584" frameborder="0"
  src="https://observablehq.com/embed/@amy5/cs448b-final-project?cells=viewof+pieChart"></iframe>
 This visualization displays the proportion of ad types from the years 1900-1946. Readers can click on each pie slice to see an example of an ad that  is in that category.
  
<iframe width="100%" height="600" frameborder="0"
  src="https://observablehq.com/embed/18965aada07599a0?cells=map"></iframe>
TODO: This visualization displays the top keyword in newspaper headlines by state for the years 1900-1946. It also show the number of publications from that state in that year. Users can select the year from dropdown.