---
title: An Examination of Premier League Attacker Values
summary: By Samuel R Radack
tags:
- Economics
- Soccer
- Machine Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: 

links:
# - icon: 
 # icon_pack:
 # name: 
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Historically, the transfer value of footballers has been an opaque idea. This may be due to the lack of transparency and regulation of finances in the European leagues. The website, Transfermrkt, is a trusted source to approximate these values. Their methodology relies on the wisdom of the crowds to determine each player's value.

The goal of this project was to use the event tracking data from Football Reference to model the Transfermarkt values. I originally started this project before the pandemic so the data I use is from the 2019-2020 season. Additionally, I only modeled Premier League attacking players because it is logical to assume each position group and league has different metrics which contribute to a player’s transfer value. I have updated this project to include multiple methods of predicting a player’s value including: linear regression, logistic regression, LASSO, support vector machine, random forest, neural network and general additive model.

The potential explanatory variable in my models include: age, minutes played, goals, assists, expected goals, non-penalty expected goals, expected assists, shots, shots on target, key passes, passes in the final third, passes in the penalty area, crosses into the penalty area, shot creating action dribbles, goal creating action dribbles, tackles in the middle third, presses in the attacking third, touches in the attacking third, touches in the attacking penalty area, drib successes, dribble attempts, targets, receptions, aerial duels won, height, and games. The response value was the Transfermarkt value for that season. Many of the explanatory variables were related to each other such as minutes and games. Logically, the more games a player plays, the more minutes that player will accumulate. To visualize this possible explanatory redundancy I create the correlation plot displayed below. Blue circles represent a positive correlation while red circles indicate a negative correlation with the darkness of each circle representing the magnitude of the correlation.

	

