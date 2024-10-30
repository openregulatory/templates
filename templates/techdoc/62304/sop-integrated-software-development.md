# SOP Integrated Software Development

| Classes | IEC 62304:2006 Section | Document Section |
|---------|------------------------|------------------|
| A, B, C | 5.1.2                  | 4                |
| A, B, C | 5.2.1                  | 4                |
| A, B, C | 5.2.4                  | 3, 7, 10         |
| A, B, C | 5.2.5                  | 4                |
| A, B, C | 5.2.6                  | 5                |
| B, C    | 5.3.1                  | 6                |
| B, C    | 5.3.2                  | 6                |
| C       | 5.3.5                  |                  |
| B, C    | 5.3.6                  | 6                |
| B, C    | 5.4.1                  | 6                |
| C       | 5.4.2                  |                  |
| C       | 5.4.3                  |                  |
| C       | 5.4.4                  |                  |
| A, B, C | 5.5.1                  | 6                |
| B, C    | 5.5.2                  | 7                |
| B, C    | 5.5.3                  | 7                |
| C       | 5.5.4                  |                  |
| B, C    | 5.5.5                  | 7                |
| B, C    | 5.6.1                  | 7                |
| B, C    | 5.6.2                  | 7                |
| B, C    | 5.6.3                  | 8                |
| B, C    | 5.6.4                  | 8                |
| B, C    | 5.6.5                  | 8                |
| B, C    | 5.6.6                  | 8                |
| B, C    | 5.6.7                  | 8                |
| A, B, C | 5.7.3                  | 8                |
| A, B, C | 5.7.4                  | 8                |
| A, B, C | 5.7.5                  | 8                |
| A, B, C | 5.8.1                  | 7                |
| A, B, C | 5.8.2                  | 11               |
| A, B, C | 5.8.4                  | 11               |
| B, C    | 5.8.5                  | 11               |
| B, C    | 5.8.6                  | 11               |
| A, B, C | 5.8.7                  | 11               |
| A, B, C | 5.8.8                  | 11               |
| A, B, C | 6.1                    | 4                |
| B, C    | 7.1.1                  | 2, 3, 6, 8, 10   |
| B, C    | 7.1.2                  | 2, 3, 6, 8, 10   |
| B, C    | 7.1.3                  | 6, 12            |
| B, C    | 7.1.4                  | 2, 3, 6, 8, 10   |
| B, C    | 7.2.1                  | 2, 3, 6, 8, 10   |
| B, C    | 7.2.2                  | 2, 3, 6, 8, 10   |
| B, C    | 7.3.1                  | 7                |
| B, C    | 7.3.3                  | 9                |
| A, B, C | 8.1.2                  | 4, 6, 8          |
| A, B, C | 8.1.3                  | 11               |
| A, B, C | 9.8                    | 8                |

| ISO 14971:2019 Section | Document Section         |
|------------------------|--------------------------|
| 4.1                    | 3, 4, 5, 6, 8, 9, 10, 11 |
| 5.1                    | 3, 4, 5, 6, 8, 9, 10, 11 |
| 5.3                    | 3, 4                     |
| 5.4                    | 3, 4                     |
| 5.5                    | 3, 4                     |
| 6                      | 3, 4                     |
| 7.1                    | 3, 4, 5                  |
| 7.2                    | 6                        |
| 7.3                    | 6, 10                    |
| 7.4                    | 10                       |
| 7.5                    | 6                        |
| 7.6                    | 10                       |
| 8                      | 10                       |
| 9                      | 10                       |

| IEC 62366-1:2015 Section | Title                                                                  | Document Section |
|--------------------------|------------------------------------------------------------------------|------------------|
| 4.1.1                    | Usability Engineering Process                                          | (All)            |
| 5.1                      | Prepare Use Specification                                              | 4                |
| 5.8                      | Perform User Interface design, implementation and Formative Evaluation | 4, 5, 6, 7       |

## Summary

This SOP describes how software as a medical device is developed. It integrates risk management and usability
engineering activities into the process.

|                                |                                                          |
|--------------------------------|----------------------------------------------------------|
| **Process Owner**              | *\<enter role of process owner\>*                        |
| **Key Performance Indicators** | *\<enter KPIs to be tracked for the Management Review\>* |

## General Notes

### Integrated Process, Evolutionary Strategy

This process integrates risk management and usability evaluation activities into the software development
process. It, therefore, covers requirements of IEC 62304, ISO 14971 and IEC 62366. There are no separate risk
management and usability engineering processes.

The Software Development Process described in this SOP resembles an "evolutionary" strategy (IEC 62304:2006,
Annex B), acknowledging that the user need is not fully understood and not all requirements are defined up
front. Whenever requirements change, the preceding process steps and their outputs need to be re-done to
ensure consistent and complete documentation.

## Process Steps

### 1. Design Input

Based on business input and product ideas, the process for product certification and registration is initiated
to create an initial device description (incl. medical device classification and software safety
classification) and high-level vision for the planned product. Technical input is considered to assess whether
the idea is feasible.

Business input could be:

 * Conversations with prospective customers
 * Market opportunities
 * Internal ideas

Changes to the product also enter the process here (i.e., as a change request as defined in SOP Change
Management).

| Participants | Management (e.g. CEO, CTO, CPO)                                                                  |
| ------------ | ------------------------------------------------------------------------------------------------ |
| Input        | Business input, Technical input, Product ideas, Change requests                                  |
| Output       | Intended use, Medical device classification, Device software safety classification (preliminary) |

### 2. Risk Management Planning

The risk management activities are planned and documented.

The Risk Management Plan defines criteria for risk acceptability in the form of a risk policy and a risk
acceptance matrix. It defines risk acceptability both for individual risks and the overall residual risk. The
risk acceptance matrix is created by performing the following steps:

* Estimate product usage over its lifetime
* Define categories for the severity of harm (for example, categories may range from zero harm to death of a
  patient)
* Define probability categories (for example, categories may range from "unthinkable’ over "rare’ to
  "certain’).
* Start by defining the least probable category which has an absolute occurrence number of less than one. From
  there on, the more frequently occurring categories are added with probability increments of 10^2.
* Create the risk acceptance matrix and define which combinations of the categories are deemed acceptable. Use
  color coding: red combinations represent unacceptable risks; yellow combinations represent risks that are
  acceptable.
* Note: no fields are marked as yellow as all risks must be reduced as far as possible.


| Participants | CPO, subject matter experts, e.g. physicians    |
| ------------ | ----------------------------------------------- |
| Input        | Device Description                              |
| Output       | Risk Management Plan, Usability Evaluation Plan |

### 3. First Risk Assessment and Usability Evaluation Planning

In the first risk and usability assessment, a preliminary hazard analysis is conducted and an initial risk
table is drafted.

The comprehensive risk analysis is performed by conducting a Failure Mode and Effects Analysis (FMEA). This analysis includes
the following activities:

 * Identifying potential failure modes
 * Identifying potential hazards, hazardous situations and harms in collaboration with subject matter experts
   (e.g. physicians). When creating a first-time risk analysis for a product, Annex C of ISO 14971 should be checked for applicable examples.
 * Estimating probabilities for the identified items and analyzing the severity of each harm, taking into
   account international standards, scientific studies, public reports, expert opinions and usability data.
 * For software devices, the probability of occurrence of a hazard is assumed as 100%. The probability of each
   hazard leading to a hazardous situation and that leading to a harm must be estimated separately as part of
   the risk analysis. Multiplied, they present the overall probability per risk. In combination, overall
   probability of occurrence and the severity of harm are evaluated against the risk policy previously defined
   for the device.

If a risk is deemed unacceptable based on our Risk Policy, it may be mitigated through Risk Control Measures
in the priority as listed below.  In general, we try to reduce the severity and probability of risks as far as
possible (AFAP).

1. Inherently safe design
2. Protective measures in the device or development process
3. Information for safety and/or training of users

Further, a usability evaluation plan is created which covers future formative and summative usability
evaluation activities.

User needs with a focus on those related to hazards are specified. These will serve as input to the
summative usability evaluation and are reviewed following the checklist for user needs review.

| Participants | CPO, subject matter experts, e.g. physicians                        |
| ------------ | ------------------------------------------------------------------- |
| Input        | Device Description, Risk Management Plan                            |
| Output       | Preliminary Hazards Analysis, Risk Table incl. Risk Acceptance Matrix (Draft), User Needs, User Needs Review Checklist, Usability Evaluation Plan |

### 4. Software Planning

Based on the device description, the user needs and the preliminary risk analysis, the next step is to plan
software development by defining software requirements. These also include the user interface specification,
e.g. wireframes, mockups or style guides.

A software development and maintenance plan is created following our template. Software versioning is to be
specified in the plan and should typically follow semver, in a format: MAJOR.MINOR.PATCH.  Significant changes
will lead to major version changes and a change of the UDI-DI, while non-significant changes lead to minor
version changes and changes of the UDI-PI only. Third-digit version changes (“patches”) result from bug fixes
(see SOP Change Management and SOP Certification and Registration).

The software system test plan is created based on the requirements. As requirements may change, the software
system test plan is continuously updated to reflect those changes.

| Participants | CTO, Software Engineer, Risk Manager, Usability Engineer                                              |
| ------------ | ----------------------------------------------------------------------------------------------------- |
| Input        | Device Description, Vision Document, Change Request, Risk Table (draft), Preliminary Hazards Analysis |
| Output       | Software Development and Maintenance Plan, Software Requirements incl. User Interface Specification, Software System Test Plan, Risk Table (updated) |

### 5. First Review: Software Planning Review

Software requirements are reviewed by following the checklist for Software Requirements Review. If the review
is successful, move forward to the next step. If it's not, the software requirements have to be reworked with
possible changes to the risk analysis and user needs. In that case, move back to the relevant step above.

| Participants | CTO, CPO, Risk Manager, Usability Engineer, Subject matter experts, e.g. physicians |
| ------------ | ----------------------------------------------------------------------------------- |
| Input        | Software Requirements, Risk Table (draft), User Needs                               |
| Output       | Checklist Software Requirements Review (filled out)                                 |

### 6. Software Architecture, Detailed Design and Implementation

Software architecture is created (and detailed design, if necessary). As the software development process
follows agile methodology, the software architecture may change as new knowledge is gained during
implementation. The end result should be that both the implementation and the documented software architecture
are synchronized.

At a minimum, an architecture diagram showing all software systems including databases and networks is
created. For each software system, public interfaces, are documented, e.g. REST APIs, internal methods.

SOUP is added/updated here, if necessary. For each SOUP, we specify the name, version, manufacturer, website
link (incl. release notes and issue tracker), requirements and prerequisites. SOUP must be verified before
moving to the next step. Possible SOUP verification criteria include sufficient test coverage by the author
and being commonly used; correct SOUP functioning is also verified through software verification and software
system testing in the following steps.

If new risks relating to software units and potential failure modes are discovered during this phase, they are
added to the risk table.

| Participants | CTO, Software Engineer                                                                      |
| ------------ | ------------------------------------------------------------------------------------------- |
| Input        | Software Development and Maintenance Plan, Software Requirements, Software System Test Plan |
| Output       | Implemented Software Items, i.e. code, Software Architecture (created/updated), Software Detailed Design (created/updated), SOUP list (created/updated), Risk Table (updated) |

### 7. Second Review, Verification, Formative Usability Evaluation, Integration

The second review covers multiple activities:

 * **Verification** of the software items based on code review and automated unit and integration tests
 * **Formative Usability Evaluation** through a usability engineer whether the user interface has been
   implemented as specified

Code review is conducted based on the following criteria:

 * Are all software requirements, software architecture and detailed design implemented correctly?
 * Does the code adhere to coding guidelines which include requirements for documentation as specified in the
   Software Development and Maintenance Plan?

Upon successful verification, the implemented software requirement is integrated into the current code base as
described in the Software Development and Maintenance Plan. The software units may be integrated only if all
activities above were successful.

| Participants | Software Engineer, Usability Engineer                                                            |
| ------------ | ------------------------------------------------------------------------------------------------ |
| Input        | Implemented Software Unit(s) incl. User Interface                                                |
| Output       | Code review result, Unit / Integration test result(s), Formative Usability Evaluation Assessment |

### 8. Software System Testing

Based on the Software System Test Plan, software system tests covering all software requirements are
performed.

If new risks are discovered during the system tests, they are added to the risk table.

If anomalies are encountered, they are added to the list of known anomalies and/or entered as new software
requirements to be fixed.

| Participants | Software Engineer                                                                                                    |
| ------------ | -------------------------------------------------------------------------------------------------------------------- |
| Input        | Software System Test Plan                                                                                            |
| Output       | Software System Test Protocols, Software System Test Report, Risk Table (updated), List of known anomalies (updated) |

### 9. Validation / Summative Usability Evaluation

Validation is done as a summative usability evaluation.

A Usability Test is conducted in the context of the actual user needs in accordance with the Usability
Evaluation Plan.

If new risks are discovered during the usability tests, they are added to the risk table.

| Participants | CPO<br>Usability Engineer<br>Users for Usability Test                                    |
| ------------ | ---------------------------------------------------------------------------------------- |
| Input        | User Needs, Labeling and Instructions for Use (if applicable), Usability Evaluation Plan |
| Output       | Usability Test Protocol(s), Summative Evaluation Report, Risk Table (updated)            |

### 10. Final Risk Assessment and Risk-Benefit Analysis

The overall risk of the product is evaluated by analyzing all identified risks so far. If unacceptable risks
exist, they are weighed against the benefits of the Medical Device as part of the Clinical Evaluation SOP and
as specified by the Clinical Evaluation Report. We only continue to release the Medical Device if the benefits
outweigh the risks.

If unacceptable risks remain which are not outweighed by the benefits, we consider adding new risk control
measures and move back in to the relevant step in the process.

The finalization of the Risk Management Report is the prerequisite for finalizing the Software Safety
Classification.

| Participants | CEO, CTO, CPO                                                                               |
| ------------ | ------------------------------------------------------------------------------------------- |
| Input        | Preliminary Hazards Analysis, Risk Table, Clinical Evaluation, Software (Release Candidate) |
| Output       | Risk Management Report, Software Safety Classification (final)                              |

### 11. Product Release and Labeling

Before release, it is ensured that all required process steps (software development, usability evaluation,
risk analysis) have been completed. Release notes are created and the list of known anomalies is
finalized. The software is only released if the remaining anomalies are deemed acceptable.

Finally, the software is assigned required labeling, including at minimum:
* The (trade) name of the device and manufacturer address
* The intended purpose of the device (where it is not obvious to the user)
* An indication that the product is a medical device, following symbols and labels specified in ISO 15223-1
* CE marking
* Unique Device Identifier (see product certification and registration process)
* Software version number in accordance with the software development plan
* Warning, precautions, contraindications and residual risks that need to be brought to the user’s attention
  as outlined by risk control measures in the risk file

**Regulatory Release:**

A product (version) is considered released with the release of its declaration of conformity or, in the case
of a minor version update, with the release of its updated software release checklist. The documents have to
be signed by both a member of Management and the Person Responsible for Regulatory Compliance (PRRC). The
regulatory release is completed by following all steps of SOP for product certification and registration.

**Technical Release:**

Following the regulatory release of the device, market placement and release is carried out by following the
deployment process.

| Participants  |
|---------------|
| CTO           |
| PRRC          |

| Input                                     | Output                                      |
|-------------------------------------------|---------------------------------------------|
| Device Description                        | Released Software                           |
| Software Release Checklist                | Software Release Checklist (filled out)     |
| Risk Analysis                             | Release Notes incl. list of known anomalies |
| User Needs                                |                                             |
| Software Requirements                     |                                             |
| Software Architecture and Detailed Design |                                             |
| Software Items incl. Verification         |                                             |
| Software System Test Report               |                                             |
| Usability Evaluation Results              |                                             |

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
