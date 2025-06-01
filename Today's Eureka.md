# Today's Eureka

## Previous Days
So far, I have figured out 
1. How to force install a package using ``` force = TRUE ``` like in the 1st example below. and how to write a package to the admin drive if the "installation paths are not writable" error message pops up (syntax below; line 2). I followed the instructions from [this link](https://stackoverflow.com/a/50364335)
```r
BiocManager::install("airway", dependencies = TRUE, force = TRUE)
BiocManager::install(c("lattice", "mgcv"), lib = "C:/Users/BARIU/AppData/Local/R/win-library/4.5")
remove.packages(c("lattice", "mgcv"), lib = "C:/Program Files/R/R-4.5.0/library")
```
2. 
## 1/6/2025
Today I figured out how to transpose a row, and by extension, any 2d object using 
```r
t()
```
I am now confused about the ~ on the next line & how to change the column name for the new dataframe I created to "ex"
