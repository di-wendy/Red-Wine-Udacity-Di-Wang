# P6
#Summary

The box plot shows the characteristics vs. Handness for the baseball players. The batting average, home run numbers and the BMI for each handness can be seen in the plot. The Batness, HR, and BMI can be clicked to review each plot.

#Data Story

In this data visulization project, the statistics of 1158 baseball players have been plotted to show the performance and characteristics of right-handed, left-handed players and players can use both hands to bat.

##Data treatment
R was used to do the pre-plot data treatment. From the following plot---left, right, both handess vs. batting average, we found a tremendous number of players have a batting average as 0.0. It is not reasonable for a professional player, so they might be pitchers who do not need to bat during the game. Those data have been screened out in our final plot.

![alt tag](https://raw.githubusercontent.com/di-wendy/P6/master/Image/Batting average.png)

##Final Plot and Conclusion
###Number of Handness
Right > Left > Both
###Handness vs. Batting Average
The left hand players  have overall higher batting average. There is no apparent difference betweeen right and both hand players regarding the 25/75 percentile.
The batting average is close to normal distribution.
##Handness vs. Homerun(HR)
The homerun distribution is very skewed. While most players have HR lower than 100, there are a few excellent individuals bat more than 500 HR.
The left hand players performed slightly better. Both hand players have the lowest HR numbers.
##Handness vs. BMI
Body Mass Index (BMI) can picture an impression about the body figure of the player. The BMI of right hand and left hand players are very similar, more than half of the players are concentrated in 24-26 (the normal weight BMI is 19-25). The both-hand players are tend to be slightly slimmer.

#Feedback
##Comment 1: 

I don’t quite understand the plot. Why the colors change? And where is the legend?

##Comment 2: 
The animation is good. However, there is no clear instruction on where to click to change the graph.

##Comment 3:
The graph is too big, occupied my screen. The Height/Weight ratio is not that understandable compared to just Height or Weigh, or we can use “Strong” to “Slim”.

##Comment 4:
I always look at the visualization first and then the README file. It wasn't clear what exactly the explanatory story was just based on the chart. 

##Comment 5:
why the BMI statistic was calculated instead of using height or weight?

#Design
1. I have added the context to explain the meaning of the line and scatter plot.

2. I have adjust the position of the graph and the location of the axis names. After shrinking the graph, the R/L/B botton became more clear to the reader.(Also applied to item 3)

4. Box plot was used instead of line plot. Legend added.

5. Values like Income/Expense is harder to interpret than just "Richness". After changing the graph to boxplot, the advantage of using BMI against "Height/weight" was not that obvious but I still kept that for the interests.

