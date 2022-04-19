---
layout: post
title: Past Project Reports
date: 2022-04-18
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: project.jpeg # Add image post (optional)
tags: [projects, Cornell, Emory] # add tag
---

## OR tools for Financial Engineering

This course covers topics like AR, MA, ARIMA, GARCH models for time-series,
 Stock Returns and Volatilities, CAPM models, Bonds and Option pricing,
 Black-Scholes Equation.

This project was aiming for investigating the effects of total number of stocks
in the market on a Beta-neutral portfolio based on CAPM model.

In this project, a number of stocks returns were simulated to be all the stocks
available in the stock market.
Then a portfolio was constructed to achieve 0 Beta so that we can avoid systematic risk.

It was found that as the total number of stocks available increases, the number of stocks that should be taken short position also increases, and the ratio of short sell stocks always remain around 50% in the portfolio.

In addition, if a limit for short selling was imposed, so that there is an upper bound for the percent wealth we invest in short selling, then the portfolio returns would be negatively impacted. 

[download pdf for 5630 project]({{ site.url }}/assets/5630_presentation.pdf)


## Service System Modeling and Design

This course was designed to investigate queues. Queues are ubiquitous in our lives, and we tried to figure out the expected waiting time for customers in the line, by modeling different types of queues.

This project was about scalping, and we simulated a queue using Python with Poisson distributed arrival rate and service rate. The scalpers were inserted with a frequency, i.e. for every K-th customers in line, a scalper would be inserted, And each incoming customer would have a certain probability of willingness to purchase a swap with a scalper ahead of him/her. 

We tried different parameters to find out suitable frequency to insert scalpers, and attempted to find a pricing model that leads to the highest profit.

[download pdf for 5130 project]({{ site.url }}/assets/ORIE5130_Project_Report.pdf)


## Data Mining

This course was taken in Emory University CS470, and main topics were supervised and unsupervised learning such as Regression, Decision Trees, K-Means Clustering, K-Medoid Clustering, Hierarchical Clustering.

The project attempted to investigate the E-Sport tournament called League of Legends by finding out the most influential attribute in the game, and also clustered different teams based on their strategies and game styles. At last we hoped to predict which types of teams are more likely to win a match.

[download pdf for 470 project]({{ site.url }}/assets/League_of_Legends_Data_Mining.pdf)
