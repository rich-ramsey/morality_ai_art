This project is the aesthetics morality project with Ionela and Emily, which was based in Zürich. 

# Project folder and file structure #

## R project file ##

All files and folders are based within an R project called 'morality.Rproj'

## Within each experimental folder (exp1, exp2), there are three main R markdown files: ##

1. wrangle.Rmd

This file wrangles raw data, produces some summary data plots, saves out data files for modelling and further analysis in later scripts.

2. model.Rmd

This file builds Bayesian regression models.

3. effects.Rmd

This file visualises and tabulates parameters.

## Within each experimental folder (exp1, exp2), there are five folders, which have largely self-explanatory titles: ##

1. /figures/
2. /tables/
3. /models/
4. /data/
5. /fits/

Note - you will need to create these folders in each experimental folder *before* you run the code, otherwise R will complain.

# Raw data and models #

Due to the large size of some of the models, which are too big for github, please download these files from the open science framework: https://osf.io/d4zme/.


# What is the easiest way to access this project? #

If you want to see and work with the code, then:

1. Clone, fork or download the project from github to your local machine.
See this link for the difference between cloning and forking. https://github.com/orgs/community/discussions/35849

2. Open the morality.Rproj file and renv() will automatically bootstrap itself.

3. Use renv::restore() to install all of the packages. Say yes.

4. At this point, you can use the project with the same package versions that are stored in the renv.lock file.

# System requirements #

Data analysis was performed in the R programming language (v4.4.0; R Core Team, 2024). 
All package dependencies were recorded and controlled via renv(). 
For an introduction to renv() for package management, see here: https://rstudio.github.io/renv/articles/renv.html.



