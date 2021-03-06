# SPHY model Pre-Processor interface plugin for QGIS
<i>Version 1.0</i>

This interface is developed as plugin for QGIS, and is used to create SPHY model input data based on a database.   
Currently two databases are available to be used with the Pre-Processor:
<ol>
<li>Hindu-Kush-Himalaya</li>
<li>Southeast Africa</li>
</ol>

These databases can be downloaded from the <a href="http://www.sphy.nl/software/" target="_blank">SPHY model website</a>.
SPHY model manuals and case-studies can also be found on this website.

The Pre-Processor plugin uses data from Natural Earth as background layers. This is not included in this repository due
to its file size. You can download a countries shapefile and raster data from the <a href="http://www.naturalearthdata.com/downloads/" target="_blank">Natural Earth</a> website.
After downloading, create a "NaturalEarthData" folder inside the "SphyPreProcess" folder. Within the "NaturalEarthData" folder you need to:
<ol>
<li>Paste the downloaded shapefile and rename it to: "ne_10m_admin_0_countries.shp"</li>
<li>Create a "HYP_50M_SR_W" folder and paste the raster into this folder and name it to: "HYP_50M_SR_W/HYP_50M_SR_W.tif"</li>
</ol> 

<b>Minimum system requirements</b>
<ul>
<li>Windows 7 or later version</li>
<li>QGIS 2.4 or later version (32 bits is mandatory)</li>
</ul>

<b>Documentation</b>
<ul>

<li><a href="http://www.geosci-model-dev.net/8/2009/2015/gmd-8-2009-2015.pdf" target="_blank">Terink, W., A.F. Lutz, G.W.H. Simons, W.W. Immerzeel, P. Droogers. 2015. SPHY v2.0: Spatial Processes in HYdrology. Geoscientific Model Development 8: 2009-2034.</a></li>

<li><a href="https://github.com/FutureWater/SPHY/blob/SPHY2.0/SPHY_manualV6.pdf" target="_blank">Terink, W., A.F. Lutz, W.W. Immerzeel. 2015. SPHY v2.0: Spatial Processes in HYdrology. Model theory, installation, and data preparation. FutureWater Report 142.</a></li>

<li><a href="https://github.com/FutureWater/SPHY/blob/SPHY2.0/SPHY_case_studies.pdf" target="_blank">Terink, W., A.F. Lutz, G.W.H. Simons, W.W. Immerzeel. 2015. SPHY: Spatial Processes in HYdrology. Case-studies for training. FutureWater Report 144.</a></li>

<li><a href="https://github.com/FutureWater/SPHY/blob/SPHY2.0/SPHY_GUIs.pdf" target="_blank">Terink, W., A.F. Lutz, W.W. Immerzeel. 2015. SPHY: Spatial Processes in HYdrology. Graphical User-Interfaces (GUIs). FutureWater Report 143.</a></li>

</ul>

<b>Acknowledgements</b></br>
The development and publication of the SPHY model source code, its binaries, GUIs, and case-studies has been supported through various (research) projects that were partly or completely funded by the following organizations:
<ul>
<li>International Centre for Integrated Mountain Development (ICIMOD)</li>
<li>European Space Agency (ESA)</li>
<li>Asian Development Bank  (ADB)</li>
<li>World Bank</li>
<li>Rijksdienst voor Ondernemend Nedeland (RVO)</li>
<li>NUFFIC</li>
</ul>

We are very grateful to these organizations that made the development of the SPHY model possible. 
We hope to continue to collaborate with these organizations in the future in order to further develop and improve the SPHY model and its interfaces.

<b>Copyright</b></br>
Copyright (C) 2018 FutureWater. The SPHY model Pre-Processor interface plugin for QGIS is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program. If not, see <a href="http://www.gnu.org/licenses/" target="_blank">http://www.gnu.org/licenses/</a>.

Contact:
info@futurewater.nl
