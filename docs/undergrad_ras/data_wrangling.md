---
layout: default
title: Data Wrangling
has_children: false
parent: RA Resources
has_toc: true
nav_order: 2
---

# Data Wrangling

Proficiency working with dataframes--be it wrangling in python, R, or another langauge--is one of the most valuable skills you can have in a lab! There are also a wealth of online resources to help you develop your data wrangling skills at your own pace, or whenever you are looking for a way to fill remaining weekly hours in the lab. 

## R Coursera Courses

There are some excellent introductory statistics courses in R available on Coursera. The following courses are provided by Johns Hopkins and an excellent starting place for someone who is relatively new to programming and R: 

- [Getting Started with Data Visualization in R](https://www.coursera.org/learn/jhu-getting-started-data-viz-r) is a great course for someone with some basic skills using R for statistical analysis and will walk you through how to make data visualizations in R. This is good for someone who may not use R as a primary coding language as well--even though other langauges may be better suited to certain analyses, R creates some of the most visually appealing figures. This course is relatively short and contains only ~11 hours of coursework. 
- [Data Science: Foundations Using R](https://www.coursera.org/specializations/data-science-foundations-r) is a self-paced beginner-leve introduction to R that will teach you the basics of using R to clean, analyze, and visualize data, as well as overview best research practices and how to use GitHub (the site used to create this wiki!). It is a longer course, projected to take ~4 months to complete at 10 hours per week. This is an excellent place to start if you have no R experience whatsoever. 
- [Data Science Specialization](https://www.coursera.org/specializations/jhu-data-science) is a more in-depth introduction to using R to clean, analyze, and visualize data within the context of a publication-focused research project. It will also cover some statistical methods that will help you better understand how to implement R to ask the right questions in your data, as well as cover topics related to machine learning and managing your project using GitHub. It is the longest introductory course, estimated at ~7 months to complete at 10 hours per week. 

More advanced courses: 

- [Advanced Statistics for Data Science](https://www.coursera.org/specializations/advanced-statistics-data-science) is a more advanced, R-based course that is great for improving your statistical knowledge and becoming more comfortable doing more advanced analyses in datasets. It is a shorter course projected to take ~1 month to complete at 10 hours per week. 

### R Cheat Sheets

Here are a couple of cheat sheets that are useful for data wrangling in R: 

- [ggplot and other R libraries cheat sheet](https://github.com/DANCE-Lab/DANCE-Management/blob/master/files/cheat_sheets.pdf)
- [Base R cheat sheet](https://github.com/DANCE-Lab/DANCE-Management/blob/master/files/r-cheat-sheet.pdf)

## AFNI and FSL

If you ever find yourself needing to work with AFNI or FSL to analyze MRI data, Andrew Jahn has extensive tutorials that will help you get oriented and begin your analyses on youtube. 

Youtuble playlists can be found below for... 

- [AFNI](https://www.youtube.com/playlist?list=PLIQIswOrUH6-v5EWwFdMsTZttt4407KW9)
- [FSL](https://www.youtube.com/playlist?list=PLIQIswOrUH69lUeHurAk9pLHOPTzQ6M72)

## Python

There are tons of resources for learning python on the internet. You can explore online platforms like [Coursera](https://www.coursera.org/specializations/python?utm_medium=sem&utm_source=gg&utm_campaign=B2C_NAMER_python_umich_FTCOF_specializations_country-US-country-CA&campaignid=300366907&adgroupid=34186056677&device=c&keyword=coursera%20python&matchtype=b&network=g&devicemodel=&adposition=&creativeid=668421944129&hide_mobile_promo&gad_source=1&gclid=Cj0KCQjwpP63BhDYARIsAOQkATav7J962mb73MD_bTxhTgp82TcIRw_mjLGdUb4aJIGVkLUXiDTcMkEaApfQEALw_wcB) and DataCamp, just to name a couple of the many available. 

Our lab github also includes a [repository](https://github.com/DANCE-Lab/RA_scripts/tree/main) where scripts written by and for RAs pertaining to lab projects can be found. This repository also includes a folder with a series of Jupyter notebooks that will walk you, step-by-step, through the very basics of variables, strings, conditionals, tuples, lists, and dictionaries--everything you neeed to start applying your skills to real-life datasets. Before working through these notebooks, I recommend perusing the document [read_me](https://github.com/DANCE-Lab/RA_scripts/blob/main/Learning_Python_Notebooks/read_me.md).

### Python Exercises

The best way to build your coding abilities is by practicing! Below are some resources and websites where you can do some python tutorials and complete some python exercises. Some of the sites have a built-in coding window where you can practice problems, whereas others may require you to practice in a notebook (in jupyter or google colab) instead.

1. [Pychallenger](https://pychallenger.com/): this site offers a free first course with additional free exercises once you have completed your first lesson. Even though you don't get full access, it has a very user-friendly interface and might be a good place to get started.

2. [HackerRank](https://www.hackerrank.com/domains/python?filters%5Bsubdomains%5D%5B%5D=py-introduction) has a number of challenges that you can work through to improve your python skills! It starts very easy, with print statements and arithmetic operators, and builds from there. HackerRank also has a very user-friendly interface where you can code directly into the site. 

3. [w3resource](https://www.w3resource.com/python-exercises/) is a little less fancy, but has a lot of materials for python learners. Challenge questions offer you input text, numbers, etc., but you will need to solve the questions in your own notebook (such as in google colab, VSCode, or jupyter)

4. [Practice Python](https://www.practicepython.org/) is another more basic website that has a TON of exercises, complete with in-depth instructions and solutions. Exercises are also rated by difficulty, so you can start with simpler ones and challenge yourself as you practice more. These exercises will also require you to solve these questions in your own practice notebooks (google colab, VSCode, jupyter).

## Accessing Python Notebooks and Viewing RA Scripts

We will be using Jupyter notebooks to begin learning about data cleaning and analysis! These notebooks can be found on the lab github, in the repository [RA Scripts](https://github.com/DANCE-Lab/RA_scripts/tree/main/Learning_Python_Notebooks) and can be opened using one of several platforms: [Anaconda](https://www.anaconda.com/products/navigator) (either by downloading the application or through the online platform), [Visual Studio Code](https://code.visualstudio.com/), or [Google Colab](https://colab.google/). VS Code and the downloaded version of Anaconda Navigator will be the best platforms for more serious or in-depth projects, but online platforms are perfect for easily accessing somewhere to practice and run through the assigned Jupyter Notebooks! 

#### Instructions for Opening Notebooks through Google Colab

If it is your first time using a Jupyter Notebook, I highly recommend starting with Google Colab as this is the easiest, most user-friendly online option. Please note: code may run more slowly on Google Colab than on your computer. 

Steps to open a practice Jupyter Notebook in Google Colab: 
1. Open [Google Colab](https://colab.google/) in your browser
2. Click on the button called "Open Colab"
3. Click on the button "GitHub" in the "Open Notebook" window
4. Open the [RA Scripts](https://github.com/DANCE-Lab/RA_scripts/tree/main/Learning_Python_Notebooks) GitHub page in your browser
5. Choose the notebook that you want to open in Colab. Copy the URL (Example: [URL for Notbook 1: Learning Python Variables: Strings and Conditionals](https://github.com/DANCE-Lab/RA_scripts/blob/main/Learning_Python_Notebooks/1_Learning_Python_Variables_Strings_and_Conditionals.ipynb))
6. Paste the URL in the Colab bar that says "Enter a GitHub URL"

This should open your notebook! Colab will automatically connect you to Python 3 and you will be able to run notebook code blocks in your browser by clicking the little triangle in the upper left hand corner of the code block (looks like a "play" button). Please reach out to your lab manager if you have any further difficulties running the notebook!