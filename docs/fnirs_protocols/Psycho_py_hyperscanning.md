---
layout: default
title: Psycho Py for Hyperscanning
has_children: false
parent: fNIRS SOPs
has_toc: false
nav_order: 17
---

# PsychoPy for fNIRS Hyperscanning

The program is located on fNIRS computer 1. It's called "hyperscan marker" and the app icon looks like small stars.
You have to note the participant which then automatically opens up the psycho py program.
Then, test the connection in Aurora with the LSL stream in the edit section of the configuration.

Once that is confirmed, open up the hyperscan app and connect the NIRSport devices. 
**Side note, the difference between the practice config and the normal config is that the practice does not need to have the optodes connected to work**
Start recoding data in the hyperscan app. Go to the psycho py window and press space. That starts the countdown. It will tell you in the window what section you are on. Baseline, video game, focus, etc. 

    Older notes
Hyperscanning timer psychopy --> lsl --> data
See if it recorded, saved as a xcel file
Hyperscanning timer psycho py --> lsl --> hyperscan trigger
opens program but have to close everything else to make it work
window --> coder mode --> open python file
edit task and task markers so that it goes through
Windows batch file actually runs the python file