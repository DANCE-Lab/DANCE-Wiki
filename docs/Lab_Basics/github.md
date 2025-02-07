---
layout: default
title: GitHub Page
has_children: false
parent: Lab Basics
has_toc: false
nav_order: 2
---

# Keeping The GitHub Page Up to Date
This GitHub page is the hub of lab protocols, procedures, and best practices. Therefore, it is important that it be kept up to date! This is also a living document that welcomes changes from all members of the lab. Lab members are welcome to create pull requests to update and add to this wiki; brief instructions for updating the github page are detailed below.

Git hub is AWESOOOMMMMMEEE

## Quick GitHub Edits
GitHub edits can be done either directly through the GitHub site or, for more complex and involved edits, by submitting pull requests through a platform like Visual Studio Code (VSC) into GitHub. If you are adding a section to an existing page or tweaking a procedure, it may be easiest for you to directly edit the pages docs. To do this, navigate to the [DANCE_Lab/DANCE-Management repository](https://github.com/DANCE-Lab/DANCE-Management) in the DANCE Lab Organization (reach out to the Lab Manager if you need to be added as a member). Click on the `Code` button and, in the left-hand toolbar, navigate to the `docs` folder. Once you select the page you would like to update, you can switch from the page `Preview` function to the page `Edit` function by clicking on the pencil in the upper right hand corner of the page preview. This will allow you to edit the page by entering [Markdown](https://www.markdownguide.org/cheat-sheet/) text into the file. Once you are finished editing, you'll submit a `Pull Request`, which will be integrated into the wiki once it is approved by the lab manager. You will add a quick message about what changes you made before completing the request.

## Updating the DANCE-Management Repository Using VSC
DANCE-Management is a repository inside the DANCE_Lab organization. It contains all files that are fundamental to producing the `Just the Docs` page that you are currently reading and folders with markdown outlining all of the information in the website subpages. You will be mostly concerned with the contents of the folder `docs`.

`docs` contains sub-folders, each of which appears as a section header in the wiki left-hand table of contents bar. You can navigate to markdown files in each subfolder, or create your own folder to establish a new section header. If you are creating new folders or markdown files, make sure to follow the naming and parent/child page conventions at the top of each markdown file (these make sure that wiki correctly populates the information you write into the markdown files). Many online tutorials exist for guiding you through more complicated github and VSC procedures.  

### Editing GitHub Files
In order to update the wiki, you will need to edit the contents of the GitHub `DANCE-Management` repository. This can be easily done with Visual Stuido Code. First, you will need a GitHub account and to be added to the DANCE-Lab organization (contact your lab manager). Make sure you are signed into your GitHub account through Visual Studio Code.

1. Open Visual Studio Code and GitHub in your browser, navigating to the DANCE-Management repository. Open a terminal in Visual Studio Code by pressing `ctrl` + ` 
2. Clone the DANCE-Management repository by clicking the dropdown on the green `code` button and copying the respository [link](https://github.com/DANCE-Lab/DANCE-Management.git)
3. in the command line of your terminal, enter `git clone` followed by the link you just copied. For example, `git clone https://github.com/DANCE-Lab/DANCE-Management.git`
4. Once cloned, you can open the folder through VSC and begin editing

### Pushing Commands to the DANCE-Management Repository
To make sure your changes are active on GitHub, you will need to frequently save changes you make in the repository (`ctrl` + `S`). Once you have finished a chunk of editing, you will need to push those changes to github.
1. Click on the `source control` icon on your VSC lefthand toolbar
2. Enter a short message that explains the changes you have made
3. Hover over the `Changes` bar, and click the plus sign 
4. Click the `Commit` button
5. Click the `Sync` button to sync your changes with the GitHub page
