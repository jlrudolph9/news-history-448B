---
layout: post
title: "CS 448B Data Visualizations Final Project: Analyzing Newspaper Visual Content From the World War Era"
---
Lucy Bell, Janelle Rudolph, Amy Tang

### About The Dataset:
The Newspaper Navigator dataset includes different types of visual content from historical newspapers from 1850 to 1963. The visual content is recognized and categorized using a machine learning object detection model which can recognize the following categories: Photograph, Illustration, Map, Comics/Cartoon, Editorial Cartoon, Headline, Advertisement. The dataset also includes textual information about the visual content itself, such as text content of a headline also compiled by the object detection model. There is also metadata regarding geographical location, newspaper information, dates, etc.

### Our Focus:
After thoroughly examining the dataset, we were most interested in photographs, advertisements, and headlines. By honing in on these three categories, we began to develop a consistent narrative focused around wartime. This article includes multiple interactive visualizations in order to accurately convey newspaper content from 1900-1946 and hone in on patterns that arose.
  
<iframe width="100%" height="784" frameborder="0"
  src="https://observablehq.com/embed/@amy5/cs448b-final-project?cells=viewof+pieChart"></iframe>
 <iframe width="100%" height="784" frameborder="0"
  src="https://observablehq.com/embed/@amy5/cs448b-final-project?cells=viewof+pieChartWar"></iframe>
 This visualization displays the proportion of ad types from the years 1900-1913 and 1919-1938. We can also see a chart with the years 1914-1918 & 1939-1946, wartime of WW1 and WW2. Try to hover over each pie slice to see an example of an ad that is in that category! We can use this to compare the popularity of ad types in war and out of war. We can see that fashion is the most popular ad type both in wartime and in peacetime, with home ads coming in close second, and food in third. It is interesting to see the differences in the rest of the ad types in war and out of war.

 During wartime, advertising focuses on essentials like food, home needs, and services. This reflects the eras priorities such as rationing, healthcare, and stability. Fashion remains relevant but emphasizes practicality, while transportation and entertainment ads decline due to resource conservation and limited leisure activities. In peacetime, the focus shifts toward consumerism, with fashion and home ads dominating as people invest in luxury goods and improvements. Food ads decrease in prominence as rationing ends, and transportation and entertainment ads recover, reflecting increased mobility and leisure activities. Overall, wartime ads highlight necessity and resilience, while peacetime ads reflect prosperity and consumerism.

 By clicking on the fashion category, you are also able to see the difference in men and women targeted fashion ads. Can you estimate the proportions for both time periods? During wartime, fashion advertisements often focused more on men, reflecting their central role in the war effort and the influence of military styles on civilian attire. Ads for men highlighted durable, practical clothing like uniforms, sturdy suits, and boots, emphasizing patriotism and resilience. Women’s fashion during these periods was often constrained by fabric rationing, leading to simpler, utilitarian designs and fewer advertisements. In contrast, peacetime brought a shift toward women’s fashion as America sought to rebuild normalcy, with ads celebrating femininity, elegance, and luxury. Economic recovery allowed for greater spending on elaborate styles and accessories, and women, as key household consumers, became the primary target for fashion marketers. Men’s fashion ads during peacetime declined in prominence, focusing instead on leisure and business attire. These shifts reflect the broader social and economic dynamics of wartime and peacetime, as well as evolving gender roles and priorities.
  
<iframe width="100%" height="600" frameborder="0"
  src="https://observablehq.com/embed/18965aada07599a0?cells=map"></iframe>
TODO: This visualization displays the top keyword in newspaper headlines by state for the years 1900-1946. It also show the number of publications from that state in that year. Users can select the year from dropdown.


  <iframe width="200%" height="642" frameborder="0"
  src="https://observablehq.com/embed/@amy5/draft-amys-part-of-cs448b-final-project@1401?cells=lineChart"></iframe>

This visualization tracks the frequency of mentions of 5 major world powers - Britain, France, Germany, Japan, and Russia -- in newspaper photos from 1900 to 1946. I chose these countries because they were some of the most prominent countries involved in the World Wars outside of the United States. The data is presented as a line graph with years on the x-axis and mention counts on the y-axis. The graph has annotations for peaks in the graph such as the Russo-Japanese War and pivotal historical moments such as the start and end of the world wars and the great depression. __Viewers can hover over points to see the exact count for any country in any particular year. Viewers can also hover over the annotations to see a blurb with additional detailed historical context.__ 

Noticeable insights: The most striking feature was the dramatic difference in coverage volume between the 1910s and later decades. France reached nearly 5,500 mention at WW1's conclusion in 1918 while maximum mentions in the 1940s barely reached 500. This was largely caused by economic challenges in the early 1920s followed by the Great Depression. In the early 1920s, price volatility and deflation cause a sharp decline in advertising revenue. This caused what could be considered unnecessary such as photos to be removed from newspapers. Therefore, despite WWII's massive historical significance, the number of images about other countries was significantly reduced. For country specific patterns, France and Germany show the most dramatic spikes during WW1 due to their heavy involvment on opposing sides of the war. Japan and Russia maintain relatively stable, lower levels of coverage except for their brief spike during the Russo-Japanese War.

### Overall Project Takeaways:
Though our visualizations answer different questions and focus on different types of visual content, it is clear that the majors events during this time period (the World Wars and the Great Depression) changed what people focused on and what types of visual contents were being shown in the visualizations.
