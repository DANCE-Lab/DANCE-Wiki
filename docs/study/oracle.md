---
layout: default
title: Oracle
has_children: false
parent: Current Studies
has_toc: false
nav_order: 5
---

# Using Oracle
Oracle is the BBL-wide database that is used to keep track of all participants that choose to be a part of BBL studies. You will need to use Oracle to creat a BBLID, which will beocme your participant's identifier, and to push self-report scales and interviews to REDCap. You will also be able to see if your participant has participated in any other BBL studies, but the MS participants are typically new to the BBL and will have to have their information entered manually to create the ID. 

## Making a BBLID in Oracle
Once you are onboarded, you should be able to log in to the [Oracle database](https://bbldm.pmacs.upenn.edu/bblmain/alarm/req_alarm.jsp). Navigate to the `Main Menu` and click on the `QuickScreen` button on the left-side toolbar. Then, click on `QuickScreen Store` to create a screen ID for your participant (this is a necessary precursor to the BBLID). Enter all required information, and check to make sure that you're not creating a duplicate screen ID by clicking the `Check Dup Name` button next to the participant's name. You should be able to find all of a participant's required data in PennChart. You can leave their Preliminary Screen Status as `Unknown`, mark their source as `ext` (external) and enter 'Baller MS Study' into the notes senction, and finally you should click "No" next to `Quick_Exclude`. 

Congratulations! You have now created a QuickScreen ID. 

Return `Home` and then click on `GETBBLID` on the left-side toolbar. click on `Get BBLID`, and then enter the participant's screen ID (SID) and all required information. Register them as `P` for proband, and then the page should generate a BBLID. Record the BBLID in the participant recruitment spreadsheet in the Baller Lab Saturn folder. 

## Enroll Participant in MS/Depression Study
Now that you have a BBLID for your participant, you can enroll them in the MS/Depression study. Navigate back to `Home` and click on `Study_Enroll` in the left-hand toolbar. Then click on `Study Enroll` to enroll your participant in the study. Enter the participant's BBLID and click `get the subject`. Once their information populates, click `Do New Enroll`. Enter all required information. Select `IRB#_msdep_k23` for protocol, and `MS_group` for study group. You can then hit `Save`. Your protocol participant should then appear as active in the protocol. Return `Home`.

## Push Self Report Scales to REDCap
You will be able to generate self reports in REDCap for the study through Oracle. Click on `REDCAP_SelfReport` in the left hand toolbar. Then, click `Subject SelfR Store`. Enter the BBLID you just created and select protocol `IRB#_msdep_k23`. This should populate seven self report scales underneath the banner `Show REDCap Scales for Proband`. Click `ENTER` to generate the REDCap ID you will use to search for the participant's self report scales in the `Participant Self Report Scales` REDCap project. Make a note of this ID. Return `Home`.

## Push GOASSESS Interview to REDCap
You will be able to generate a record for your participant's GOASSESS clinical interview in Oracle. Click on `REDCap Interview` in the left hand toolbar. Click on `SubScale IntV Store`. Enter your subject's BBLID and the protocol `IRB#_msdep_k23`. Select the correct GOASSESS interview under `Battery Assessment` (interview updates currently in progress, as of 12/7/23) and double check the list of scales populated below. Fill in all required fields and select "Intake Proband" under `Interview Type`. Click `ENTER` to generate the REDCap ID you will use to search for the participant's interview in REDCap under the `GOASSESS Clinical Interview` REDCap project. Make a note of this ID and return `Home`.

## Logging Participant Contact in Oracle
You should also log how and when you contacted your participant in Oracle using the `Contact Entry` button in the left hand toolbar. Click `BBLID Search` to find your participant, and click `Contact Entry` to see a history of when and how the participant was contacted. Add new contact info at the bottom of the page if necessary. Click the envelope/phone icon on the far left to add a new contact entry for an existing mode of contact. Fill out necessary information to reflect the interaction you had with your participant. Make sure to also log contact and study information in the Saturn participant recruitment spreadsheet.
