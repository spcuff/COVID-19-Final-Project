# COVID-19 Time Lapse Visualization Project
Heinz College of Information Systems and Public Policy

Advanced GIS (90-753-A4) Spring 2020

Authors: Sean Cuff and Christopher Ibeling

## Project Overview
When reading about or watching video content about the current pandemic, the maps that most Americans see often provide totals to date of confirmed cases or the number of deaths. What is not as frequently captured in these maps, however, is the factor of time in the outbreak. Certainly one of the most alarming characteristics of the Coronavirus outbreak is the speed at which it has spread, and a sense of that speed can be lost when viewing a static map on a consistent basis. After all, it is in the public interest to convey the most up-to-date information on the crisis as possible, in order to avoid confusion, misinterpretation, and misinformation.

With this project, we want to demonstrate how quickly Covid-19 had moved across the country by producing a time-lapse map showing the spread of confirmed cases. The time series begins with the first known case in We also wanted to provide the sense of how Coronavirus spread to the communities of the viewer, and will develop this map at the county level. The time lapse will begin on January 21, 2020 when the first confirmed case in the United States was reported, It will then walk through each following day, highlighting the counties that reported one or more confirmed cases of Coronavirus. The full rotation of the map’s loop should capture what an outbreak’s exponential rate of infection looks like visually.

### Project Goals
-  Effectively impress upon the audience the speed at which Coronavirus had spread through communities across the country using a time-lapse map of confirmed cases. 
-  Visually demonstrate the proximity of these issues to the audience by developing a map at the county level.
-  Establish a compelling case for continued stay at home orders in the wake of ideologically motivated public protests.

## COVID-19 Spread in the United States
The first confirmed case of Covid-19 in the United States first emerged in Snohomish County Washington on January 21, 2020. Slowly over the following couple of weeks, the virus began to emerge in seemingly disparate parts of the country, namely Cook County, IL, Orange County, CA, and Maricopa County, AZ. Through February, however, confirmed cases of Coronavirus appeared to be growing at a relatively controlled rate and predominantly confined to certain pockets of the country. February’s numbers also coincided with most local health systems efforts to increase their testing capabilities. Many health officials have pointed out that the paucity of testing kits and resources concealed the full extent of the virus’ spread and severity throughout the United States. At the beginning of February, there were a total of 7 confirmed cases in the entire county. By the end of the month, that number had only increased to 66 total cases. 

The second week of March, however, certainly marked a turning point in the United States’ experience of handling the Coronavirus outbreak. As more cases resulted in hospitalizations and testing capabilities increased, the number of counties reporting confirmed cases of Covid-19 jumped substantially. On March 6th, there were a total of 226 confirmed cases across the country. Within the subsequent 48 hours, that number had nearly doubled to 425 total cases of Coronavirus. By the end of the day on March 11th, the total number of cases had surpassed 1,000.  By the end of the second week of March, the government response to the spread of Coronavirus, both locally and federally, had taken on a strikingly different tone. The White House declared a national emergency. By the time the first statewide stay at home order was issued in California on March 19th, the number of total cases had soared to 8,286 cases and the virus was confirmed present in every state. 

The experience of the Covid-19 outbreak through March and April was one of exponential growth. Even with the limited testing abilities of most counties across the United States, the reported number of total cases jumped significantly on a daily basis. On several days it doubled. By April 24th, the outbreak of Covid-19 had reached just about every county throughout the United States.

## Visualizing the Spread of COVID-19
We developed the time-series maps for this project by using two different approaches: ArcGIS Layout to GIF and ArcGIS Animation. We ultimately turned to these methods as developing a time-lapse map with such a large number of polygons presented a number of logistical challenges. Particularly throughout April when most counties across the country were reporting cases of Covid-19, the ArcGIS Pro and Online software struggled at smoothly rendering each day’s map. The two approaches, then, allowed us to draw on the maps developed in ArcGIS Pro and share a time-series product that loops and renders smoothly.

### ArcGIS Layout to GIF
This approach emerged by examining the html code of a couple of health department websites who were sharing time-lapse Covid maps of their own. Since time-series maps are essentially stop-motion style videos, we decided to take advantage of some of ArcGIS Pro’s layout features to develop our Covid time-lapse GIF. 

![ ] (covid_timelapse.gic)

Using a layout of the map, we included a line chart of the total number of cases to provide a sense of the intensity of the spread along with the visual of its geographical spread. The layout format allowed us to step through each day of the slider and export the layout at a jpeg which ultimately formed the Covid GIF.
