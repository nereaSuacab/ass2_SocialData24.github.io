---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Assignment 2
---

## Introduction

The main goal of this study is to analyze a dataset that contains crime reports in San Francisco between the years 2003 and 2018. This dataset has different information that can be taken into account for the project. The essential details are the location, date and resolution. Therefore, with the wide range of incident cateogries and geographic coverage, it offers insights into long-term crime trends and patterns. 

Our foucs is on the crime category of "UNDER INFLUENCE OF ALCOHOL IN A PUBLIC PLACE" since we would like to know how has evolved during the years and its presence during the week days and times of the day. In our opinion, since the incident is related with alcohol, we think that it might be more common during Fridays and Saturdays and at night. However, we should analyze the data to confirm these facts. Moreover, the location of where these crimes took place is also relevant.

![Image Description](images/plot1.png "Figure caption test")

In order to asses the prevalence of the specific chosen crime, we created a subplot of three different analyses. First of all, we wanted to know the presence of being in a public place under the influence of alcohol along the week. Given that social gatherings and festivities are more prevalent on weekends, we anticipated heightened alcohol consumption during these periods. Observing the bar plot, indeed validates this assumption revealing a higher occurrence of the crime on Saturdays and Sundays.

Another crucial aspect to evaluate was the timing of these offenses, therefore we generated a polar plot. It can be observed ithat the focal crime usually occurs during nighttime hours (between 9 pm and 12 pm) and extends into the early morning (between 12 pm and 3 am). These findings align with the notion that individuals tend to engage in this offense when they are out partying, usually at night.

Finally, a comparative assessment of the crime presence between the initial and final years of the dataset was done through the calendar plots created with *calplot*. Taking into account the colorbar that denotes varying degrees of crime prevalence, dark red and orange cells indicate lower occurrences, while blues and purples mean heightened incidences. Therefore, **it becomes evident that the incidence of public intoxication has decreased over the course of the dataset, particularly notable in the year 2017 where an increase of darker red-orange cells is observed**.

In reflection, the decline of this specific crime highlights the importance of taking proactive steps to address it. We could think of various factors that can drive to this decrease, like changes in societal attitudes towards alcohol, stricter enforcement of laws, and increased education on responsible drinking. It is important for authorities that, even though the prevalence of this crime decreased over the years, keep doing what they are doing to keep or even reduce more the number of offenses and create safer environments.

<iframe src="images/scatter_plot.html" width="100%" height="500px"></iframe>

## Map 

<object data="images/crime_map_2013.html" width="100%" height="500px"></object>

