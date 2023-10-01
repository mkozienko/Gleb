This folder contains all the important code (functions, types of statistical analysis, grapths, etc) we came up with during our research in more or less chronological order. 


1) Masting0 -- MASTREE PLAYGROUND.Rmd
This document serves as an introduction to R language if needed.


2) masting1--initial exploration -- final.Rmd

This document provides instruction on how to get the Masting data that we were using.
It also shows our first (failed) attempt to get the climate data


3) Masting2--functions for climate and get address-- final.Rmd

This document has functions and code chunks we were using to get climate data and add it to our masting data.
Most likely you will not need it unless you want to get extra data.

Items of interest:
- cdsDownload()
    Function to download ERA5-Land climate data (in form of .nc files) from the Copernicus website using the ecmwfr package.
    
- mastFaSyl()
    Function that unpacks .nc files with climate data downloaded with cdsDownload(), turns it into data frame.


4) masting3 -- initial versions of masting threshold and visualizations -- final.Rmd

This document has initial versions of masting threshold functions, as well as visual exploration of how well these functions work.

FEEL FREE TO IGNORE THIS DOCUMENT COMPLETELY, AS UPDATED VERSIONS OF THESE FUNCTIONS ARE PRESENT IN "masting4 -- define mast years, compute mast periods" RMD file.


5) masting3.5--k-means vs k-medians -- final.Rmd

This code introduces another threshold metod that we tried -- k-medians.
It also serves as a demonstration why we used k-medians as one of the thresholds instead of k-means.

FEEL FREE TO IGNORE THIS DOCUMENT COMPLETELY, AS UPDATED VERSIONS OF THESE FUNCTIONS ARE PRESENT IN "masting4 -- define mast years, compute mast periods" RMD file.


6) masting4 -- define mast years, compute mast periods -- final.Rmd

This document has initial versions of masting threshold functions, UPDATED versions of masting threshold functions, function to compute mast periods (intervals between mast years), as well as visual exploration of how well these functions work.

Items of interest:
- functions that classify years as mast versus nonmast based on the relative size of seed output
    * ADM_funct()
    * ADCY_all_sites()
    * MSD_orig()
    * KMDN()
- function that computes mast periods (intervals between mast years)
    * mast_intervals_from_study()



7) Masting5 -- Initial Statistical Analysis -- final.Rmd

This document contains our initial attempts to statistical analysis. 
Statistical analysis that we focused most of our time on is present in the folder "Statistical analyses for different species"
(~R code/Final RMDs for future research, cleaned/Statistical analyses for different species)
However, some of the methods described here may be worth revisiting.

Items of interest:
- permutations test
- t-test
- Linear Mixed-Effects model
- Binary logistic regression 

