# ML-learning-Project
This project is created for EL-GY 9123 at NYU Tandon taught by [Sundeep Rangan](http://wireless.engineering.nyu.edu/sundeep-rangan/)

## Problem
How does one predict sales for a game based on genre, publisher, and platform?

#### Features
* genre
* publisher
* platform

#### Output
* US sales

## Hypothesis
There is a high correlation between the 3 features to predict game sales.

## Things to Note
* All game sales are in millions
* A bad game is defined as sales under 5 million
* A good game is defined as sales 5 million < 10 million
* A best seller is defined as sales over 10 million
* All data after 2015 was droped due to the data being pulled in Oct 2016

## Information Breakdown
1. Use file from [Kaggle](https://www.kaggle.com/gregorut/videogamesales)
2. Import data and verify it's correct
3. System statistic breakdowns
  * XBox
  * XBox 360
  * PC
  * Playstation
  * Playstation 2
  * Playstation 3
4. Combine information for analysis
5. Training of data
6. Testing on popular games for PS4 and XBox 1
  * Crash Bandacoot 3; PS4; activision & sony interactive entertainment
  * Watch Dogs 2; PS4, PC, and XB1; Ubisoft
  * Destiny 2; PS4, PC, and XB1; activision
  
## Things Learned
1. Hypothesis rejected
2. Companies probably use other featuers to project there sales due to the low accuracy used off the consumer considerations.
