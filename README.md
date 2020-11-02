# Data Visualization project on Space Missions

## The dataset used for this project is available at [Kaggle](https://www.kaggle.com/agirlcoding/all-space-missions-from-1957). It includes data about Space Missions since 1957.
Data attributes include: <br />
* Company Name that is associated with the Space Mission <br />
* Location of the launch <br />
* Date and Time of the launch <br />
* Details describing the mission <br />
* Status Rocket stating whether Rocket is Active or Retired <br />
* Rocket <br />
* Status Mission stating whether the mission was a success or a failure <br />

## Prototypes

1. Below is a stacked bar chart that shows the Number of Space Missions by Company color coded by the status of the mission.<br />

[![image](https://user-images.githubusercontent.com/51784083/94752416-2b65da00-0359-11eb-8a70-958394a4aa75.png)](https://vizhub.com/naisargidave/1264b2b5b1254558afa43c4759c15742)

2. Here is a stacked area chart that shows the total number of space missions over the years where each company is represented by a different color. <br />

[![image](https://user-images.githubusercontent.com/51784083/94752748-1d648900-035a-11eb-8bbe-6845a96b9ca2.png)](https://vizhub.com/naisargidave/565903655f0e4171af91a310afc13e55)

## Tasks:

* How do the number of missions for each company vary over the years?
* What percent of the total number of missions were a sucess and what percent of the missions failed?
* Which location had the most number of successful missions and which one had the most number of failed missions?

## Sketch:

Below is a rough sketch of the world map that shows a pie chart which represents the aggregated mission status for different countries. This visualization would be helpful in determining which location had the most number of successful missions and which one had the most number of failed missions.

![image](https://user-images.githubusercontent.com/51784083/94753273-b9db5b00-035b-11eb-8174-09014a869b7a.png)

## Uncertainty:

Creating a map visualization is a challenge in itself and the above shown sketch combines that with pie charts for different countries. Developing the above shown sketch as a full blown visualization is a challenge.

## Deliverables schedule

| Task      | Deadline |
| ----------- | ----------- |
| Develop and Refine the First Chart | 14 Oct 2020 |
|  Develop and Refine the Second Chart | 21 Oct 2020 |
| Develop and Refine the Third Chart | 28 Oct 2020 |
| Integrate all the charts and provide navigation between them  | 04 Nov 2020 |
| Check the documentation in all the visualizations | 04 Nov 2020 |

## Interaction

* Add a Dropdown to select the attribute for x-axis of the chart.
* Add Brushing technique where the user is able to select the year range in the chart.

## Project Outcome 

1. The stacked bar chart shows the Number of Space Missions by Company/Country/Status Rocket color coded by the Status of the Mission. The dropdown selection is used to determine the x-axis of the visualization. 

[![image](https://user-images.githubusercontent.com/51784083/97826682-3c737500-1c90-11eb-9aba-58a7ff10cbae.png)](https://vizhub.com/naisargidave/db10fd5f23ba404eb4bfdd578053a5fd)


2. Number of space missions by country are displayed on the word map. The size of the circle is proportionate to the number of missions for that country. The histogram executes brusing where only the year range selected is displayed on the map.

[![image](https://user-images.githubusercontent.com/51784083/97826725-5a40da00-1c90-11eb-976d-b0838e888ddf.png)](https://vizhub.com/naisargidave/a3e37b300fb54af2b25d98e2389d2d1f)


3. The scatter plot shows the number of space missions trend from the year 1955 to 2020 for USA, China, Kazakhstan and Russia where hovering over the color legend highlights the trend for that country.  

[![image](https://user-images.githubusercontent.com/51784083/97826753-747ab800-1c90-11eb-9d78-18300f54c789.png)](https://vizhub.com/naisargidave/af177a5813b14088baaf2a987141bee0)

## Future Work

Combine the map visualization with a pie chart showing the number of missions by mission status for each country. 
