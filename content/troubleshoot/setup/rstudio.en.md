---
title: "RStudio Setup"
weight: 2
---

<ol>
<li>The first step is to install <strong>R</strong>.  R is the free statistical programming language and environment that we will use in this course. You can get a copy from the Comprehensive R Archive Network (CRAN) <a href="https://cran.r-project.org/">here</a>, just follow the links under ‘Download and Install R’.

<br><br>

<li> The next step is to install <strong>RStudio</strong>. Rstudio is an alternative front end for R, which many people prefer to use. It provides an R code editor, R session window, R graphics window and other information, all in a convenient integrated environment. You can get it from <a href="https://www.rstudio.com/">here</a> at the foot of the page, under ‘R studio desktop’, or go straight <a href="https://www.rstudio.com/products/rstudio/download/#download">here.</a>

<br><br>
<li> R can be extended using packages. These are collections of functions and data that allow us to re-use code developed by others. We will be using many different packages in this course, but one of the most important will be the <strong>rmarkdown</strong> package. This package allows us to document data analyses done using R. The workshops and the homework will be done using rmarkdown so you will need to download and install this package in RStudio. We will cover how to do this in the lectures in week one, so please see the materials there if you need more help with this. The steps are:
<ol>
  <li> Open RStudio from the Start menu on your computer.
  <li> In the console (bottom left - see the demo in lectures if you are not sure!) type 

  ```{r colplot, echo = T}
  install.packages("rmarkdown")

```
  </ol>
  <br><br>
  <li> <strong>pandoc</strong> is document conversion software that is used by the rmarkdown package to convert files into different formats. To install pandoc, follow  instructions <a href="https://pandoc.org/installing.html">here</a>. 

<br>

</ol>
