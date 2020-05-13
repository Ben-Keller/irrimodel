---


---

<h1 id="irrimodel-v1.0">IrriModel v1.0</h1>
<p>An open source irrigation model and interactive visualization tool. For use by researchers, technology developers, financiers, and development agencies to assess the climatic datasets linked to irrigation and the potential impacts of irrigation technology and financial schemes.</p>
<p>The interface for IrriModel was developed using Jupyter notebook widgets, and this allows the entire functionality of the model and each of its functions can be explored through interactive maps and charts.</p>
<h3 id="model-parameters">Model Parameters</h3>
<p>distance to market, population size, market prices by crop, cropping intensity increase, changes in supply/demand, and expected increase in production per water input ?</p>
<h2 id="model-design">Model Design</h2>
<p>The model primarily exists in three files:</p>
<p><a href="github.com/ben-keller/irrimodel/irriModelInterface.ipynb"><strong>irriModelInterface.ipynb</strong></a></p>
<p>The interface is the central component of interacting with and displaying the parameterized maps and charts which are implemented in the python script.</p>
<p><a href="github.com/ben-keller/irrimodel/irriModel.py"><strong>irriModel.py</strong></a></p>
<p>All functions used in the Jupyter script are defined in this python script. There are general functions for geoprocessing of spatial datasets, as well as specialized functions for working with .</p>
<p><a href="github.com/ben-keller/irrimodel/irriModelParameters.xlsx"><strong>irriModelParameters.xslx</strong></a></p>
<p>The parameters xlsx file allows a user to control the input variables for several components of the model, including:</p>
<ul>
<li>Suitability factor thresholds for irrigation technologies</li>
<li>Soil suitability factor thresholds for irrigation</li>
<li>Crop metadata (coefficients, season timing)</li>
<li>County metadata and country level datasets</li>
<li>Farm Typologies</li>
</ul>
<p>For more examples and usage, please refer to the <a href="github.com/ben-keller/irriModel/Documentation.pdf">Documentation.pdf</a> file.</p>
<h2 id="development-setup">Development setup</h2>
<p>Run the file <a href="http://irriModelTest.py">irriModelTest.py</a> (link here???) to check if all dependencies are ready. This was developed in Python 3.6.</p>
<p>OS X &amp; Linux &amp; Windows:</p>
<pre class=" language-sh"><code class="prism  language-sh">python test/irriModel.py
</code></pre>
<h3 id="libraries">Libraries</h3>
<p>jupyter,rasterio, matplotlib, IPython, ipywidgets, cartopy, gdal, csv, io, json, requests, zipfile, numpy, collections, pandas, mpl_toolkits, scipy, time, folium, imageio, geopandas, fiona, datetime, calendar, WaporAPI, os.path, osgeo, shapefile, shapely, operator</p>
<h2 id="input-datasets">Input Datasets</h2>
<p>All datasets with a license to allow redistribution (CC BY 3.0 and 4.0) are available as a bulk download zip file <a href="link?????">here</a>. Any datasets with data available through their API has the download code in the data download section of the Jupyter Notebook.</p>
<p>All other datasets are available as download links in the metadata file here. Instructions for how to organize your file structure so the model can find every dataset, as well as attributions for all datasets can be found in the <a href="github.com/ben-keller/irriModel/Documentation.pdf">documentation</a>.</p>
<h2 id="release-history">Release History</h2>
<p>Version 0.1 - May 29th 2020 (not publicly released)</p>
<h2 id="authors">Authors</h2>
<ul>
<li><strong>Ben Keller</strong> - <a href="https://www.linkedin.com/in/benjaminckeller/">linkedin.com/in/benjaminckeller/</a></li>
<li><strong>Tess Russo</strong></li>
</ul>
<p>This project was created by <a href="https://www.intellectualventures.com/what-we-do/global-good-fund/our-work">Global Good at Intellectual Ventures</a> with funding from the Gates Foundation Venture Trust.</p>
<h2 id="license">License</h2>
<p>Distributed under the MIT or CC BY 4.0??? license. See <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a><br>
for more information.</p>
<p><a href="https://creativecommons.org/licenses/by/4.0/"><img src="https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg" alt="License: CC BY 4.0"></a></p>
<p>(<a href="https://github.com/ben-keller/irriModel/">https://github.com/ben-keller/irriModel/</a>)</p>
<h2 id="model-documentation">Model Documentation</h2>
<h3 id="function-category-1">Function Category 1</h3>
<h4 id="function-1">Function 1</h4>
<h4 id="function-2">Function 2</h4>
<h4 id="function-3">Function 3</h4>
<h4 id="function-4">Function 4</h4>
<h4 id="function-5">Function 5</h4>
<h3 id="function-category-1-1">Function Category 1</h3>
<h4 id="function-1-1">Function 1</h4>
<h4 id="function-2-1">Function 2</h4>
<h4 id="function-3-1">Function 3</h4>
<h4 id="function-4-1">Function 4</h4>
<h3 id="function-category-1-2">Function Category 1</h3>
<h4 id="function-1-2">Function 1</h4>
<h4 id="function-2-2">Function 2</h4>
<h4 id="function-3-2">Function 3</h4>
<h4 id="function-4-2">Function 4</h4>
<h3 id="hydrology-model">Hydrology Model</h3>
<p><img src="https://i.ibb.co/nD3MXV9/water-balance-v1-01.png" alt="enter image description here"></p>
<h4 id="function-1-3">Function 1</h4>
<h4 id="function-2-3">Function 2</h4>
<h4 id="function-3-3">Function 3</h4>
<h4 id="function-4-3">Function 4</h4>

