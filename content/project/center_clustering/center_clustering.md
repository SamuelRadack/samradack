---
title: Clustering NBA Centers based on 2020-21 NBA Season Play Type Frequencies
subtitle: Classifying Centers into Four Offensive Archetypes
summary: By Samuel R Radack
tags:
- Data Visualization
- Basketball
- Machine Learning
- R
authors:
- Samuel Radack
- Basketball Reference
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
In today's NBA big men can occupy a vast array of roles on the offensive side of the ball. There are bigs that rely on movement such as cuts and rolls to provide offense such as Robert Williams and Dwight Powell. There are also bigs who are enabled to have a more diverse playing style because of their range of talents like Nikola Jokic and Al Horford. 
  
Grouping these center into clusters of playing styles can be informative on how offenses can be modeled around individual skill set. Take for example the way the Minnesota Timberwolves altered their playing style after the hiring of Chris Finch the lauded architect of the Joic-centric Nuggets offense. While it is likely that a team would only build an offense around one of the elite all around offensive centers, the clustering can also be used to find players whose playing style can benefit a current roster or could be optimized by a current roster. This is reflected in the Atlanta Hawks acquisition of Clint Capela. Based on the NBA's tracking data, over 70%  of Capela's play came off of what I define as movement: transition, cutting and rolling plays. This compliments the ability of Atlanta's young star, Trae Young, to play in a pick and roll scheme as an elite passer.
  
When using the nearest comparison tool to find the players with most similar play type profile to Clint Capela, one player that stood out is Isaiah Stewart of the Detroit Pistons. The Pistons have a promising arsenal of playmakers in their previous two lottery picks, Cade Cunningham and Killian Hayes. One strategy they could attempt is to fascimile the relationship of Young and Capela. This hypothetical extends further when you factor in the Pistons' signing of Kelly Olynyk. The cluster I grouped Olynyk in was the same as another young Hawks player, John Collins. I labeled this group as stretch bigs, characterised by the plurality of their plays being classified as spot ups. These types of bigs spread the floor and importantly endeavour to evacuate the paint of both themselves and their defenders. Stretch bigs can have the ability to both play alongside traditional bigs such as Capela and Collins, but also give the team the option of going small. It is important to note that this option may sacrafice as much on defense as it gains from spacing on the offensive side.
    
Another way this analysis can be utilized is by identifying ways in which a player can alter their play type distribution to maximize what they are good at. A good example for this is Lauri Markkanen, newly of the Cleveland Cavaliers. Markkanen averages 1.53 points per possession on cuts yet only has cuts as 8% of his play diet). Compare that with Robert Williams III who averages 1.59 points per possesion on cuts, but they eat up 30% of his plays. Markkanen's offensive production may be aided by a scheme in which he is encouraged to make more cuts.
    
Please find the R Shiny App attached below!


* [Application](https://samuelradack.shinyapps.io/Center_Clustering/)

