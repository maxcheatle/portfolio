---
title: Football's Fine Margins
description: Analysing and visualising West Ham's statistical performance since 2017
slug: whu
date: 2023-07-14 00:00:00+0000
image: cover.png
categories:
    - R
tags:
    - Data Analysis
    - Data Visualisation
    - Linear Regression
    - Sport
    - Football

links:
  - title: FBREF
    description: Historical repository of football team statistics
    website: https://fbref.com/en/comps/9/Premier-League-Stats
    image: https://cdn.ssref.net/req/202307011/logos/fb-logo.svg
    
---

## Intro

Here, I take a look at West Ham's statistical performance in the Premier League since the 2017/18 season. To retrieve the data, I have used web scraping with R packages `rvest` and `robotstxt`.

*Note: To protect the integrity of the website I have scraped from, I have opted not to share any of the code or raw data used.*

## The Hunt for Points

Wherever your favourite team lies in the Premier League table, the weekly neccessity to score points holds true for everyone. So, since the 17/18 season, how often do West Ham score points?

![West Ham Premier League results since 17/18](match_results.png)

Unsuprisingly, West Ham aren't exactly winning every week... But, there is a positive to take from the *relatively* high 58% rate that West Ham do score points in the Premier League.

For context, in the modern-day 38-game Premier League season, a team winning 36% and drawing 22% of games would collect 49.4 points (49). That's well clear of the pundits' famous 40 points to secure Premier League safety, and would typically be enough to finish around 10th.

## Winners and Losers

So, we've now seen that while West Ham certainly aren't the scariest football team around, they are more than capable of giving the top teams a run for their money. But, since 17/18, what teams have the East Londoner's had the most success against? Who are their bogey teams?

![West Ham's favourite opponents](wins.png)

Here, we see the 9 teams that West Ham have most frequently beat since 17/18. Unfortunately for the Hammers', only two of these teams remain in the Premier League (Fulham, Aston Villa). 

Note that some of the teams here have a small sample size, like Huddersfield, who West Ham have only played 2 times since the 17/18 season due to their single-year appearance in the top divison during the studied period. 

![West Ham's least favourite opponents](losses.png)




