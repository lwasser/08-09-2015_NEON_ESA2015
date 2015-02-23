---
layout: home
description: "A NEON data workshop."
Tags: []
image:
  feature: texture-feature-07.jpg
  credit: NEON
  creditlink: http://www.neoninc.org
---

<div id="objectives">
<h2>A NEON Data Carpentry Workshop</h2>
Date: 9 August 2015, 8:30AM - 5PM
Instructors: Leah Wasser, ???
Assistants: Natalie Robinson, Claire Lunch, Kate Thibault
Special Thanks to Content Contributors: Tristan Goulden

<h2>A Hands-on Primer for Working with Big Data in R: Introduction to Common Formats & Efficient Data Visualization</h2>

<p>Ecologists working across scales and integrating disparate datasets face new data management and analysis challenges that demand tools beyond the spreadsheet. This workshop will overview three key data formats: ASCII, HDF5 and las and several key data types including temperature data from a tower, vegetation structure data, hyperspectral imagery and lidar data, that are often encountered when working with ‘Big Data’.  It will provide an introduction to available tools in R for working with these formats and types.</p> 

<p>In the first half of the workshop, we will learn how to (1) access and visualize large datasets in these formats using R, and (2) to use metadata to efficiently integrate datasets from multiple ecological data sources for analysis. In the second half of the workshop, we will apply the knowledge from the first half to work through a practical example of integrating field-collected vegetation structure data with remotely sensed LiDAR data. For this example, we will use data collected by the National Ecological Observatory Network (NEON), a continental-scale, NSF-funded effort to collect and freely serve terabytes of data per year (stored in a diversity of formats) over the next 30 years to enable ecological research. </p>
<p>Participants will leave the workshop with a basic understanding of the data that NEON and other large projects offer and some basic tools that support the use of Big Data to enhance their own research. </p>


<h3>Goals / Objectives</h3>
After completing this activity, you will:
<ol>
<li>Understand what the Hierarchical Data Format (HDF5) is.</li>
<li>Understand the key benefits of the HDF5 format, particularly related to big data. </li>
<li>Understand both the types of data that can be stored in HDF5 and how it can be stored / structured.</li>
</ol>

<h3>What You'll Need</h3>
<p>Internet access and a working thinking cap.</p>

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