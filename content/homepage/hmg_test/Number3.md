---
title: "Neighbourhoods"
weight: 4
header_menu: true
---

We can also explore the individual New York neighbourhoods. Could there be any locational differences in air pollution?

To explore this we'll take a look at some geoplots of New York City. Here below you can see an interactive map of New York containing air pollution information on the city's neighbourhoods. Can you see any pollution hotspots in the city?

{{< infobox "Try using the dropdown to change between air pollutants and the slider to see how it changes over the years!" >}}






{{< include-html "content/homepage/bokeh_plots/pollutants_multi_select_choropleth.html" "Looking at the plot we can see that there is definitely a hotspot of pollution in and around Manhattan. This trend remains pretty much consistent for either particle type as well as when scrolling through the years." "But what could be causing this hotspot and which neighbourhoods are the ones that remain consistently highest in pollution? Let's look into some different sources of pollution to try to get a better idea on what could be causing this." >}}

In the dataset we have information on both pollution due to boiler emissions for the years 2013 and 2015 as well as some traffic density information on each neighbourhood for the years 2005 and 2016. Let’s look at a geoplot of these pollutants to see if we can shed some light on the Manhattan pollution.
{{< html-side-by-side "content/homepage/bokeh_plots/boiler_multi_select_choropleth_small.html" "content/homepage/bokeh_plots/traffic_multi_select_choropleth_small.html" >}}

Looking at these geoplots we start to get an idea on why Manhattan is so polluted. The difference in boiler emissions when comparing Manhattan to any other borough is drastic. We can see that it looks like the Bronx has the most miles travelled. There is also a high amount of miles travelled in Manhattan, although the differences are not nearly as substantial as for the boiler emissions!