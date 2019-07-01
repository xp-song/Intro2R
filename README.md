# Intro2R

This repository contains teaching materials for an introductory 3-hour workshop to R. It is designed for those with minimal coding experience. It introduces the basics of R and the RStudio IDE (Integrated Development Environment). Just like how Microsoft Word as a software application provides many more functions than a basic text editor, an IDE provides comprehensive facilities for coding.

We will be working entirely with RStudio, and running most of our scripts in R Notebooks (files ending with _.Rmd_). R Notebooks, unlike basic R scripts (files ending with _.R_), are documents that allow us to intersperse regular text with chunks of code. Each chunk of code can be executed independently to produce outputs/visualisations, visible alongside the code inputs. This allows us to interact with our code, render documents (e.g. Word, PDF, [HTML](http://htmlpreview.github.io/?https://github.com/xp-song/photo-classify/blob/master/Photo_classification.html)) with a click of a button, and create reproducible workflows that reflect real-time changes in data. However, while RStudio and R Notebooks provide many powerful functions, please note that knowing how to use basic R scripts (even without an IDE) is still essential, for example, to execute code on high performance computing clusters.

This workshop is designed to be a crash-course. We will thus spend more time using R to organise, visualise, and perform statistical analyses on data. Hopefully this will help kick-start your journey to becoming more data-savvy :) There are many comprehensive online courses in R that cover the fundamentals of the language, which I highly recommend. Links to these materials will be provided.

## Workshop outline:

1. R environment and syntax
2. Data types and structures
3. Data wrangling and visualisations
4. Statistical analyses
5. Other useful packages


## Instructions:

Before the workshop, please install the most recent versions of [R](https://cran.r-project.org) and [R Studio](https://www.rstudio.com/products/rstudio/download/#download) onto your computer. After doing so, [download the materials for this workshop](https://github.com/xp-song/Intro2R/archive/master.zip) from the Github repository [Intro2R](https://github.com/xp-song/Intro2R). 



In the downloaded folder you will see a few important items. 

* The RStudio Project file (ending with _.Rproj_). Opening it boots up RStudio. You might want to imagine this file as a kind of 'homing beacon'. The folder it is placed in is the 'working directory', and where all sorts of (hidden) files will be stored (e.g. _.Rhistory_ containing past code you ran in the last session, _.Rprofile_ containing your preferences/settings, etc.). The _.Rproj_ file also interfaces with version control systems (i.e. Git).

* R Notebooks (ending with _.Rmd_) for each lesson.

* The _'html'_ folder. It contains the nicely rendered HTML of each _.Rmd_ file.

* The _'data'_ folder. It contains example datasets we will use in this workshop

* The _'admin'_ folder. It contains files/examples that will be mentioned during the course.

* The _'output'_ folder (empty). When generating outputs (i.e. figures, graphs), we will specify that our code exports them to this location.
