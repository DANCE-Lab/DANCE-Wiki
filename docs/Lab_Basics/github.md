---
layout: default
title: GitHub Page
has_children: false
parent: Lab Basics
has_toc: false
nav_order: 2
---

# Keeping The Internal Wiki Up to Date
This GitHub page is the hub for lab protocols, procedures, and best practices. Therefore, it is important that it be kept up to date! This is also a living document that welcomes changes from all members of the lab. Lab members are welcome to create pull requests to update and add to this wiki; brief instructions for updating the github page are detailed below.

## DANCE GitHub Structure
The DANCE-Lab organization contains a number of repositories. Two of them are actively used in the upkeep of this internal wiki (DANCE-Wiki and DANCE-Wiki-Updates). There is one other wiki-related repository named "DANCE-Management-ARCHIVED". This repository is a backup of an earlier version of the internal wiki and is maintained A., as a backup for emergencies and B., as a template for any future wikis that members of the lab may need to create. Please note that wikis can be easily duplicated by forking the relevant repository. 

To gain access to the DANCE-Lab GitHub page, **you will need a github account. Once you have created one, please give your github username to the lab manager**. The lab manager will add you to the organization and provide you with "write" access to the DANCE-Wiki-Updates repository. DANCE-Wiki-Updates does not host this internal wiki page, but is directly linked to the repository that does, DANCE-Wiki. To contribute to the internal wiki, you will directly update DANCE-Wiki-Updates repository and initiate a pull request to merge DANCE-Wiki-Updates with DANCE-Wiki. Detailed instructions for completing this process are written below.

## Quick GitHub Edits
GitHub edits can be done either directly through the GitHub site or, for more complex edits and creating new pages, by submitting pull requests through a platform like Visual Studio Code (VSC) into GitHub. If you are adding a section to an existing page or tweaking a procedure, it may be easiest for you to directly edit the pages docs. To do this, navigate to the [DANCE_Lab/DANCE-Wiki-Updates repository](https://github.com/DANCE-Lab/DANCE-Wiki-Updates) in the DANCE Lab Organization (reach out to the Lab Manager if you need to be added as a member). Click on the `Code` button and, in the left-hand toolbar, navigate to the `docs` folder. Once you select the page you would like to update, you can switch from the page `Preview` function to the page `Edit` function by clicking on the pencil in the upper right hand corner of the page preview. This will allow you to edit the page by entering [Markdown](https://www.markdownguide.org/cheat-sheet/) text into the file. Once you are finished editing, you'll submit a `Pull Request` (see below), which will be integrated into the wiki once it is approved by the lab manager. You will add a quick message about what changes you made before completing the request.

## Updating the DANCE-Wiki-Updates Repository Using VSC
DANCE-Wiki-Updates is a repository inside the DANCE_Lab organization. It contains all files that are fundamental to producing the `Just the Docs` page that you are currently reading and folders with markdown outlining all of the information in the website subpages. You will be mostly concerned with the contents of the folder `docs`.

`docs` contains sub-folders, each of which appears as a section header in the wiki left-hand table of contents bar. You can navigate to markdown files in each subfolder, or create your own folder to establish a new section header. If you are creating new folders or markdown files, make sure to follow the naming and parent/child page conventions at the top of each markdown file (these make sure that wiki correctly populates the information you write into the markdown files). Many online tutorials exist for guiding you through more complicated github and VSC procedures. 

### Editing GitHub Files
In order to update the wiki, you will need to access the contents of the GitHub `DANCE-Wiki-Updates` repository. This can be easily done with Visual Studio Code (VSCode). First, you will need a GitHub account and to be added to the DANCE-Lab organization (contact your lab manager). Make sure you are signed into your GitHub account through Visual Studio Code.

1. Open Visual Studio Code and GitHub in your browser, navigating to the DANCE-Wiki-Updates repository. Open a terminal in Visual Studio Code by pressing `ctrl + ` **OR** click the hyperlinked prompt `clone a git repository` and follow the prompts to paste the repository link into the search bar
2. Clone the DANCE-Wiki repository by clicking the dropdown on the green `code` button and copying the repository [link](https://github.com/DANCE-Lab/DANCE-Wiki-Updates.git)
3. In the command line of your terminal, enter `git clone` followed by the link you just copied. For example, `git clone https://github.com/DANCE-Lab/DANCE-Wiki-Updates.git`
4. Once cloned, you can choose a destination for the repository contents to be stored on your computer. Open the folder through VSC and begin editing

### Pushing Commands to the DANCE-Wiki Repository
To make sure your changes are active on GitHub, you will need to frequently save changes you make in the repository (`ctrl` + `S`). Once you have finished a chunk of editing, you will need to push those changes to github.
1. Click on the `source control` icon on your VSC left toolbar
2. Enter a short message that explains the changes you have made
3. Hover over the `Changes` bar, and click the plus sign 
4. Click the `Commit` button
5. Click the `Sync` button to sync your changes with the GitHub page

## Submitting a Pull Request to Sync DANCE-Wiki-Updates with DANCE-Wiki
Congratulations! You have successfully updated the DANCE-Wiki-Updates repository. If you navigate to this repository on the GitHub page, you will be able to see your changes reflected in the repository contents. However, these changes are not yet added to the website. To push your commits to the DANCE-Wiki repository, you must submit a pull request to merge DANCE-Wiki-Updates with DANCE-Wiki, which must be approved by a member of the lab admin team. 

1. Navigate to the main page of the [DANCE-Wiki-Updates repository](https://github.com/DANCE-Lab/DANCE-Wiki-Updates). The bar above the website contents should reflect your recent changes and state **'This branch is ___ commits ahead of DANCE-Lab/DANCE-Wiki:master'**. You can push that commit to DANCE-Wiki by clicking on the button to the right that reads `Contribute`. **DO NOT click `Sync fork`.**
2. Clicking `Contribute` will produce a dropdown with a button `Submit Pull Request`. Click this, and it will take you to a new pull request page. 
3. When prompted, add a short description of your changes and submit the pull request. This will then be pushed to the DANCE-Wiki repository and, once approved by lab admin, your changes will be live on the lab website.
