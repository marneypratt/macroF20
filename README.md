# Macroinvertebrate Data Analysis for Bio 131 Fall 2020

### by Marney Pratt

### Last updated on October 15, 2020

This webpage details how to download this project which includes all the files you need to analyze data for your Freshwater Macroinvertebrate Project for Bio 131.

It is assumed that you have access to R and Rstudio (installed on your computer or access to an RStudio cloud-based server) and that you know how to install any needed packages.


## Download this repository from GitHub using the usethis package

This series of instructions will copy all the files you need from here on GitHub to your computer or cloud-based RStudio. 

1. If you haven't already installed the usethis package (you can check your list of packages to see if it is already there), then install the usethis package by typing this code into the RStudio console and press Enter:

`install.packages("usethis")`

2. Once the package is installed, then you need to load usethis. This is similar to opening an app on your phone or computer. To load usethis, type this code into the RStudio console and press Enter:

`library(usethis)`

3. To download the repository, use this code:

`use_course("https://github.com/marneypratt/macroF20/archive/master.zip")`


4. When told "Downloading into..." "OK to proceed?" select the number for the option next to "I agree" and note what directory it is putting the zipped file into. (Note that you can move the files later if needed)

5. When asked "Shall we delete the ZIP file" select the number for the option that says "Definitely"

A new session of RStudio will open with the unzipped folder containing all the files you need ready for you.

## Download this repository from GitHub as a ZIP file

If the above method does not work, then just download the repository as a zip file.  

1. In the GitHub repository, gor to the green "Code" button and "select Download ZIP"

2. Save the zipped file somewhere on your computer where it will be easy to find again

3a. If you are using the desktop version of R and RStudio, extract all the files from the ZIP file somewhere on your computer where you are keeping all your R files.  

3b. If you are using a cloud-based version of RStudio, then import the ZIP file directly into RStudio using the Import function under the Files tab in the lower right window of RStudio.

4. Browse to the folder with all the unzipped files using the Files tab in the lower right window of RStudio. Click on the "macroF20.Rproj" project file to open the project and begin working.

