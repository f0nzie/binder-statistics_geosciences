# binder-statistics_geoscience

>   Making reproducibility stronger in Jupyter and Rmarkdown
>
>   Creating live applications from Jupyter notebooks

[![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-oilgains/data_vis_statistics_geosciences/main)

## Introduction

This is a step-by-step guide on how to turn your Jupyter notebooks into live applications by adding a remote virtual machine running in [my.binder.org](https://mybinder.org/). The virtual machine is automatically built in the background after you supply a list of the packages that your notebooks or scripts require. 

## Motivation

Although, my main objective was not writing, or develop, on how to convert Jupyter notebooks to running applications, but rather convert the Jupyter JSON format to [Rmarkdown](), and then be able to run them from remote sessions of [RStudio]() and [RShiny](), it was difficult to ignore the value that live Jupyter notebooks would bring to Python users. So, this is a by-product, or a side-effect, of my efforts of making Jupyter more reproducible through Rmarkdown.



## Credits

Thanks to the author of the original repo, [Abby Azari](https://github.com/abbyazari) on the development of Data Visualization for Geosciences.

Original repository: https://github.com/abbyazari/data_vis_statistics_geosciences



>    Alfonso R. Reyes
>
>   The Woodlands, Texas



# README

# Data Visualization & Statistics in the Geosciences 2019
UPDATE: The 2020+ versions of this class are hosted on a the following [course specific Github page](https://github.com/clasp423/data_vis_statistics_geosciences).

This repository contains the laboratory portion of a split upper level undergraduate / graduate class in Python on data visualization and statistics for geo &amp; space scientists. There are two branches hosted here from 2019 and 2018 versions of the course. 

The labs uploaded will be in Jupyter primarily and coded in Python 3.5+. However, most of the functions and methods should work in Python 2.7. If you do not have/know what Jupyter is - you can download Python/Jupyter from Anaconda or Canopy as a fully installed and interactive environment. This will support most if not all of the packages used in the labs and then you can navigate to Jupyter through Anaconda/Canopy.

Make sure you check out the [Frequently Asked Questions](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/FAQ/FAQ.md) section as you go through the labs. 

Please see our liscense at the end of this readme. This class has been developed in collaboration between [Dr. Michael Liemohn](http://clasp.engin.umich.edu/people/liemohn) of the Climate & Space Sciences & Engineering department and [Abby Azari](https://abbyazari.github.io/). The 2019 version updated with the assistance of [Brian Swiger](https://github.com/briswi). 

If you find it useful and end up using in your work please cite this as: 
- Azari, A. R., Liemohn, M. W., & Swiger, B. M. "Data Visualization and Statistics in the Geosciences". Accessed on *insert date*. github.com/abbyazari/data_vis_statistics_geosciences. 2019.



# Current Content

### [Lab 1 - Intro to Python - What is `pandas`?](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab1/Lab1_ClimaticAverages_GlobalTemperatures.ipynb)

*   Temperature Changes: Looking at Global Temperature Variances in the Last Century 

### [Lab 2 - Multi-plots and `datetime` objects](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab2/Lab2_BirdRanges.ipynb)

*   Ecosystem Impacts: Looking at Audubon Society Data on Bird Wintering Patterns

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Note: http://climate.audubon.org/article/audubon-report-glance#FAQ-4. Update for 2020  planned.

### [Lab 3 - Image Manipulation and Spacecraft Data ](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab3/Lab3_JupiterFlyBy.ipynb)

*   Jupiter Images with Jupyter: Looking at Spacecraft Image Data from the Recent Juno Mission  

### [Lab 4 - Data Merging and Indexing with Spacecraft Data](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab4/Lab4_JupiterFlyBy.ipynb)

*   Jupiter Data with Jupyter: Looking at Magnetic Field Data from the Recent Juno Mission

>    Note: For the error analysis section there are equations written in LaTeX. They might not show up with Github's preview - if you want to view these please download the Jupyter notebook.  

### [Lab 5 - Group-by, Normal Distributions & Boxplots](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab5/Lab5_NormalsTempsHealthImpacts.ipynb)

*   Health Impacts: Normal Distributions of Temperature and Boxplots of Extremes

### [Lab 6 - Linear Regression & Geo-Mapping with Sea Ice](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab6/Lab6_MappingSeaIce.ipynb)

*   Arctic Indicators: Calculating Rates of Change of Sea Ice Extent & Mapping.

>    Note: The netCDF file required for analysis must be downloaded separately. You can find the gridded ice concentration data from the [National Snow & Ice Data Center](http://nsidc.org/data/G10010). Additionally this lab is dependent on the Python packages for [netCDF-4](http://unidata.github.io/netcdf4-python/) and [Basemap](https://matplotlib.org/basemap/).

### [Lab 7 - Correlation Coefficients, Classification Problems & Space Weather](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab7/Lab7_SpaceWeatherClassifiers.ipynb)

*   Space Weather: Solar Impacts on Geomagnetic Storms

### [Lab 8 - Object Oriented Programming and Bootstrap Analysis](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/Lab8/Lab8_SpaceWeatherBootstraps.ipynb)

*   Space Weather: Linear Regression with Bootstrap Analysis

### [EXTRA Data Visualization Basics](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/VisualizationBasics/Visualization_Basics.pdf)

*   Mini lessons and lectures for the [2018 ICOS Big Data Summer Camp](https://github.com/ICOSBigDataCamp/2018-summer-camp) at University of Michigan

### [EXTRA Course Lecture - From Chart to Art](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/VisualizationBasics/CLaSP405_W19_4Visualization.pdf)

*   Lecture for course on visualization basics.

### [Frequently Asked Questions](https://github.com/abbyazari/data_vis_statistics_geosciences/blob/master/FAQ/FAQ.md)

*   Grouping of frequently asked questions on programming, visualization, and statistics.



Lab 1 <img width="1500" alt="img1" src="./Lab1/Figures/Example_TempVariants_GlobalYearlyAverages_Transparent.png">  Lab 2 <img width="1500" alt="img2" src="./Lab2/Figures/LatitudeBirds_NorthAmerica_TempAnomalies.png">

**Lab 3** <img width="1500" alt="img3" src="./Lab3/FinalPNGs/augmentedProject.png"> 



**Lab 4** <img width="1500" alt="img4" src="./Lab4/Figures/JunoCam_MagData_2017-086-08-20.png" alt="Drawing4"> 
**Lab 5** <img width="1500" alt="img5" src="./Lab5/Figures/SummerTemps.png">  **Lab 6** <img width="1500" alt="img5" src="./Lab6/Figures/2010SeaIceConcentration.png"> 
|Lab 7 <img width="1500" alt="img7" src="./Lab7/Figures/LongDurationSolar.png"> |Lab 8 <img width="1500" alt="img8" src="./Lab8/Figures/BootstrapLinearFits.png">



This README will be updated to reflect current changes. Data used in the lessons will be accredited to the providers. Lab assignments are available and will be mentioned in the tutorials but are not linked. 

Discussions with climate scientist [Samantha Basile](http://clasp.engin.umich.edu/people/sjbasile/GSTUDENT) were critical in developing these materials. We also thank planetary scientist [Camilla Harris](https://github.com/cdkharris) for discussions of Juno data, Gabriel Harp the Research Director of ArtsEngin at University of Michigan for pointing us toward climate health impact data, space scientist [Doga Ozturk](http://orcid.org/0000-0002-8071-2707) for expertise in space weather informatics, solar physicist [Yeimy Rivera](http://clasp.engin.umich.edu/people/yrivera/GSTUDENT) for expertise in solar surface data, and Jeff Lockhart of the [Computational Social Scientists](https://github.com/UM-CSS) (CSS) for offering resources through CSS.

Last update 12/4/2019

# License
The content and lessons of this repository itself is licensed under the [Creative Commons Attribution-Non Commercial 4.0 license](https://creativecommons.org/licenses/by-nc/4.0/). However, the specific code used within the notebooks taken out of context and to format and display that content is licensed under the [MIT license](https://choosealicense.com/licenses/mit/).