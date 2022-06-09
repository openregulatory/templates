# Software Development and Maintenance Plan

> This document is related to your product. You somehow need to associate it with it. The easiest way would be
> to just put all product-related documents into a folder in your QMS so that the association is
> clear. Alternatively, you could mention the related product and version here, but then you'd have to update
> the version here any time you do a new release. Painful!

This document summarizes development and maintenance activities.

## Mapping of Standard Requirements to Document Sections

| ISO 13485:2016 Section                | Document Section |
|---------------------------------------|------------------|
| 7.3.2 Design and Development Planning | 1, 2, 3, 7       |

| Classes | IEC 62304:2006 Section                                                     | Document Section |
|---------|----------------------------------------------------------------------------|------------------|
| A, B, C | 4.4.2 Risk Management Activities                                           | 1                |
| A, B, C | 5.1.1 a) (Processes)                                                       | 1                |
| A, B, C | 5.1.1 b) (Deliverables)                                                    | 1                |
| A, B, C | 5.1.1 c) (Traceability)                                                    | 1                |
| A, B, C | 5.1.1 d) (Configuration and Change Management)                             | 1, 5             |
| A, B, C | 5.1.1 e) (Problem Resolution)                                              | 1                |
| A, B, C | 5.1.2 Keep Software Development Plan Updated                               | 1                |
| A, B, C | 5.1.3 Software Development Plan Reference to System Design and Development | 2                |
| C       | 5.1.4 Software Development Standards, Methods and Tools Planning           |                  |
| B, C    | 5.1.5 Software Integration and Integration Test Planning                   | 3, 8             |
| A, B, C | 5.1.6 Software Verification Planning                                       | 7                |
| A, B, C | 5.1.7 Software Risk Management Planning                                    | 1                |
| A, B, C | 5.1.8 Documentation Planning                                               | 6                |
| A, B, C | 5.1.9 Software Configuration Management Planning                           | 5                |
| B, C    | 5.1.10 Supporting Items to be Controlled                                   | 5                |
| B, C    | 5.1.11 Software Configuration Item Control Before Verification             | 5                |
| B, C    | 5.1.12 Identification and Avoidance of Common Software Defects             | 4                |
| A, B, C | 6.1 Software Maintenance Plan.                                             | 9                |

## 1 Relevant Processes and Documents

Please see the relevant processes for the following activities:

 * Risk management activities incl. SOUP risks: SOP Integrated Software Development
 * Problem resolution: SOP Problem Resolution
 * Software development incl. deliverables, traceability, regular update of software development plan: SOP
   Integrated Software Development
 * Change management: SOP Change Management
 * SOUP List
 * SOP Usability Engineering

## 2. Required Resources

### 2.1 Team

| Role               | Count | Names                    |
|--------------------|-------|--------------------------|
| Frontend Developer | 2     | Ada Lovelace, Steve Jobs |
| Backend Developer  | 1     | Alan Turing              |

### 2.2 Software

Describe your device's software safety class according to IEC 62304 and your reasoning behind the classification.

#### Programming Languages

> List the languages you’ll be using, including compiler and language versions.

| Name   | Version |
|--------|---------|
| Python | 3.8     |

#### Development Software

> List software used to support development, e.g., IDEs.

| Name    | Version  |
|---------|----------|
| PyCharm | 2020.1.4 |

### 2.3 System Requirement / Target Runtime

> List your target runtime(s).

| Name    | Version |
|---------|---------|
| CPython | 3.8     |

> Specify system requirements, e.g., the minimum specifications of the server / compute instance you'll be
> running your software on

*Minimum system requirements:*

 * *Server-grade dual-core CPU, e.g., Intel Xeon E3-1230 v5 or higher*
 * *4 GB of RAM*
 * *1 GBit/s up- and downlink*
 * *20GB SSD storage*

## 3 Design Phases

> The 13485 requires you to specify "Design Phases". Here are some suggestions which you could use.

| Title          | Date | Description |
|----------------|------|-------------|
| Specification  |      |             |
| Implementation |      |             |
| Testing        |      |             |
| Validation     |      |             |
| Release        |      |             |

## 4 Avoiding Common Software Defects Based on Selected Programming Technology

> Discuss how your selected programming technology may introduce risks and how you plan to avoid them. With
> modern, dynamically-typed languages, an obvious risk is that you encounter runtime exceptions. So you could
> argue that your test coverage is great and compensates for that. You could also link to your risk analysis
> here if you analyse those risks further.

## 5 Configuration Management and Version Control

> Describe which version control software you're using (probably git, like all human beings on this planet
> right now, except enterprise developers). Also describe your branching model, i.e., how your developers
> create branches during development, how you name them and how you merge them (pull requests? merge commits?
> squash before?). Your code review will be described in the next section.
>
> Importantly, describe which things (code, build files, etc.) are put in version control. Describe how you
> name versions and how you tag them. Your goal should be that you can retrieve an old version and build
> it. Why? Something with a newer version may go wrong (harm patients) and you may need to roll back.

*git is used as version control software. All source code and build files are committed to version control.*

*When implementing software requirements, developers create a new branch starting at master. During
development, developers may create intermediate commits on this development branch.*

*When implementation is completed, a new merge commit to master is created.*

***This is also the activity which constitutes integration of software units.***

*For each release, the goal is to be able to uniquely identify it and retrieve all relevant files (code,
configuration files like build scripts, SOUPs, etc.) at any time in the future.*

*When a new software version is released, its commit is tagged in git. The tag is constructed by adhering to
semver ([semver.org](https://semver.org)) 2.0.0 which results in a version of format MAJOR.MINOR.PATCH,
e.g., 1.0.0.*

## 6 Documentation Activities

> Describe your policy on what should be documented while you develop software. Maybe you want to require
> your developers to document all methods which are private. Maybe you want to keep an up-to-date software
> architecture diagram in the repository, etc.

## 7 Implementation Verification Activities

> Describe verification activities, e.g. code review.

*For each pull request, a code review is performed by a team member who was not the main author of the code
under review. The code review is only marked as "approved" if the code complies with the code review
criteria. This is:*

 * *Code fulfils the software requirements*
 * *Adherence to [PEP8 Style Guide](https://www.python.org/dev/peps/pep-0008/)*

## 8 Software System Test Activities

> Describe software system test activities. This could be continuous integration which is triggered by opening
> a pull request (e.g. Travis CI, Circle CI). Describe what is tested and how that automated system works.

*Integration tests are included in software system tests.*

## 9 Validation Activities

Validation is carried out as formative and summative usability evaluation as described in the software development process. A usability evaluation file (plan, protocol and report) will be prepared.

## 10 Maintenance Activities

> Describe how often you check SOUP issue trackers and how you document them.

*SOUP issue trackers are checked at least once every 6 months. The verification date is updated in the SOUP
list accordingly.*
