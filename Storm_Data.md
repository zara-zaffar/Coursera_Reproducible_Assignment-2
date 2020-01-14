# Coursera Reproducible Research: Course Project 2

## Severe weather events in the US and their impacts on health and economy

# Synopsis

In this report, we aim to analyze the impact of different weather events on public
health and economy based on the storm database collected from the U.S. National 
Oceanic and Atmospheric Administration's (NOAA) from 1950 - 2011. We will use the
estimates of fatalities, injuries, property and crop damage to decide which types 
of event are most harmful to the population health and economy. From these data, we 
found that excessive heat and tornado are most harmful with respect to population 
health, while flood, drought, and hurricane/typhoon have the greatest economic 
consequences.

## Data Processing

The raw data were available from a URL provided by the Coursera project instructions, and were downloaded using the download.file() function in R:

```{r, echo
download.file("https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2","storms.csv.bz2")

```}
