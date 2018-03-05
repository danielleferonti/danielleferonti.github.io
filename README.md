# danielleferonti.github.io
Project


---
title: "CourseRA9_Wk2_Proj"
author: "DM Feronti"
date: "February 20, 2018"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Assignment: R Markdown & Leaflet

Create a web page using R Markdown that features a map created with Leaflet.

Host your webpage on either GitHub Pages, RPubs, or NeoCities.

Your webpage must contain the date that you created the document, and it must contain a map created with Leaflet. We would love to see you show off your creativity!

```{r MyMap}
library(leaflet)
OSU_Map <- leaflet() %>%
  addTiles()
OSU_Map<- OSU_Map %>%
  addMarkers(lat = 40.0017, lng= -83.0197,
             popup ="Ohio Stadium...O-H!")
OSU_Map

```
