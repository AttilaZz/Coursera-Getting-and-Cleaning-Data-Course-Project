# Introduction

The script `run_analysis.R`includ code that performs the 5 steps that are described in the course's final project.


* First, all the similar data is merged using the `rbind()` function. By similar, we address those files having the same number of columns and referring to the same entities.
* Then, only those columns with the mean and standard deviation measures are taken from the whole dataset. After extracting these columns, they are given the correct names, taken from `features.txt`.



# Variables