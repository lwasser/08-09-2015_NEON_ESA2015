---
layout: home
description: "A NEON data workshop."
Tags: []
image:
  feature: texture-feature-07.jpg
  credit: NEON
  creditlink: http://www.neoninc.org
---

#A Hands-on Primer for Working with Big Data in R: Introduction to Common Formats & Efficient Data Visualization
##A NEON Data Carpentry Workshop

<div id="objectives">

<p><Strong>Date:</Strong> 9 August 2015, 8:30AM - 5PM </p>
<Strong>Instructors:</Strong> 
<ul>
<li>Leah Wasser, Senior Scientist, NEON Education / Data Products </li>
<li>does anyone else want to actually teach? OR just assist? open to whatever! </li>
</ul>

<Strong>Assistants:</Strong> 
<ul>
<li>Natalie Robinson</li>
<li>Claire Lunch, NEON Staff Scientist, Data Products</li> 
<li>Kate Thibault, NEON Senior Scientist, FSU</li>
<li>Mike Smorul, SESYNC</li>
<li>Ian Munoz, SESYNC</li>
</ul>

<Strong>Content Development Team:</Strong> 
<ul>
<li>Tristan Goulden, Staff Scientist AOP</li>
<li>Sarah Elmendorf, Staff Scientist Data Products</li>
</ul>

<p>This workshop will providing hands on experience with working hierarchical data formats(HDF5), and lidar data in R. It will also cover spatial data analysis in R. </p>

<a href="http://lwasser.github.io/08-09-2015_NEON_ESA2015/about/">Read Full Abstract Here.</a>


<h3>Goals / Objectives</h3>
After completing this workshop, you will:
<ol>
<li>Know what the Hierarchical Data Format (HDF5) is.</li>
<li>Know How to create and read from HDF5 files in R.</li>
<li>Know what liDAR data are.</li>
<li>Know how to work with spatial raster data in R </li>
</ol>

You will also learn more about:
<ol>
<li>Hyperspectral remote sensing data</li>
<li>Lidar Data.</li>
</ol>

<h3>Before the Workshop Please</h3>
<p>Download All Data Here</p>
Install Packages using this script. Package list includes:
* GDAL
* RHDF5

</div>

##SCHEDULE


| Time        | Topic         | Instructor | Download Data |
|-------------|---------------|------------|---------------|
| 8:30-9      | Setup / Intro | ??         |               |
| 9-10:30     | Topic 1       |            |               |
| 10:30-10:45 | BREAK         | Coffee     |               |
| 10:45-12:00 | Topic 2       | ??         |               |
| 12:00-1:00  | LUNCH         |            |               |
| 1:00-3:00   | Topic 3       | ??         |               |
| 3:00-3:15   | BREAK         | ??         |               |
| 3:15-5:00   | Topic 4       | 15         |               |


##Setup
To participate in the workshop, you will need working copies of the software described below. Please make sure to install everything (or at least to download the installers) before the start of the workshop.

#HDFView

Hierarchical Data Format 5 (HDF5) is a file format used to store, package, and simultaneously organize large quantities of related data. Although we will use R to analyze data stored in this format, HDFView is free-ware that allows for quick and easy viewing and editing of these files.

#R

R is a programming language that specializes in statistical computing. It is a powerful tool for exploratory data analysis. To interact with R, we recommend, but do not require, RStudio, an interactive development environment (IDE). We will use several packages, including rhdf5 and gdal. DOWNLOAD (1) the package installation script here, (2) the gdal libraries, and (3) the hdf5 libraries.

#Optional resources

##QGIS

QGIS is a cross-platform Open Source Geographic Information system.

Online LiDAR Data Viewer (las viewer)

plas.io is a Open Source LiDAR data viewer developed by Martin Isenberg of Las Tools and several of his colleagues.