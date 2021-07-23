---
title: College Basketball Reference Data - 2021 NBA Draft Comparisons
subtitle: Finding 2021 NBA draft prospec's three nearest neighbors from 2014 draft onwards

# Link this post with a project
projects: []

# Date published
date: "2020-12-13T00:00:00Z"

# Date updated
lastmod: "2020-12-13T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- Samuel Radack
- Basketball Reference

tags:
- Data Visualization
- Basketball
- R
---
![plot]()

An R Shiny Application for visualizing a given draft prospect's three nearest neighbors. Only players who played in college are included in the data set. To adjust the "importance" of each distance factor, use the sliders on the left. You are able to "zero out" distance factors. This means you could try to find an offensive comparison by "zeroing out" all of the defensive metrics. The method used is finding the Euclidian distance between players given the listed statistics. The app runs slowly due to the amount of data that needs to be recalculated when adjusting the weights.

* [Application](https://samuelradack.shinyapps.io/NBA_draft/)
