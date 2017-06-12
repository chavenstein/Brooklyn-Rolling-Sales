---
title: "README.md"
author: "Chris Havenstein"
date: "June 11, 2017"
output: html_document
---



*** 



![](http://www1.nyc.gov/assets/home/images/global/nyc.png) ---  **Brooklyn Roling Housing Sales** 

> (Image obtained from: http://www1.nyc.gov/assets/home/images/global/nyc.png)


## Summary


* This README.md file describes the process of running an analysis of the Brooklyn Rolling House Sales data. These house sales data include all sales from May 2016 to April 2017 for the Brooklyn borough within New York City, New York.

* The original data can be found at [The Rolling Housing Sales for NYC Website](http://www1.nyc.gov/home/search/index.page?search-terms=Rolling+sales+update).

* This project has 3 folders in the root directory.

    + data --- contains the raw data file "rollingsales_brooklyn.csv"
    
    + paper --- contains an analysis commentary file --- Analysis.md
    
    + source --- contains the R script file --- "R_rollingsales_brooklyn.R" 



## Step 1

* First, you will need to fork or clone this repo. 

> https://github.com/chavenstein/Brooklyn-Rolling-Sales



## Step 2

* Second, open the R_rolling_sales_brooklyn.R file. This file is located in -- /source/R_rollingsales_brooklyn.R .

* In R_rollingsales_brooklyn.R, set the working directory to the root folder for the project. This is in line 10 of the code in this R script file. As an example, I have provided my path below, but you will need to set your own for the root directory of the project.

    + Note that this root directory when you setwd() for the project should have the folders contained in "Summary" above.

```{r}
## Found on line 10 of R_rolling_sales_brooklyn.R file
setwd("C:\\Users\\Chris\\Desktop\\SMU information\\MSDS 6306 - Doing Data Science\\Wk5\\Brooklyn")
```

## Step 3

* After you set your working directory, as explained in step 2, feel free to run R_rolling_sales_brooklyn.R and examine the outputs for each step.

* I have provided my own analysis commentary file in "Analysis.md". However, you may find something I do not, as well!

* Have fun!