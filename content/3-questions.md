---
title: How to Evaluate Visualizations
nav: Questions
description: Questions we can ask to start critically evaluating data visualizations
---

## Is source data cited?

Read over the full visualization and accompanying text. 
Unlabelled elements, lack of citation to data sources, and lack of authorship information should raise immediate red flags. 

Try to find out more about the data source: 
Is it authoritative and up to date? What is the quality? Are they clear about uncertainty? Is this data correct for the question? What information is missing?

Try to think about biases: 
What biases are in the data? What biases did the visualization creator introduce and what are your own that impact interpretation?
Are text descriptions biasing your impression of the data?

{% include figure.html img="https://imgs.xkcd.com/comics/convincing.png" alt="comic shows a couple breaks up because one does not label the axis of her chart" caption='<a href="https://xkcd.com/833/">xkcd Convincing</a>' %}

## Is the visualization well designed?

Choosing the wrong type of chart for the specific data and question can make a visualization misleading or confusing. 
Each chart type can help reveal specific relationships and patterns in the data, and also may create specific limitations on our ability to compare elements. 

Does the chart type support the visual argument or comparison (e.g. [Data to Viz Caveats](https://www.data-to-viz.com/caveats.html))? 

Do design elements, such as unnecessary embellishment or bad color choices, make it confusing to read?

Does the chart follow conventions and expectations (e.g. natural color progression of values, numbers rise as they go up the axis)?

Is there too many variables or data points (e.g. "spaghetti charts")?

Are statical elements used correctly (e.g. trend lines tweaked to change your perception of the data)?

{% include figure.html img="https://imgs.xkcd.com/comics/curve_fitting.png" alt="comic showing a series of the same line chart with wildly different trend lines drawn through" caption='<a href="https://xkcd.com/2048/">xkcd Curve-Fitting</a>' %}

## Is the scale correct?

One extremely common misleading feature is misusing scale in charts--such as omitting the baseline, truncating an axis, or using different axis. 
This is often done to exaggerate or diminish the appearance of change, e.g. stretch the x-axis to make line chart appear steeper or flatter.

## Is the data appropriate? 

Visualizations are summarizing and abstracting data so that we can understand complex patterns and huge volumes of information in a concise representation. 
However, this process can incorrectly omit or cherry-pick (such as removing data to smooth trends, limit scope, binning) to present only the most convincing slice of the data.
This is often confounded statistical bias and our own confirmation bias. 

{% include figure.html img="https://imgs.xkcd.com/comics/state_word_map.png" alt="comic map of USA with words across each state saying that you can manipulate the data to say anything" caption='<a href="https://xkcd.com/1845/">xkcd State Word Map</a>' %}

## Are the patterns misleading?

Are the trends or variables depicted in the visualization actually related? 

Charts make it easy to correlate causation between totally unrelated or random things, see [Spurious Correlations](https://www.tylervigen.com/spurious-correlations).
In fact, random processes rarely appear random--we want to make data into a story and naturally seek patterns in it!

Other common issues are incorrectly using absolute vs relative values, e.g. distributions on a map that simply match population density, dollar amounts compared without inflation, or failing to use per population. 

{% include figure.html img="https://imgs.xkcd.com/comics/heatmap.png" alt="comic showing three maps with the same pattern that matches population density" caption='<a href="https://xkcd.com/1138/">xkcd Heatmap</a>' %}

{% include figure.html img="https://imgs.xkcd.com/comics/base_rate.png" alt="comic showing a bar chart with 90% right handed people causing 90% of errors" caption='<a href="https://xkcd.com/2476/">xkcd Base Rate</a>' %}
