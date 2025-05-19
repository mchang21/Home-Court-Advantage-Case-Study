# Home Court Advantage Case Study

This analysis is a group project for COGS 108 - Data Science in Practice.

## Introduction

We seek to analyze whether having the home court will give the home team an advantage in the NBA. This final is largely inspired by other articles analyzing home-field advantage in the NFL in 2018 and over the pandemic. 

It is more unclear as to why there may appear to be a home-field advantage in the NFL, but an intuitive estimate is that advantages stem from not being able to hear the snap count due to the effect of crowd noise on players (Hermsmeyer). According to Hermsmeyer, this disadvantage may amount to being less effective at rushing, and based on his analysis of rushing yards, road teams average 4.27 yards whereas home teams average 4.37 yards per rush which emphasizes this hypothesis that crowd noise plays a role in home field advantage. However, it is not clear whether crowd noise is a significant factor in causing home-field advantage. Given the information above, one would also expect road teams to draw more  false start penalties; however, this assumption is false with false start penalties being called on 1.4% of home team plays and 1.34% of away team plays (Hermsmeyer). Other potential contributors to advantages that has been examined is the strain of the travel, game officials, and stadium altitude. 

Yet over the pandemic and even after the pandemic, we see home teams struggle to be able to utilize this apparent leverage with road teams winning 63-56, a 52.9% win percentage (Schalter). This is a tremendous difference for home teams compared to previous seasons considering the impact the pandemic has had in preventing fans from being able to attend games in person. Obviously, there is some factor which plays a role in giving home-field teams an advantage over road teams, and we want to analyze how this translates in other sports.

Sources: [Hermsmeyer](https://fivethirtyeight.com/features/the-nfls-home-field-advantage-is-real-but-why/) and [Schalter](https://fivethirtyeight.com/features/fans-are-back-at-nfl-games-but-home-field-advantage-isnt-yet/)

## Task

Analyze whether playing on home court provides a competitive advantage for NBA teams.

## Question

Does a NBA team playing at home have an advantage?

## Data Set

The data we are using is sourced from [Kaggle](https://www.kaggle.com/nathanlauga/nba-games?select=games.csv) where the data is collected from the official NBA stats website by user Nathan Lauga. The data consists of all NBA games ranging from 2004 - Nov. 2021. The two datasets we are using are games.csv and teams.csv. Out of the entire dataset, we are using data between the years 2009 and 2018.