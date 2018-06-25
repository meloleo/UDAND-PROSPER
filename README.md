# Readme - Prosper Exploratory Data Analysis

## Introduction
This project uses Prosper Loan data, which includes information on 113,937 loans with 81 variables each. The overarching goal was to discover whether there are correlations between any variable (or multiple variables) and a person defaulting on a short term loan. This exploratory data analysis report uses R to parse and plot relationships between these variables.

## Installation
1. Clone my repository and the Udacity Intro to Machine Learning repository using Github Desktop or Terminal.

    ```
    $ git clone https://github.com/meloleo/UDAND-PROSPER.git
    ```

2. If necessary, install R from the [Comprehensive R Archive Network (CRAN)](http://cran.r-project.org/), and [RStudio](http://www.rstudio.com/products/rstudio/download/).
3. In RStudio, run the following to install the required packages:

    ```
    install.packages("ggplot2", dependencies = T) 
    install.packages("knitr", dependencies = T)
    install.packages("dplyr", dependencies = T)
    ```

4. Use RStudio to open and run `UDAND_PROSPER_SHEN.rmd`.
