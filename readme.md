GE Lab 
======

# Overview #####
Ge Lab is the home page of our orgnization. 
The contain are mainly static.

In order to make the maintaining easily, we decide to use R Markdown generate these pages we need.
And, thanks to github.io, we can host the site on github.

# Structure
Project has two major folder: **code/** and **docs/**. 
**code/** saves all _.Rmd_ files that used to generate the web pages.
**docs/** saves all web pages we generated by _.Rmd_ files. 

# Build and publish

## Build whole site
1. Start R console at project folder (or setwd([directory project folder]) ) 
2. Execute `rmarkdown::render_site(input = "code", quiet=TRUE)`
3. Result will save in **docs/** folder

## Build a page
Click Knit in RStudio will update the changes of that page into **docs/** folder.    

## Publish
Commit and push will publish the site to github.io automatically.

# Notice
Please do not add, delete or modify anything in **docs/** folder unless you are going to create pages manually.
