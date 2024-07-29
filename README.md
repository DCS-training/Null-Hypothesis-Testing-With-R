# Null Hypothesis Testing With R

This two-class course will focus on developing theoretical and practical skills for null hypothesis testing in R.

The course will begin with a brief overview of statistics and go on to cover different types of null hypothesis testing methods and how to choose the right one.

The course will ultimately build on an understanding of basic statistical analysis and show how more complex statistical analyses can be used in R. The relatively advanced techniques and theory behind all of this are highly applicable to wider concepts and will allow you to apply and build on the core concepts with your own research.

Learning outcomes: 

Deepen understanding of fundamental hypothesis testing concepts, including types of variables and their associations 
Understand the different test/post hoc test and their relationship with the type of variables 
Be able to choose the appropriate testing according to datasets and hypotheses 
Know how to report results 
This is an intermediate-level course. A basic understanding of R and statistical analyses is assumed. Attendees will need to be familiar with the RStudio interface and how to run code in it.


# Installing R and Packages needed 
## Installing R and R Studio
### For R On Noteable

1. Go to https://noteable.edina.ac.uk/login
2. Login with your EASE credentials
3. Select RStudio as a personal notebook server and press start
4. Go to File > New Project> Version Control > Git
5. Copy and Paste this repository URL [https://github.com/DCS-training/Null-Hypothesis-Testing-With-R](https://github.com/DCS-training/Null-Hypothesis-Testing-With-R) as the Repository URL (The Project directory name will be filled in automatically but you can change it if you want your folder in Notable to have a different name).
6. Decide where to locate the folder. By default, it will locate it in your home directory
7. Press Create Project
Congratulations you have now pulled the content of the repository on your Notable server space.

### Install it locally
1. Go to (https://www.r-project.org/)[https://www.r-project.org/]
2. Go to the download link
3. Choose your CRAN mirror nearer to your location (either Bristol or Imperial College London)
4. Download the correspondent version depending if you are using Windows Mac or Linux
- For Windows click on install R for the first time. Then download R for Windows and follow the installation widget. If you get stuck follow this (video tutorial)[https://www.youtube.com/watch?v=GAGUDL-4aVw]
- For Mac Download the most recent pkg file and follow the installation widget. If you get stuck follow this (video tutorial)[https://www.youtube.com/watch?v=EmZqlcKkJMM]
5. Once R is installed you can install R studio (R interface)
6. Go to (www.rstudio.com)[www.rstudio.com]
7. Go in download
8. Download the correspondent version depending on your Operating system and install it. If you get stuck check the videos linked above. 

## Install the libraries 
```
install.packages("tidyverse")


library("tidyverse") #for cleaning and sorting out data

``` 

# What you are going to find in this repo
Once ready, you are going to find 

-  .ppt presentations used during the course
-  example code 


# Author
 Fang Jackson-Yang

# Copyright

This repository has a [![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/) license

