# DKKZ1 
## Explanation for files
### 2.R 
the r script file, code for how to scrape the data from the web, if you run the code, you might get the file as same as All_data
#### packages need
RSelenium, rvest,purrr,dplyr,ggplot2,plotly,countrycode,data.table
### assessment_shiny
the app.R file for shiny, if you tap the **'Run App'** button in R studio you will get R shiny application for three interactive visualisation
#### packages need
shiny,ggplot2,dplyr,plotly,countrycode
#### dataset need
The file already contains a copy of dataset **all_data1**, ensure that you set up the working directory correctly, if the dataset in the file is damaged due to compression, please copy **all_data1** and move into the file, to ensure that the code can run properly
### Assignment Cover sheet_SRI_
the cover sheet for this task
### dkkz1.qmd
the Quarto file, if you tap the **'Run Document'** button in R studio you will see the results in the 'Viewer' which is on the bottom right of the R studio
#### dataset need
ensure that the dataset **all_data1** is in the working directory
### dkkz1
html file for dkkz1.qmd, due to unknow reasons, three interactive visualisation seems can't run successfully in this file
### dkkz1_files

### All_data
the dataset scraped by **2.R**, .csv format
### all_data1
the dataset **All_data** after clean and tidy, .csv format
