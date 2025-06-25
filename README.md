# MLB-Offensive-Production-Analysis

## This repository presents an analysis of run production in Major League Baseball throughout history.

## Data Source

Sports Reference 
https://www.baseball-reference.com/leagues/majors/bat.shtml

## Contents

I turned a .csv file from Sports Reference into a dataframe and performed some basic data aggregation. I also wrote a function (cell 27) that outputs a dataframe showing the years where the runs scored per game (column 'R') is in the 90th percentile. I wrote another function (cell 28) showing the years where runs scored per game (column 'R') is in the 80th percentile. I used a while loop (cell 29) to create a dataframe containing the average runs scored per game in each decade. I performed a simple linear regression (cell 30) to model the relationship between runs (the dependent variable) and home runs (the independent variable).
