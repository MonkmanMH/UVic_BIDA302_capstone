---
title: "Gapminder: 200 Countries, 200 Years"
subtitle: "Capstone project: BIDA 302"
author: "<YOUR NAME HERE>"
output: github_document
---


Package load:
```{r setup}

library(tidyverse)
library(readxl)

```


## Introduction


In this project, you will recreate  single year versions of the chart Hans Rosling shows in the video here:

* Gapminder, [200 Countries, 200 Years, 4 Minutes](https://www.gapminder.org/videos/200-years-that-changed-the-world-bbc/)




### Data files

The four files that you will need, downloaded from https://www.gapminder.org/data/, can be found in the "data" folder of this project.

There are CSV files for the following:

* Income: "income_per_person_gdppercapita_ppp_inflation_adjusted.csv"

* Life expectancy (years): "life_expectancy_years.csv"

* Population: "population_total.csv"

In addition, there is an Excel file that you'll need to use to get the region (continent) that each country is in. 

* "Data Geographies - v1 - by Gapminder.xlsx", sheet = "list-of-countries-etc"






## References

https://towardsdatascience.com/how-to-build-animated-charts-like-hans-rosling-doing-it-all-in-r-570efc6ba382


