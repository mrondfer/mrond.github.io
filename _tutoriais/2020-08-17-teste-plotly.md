---
title: Test - Plotly
classes: wide
mathjax: true
date: 2020-08-15
tags: [matemática,plotly,gráficos]
---

<div id="tester" style="width:600px;height:250px;"></div>
<script>
        window.PlotlyConfig = {MathJaxConfig: 'local'}
</script>
<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
<script>
	TESTER = document.getElementById('tester');
	Plotly.newPlot( TESTER, [{
	x: [1, 2, 3, 4, 5],
	y: [1, 2, 4, 8, 16] }], {
	margin: { t: 0 } }, {displaylogo: false} );
</script>