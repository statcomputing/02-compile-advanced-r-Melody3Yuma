# Homework 2 #

## Homework Details 
Use git to clone the source of Hadley Wickham’s Advanced R Programming from his GitHub repository to a local space on your own computer. Build the book using RStudio. During the building process, you may see error messages due to missing tools on your computer. Read the error messages carefully and fix them, until you get the book built. You may need to install some R packages, some fonts, some latex packages, and some building tools for R packages. On Windows, some codes for parallel computing may not work and need to be swapped out. Document the problems you encountered and how you solved them in an R Markdown file named README.Rmd. Push it to your homework GitHub repository so that it can help other students to build the book.

## Step 1
We need to download packages 'devtools', 'bookdown', 'knitr' and install Mactex on your computer

## Step 2
Knit the file index.rmd. Error messages include:

+ No 'lobstr' package
+ No 'emo' package; This package is not avaible on CRAN. Need to download from Hadley's repo
+ No 'sloop' package
+ No 'RSQLite' package
+ No 'zeallot' package
+ No 'profvis' package
+ No 'bench' package
+ No 'ggbeeswarm' package

## Step 3
Build the book. It is fine to directly build git_book. However, pdf_book needs some extra work.

+ The font 'Inconsolata' is a main issue. I can download the font but failed to install in the correct path. 

In overall, the remaining issue is a {\Latex} issue rather than R or Git issue. If using Windows, things may be different. 

## Conclusion
In the end, I compiled the pdf version of the book by using Mactex manually. I changed the font from Inconsolata to Georgia. There were some other warnings but the book is successfully generated (can be found in ~/adv-r/_main.pdf). The majority of the contents are there. Table of contents and references at the end of each session are missing compared to the git_book version (adv-r/_book/index.html). 