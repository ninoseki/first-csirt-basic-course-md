# Lab for Module 3: CSIRT Operation

## Copyright

Copyright © by Forum of Incident Response and Security Teams, Inc.

FIRST.Org is name under which Forum of Incident Response and Security Teams, Inc. conducts business.

This training material is licensed under Creative Commons Attribution-Non-Commercial-Share-Alike 4.0 (CC BY-NC-SA 4.0)

FIRST.Org makes no representation, express or implied, with regard to the accuracy of the information contained in this material and cannot accept any legal responsibility or liability for any errors or omissions that may be made.

All trademarks are property of their respective owners.

Permissions beyond the scope of this license may be available at first-licensing@first.org


## Lab Introduction

Open your Lab Student Guide

Your instructor will guide you through each step

## Lab Steps: Incident Management Processes

1. Plan and prepare
1. Detect
1. Triage
1. Analyze
1. Respond
1. Conduct post-mortems and lessons learned sessions

## Lab Scenario

- You work in your organization's CSIRT team in Europe
- An exposed database resides in New Zealand
- Your organization's headquarters is in the U.S.
- An email has arrived from your friend Francis, from your football league, notifying you that she has discovered information internal to your organization posted on pastebin.com
- After you have completed your analysis, you find out that the media has picked up this incident

## Instigating Email

```
From: Francis
To: me
Subject: Have you seen this?
Hi,
My buddy forwarded me this as he knows that I know someone (you) from <COMPANY>.
-----Original Message-----
Hi Francis, Have you seen this? What is going on?
<COMPANY> Hacked, Defaced & Data Leaked
A hacker l33t3_guy has contacted us with the first large breach of the year 
The breach is on another giant this time <COMPANY> sites have become targets of l33t3_guy.
The attack has left <COMPANY> websites defaced and a dump of the servers database has been leaked and uploaded to two mirrors on public file sharing sites. The files have since been removed from depositfiles.com but are still available on www.pastebin.com/xxx at the time of publication.
The leak is a 24mb compressed rar file that contains 4 folders with contents ranging from txt files to sql db dumps and further rar and zip files.
```

## Sample of pastebin.com Contents

file1.txt

```
ID jmeno email heslo login prijmeni vyrobek rowguid
14 Daniel prentis@kaktus.mx p prentis Prentis B56778DF-8C6E-4E4E-B3AC-09ABF55CCC5F
15 gggg fffff a admin fffffff C3D23D86 . . .
17 f f f f f f 0615821E . . .
16 q q q q q q 85FC2FD6 . . .
20 Jan zich@kaktus.mx disevycpat janzich Zich . . .
```

file2.txt

```
id jmeno prijmeni email mesto ulice psc telefon pohlavi rokNarozeni login heslo
3 test test j.pavlik@kaktus.mx ccc xxx 100 123 0 222 test 123456
20 Eduard Mácha e.macha@kaktus.mx Ostrava Na skotnici 304 111 05 606742819 1 1969 macho molly
```

## CSIRT Contacts

Internal Contacts:

- Legal: Leslie Lu, based in London, U.K.
- PR: Patrick Pan, based in Palo Alto, U.S.
- DB contact: Devi Dharma, based in New Zealand

External Contacts:

- Media contact: Milli Massimo, The Local Times
- Administrator at pastebin.com: Amir Au


Information on exposures:

- Daniel Prentis, prentis@kaktus.mx and Jan Zich, zich@kaktus.mx
- J. Pavlik, j.pavlik@kaktus.mx
- Eduard Ostraa Na, e.macha@kaktus.mx

Global Guide to Breach Notifications: http://www.theworldlawgroup.com/wlg/Global_Data_Breach_Guide_Home.asp

## Step 1: Plan and Prepare

- What are the three key relationships within your organization?
- Are there any you still need to establish?
- What are your three key external relationships?

## Step 2: Detect

- From whom did you get the suspected incident? What that person internal or external?
- What information in the files might be sensitive?
- What information do you need to collect to perform triage?
- What digital evidence can you collect? Where should you store it? Do you have a policy at your organization?

## Step 3: Triage

- How does this incident impact your organization?
- What severity would be assigned? What incidents have higher priority? Lower?
- What might have higher urgency? Lower urgency?
- In your organization, how are urgency levels defined?

## Step 4: Analyze

- What are your first steps?
- What are your conclusions?
- What teams did you work with in this phase?

## Step 5: Respond

- What steps do you need to take to clean up the attack?
- Who do you need to contact, internally and externally?
- How does your internal communications plan differ from your external plan?
- For your organization, do you involve Legal and PR?
- What actions do you need to take in addition to contacted the affected individuals?
- What do you do when you find out Leslie Lu has left the company?

## Step 6: Conduct Post-Mortem and Lessons Learned Sessions

- What tasks did you list to include your processes?

## Learning Check

How would your organization handle this incident differently than we did in this lab?
