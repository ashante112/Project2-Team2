<h1>Global Volcanic Activitiy Visualizer</h1>


<h2>Providing users an interactive means to explore data themselves</h2>


  

<p>Project involves creating a visualization of volcanic activities worldwide.</p>
<p>In light of the current volcanic eruption of Saint Soufrere which took place in Saint Vincent and Grenadines, this project focuses on bringing awareness to the scope of volcanic activities in an interactive and geographic visualization. This is a great opportunity to learn how scientists can use data to view trends in natural phenomena to make predictions on eruptions and proactively save lives.</p> 


<ul><li>Visualizations are creted utilizing  Python Flask–powered API, HTML/CSS, JavaScript, and PostgreSQL</li>
<li>Custom “creative” D3.js project (i.e., a nonstandard graph or chart)</li>
<li>Combination of web scraping and Leaflet and Plotly</li>
<li>Dashboard page with multiple charts that update from the same data</li><ul>


<p float="left">
<img src = "https://github.com/ashante112/Project2-Team2/blob/main/Images/leaflet1.png" width=400 height=200>
<img src = "https://github.com/ashante112/Project2-Team2/blob/main/Images/leafletWithMarker.png" width=400 height=200>
<img src = "https://github.com/ashante112/Project2-Team2/blob/main/Images/interactive.png" width=400 height=200>
<img src = "https://github.com/ashante112/Project2-Team2/blob/main/Images/webScrape1.png" width=400 height=200>
</p>
  
<h2>Data Sources:</h2>

<ol><li><h3>Smithsonian Institution: Global Volcanism Program</h3>
<p>Site: <a href="https://volcano.si.edu/search_volcano.cfm">https://volcano.si.edu/search_volcano.cfm</a>
  <p>File Type: <a href="Data/GVP_Volcano_List.xls">Excel</a></p>
<p>"Volcanoes of the World" is a database describing the physical characteristics of Holocene volcanoes and their eruptions. This search returns a list which may be filtered based on a volcano name, volcano type, features, evidence of recent activity, location (set using a map), country, rock types, population within various distance ranges, or the availability of images. Name and country searches will also return subfeature names and synonyms; using other filters will result in only primary volcano names being returned. A standard set of fields is shown on the screen display, but full results with additional content may be downloaded into an Excel spreadsheet.</p></li>

<li><h3>NOAA: Significant Volcanic Eruption Database</h3>
<p>Site: <a href="https://public.opendatasoft.com/explore/dataset/significant-volcanic-eruption-database/information/">https://public.opendatasoft.com/explore/dataset/significant-volcanic-eruption-database/information/</a></p>
<p>File Type: <a href="https://public.opendatasoft.com/api/records/1.0/search/?dataset=significant-volcanic-eruption-database&q=&facet=year&facet=tsu&facet=eq&facet=name&facet=location&facet=country&facet=type&facet=status&facet=deaths_description&facet=missing_description&facet=injuries_description&facet=damage_description&facet=houses_destroyed_description&facet=total_deaths_description&facet=total_missing_description&facet=total_injuries_description&facet=total_damage_description&facet=total_houses_destroyed_description&facet=houses_damaged_description">Json</a></p>
<p>The Significant Volcanic Eruption Database is a global listing of over 500 significant eruptions which includes information on the latitude, longitude, elevation, type of volcano, and last known eruption. A significant eruption is classified as one that meets at least one of the following criteria: caused fatalities, caused moderate damage (approximately $1 million or more), with a Volcanic Explosivity Index (VEI) of 6 or larger, caused a tsunami, or was associated with a major earthquake.</p></li>

<li><h3>Oregon State University / Volcano World / Deadliest Eruption</h3>
  <p>Site: <a href="http://volcano.oregonstate.edu/deadliest-eruption">http://volcano.oregonstate.edu/deadliest-eruption</a>
<p>File Type: Web scraping</p>
<p>The list contains eruptions with more than 500 known human fatalities. These are the most deadly eruptions known. Other eruptions have been as big or bigger than these, but no one lived nearby to be threatened (for example the Valley of 10,000 Smokes eruption in Alaska in 1912). The Mt. St. Helens eruption in 1980 in Washington state was a far less dangerous eruption than these, only 61 humans died, although thousands of deer and other animals perished.</p></li>
</ol>

 
