# Lab for Module 4: Working with Information Sources

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

## For Each Scenario

For each question in each scenario, ask:

- Which tools are appropriate for investigating the information presented in this question?
- Would you categorize this information as primary, secondary, or tertiary?
  - Primary: the original source of a vulnerability
  - Secondary: information derived from that primary information or from a security database, article, or journal
  - Tertiary: information derived from secondary information

## Scenario 1: Incident Mitigation

- You notice there is a system within your organization that is performing downloads from unusual domains on the Internet
- You find the system is Joan's computer in Finance
- You see that Joan's antivirus and system update processes are not active
- You discover the first download was trafficconverter.biz and from then on there was the strange download every day
- You create a hash of the executable, `59c23e92625559f541b0cbed46f07dc`, and find out that Norton named this worm "Conficker" and Symantec called it "W32.Downadup"

## Scenario 1 Questions: Incident Mitigation

1. What can you find out from the network traffic log file?
1. How could you determine that it was Joan's machine?
1. Is there any general information on the Web about malware that "disables antivirus software?"
1. What does a search indicate about the trafficconverter.biz site?
1. What can you find out from the hash and what does it tell you?
1. What type of file is it and where does it run?
1. What are the vulnerabilities that were exploited?
1. What could have been done to prevent this incident from arising within your organization?
1. What is the family of the malware, e.g., is it a virus, Trojan, or other type of malware?
1. Are your Windows 7 systems affected?
1. How can you determine whether other machines in your organization are infected?
1. Is this an advanced persistent threat (APT)? How can you tell?
1. What other useful information did you learn along the way that you can share?

## Scenario 1 Question Review

1. What can you find out from the network traffic log file?
1. How could you determine that it was Joan's machine?
1. Is there any general information on the Web about malware that "disables antivirus software?"
1. What does a search indicate about the trafficconverter.biz site?
1. What can you find out from the hash and what does it tell you?
1. What type of file is it and where does it run?
1. What are the vulnerabilities that were exploited?
1. What could have been done to prevent this incident from arising within your organization?
1. What is the family of the malware, e.g., is it a virus, Trojan, or other type of malware?
1. Are your Windows 7 systems affected?
1. How can you determine whether other machines in your organization are infected?
1. Is this an advanced persistent threat (APT)? How can you tell?
1. What other useful information did you learn along the way that you can share?

## Scenario 2: Vulnerability Research

- Symantec announced an Adobe zero-day was found by the security researcher Kafeine
- Adobe has confirmed this vulnerability and issued a security bulletin
- The infection presents itself to users in two paths:
  - As an Adobe PDF file on spam email attachments that automatically download the malware
  - Through "malvertizing" that pops up on unreliable web pages

## Scenario 2 Questions: Vulnerability Research

1. What are some advisories of interest, articles, and blog posts that may be used as primary sources of information?
1. If your organization runs Windows 8 and Internet Explorer 10, should you be concerned?
1. According to NIST, what is the CVSS score (out of 10+10+10 or 30)? Does that make you more concerned or less?
1. According to the Adobe Security Bulletin, what are the adverse effects of this malware?
1. Which release or releases are the vulnerable ones?
1. What are some ways to detect whether a computer has been infected by this vulnerability?
1. What are the two ways your users can get the update?
1. Based on your CSIRT policies, how will you communicate about this incident to your users?
1. What other useful information did you learn along the way that you can share?

## Scenario 2 Question Review

1. What are some advisories of interest, articles, and blog posts that may be used as primary sources of information?
1. If your organization runs Windows 8 and Internet Explorer 10, should you be concerned?
1. According to NIST, what is the CVSS score (out of 10+10+10 or 30)? Does that make you more concerned or less?
1. According to the Adobe Security Bulletin, what are the adverse effects of this malware?
1. Which release or releases are the vulnerable ones?
1. What are some ways to detect whether a computer has been infected by this vulnerability?
1. What are the two ways your users can get the update?
1. Based on your CSIRT policies, how will you communicate about this incident to your users?
1. What other useful information did you learn along the way that you can share?

## Learning Check

How can dividing information into primary, secondary, and tertiary help in scenarios like the ones in this lab?
