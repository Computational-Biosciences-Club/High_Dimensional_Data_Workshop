# Using R Studio Cloud

R studio is an integrated development environment (IDE) for the R language and provides a lot of utility to anyone writing R code. Luckily, the developers of Rstudio developers have created a cloud solution for easy setup and access all through a web browser.

### Creating an Account

Creating an account on Rstudio cloud is straightforward. To break it down into steps:
1. Go to https://rstudio.cloud
2. Click "Sign Up" on the top right of the homepage
3. Do not worry about the toggle for Plus, if the dialog box says "Cloud Free" you can click "Sign Up"
4. Either use Google, Github, or create an account through their system

### Getting Started
After signing up for an account you'll be taken to a page called "Your Workspace" where all your projects will be listed (you shouldn't have any if this is your first time!). Think of Projects like individual server instances, these are separate environments that don't interact with one another. Each one may have many different R scripts, packages, and other files. For example, I made a new project for each homework assignment I had during a class. You can create different Workspaces as well using the sidebar on the left, but for now we'll focus on just creating a project.

##### Please note, there is a built-in tutorial for Rstudio on the top right of the Environment tab labeled "Tutorial". It will ask you to install the learnr package, but after doing so will walk you through a lot of the basics and is highly suggested if this is your first time using these tools. The following is just a basic layout tutorial to help you understand what you're looking at.

#### To create a new Project:
1. Click on the blue button labeled "New Project" on the top right of the Workspace page
2. You'll get a drop down, select "New Rstudio Project"
3. The project may take some time to load while the server spins up your instance (setting aside resources for you, loading up R and Rstudio)
4. Once done you'll be taken straight to the Rstudio interface. You can name your project by clicking the "Untitled Project" dialog on top.

#### Uploading Files
You will need to upload the data files to your cloud project directory before you can work with them. Keep in mind that this is your default working directory after creating a project, and so all files and directories in your scripts will be read relative to it. 

To upload a file during your Rstudio Cloud session:
1. In the Files pane (this will usually be on the right side of the screen) click "Upload". 
2. Click "Browse..." under "File to upload".
3. Choose the file on your local machine that you would like to upload.

Keep in mind this only allows you to upload one file at a time, so if you would like to upload multiple files your options are to upload the files one by one or upload a compressed .zip file that will be automatically expanded upon uploading. 

### Understanding Rstudio
All things considered, Rstudio is a lot if it's your first time seeing it. I'll definitely miss some things, but here's some basic areas of the screen to pay attention to:
- Toolbar (top, thin bar): This is very similar to any other toolbar in a file system/text editor. It includes options for dealing with the R session running in the background (Session tab) as well as opening/saving/etc files (File tab). 
- Editor/Console (left, text box): This is where all text entry-related tasks will occur. Console (command-line R session), Terminal (Bash terminal giving you access to the server running this instance), and any text files you open will be available for editing and viewing here.
- Environment (top right): This panel lists off useful things related to whatever you're doing in Rstudio at the moment. When you set any variables, load something into memory, or create functions they will show up in the Environment tab. 
- Files/Plots (bottom right): This is where you can use a file explorer-type tool to look at the current directory structure. You can load a file into the editor simply by clicking on it here, just like in Windows/MacOS. You can also view any plots you've created in this panel by clicking the "Plots" tab, there are arrows to move back and forth through all the plots currently in memory. All of these functions have handy options at the toolbar on top of the panel to save plots, ***upload data from your computer to the cloud session***, and more.

##### It was stated above, but just to reiterate: the easiest way to upload any local data/files to the cloud session is to start your project, and then click the "Upload" button on the "Files" tab of the Files/Plots panel on the bottom right.
