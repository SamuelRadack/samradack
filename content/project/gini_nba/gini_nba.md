---
title: An Examination of NBA Roster Salary Distribution
summary: By Samuel R Radack
tags:
- Economics
- NBA
- Basketball
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

  There are a vast number of ways to construct an NBA roster given the limitations of the collective bargaining agreement. One strategy would be to load up on All NBA caliber players such as the 2020-2021 Brooklyn Nets with Kevin Durant, James Harden and Kyrie Irving. In contrast, you could also build a team by adding players who contribute in smaller roles but when put together are more valuable than the sum of their parts. The 2003-2004 Detroit Pistons are a good example of this with Ben Wallace, Chauncey Billups, Rasheed Wallace, Tayshaun Prince and Richard Hamilton.
  
  
  This project will evaluate the larger trends of how teams have divided their money amongst their players from the 1990-1991 season through the present day. The data collected for this project was sourced from https://www.basketball-reference.com.


   The measure of inequality that I will use is referred to as the Gini coefficient. The measure comes from the field of economics and is used to evaluate the statistical dispersion of a monetary value of a population. The Gini coefficient is calculated by taking the sum of the products of quantiles of a population and their corresponding shares of value which those populations hold. This could be examining the share of wealth that the five quintiles of US citizens hold. For this project, we can get more granular by looking at the share of each player on a roster.
   
   
  Below is an example of a Lorenz curve. This is the visualization of how the Gini coefficient is calculated. In our example, we use data from the 2020-2021 Brooklyn Nets. The diagonal line in the diagram would represent a roster with perfect equality. This would mean the salary of all the players is equal for that given year. The Gini coefficient is equal to the area of the blue shaded area under that diagonal line divided by itself. That value is equal to 1. Intuitively, a perfectly unequal salary distribution, where only one player is paid, would tend towards a Gini coefficient of 0. The Nets’ Lorenz Curve is represented by the curved line and the red shaded are under that line. The gini coefficient for them would therefore be the red area divided by the area under the diagonal curve. This leads to a gini coefficient of 0.176. This is a relatively unequal distribution when compared to the larger landscape of NBA history.
  
  
![lorenz_curve](/img/lorenze_curve.png)
  
  Next we will analyze the trend in the median gini coefficient by year. In the visual below the blue line represents the downward tendency of salary equality in the past three decades. The vertical redlines show the years when the collective bargaining agreements were renegotiated. These renegotiations do not have a clear effect on the inequality of player’s salaries. One thing that is interesting to note is the rise in the median gini coefficient in the 2020-2021 season. This is likely due to the way two-way contracts were handled by the NBA. Because those two-way players counted on the rosters, the max contracts represented a smaller portion of the roster.
  
![gini_over_time](/img/gini_over_time.png)

  Finally, we will examine the relationship between salary distribution and team success. Below is a scatter plot of the gini coefficient and winning percentage of each team from the 1990-1991 season until the present. Playoff teams are colored green and championship teams are colored blue. There is no clear trend to be drawn from this relationship. What we can glean from this is that there is no correct way to distribute salary between players, at least when it comes to the equality of their contracts.

![team_performance](/img/team_performance.png)

  In the future I would like to explore the implications of total salary cost on team performance. I assume that this may present a stronger relationship (a team that pays the luxury tax is likely doing so to maintain a roster of high quality player). I would also like to examine a measure of inequality based on usage percentage and minutes played. Could sharing on court responsibility in a more equitable way yield better results, or should teams aim for a heliocentric style offense like those of the James Harden Rockets and Luka Doncic Mavericks.

