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

### Project details

Information on the project details and problem space, as well as our initial look into existing solutions and areas for further investigation can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/specification).

### Requirement Elicitation

The directory containing our requirement elictation plans is located [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/requirements_elicitation).

### User Personas

Four personas representing key users and stakeholders have been created and can be accessed [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/user_personas).

### Motivational Model and Do-Be-Feel table

A Do-Be-Feel session was run with the client to flesh out the goals for the system. The resulting Do-Be-Feel table and a derived motivational model can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/DoBeFeel_%26_Motivational_model).

### User Stories

User stories are provided that try to completely cover the capabilities required by the client and our understanding of the problem domain. 2 scenarios have also been documented, along with the user story map [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/user-stories).

### Acceptance Criteria

Acceptance criteria based on user stories can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/docs/acceptance_criteria_tests/accetanceCriteria.pdf).

### Acceptance Testing

Acceptance testing based on acceptance criteria can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/docs/acceptance_criteria_tests/acceptanceTests.pdf).

### Traceability Matrix

The traceability matrix can be found [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/docs/acceptance_criteria_tests/traceabilityMatrix.pdf).

### User Testing

Multiple scenarios to cover the varying requirements of the clients have been documented, along with our process for conducting the user testing. We have also provided a reflection of the user testing. This can be accessed [here](https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/docs/user-testing).

### Low Fidelity Prototype

A low fidelity prototype has been created to demonstrate a general idea of the solution envisaged by the team. Live version of the prototype can be found [here](https://marvelapp.com/prototype/9h3de41). The paper prototype sceens can be found [here](<https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/prototypes/low_fidelity/>).


### High Fidelity Prototype

 Live link to [Figma](https://www.figma.com/file/Xmit6kEwCE30QLxYb5rysC/Telstra-Dat-Normalisation?node-id=0%3A1). The paper prototype sceens can be found [here](<https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/tree/main/prototypes/high_fidelity>).

### Moodboard

The moodboard that defines the look of  high fidelity prototype can be found
[here](<https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/ui/moodboard.pdf>).

### Data Sample

Data samples used for the prototype can be found
[here](<https://github.com/Ishan27g/SWEN90009_2021_DN-Koala/blob/main/data_samples/dataSample.pdf>).


### Release notes

#### This release contains the following additions

+ Added Acceptance Criteria and Acceptance Tests
+ Added Traceability Matrix
+ Added Data Sample
+ Added a high fidelity prototype, with screens and link to live version
+ Added Moodboard

#### This release contains the following deletions

NA

All changes have been made on the master branch - no side branches have yet been created and merged, as our workflow is structured so that most documentation work takes place in confluence / google-docs, with only a single team member exporting content to GitHub.
