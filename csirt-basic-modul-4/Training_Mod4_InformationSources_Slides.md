# Module 4 Working with Information Sources

## Copyright

Copyright © by Forum of Incident Response and Security Teams, Inc.

FIRST.Org is name under which Forum of Incident Response and Security Teams, Inc. conducts business.

This training material is licensed under Creative Commons Attribution-Non-Commercial-Share-Alike 4.0 (CC BY-NC-SA 4.0)

FIRST.Org makes no representation, express or implied, with regard to the accuracy of the information contained in this material and cannot accept any legal responsibility or liability for any errors or omissions that may be made.

All trademarks are property of their respective owners.

Permissions beyond the scope of this license may be available at first-licensing@first.org

## Agenda

By the end of this module, you will be able to:

- Categorize levels of information sources
- Establish how to work with open-source and proprietary intelligence
- Identify methods for gathering and handling critical information
- Define processes that allow information sharing and exchange
- Practice gathering information from various sources

## Section 1: Categorizing Information Sources

### Information Sources and Types

- Information sources provide critical data for CSIRTs that can be used to identify, analyze, and resolve vulnerabilities
- Information sources are then categorized into three types:

### Primary Information Source

A primary information source is, generally, the first person to discover a vulnerability or report it to the CSIRT

### Secondary Information Source

A secondary information source is a security database, article, or journal whose data can be used to analyze and/or resolve the vulnerability

### Tertiary Information Source

A tertiary information source is a report that synthesizes data from secondary sources or from your own analysis of similar incidents or vulnerabilities

### Information Sources in Use

| Vulnerability | One of your users finds a URL that asks for a login and password and sends the suspicious email to the CSIRT immediately
Information Sources in Use |
| Primary Information Source | |
| The CSIRT looks through three security articles and the Common Vulnerability Enumeration (CVE) database to assess the severity, commonality, and means of removal for this vulnerability |
| Tertiary Information Source | The CSIRT scans an internal database for reports compiled by the CSIRT team on similar incidents or vulnerabilities |

### Phishing Example

- Your organization is being targeted by a phishing attack
- You need to gather as much information as possible to resolve the incident
- Classify information as primary, secondary, and tertiary

### Phishing Example: Primary Information

- Who was the intended target of the attack?
- What is the URL and hostname of the attacker?
- What was the social engineering method?

- URL
- Social engineering method
- Sender email

### Phishing Example: Secondary Information

- Who is the owner of the URL and what is his or her location?
- What is the sender's name and location?
- Has anyone already been phished inside organization?
- What type of data has been compromised?
- How was the system initially accessed?
- Which passwords were used to access the system?

- Sender IP address
- Spoofed or not
- Geo location
- Known campaign internally
- IP address
- Owner of domain
- Geo location
- Hosting service provider

### Phishing Example: Tertiary Information

- Are there reports about similar phishing incidents in the past?
- What other attacks, if any, have been documented online on this URL or domain?

- URL content
- URL reputation
- Known campaign externally

### Circle of Information

- Sender IP address
- Spoofed or not
- Geo location
- Known campaign internally
- URL
- Social engineering method
- Sender email
- IP address
- Owner of domain
- Geo location
- Hosting service provider
- URL content
- URL reputation
- Known campaign externally

### Learning Check

If the primary, secondary, and tertiary information sources about an incident differ from each other, what do you do?

## Section 2: Types of Information

### Types of Information

Types of common information you might need to gather:

- IP address (source and destination)
- Domain name
- Internet service provider (ISP)
- Email address
- System logs

### Open-Source Intelligence

- Open-source intelligence is information made available for public consumption that can be accessed over the Internet by anyone at any time
- Types of open-source intelligence:
  - nslookup
  - ht://Dig
  - Google
  - Social media

### Proprietary Intelligence

- Proprietary intelligence describes a technology owned exclusively by a single company that carefully guards knowledge about the technology or the product's inner workings
- Types of proprietary intelligence:
  - Maltego
  - Deep Magic
  - Cuckoo Sandbox

### Learning Check

What are the protocols in your organization for the types of information that can or cannot be shared, and how the information will be distributed?

## Section 3: Information Gathering Process

### Information Gathering Process

Gather/Handle => Verify/Score => Save => Share

- When researching a vulnerability, the information you collect is your weapon against it, so it is imperative that you be thorough
- When a vulnerability is detected, a CSIRT will need to accumulate all relevant information to identify the threat

### Information Gathering Process

- When researching a vulnerability, the information you collect is your weapon against it, so it is imperative that you be thorough
- When a vulnerability is detected, a CSIRT will need to accumulate all relevant information to identify the threat

### Gathering and Handling Information

There are two forms of information gathering: proactive and reactive.

- Proactive information gathering is forecasting the possibility of a threat and taking the necessary precautions to avert it
- Reactive information gathering is waiting for a threat to happen and reacting appropriately to that particular type of threat

### Gathering and Handling Information: Proactive

- Proactive information gathering example: Signing up for RSS feeds
- Other forms of proactive information gathering:
  - Regular system checks
  - Periodic CSIRT team drills
  - Subscribing to email lists
  - Setting the appropriate level of logging and checking periodically
  - Developing a background script for analysis

### Gathering and Handling Information: Reactive

- Reactive information gathering example: Using Google to research the threat, its effects, and how to properly eradicate the vulnerability
- Reactive information gathering is any attempt at gathering information made after a threat is detected

### Verifying and Scoring Collected Information

The verification process begins with your information source

- If you have a primary information source, your verification is as easy as speaking with that source
- If you have only secondary information sources, additional research might be required for proper verification
- Apply a score to information once it is verified

### Saving Information for Analysis

- All information collected should be saved and stored for analysis
- This becomes proactive information and is beneficial for:
  - Training and tools for future CSIRT members
  - Possible information sharing for other CSIRTs and organizations
  - Future analysis of the effectiveness of the CSIRT
- Use a file system or Incident Management system

### Importance of Sharing Information

- Sharing information is reciprocal in its benefits
- Without the sharing of information, open-source intelligence would be far less beneficial and vulnerabilities would be more difficult to identify

### Establishing and Maintaining Sharing Relationships

- Creating and maintaining relationships is crucial to the success of a CSIRT
- CSIRTs commonly establish relationships with:
  - Other CSIRTs at neighboring/like organizations
  - ISPs
  - Social media outlets

### Learning Check

In which situations are differences in the way team members gather information helpful to your team?

In which cases is varying from the norm not helpful?
