# Telstra - Security Data Normalization: SWEN90009_2021_DN-Koala

Repository for SWEN90009 Telstra - Security Data Normalization Project for Team Koala

## Project Overview

Everyday Telstra recieves terabytes of log files from tens of thousands of firewalls, load balancers, servers, and network devices. These logs are collected, parsed, and are then analysed in real time to derive insights around security and network load. As the content and format of the logs are highly varied and often subject to changes and updates, their fields and contents must be normalized before meaningful analysis and comparison of log data can take place. 

Currently, this normalization process requires significant manual labour, with engineers and interns investigating the different log formats and creating parsers to extract, aggregate, and normalize fields for export onto Telstra's Elastic and Splunk anayltics platforms. As no process currently exists at Telstra to automatically normalize logs with unknown or unmapped formats, significant amounts of data is unavailable for analysis at any given time - log data from devices with new log formats, devices that have updated their log file structure, and devices that haven't yet been investigated will all be unusable until manual review has been carried out. Furthermore, the manual effort required to normalize log data leaves the process prone to human errors.

We are tasked with investigating possible routes towards creating an automated or semi-automated normalization process that will allow logs from varied systems and devices to be quickly normalized and prepared for export to a range of analytics platforms, with the aim of saving manual processing time and reducing error rates.

## Solution Diagram
<image src="/images/SolutionDiagram.png"> 
Fig 1. The role of the normalization solution in the client's workflow
</image>

## Key documents

Copies of documents relating to product details and requirements created during the requirement analysis and investigation process have been saved in this repository. As the project progresses and our investigation grows more detailed, new documents and directories will be added to the repository and linked to here.

#### Project details
Information on the project details and problem space, as well as our initial look into existing solutions and areas for further investigation can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/docs/specification/Sprint-1-Specification.pdf).

#### Requirement Elicitation
The directory containing our requirement elictation plans is located [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/requirements_elicitation).

#### Meeting minutes
Meeting minutes are taken during each client and team meeting and have been grouped by sprint. A list of sprint minutes is provided below:
+ [Sprint 1 minutes](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/docs/meetings/Sprint-1-meeting-minutes.pdf)

## Release notes
As we were creating and structuring our repository during this sprint, no feature branches have been merged into master. 
However, the following additions were made during this sprint:

+ Created repository, filled out basic structure
+ Added project overview and useful links to readme
+ Added documents containing meeting minutes, requirement elicitation plans, and project specifications 
