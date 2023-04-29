---
name: Final Project Part 3.1
tools: [Python, HTML, vega-lite]
image: IS445/assets/chart1.png
description: by John Gadomski
custom_js:
  - vega.min
  - vega-lite.min
  - plotly
  - matplotlib.pyplot
---

# Unleashing the Power of NFL Big Data: An Interactive Exploration
#### The National Football League (NFL) is one of the most popular sports leagues in the world, with millions of fans tuning in each week to watch their favorite teams and players. But what goes on behind the scenes? How do coaches and players use data to gain an edge on the competition? In this article, we will take a deep dive into the world of NFL data and explore some of the most fascinating insights and trends from the past few seasons.
By John Gadomski <br />

Final Project Part 3.1

Our primary dataset will be the NFL Big Data set, which contains a wealth of information on player and team performance. Using this dataset, we will create an interactive visualization that allows users to explore player performance across different variables, such as speed, acceleration, and distance traveled. Users can select specific games or players to analyze, and the visualization will update in real-time to show how different variables impact performance.

Main Interactive Visualization: 

Analyzing player height and weight in the NFL can provide us with valuable insights into the sport. By using position as a tooltip variable, we can observe how different positions require different physical attributes. For example, players like cornerbacks and wide receivers tend to be smaller in stature and have lower body weights. On the other hand, positions like offensive and defensive linemen require larger body sizes and higher body weights.

This information can be useful for coaches and team managers when selecting and training players for specific positions. It can also help in identifying potential talent based on physical attributes. Additionally, analyzing player height and weight can provide insights into trends and changes in the sport over time, such as changes in playing styles and positions. Overall, analyzing player height and weight can provide valuable information for improving player performance and enhancing team strategy.

![figure 01](/IS445/assets/chart1.png)
Figure 1: br />

![figure 01](/IS445/assets/newplot.png)
Figure 1: br />

As a user, I can hover over the data points on the scatter plot and see the player name in the tooltip that pops up. By using the tooltip feature to check for player name, I can quickly identify specific players on the plot and see where they fall in terms of their height, weight, and position. This could be particularly useful for coaches and analysts who are looking to evaluate players' physical attributes in order to determine their role on the team or their potential for success at the professional level.

Analyzing the tendencies of players' height and weight by position can provide valuable insights for NFL analysts and coaches. For example, knowing that cornerbacks and wide receivers tend to be smaller and lighter than other positions, such as linemen or linebackers, can help coaches make more informed decisions when drafting or signing players. By analyzing the height and weight of successful players at a particular position, coaches and analysts can also identify physical attributes that may be indicative of success in that position. This type of analysis could help teams identify hidden gems in the draft or free agency, or help them make more informed decisions when building their roster. Ultimately, understanding the tendencies of players' height and weight by position can help teams gain a competitive advantage in a league where even small differences can make a big impact.

![figure 04](/IS445/assets/chooseplayer.png)
Figure 3: <br />
Creator: John Gadomski  <br />
Description: Interactive Plot that allows you to choose specific player and see their height, weight, and position


![figure 01](/IS445/assets/chart1.png)
Figure 1: br />

![figure 02](/IS445/assets/chart2.png)
Figure 3: <br />
Creator: John Gadomski  <br />
Description: <br />

![figure 03](/IS445/assets/chart3.png)
Figure 3: <br />
Creator: John Gadomski  <br />
Description: <br />

![figure 04](/IS445/assets/chart4.png)
Figure 3: <br />
Creator: John Gadomski  <br />
Description: <br />


Contextual Visualization #1: 
To provide a broader context for our analysis, we will include a chart showing the distribution of player positions across the league. This visualization will allow users to see how different positions are distributed and may help explain some of the trends we observe in our primary dataset. 


{% include elements/button.html link="https://github.com/jgadomski/jgadomski.github.io/blob/main/_data/NFLPlayer.csv" text="The Data" %}
{% include elements/button.html link="https://github.com/jgadomski/jgadomski.github.io/blob/main/python_notebooks/%5BIS445%5DFinalProjectPart3Code.ipynb" text="The Analysis" %}

Source of data: https://www.kaggle.com/competitions/nfl-big-data-bowl-2020 
