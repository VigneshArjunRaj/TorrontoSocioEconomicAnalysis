
<h1>Geospatial Analysis of Toronto Photos and Socioeconomic Data</h1>
<h2>Overview</h2>
<p >This project conducts an in-depth geospatial analysis of Flickr photo data and socioeconomic data for the city of Toronto. The goals are:</p>
<ol class="list-decimal pl-8 space-y-2" depth="0">
<li index="0">Explore spatial autocorrelation and clustering of socioeconomic variables</li>
<li index="1">Identify and analyze areas of photographic interest using density-based clustering</li>
<li index="2">Relate areas of interest to urban planning and tourism data</li>
</ol>
<h2>Datasets</h2>
<p class="whitespace-pre-wrap">The following datasets are used:</p>
<ul class="list-disc pl-8 space-y-2" depth="0">
<li index="0">Toronto Census Tract socioeconomic data (employment, education, income, etc) from <a href="https://darribas.org/gds15/content/labs/lab_02.html">Prof. Dani Arribas-Bel</a></li>
<li index="1">Geocoded Toronto Flickr photo subset from <a href="https://darribas.org/gds15/content/labs/lab_02.html">Prof. Dani Arribas-Bel</a></li>
<li index="2">Toronto park, recreation facility, public washroom, business improvement area, and neighborhood improvement area geospatial data from the <a href="https://open.toronto.ca/">City of Toronto Open Data Portal</a></li>
<li index="3">Toronto Census Tract boundaries geospatial data from <a href="https://darribas.org/gds15/content/labs/lab_02.html">Prof. Dani Arribas-Bel</a></li>
</ul>
<h2>Analysis</h2>
<p class="whitespace-pre-wrap">The analysis includes:</p>
<ul class="list-disc pl-8 space-y-2" depth="0">
<li index="0">Choropleth maps of employment and education levels using Fisher Jenks classification</li>
<li index="1">Spatial autocorrelation analysis including Moran's I and LISA cluster maps</li>
<li index="2">Kernel density estimation and histogram analysis of variable distributions</li>
<li index="3">DBSCAN clustering to identify areas of photographic interest</li>
<li index="4">Quantile choropleth maps of photo density by tract</li>
<li index="5">Visualization of areas of interest relative to urban planning and tourism data</li>
<li index="6">Discussion of insights and use cases related to tourism, business improvement, and neighborhood planning</li>
</ul>
<h2>Usage</h2>
<p class="whitespace-pre-wrap">The full analysis is contained in the Jupyter notebook <code>geospatial_analysis.ipynb</code>. To replicate:</p>
<ol class="list-decimal pl-8 space-y-2" depth="0">
<li index="0">Clone this repository</li>
<li index="1">Install Python dependencies like <code>geopandas</code>, <code>matplotlib</code>, <code>scikit-learn</code>, etc</li>
<li index="2">Download the required datasets from the provided sources</li>
<li index="3">Run the notebook cells sequentially to reproduce the analysis and visualizations</li>
<li index="4">Refer to the report for interpretation and discussion of key findings</li>
</ol>
