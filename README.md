# Personal-Dataset
## Motivation
Soccer has always been my favorite sport growing up. I loved to play it, I loved to watch, and when I realized it could become part of a field I love, that being statistics, I instanlty took intrest in analyzing premier league statistics. I first set out to answer the question of how do the preseason predictions for ranking compare to the current season rankings. Once I started pulling data from the FiveThirtyEight prediction tables, I found that the more interesting data for me was the how the defence and offence ranking effect premier league standings. When looking at the data they seemed to be calculated in different ways, whch made me curous as two how they calculated these numbers, and why they are based on such a small point scale. For this project I have decided to pull Offense and deffense rankings for all premier league teams fro the pre-season and current season stats to see the accuracy, the change, and the wieght these rankin ghold when it comes to the actual results of the game.

## Data Process
I collected my data from a source called FiveThirtyEight. FiveThrityEight is a website that uses statistical analysis to present compelling stories of subjects ranging from politics, entertainmnet, and sports. I was able to pull a forecast of the 2020-21 premier league standings before the season started and vs how the current season has matched up to their forecast. Since my data wasn't formed from a poll, there was no missing data, hence, I didn't have to do much cleaning in terms of the data I pulled from FiveThirtyEight. I did however, have to condense a lot fo the data to make sure I only represented what was important to my question. Of the data that was represented in the forecast I decided to only pull three of the nine columns included in the forecast.; Offense, defense, and overall pts. 

## Visualization
Visualization for pre season predictions
https://raw.githubusercontent.com/catdennis/Personal-Dataset/master/Visual%20Analysis%20for%20DA%20115-1.png

visualization for current season standings
https://raw.githubusercontent.com/catdennis/Personal-Dataset/master/current%20PL%20off%20vs%20def-1.png

## Analytics
For my analytics I have decided to perform tukeys five number summary to compare how the averages for Ofense and Defense ranking have changed throughout the season. For the preseason predictions, the five number summary for offence ranking had a;
### Minimum: 1.6, Quartile Q1: 1.7, Median: 1.9, Quartile Q3: 2.1, Maximum: 3.1. 
The maximum was predeicted to be held my Man City who was also predicted to be in first place. Similarly the defense had a five number summary of;
### Minimum: 0.2, Quartile Q1: 0.55, Median: 0.75, Quartile Q3: 0.9, Maximum: 1.0. 
The minimum score of 0.2 went to Man City aswell. It is interesting to see that in regards to these scales, it is better to have a higher rating for offence and a lower rating for defence.
I decided to compare these summaries to the current season rankings for Offense and Defense, and found that, Offense had a five number summary of;
### Minimum: 1.5, Quartile Q1: 1.75, Median: 2, Quartile Q3: 2.25, Maximum: 2.9. 
Compared to the begining of the season the maximum as decreased and the minimum has also decreased, creating a smaller inertval of data. I found it interesting that eventhoguh Man City is currently ranked 6th in the premier league, they are still predicted to finish first overall with a offense rating of 2.9. For defense the five number summary showed;
### Minimum: 0.2, Quartile Q1: 0.5, Median: 0.75, Quartile Q3: 0.8, Maximum: 1.0. 
Suprisingly there was difference in the five number summary for defense from pre season to current season. I would have suspected a larger change in defense considering there have been a lot of upsets during this season, and many times expected to finish top of table, slowly tanking down the standings.

