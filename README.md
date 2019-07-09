# Intro2R

This repository contains teaching materials for an introductory workshop to R. It is designed for those with minimal coding experience. It introduces the basics of R and the RStudio IDE (Integrated Development Environment). Just like how Microsoft Word as a software application provides many more functions than a basic text editor, an IDE provides comprehensive facilities for coding.

We will be working entirely within RStudio, and running most of our scripts in R Notebooks, which are documents that allow us to intersperse regular text with chunks of code. Each chunk of code can be executed independently to produce outputs/visualisations, visible alongside the code inputs. This allows us to interact with our code, render documents (e.g. reports, presentations, webpages) with a click of a button, and create reproducible workflows that reflect real-time changes in data.  

This workshop is designed to be a crash-course. We will dive right into organising, visualising and analysing data, to give you a taste of the power of R and its potential applications. Hopefully this will help kick-start your journey to becoming more data-savvy :) Please note that it is not meant to be a lesson in statistics, or to substitute learning the fundamentals of the language. There are many comprehensive online courses in R which I highly recommend. Links to these materials will be provided in the slides.

## Workshop outline:

1. Getting Started
1. R Environment and Syntax (slide deck 1)
2. Data Wrangling and Visualisation (slide deck 2)
3. Other Applications


## Instructions:

Before the workshop, please install the most recent versions of [R](https://cran.r-project.org) and [R Studio](https://www.rstudio.com/products/rstudio/download/#download) onto your computer. After doing so, [download the materials for this workshop](https://github.com/xp-song/Intro2R/archive/master.zip) from the Github repository [Intro2R](https://github.com/xp-song/Intro2R). 



In the downloaded folder you will see a few important items. 

* The RStudio Project file (ending with _.Rproj_). Opening it boots up RStudio. You might want to imagine this file as a kind of 'homing beacon'. The folder it is placed in is the 'working (home) directory', and where all sorts of (hidden) files will be stored (e.g. _.Rhistory_ containing past code you ran in the last session, _.Rprofile_ containing your preferences/settings, etc.). The _.Rproj_ file also interfaces with version control systems (i.e. Git).


* The _'notes'_ folder. It contains the course notes in _.Rmd_ format (R Notebooks) and nicely rendered HTML.

* The _'slides'_ folder. It contains the presentation slides for the workshop (view HTML).

* The _'data'_ folder. It contains example datasets we will use in this workshop.

* The _'output'_ folder (empty). When generating outputs (i.e. figures, graphs), we will specify in our code to export files to this location.
