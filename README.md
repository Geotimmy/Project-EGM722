# Project EGM722
 How to guide

Building maps with Python

Introduction

This is a how to guide on developing maps using python. 
The guide shows you how to make two types of maps of Iceland using data provided on a GitHub repository. Map one is a map of the counties of Iceland, roads and rivers and the second is a Choropleth map showing the population of Iceland per county. You also learn how to use a python to generate a GeoDataFrame, slice, merge and join geospatial data. Thus, you develop a basic understanding of using python which is widely used to speed up data analysis in a GIS and Remote Sensing environment.
“Don't spend your time doing work a well-trained monkey could do. Even if you've never written a line of code, you can make your computer do the grunt work” (Sweigart A, 2019)

Setup and Installation

Step 1: 
In order to access and run the code you need to install and sign up to GitHub and install Anaconda on your computer. GitHub is a community where developers can create repositories work together or alone on software and projects using code. To install GitHub, you can follow instructions from this website here: https://git-scm.com/downloads. Anaconda is “The birthplace of Python data science “(Anaconda.com) which brings various data science communities and technologies together to develop machine learning.  To install Anaconda, go to this website: https://docs.anaconda.com/anaconda/install/.

Step 2: 

To access the codes repository, you need to first clone the repository to your computer
1.	In Github Desktop select File> Clone Repository.
2.	Select the URL tab, and then enter the following:      https://github.com/Geotimmy/Project-EGM722.git
3.	Open Git Bash (from the start menu) then navigate to a folder dedicated to this tutorial. Now, type in the following command:  
git clone https://github.com/Geotimmy/Project-EGM722.git
You should see some notifications about unpacking and downloading files. The repository should then be set up.

Step 3:

Once the repository is cloned you need to create a conda environment to work through the script. You can use the environment.yml file provided in the repository. If you have Anaconda Navigator installed, you can Import from the bottom of the Environments panel.
Alternatively, you can open command prompt (with Windows you can use Anaconda command prompt)
First navigate to the folder where you cloned the repository and run the following command:
C: Users\Geotimmy> conda env create -f environment.yml
This can take a little time to run

Step 4:

Starting Jupyter-notebook 
In Anaconda Navigator check that the environment Project-EGM722 is activated (there should be a ‘base root ‘and a second environment)
Using anaconda prompt, navigate to the folder where the guide is located (like you did in the previous step) then active your new environment (conda activate Project-EGM722). Launch Jupyter-notebook and navigate to the folder where the how to guide (EGM722-assignment) is located.
Launch the notebook (jupyter-notebook.exe), which should launch a web browser window and give you an overview of the folder. Then open the file. 
Dependencies
Required dependencies:
•	matplotlib
•	cartopy
•	Pandas
•	geopandas
•	shapely

Test data

The test data was sourced from three free online websites:
Diva GIS
https://www.diva-gis.org/gdata  
Data used was Country: Iceland
•	Administrative areas
•	Roads
•	Gazetteer
Mapcruzin
https://mapcruzin.com/free-iceland-arcgis-maps-shapefiles.htm
•	Iceland Waterways
•	Iceland Points of interest 
Population statistics were sourced from:
Hagstofa
Population by municipalities, sex and age 1 January 1998-2020 - Current municipalities. www.hagstofa.is. Statistics Iceland. 1 January 2020.
This data was exported as a CSV file on the website.
GitHub Repository Link: https://github.com/Geotimmy/Project-EGM722.git
