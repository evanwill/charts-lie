---
title: Examples
nav: Examples
---

<svg id="line-chart"></svg>
<script src="{{ '/assets/lib/chart.xkcd.min.js' | relative_url }}"></script>
<script>
    const svg = document.getElementById('line-chart');
    const lineChart = new chartXkcd.Line(svg, {
  title: 'Monthly income of an indie developer', // optional
  xLabel: 'Month', // optional
  yLabel: '$ Dollars', // optional
  data: {
    labels: ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10'],
    datasets: [{
      label: 'Plan',
      data: [30, 70, 200, 300, 500, 800, 1500, 2900, 5000, 8000],
    }, {
      label: 'Reality',
      data: [0, 1, 30, 70, 80, 100, 50, 80, 40, 150],
    }],
  },
  options: { // optional
    yTickCount: 3,
    legendPosition: chartXkcd.config.positionType.upLeft
  }
})
</script>

Look at the example *line chart* above to identify the basic elements of a data visualization. 

- "scaffolding": titles, legends, scales, byline, sources
- visual elements: size, shape, color, position, brightness, texture, orientation
- visual argument

## Explore Examples

- [The Data Visualization Catalogue](https://datavizcatalogue.com/)
- [Periodic Table of Visualization Methods](https://www.visual-literacy.org/periodic_table/periodic_table.html)
- [Data to Viz](https://www.data-to-viz.com/)
- [Data and information visualization, on Wikipedia](https://en.wikipedia.org/wiki/Data_and_information_visualization)
- [Gapminder resources](https://www.gapminder.org/resources/)
- [Visual Vocabulary](https://ft-interactive.github.io/visual-vocabulary/)
- [Data Viz Project](https://datavizproject.com/#)
- [A Map of Places in the US with the Same Name](https://pudding.cool/2023/03/same-name/)
