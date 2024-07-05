---
layout: default
title: GitHub Page
has_children: false
parent: Lab Basics
has_toc: false
nav_order: 2
---

# Keeping The GitHub Page Up to Date
This GitHub page is the hub of all lab protocols, procedures, and best practices. Therefore, it is important that it be kept up to date! Whenever IRB changes impact recruitment practices, platforms change, personnel change, or other protocol-impacting changes occur, they should be reflected on this site. The following steps will go over the very basics of upating this GitHub repository. 

## Quick GitHub Edits
GitHub edits can be done either directly through the GitHub site or, for more complex and involved edits, by pushing changes from Visual Studio Code (VSC) into GitHub. If you are adding a section to an existing page or tweaking a procedure, it may be easiest for you to directly edit the pages docs. To do this, navigate to the [Baller_Lab_Guide repository](https://github.com/Baller-Lab/Baller_Lab_Guide/tree/master) in the Baller Lab GitHub Organization. Click on the `Code` button and, in the left-hand toolbar, navigate to the `docs` folder and to the `Lab_Basics` and `study` subfolders. Once you select the page you would like to update, you can switch from the page `Preview` function to the page `Edit` function by clicking on the pencil in the upper right hand corner of the page preview. This will allow you to directly update the page by entering [Markdown](https://www.markdownguide.org/cheat-sheet/) text into the file. Once you are finished editing, you'll hit the green `Commit Changes` button in the upper right corner of the window. You will add a quick message about what changes you made to the file and then commit them to the repository.

## How to manually publish Git website if it fails to update after commits
In the Baller_Lab_Guide repository, click "Settings", and go to "Pages" (on the left). At the top, you should see the following: "Last deployed by @ballere ballere 4 minutes ago." Click the "deployed" hyperlink, and at the top right of the screen, click "Re-run all jobs." This will manually build your page. Once the full build is complete (all dots green), recheck the website to make sure it works.

A couple of other settings to verify in "Pages." 

1. Build and Deployment: Source -> Deploy from branch
2. Branch: master /root

Setting to verify in "Actions" (left side of page

1. Click "General"
2. Verify first bubble clicked: Allow all actions and reusable workflows

## Updating the Baller_Lab_Guide Repository Using VSC
The Baller_Lab_Guide is a repository inside the Baller_Lab organization. It contains all files that are fundamental to producing the `Just the Docs` page that you are currently reading and folders with markdown outlining all of the information in the website subpages. You will be mostly concerned with the contents of the folder `docs`. 

`docs` contains two folders: `Lab_Basics` and `study`. `Lab_Basics` contains the files outlining lab infrastructure, the Wix page, and this page. The `study` folder contains all files detailing how to execute a research visit in the Baller Lab. As the lab grows, you can add more folders and pages to meet the lab's needs. However, to do this, you will need some familiarity with GitHub and Visual Studio Code. Luckily, there are many tutorials online that will help answer any questions you have. 

### Editing GitHub Files
In order to add to this page, you will need to edit the contents of the GitHub `Baller_Lab_Guide` repository. This is easily done with Visual Stuido Code. First, you will need a GitHub account and to be added to the Baller_Lab organization (Prof. Baller will be able to do this for you). Make sure you are signed into your GitHub account through Visual Studio Code.

1. Open Visual Studio Code and GitHub, navigating to the Baller_Lab_Guide repository. Open a terminal in Visual Studio Code by pressing `ctrl` + ` 
2. Clone the Baller_Lab_Guide repository by clicking the dropdown on the green `code` button and copying the respository [link](https://github.com/Baller-Lab/Baller_Lab_Guide.git)
3. in the command line of your terminal, enter `git clone` followed by the link you just copied. For example, `git clone https://github.com/Baller-Lab/Baller_Lab_Guide.git`
4. Once cloned, you can open the folder through VSC and begin editing

### Pushing Commands to the Baller_Lab_Guide Repository
To make sure your changes are active on GitHub, you will need to frequently save changes you make in the repository (`ctrl` + `S`). Once you have finished a chunk of editing, you will need to push those changes to github.
1. Click on the `source control` icon on your VSC lefthand toolbar
2. Enter a short message that explains the changes you have made
3. Hover over the `Changes` bar, and click the plus sign 
4. Click the `Commit` button
5. Click the `Sync` button to sync your changes with the GitHub page
