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

Copies of documents relating to requirements analysis and product specifications have been saved in this repository. As the project progresses and our solution grows more detailed, new documents will be added to the repository and will become accessible via links provided below.

#### Project details
Information on the project details and problem space, as well as our initial look into existing solutions and areas for further investigation can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/docs/specification/Sprint-1-Specification.pdf).

#### Requirement Elicitation
The directory containing our requirement elictation plans is located [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/requirements_elicitation).

#### User Personas
Four personas representing key users and stakeholders have been created and can be accessed [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/user_personas).

#### Motivational Model and Do-Be-Feel table
A Do-Be-Feel session was run with the client to flesh out the goals for the system. The resulting Do-Be-Feel table and a derived motivational model can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/DoBeFeel_%26_Motivational_model).

## Release notes
The following changes were made during this sprint:

+ Created Do-Be-Feel table and associated motivational model 
+ Developed personas
+ Updated specification to reflect our latest understanding of the desired solution
+ Updated requirements elicitation documents to reflect changes from sprint 2
+ Removed meeting minutes (minutes can still be found on confluence)

