
## Table of Contents 
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)

## General Information
This repository consists of the files from meta-analyses section of the project "Music Interventions to Improve Sleep in Adults with Mental Health Problems: A systematic review and meta-analyses".

## Technologies Used
Project was created with: 
* R version: 4.2.0 (2022-04-22)
* RStudio version: 2023.06.1+524
* MacOS Monterey version: 12.3

## Setup

### Viewing Results 
To view the R codes and results of the meta-analyses: 
* Download the file "Music_Meta.html" from the repository.

### Replicating Results in R
To re-run or replicate the results in R: 
* Download the R Markdown file "Music_Meta.Rmd".
* Download the required data files: 
  - "sleep.csv"
  - "depression.csv"
  - "anxiety.csv"

**Note:** Ensure all the .csv data files are in the same folder as the Markdown file when running the code. Alternatively, you can use the Github path of the .csv data files in your R code 

``` R
# Example using Github path 
dat_sleep <- read.csv ("https://raw.githubusercontent.com/Tuesday1234567/music_meta/Updating/sleep.csv")

    




