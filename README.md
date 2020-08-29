# How are the Major Player Attributes Related to the Overall Ratings of Players in Fifa 20? (An Insight using Multiple Linear Regression in Python)

## Part 1: Project Background 
  The Fifa soccer video game series has always been a passion of mine since I was twelve. I was always very curious of how the major attribute statistics of players (typically pace, shooting, dribbling, passing, physical, defending for field players and diving, handling, kicking, reflexes, speed, positioning for goalkeepers) were related to the overall statistic. I decided to explore the variables using multiple linear regression in order to predict the overall using major attributes and learn about their relationship. The code can be seen on the ipynb file in this repo, and the dataset here: https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset

## Part 2: Data Cleaning
  In this part of the project, I observed the data from a bird's eye view and decided to go deeper. Here are some of the aspects that I learned about the data and my relevant actions done.
  > The data consisted of 18278 observations and 104 columns
  > The data had no missing values 
  > The 'Player Position' column consisted of more than 600 unique positions
  > To observe how different attributes affect different players, I divided the dataset into three sub-datasets: defensive field players, non-defensive field players, goalkeepers
  
## Part 3: Exploratory Data Analysis
  In EDA, I attempted to explore the data in-depth. I observed correlation coefficients, distributions, basic statistical summaries, and pairwise plots for each of the sub-datasets. My findings include:
  > For defensive field players, Defending (r = 0.8203) and Passing (r = 0.7946) seem to have the highest correlations with overall. Pace had the lowest (r = 0.0793).
  > For non-defensive field players, Passing (r = 0.6696) and Dribbling (r = 0.5835) seem to have the highest correlations with overall. Pace (r = 0.1933) also seems to have the lowest.
  > For goalkeepers, Diving (r = 0.9489) had the highest and Speed (r = 0.4807) had the lowest correlations with overall, but other attributes such as Handling, Reflexes, Positioning all had correlation values above 0.9 and were highly correlated with overall as well. 
  > The overall statistic seem to be normally distributed.
  > The correlation coefficients were reflected on the pairplots with strong linearity for certain variables and the overall.

## Part 4: Model Building and Evaluation
  For this part, 

## Part 5: Final Thoughts and What I've Learned

## Part 6: Resources that Helped Me with this Project

https://datatofish.com/multiple-linear-regression-python/
https://searchengineland.com/heres-how-i-used-python-to-build-a-regression-model-using-an-e-commerce-dataset-326493
http://faculty.marshall.usc.edu/gareth-james/ISL/
https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset 
https://python-graph-gallery.com/74-density-plot-of-several-variables/
