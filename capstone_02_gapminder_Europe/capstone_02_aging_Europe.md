---
title: "Gapminder: Aging Europe"
subtitle: "Capstone project: BIDA 302"
author: "<YOUR NAME HERE>"
output: github_document
---

## YOUR NAME HERE



Package load:
```{r setup}

library(tidyverse)
library(readxl)

```


## Introduction

In this project, you will recreate an approximation of the chart Hans Rosling shows in the video here:

* Presentation Zen, [Hans Rosling: the zen master of presenting data](https://www.presentationzen.com/presentationzen/2010/07/hans-rosling-tips-on-presenting-data.html), 2010-07-11

This image captures the 1961 version of the plot:
![Hans Rosling, aging Europe 1961](Hans_Rosling_aging_europe.JPG)


Make three versions of the chart, each showing a different year.


### Data files

There are four files from https://www.gapminder.org/data/ that you will need; these are in the "data" folder

There are CSV files for the following:

* Population, total: "population_total.csv"

* Population, aged 60+: "population_aged_60plus_years_total_number.csv"

* Babies per woman (total fertility): "children_per_woman_total_fertility.csv"

In addition, there is an Excel file that you'll need to use to get the region that each country is in. 

* "Data Geographies - v1 - by Gapminder.xlsx", sheet = "list-of-countries-etc"




## references

For additional references, including examples of using {gganimate}, see the page for [Capstone #1](https://github.com/MonkmanMH/UVic_BIDA302_capstone/blob/master/capstone_01_gapminder_200_countries/capstone_01_200_countries.md)


