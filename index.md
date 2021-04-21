### Note:
This guide assumes you have already set up Git and the Git extension in Visual Studio. If you haven't, and want to know how, [click here](https://ucsd-health-rmas.github.io/StartupGuide/) to go to the startup guide.

# Creating a New Repository
Repositories are a lot like file folders in a shared drive. To create a new repository in the organiztion's shared Github, follwo these instructions! First, in Visual Studio, click on the "Git" option in the top left, and select "create Git repository" from the dropdown. 
![CreateRepo](https://user-images.githubusercontent.com/80896632/112210899-7e1da180-8bd8-11eb-8069-dd3a11ce437e.png)

You should now see a screen like this!
![login](https://user-images.githubusercontent.com/80896632/112217124-862d0f80-8bdf-11eb-8742-40dfd62dd12b.png)

If you haven't already logged in to you Github account through Visual Studio, click the login button to open a pop-up window. Enter your username and password to link your Visual Studio to your Github account and allow Viaul Studio to push and pull files from Github. Once you've logged in, make sure you switch the "owner" field from your personal Github account to the organization's Github account (Note: This requires you to already be a member of the organization!)

![LoginWrong](https://user-images.githubusercontent.com/80896632/112217616-fb98e000-8bdf-11eb-9ca0-6952ae40d84c.png)
![LoginRight](https://user-images.githubusercontent.com/80896632/112217627-ff2c6700-8bdf-11eb-9355-2d1a9240dff9.png)

If you don't switch this field, you'll create a repository in your personal Github, which is fine, but not the goal of this guide 😅

Finally, choose a name for your new repository under "Repository name". This will be the name of the folder in the organization's Github page. Also, consider changing the name of the local repository in the top field. This is the directory where your files will be locally stored on your workstation. 
![LoginFinal](https://user-images.githubusercontent.com/80896632/112218276-c5a82b80-8be0-11eb-9fd5-88e32707e385.png)

Hit _Create and Push_ to build the repository, and that should be it! You can check on the Organization's Github page to check that the repositoryn was built sucessfully.

![CreateFinal](https://user-images.githubusercontent.com/80896632/112218521-09029a00-8be1-11eb-9ba5-2e906f8ad811.png)



# Cloning a Solution from a Repository 
### (Downloading a solution that already exists on the Github)
_Cloning_ a repository is the process of downloading a copy of the repository to your local computer. Once downloaded, you will have access to any files or code that was stored in the repository. You are then able to modify these files however you want. Once you've changed a file, you must _commit_ the changes. This updates the saved copy of the file in your local computer (the copy of the file located in the remote repository remains unchanged). In order to update the _remote_ repository located on Github/com, you must  
_push_ your _commits_ to the remote repository. See below for the step-by-step guide for doing this!

### First, click on the clone repository button from the Git dropdown
![clone repo](https://user-images.githubusercontent.com/80896632/115495824-52b0c580-a21d-11eb-867e-59041362ab37.png)

### Next, copy the link to the repository from the Github page by clicking the "Code" dropdown button
![https copy](https://user-images.githubusercontent.com/80896632/115496060-be932e00-a21d-11eb-9499-3decd7265e69.png)

### Paste that link into the repository location field in Visual Studio and hit the clone button
(Note, if you want to change where the repository is stored on your local machine, change the path directory field)
![clone](https://user-images.githubusercontent.com/80896632/115496126-dcf92980-a21d-11eb-959a-406ab737775d.png)

### That it, you're under source control! You should see the solution explorer on the side of your Visual Studio dashboard now.
![solution explorer](https://user-images.githubusercontent.com/80896632/115496243-1d58a780-a21e-11eb-90a1-cd62b743f235.png)





