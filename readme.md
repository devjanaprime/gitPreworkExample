Week 3 Prework Git Example
====================
Git can be pretty intimidating so let's take a step by step approach.
First, let's examine the project you are asked to create for this week:  
![assignment overview](http://devjana.net/prework/week3Pics/00 assignmentOverview.png)

Get this in order. Just somethign simple with the html, css, and js files. Nothing too fancy needed. The goal here is to get you used to using Git in the terminal. You can always update this stuff later.

Project in order? OK. Now log in to github and create a new repo:
![new repo button](http://devjana.net/prework/week3Pics/01 newRepoButton.png)

Make sure to name it correctly:
![name repo](http://devjana.net/prework/week3Pics/02 nameRepo.png)

You'll now see something like the following. This is fine for now as your shiny new repo is bereft of actual content - a situation we'll shortly seek to rectify.
![new github repo](http://devjana.net/prework/week3Pics/05 gitInstructions.png)

Leave the repo URL tab open as we'll return to it later.

Next, let's open the Terminal. If you are new to Macs you'll find the Terminal in Application - Utilities:
![open terminal](http://devjana.net/prework/week3Pics/03 terminal.png)

Now we'll need to navigate to the project folder. I've put mine on the desktop in a folder named "gitExample". We'll use the "cd" command to move through the system. Usually you are at your user folder when you open terminal. From here, since my folder is on the desktop, I will use "cd desktop" to got to the desktop. Then I'll use "cd gitExample" to enter the project folder:
![navigate to project folder](http://devjana.net/prework/week3Pics/04 navigateToFolder.png)

Your project is likely not in the same folder so take a few moments to get acqainted with this process and navigate to your project's folder. You can use the "ls" command to list the files/folders in the current folder at any time.
Once you've navigated to your project folder, we'll need to initialize git and set up our repo as the "remote". Let's look at the instructions github gave us when we created the new repo:
![git instructions](http://devjana.net/prework/week3Pics/05 gitInstructionsUpdated.png)

Let's use these commands in the folder of our project in the Terminal. This will "commit" the current state of the project. At this point the changes are saved only locally. We're going to want to "push" them to our remote repo shortly.
In the example
![local add commit](http://devjana.net/prework/week3Pics/06 localAddCommit.png)



![push to origin master](http://devjana.net/prework/week3Pics/07 pushToOriginMaster.png)

If all went well, you should see a message similar to the following which lets you know that the push was successful:
![origin updated](http://devjana.net/prework/week3Pics/08 originUpdated.png)

Refresh the guthub repo page and you'll see your work is now in the remote repo:
![github updated](http://devjana.net/prework/week3Pics/09 githubUpdated.png)

Now that you've successfully pushed your project to github you'll be able to access it from wherever. If you'd like to continue to make changes you can simply add/commit when changes are made then "git push origin master" and the github repo will be updated!
