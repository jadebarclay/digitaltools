---
section: Analysis
nav_order: 4
title: Data visualisation 
topics: Tableau; RAWGraphs; PowerBI
description: >
    No matter what tool you use, you'll need a little bit of training to make good data visualisations.
# youtubeid: moJgWrD6dwg
---

The Library has produced an [online introduction](https://sway.office.com/O9vEKmTmBXPxGOnE) you might find useful.

{% capture dataviz %}
- [Data to Viz](https://www.data-to-viz.com/): Helps you to decide which type of graph is appropriate to your data. 

- [Tableau](https://public.tableau.com): academics and students have access to the full desktop version (see the [Tableau Gallery](https://public.tableau.com/en-us/s/gallery) for some great inspiration)

- [RAWGraphs](https://app.rawgraphs.io): Free and open source, secure browser-based visualisation (you can also run it locally, i.e. outside of a browser). Intended to 'bridge gap between spreadsheet applications and graphics editors'. Version 2.0 beta is available.

- [PowerBI](https://powerbi.microsoft.com): Connects well with other Microsoft data sources but costs money to use.

- [Prism](https://www.graphpad.com/scientific-software/prism/)

- [Chart.js](https://www.chartjs.org): Simple yet flexible JavaScript charting for designers & developers. 

{% capture bestdataviz %}
**Our recommendation: Tableau**

Tableau can produce beautiful results quickly and is free to academic researchers. It's not supported by the University — but neither are any of the others.
{% endcapture %}

{% include alert.html text=bestdataviz color="primary" %}

{% endcapture %}

{% include card.html header="<i class='fas fa-eye'></i> Data visualisation tools" text=dataviz %}

{% capture chartjs %}
<div>
  <canvas id="myChart"></canvas>
</div>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script> 

<canvas id="myChart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById('myChart');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            y: {
                beginAtZero: true
            }
        }
    }
});
</script>
{% endcapture %}

{% include card.html header="<i class='bi bi-chart-bar'></i> Sample Chart.js output" text=chartjs %}

Activity: Want to try out some data visualisation? Of course you do!

{% include button.html text="Go to the Tableau activity" link="activity-tableau.html" color="info" %}
