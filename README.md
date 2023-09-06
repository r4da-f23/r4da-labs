# Lab Workflow
## Fall 2023

This document outlines the steps you need to follow to get this file into the your local computers. 
This repo has the following structure: 

```
├── data
│   └── un_votes.csv
├── figures
├── images
│   ├── github-code-url.png
│   ├── new-project.png
│   ├── quarto.png
│   └── rstudio.png
├── README.md
├── r4da-week01.pdf
├── r4da-week01.qmd
├── r4da-labs.Rproj
└── slides.scss
```

### How to load the project into RStudio 

#### 1. Get the URL of the repo 

Scroll to the top of the page. Click on the green `Code` button and copy the HTTPS link for the repo by clicking on the clipboard icon. 

![](images/github-code-url.png)


#### 2. Import the repository in RStudio

1. Open RStudio and select `File` > `New Project` > `Version Control` > `Git`. 

![](images/new-project.png)

2. In the final window, paste the repo URL you grabbed from GitHub in the `Repository URL` window. 
Click on `Browse` to select the folder on your computer where you want to store the project. I suggest you set up a folder on your computer for all the class content and always use this as a destination to store your material for the course. Make sure there are no special characters (e.g., umlauts) in teh directory path.

3. Click on `Create Project`. 

If everything worked fine, you should now have a subfolder `r4da-labs` in the folder our selected when cloning the project. 

For in-class material, you will be granted permission to pull files (i.e. clone or download) and not upload them. You will need to `pull` to get the new `qmd` file and/or data files each week. 
