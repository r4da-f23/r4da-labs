# Week 1: Meet the Toolkit 
## February 14, 2023

This repo contains the material for our first code-along. To proceed, you need to install all the software on your machine. You can find the instructons on our course website: https://r4da.live/resource/install.html. 

This repo contains the files and folders:

- `Readme.md`: the current file
- `week01_meet_the_toolkit.Rproj`: the RStudio project file
- `r4da_week01.qmd`: the Quarto markdown document (main file with analysis)
- `r4da_week01.pdf`: PDF file with the output from `r4da_week01.qmd`
- `r4da_week01.html`: HTML file with the output from `r4da_week01.qmd`
- `.gitignore`: internal file which controls the files that are tracked in version control 
- `data/un_votes.csv`: dataset in comma separated values format 
- `images`: subfolder with images by files in the repo 
- `r4da_week01_files`: subfolder with files for HTML output document 


Your first step should be to clone the repository onto your machine. This is how you can do it:

### How to load the project into RStudio 

#### 1. Get the URL of the repo 

Scroll to the top of the page. Click on the green `Code` button and copy the HTTPS link for the repo by clicking on the clipboard icon. 

![](images/github-code-url.png)


#### 2. Import the repository in RStudio

1. Open RStudio and select `File` > `New Project` > `Version Control` > `Git`. 

![](images/new-project.png)

2. In the final window, paste the repo URL you grabbed from GitHub in the `Repository URL` window. 
Click on `Browse` to select the folder on your computer where you want to store the project. I suggest you set up a folder on your computer for all the class content and always use this as a destination to store your material for the course. 

3. Click on `Create Project`. 

If everything worked fine, you should now have a subfolder `week01_meet_the_toolkit` in the folder our selected when cloning the project. 

For in-class material, you will normally be granted permission to pull files (i.e. clone or download) and not upload them. 
