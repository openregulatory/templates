# Document Roadmap TechDoc

This is a proposed roadmap to creating the TechDoc file. The documents are grouped by "Design Phase". To each
document, a responsible person is assigned as the author. Go through the list phase by phase. You can mix up
the order of documents within a phase, but I recommend to finalize documents from one phase before moving on
to the next.

### PHASE 1: Planning & Feasability

| Document                                        | Author                        | Comment                                                                                                                                                                            |
|-------------------------------------------------|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Intended Use                                    | CEO                           | This is the most important document of your TechDoc. Business and Regulatory Strategy depend on it.                                                                                |
| Medical Device Classification                   | QA/RA Manger                  | Defining the product's medical device classification acc. to MDR.                                                                                                                  |
| Product Roadmap                                 | Product Manager               | Not an essential document. This is for feasibility assessments and resource planning. Helps to keep track of what's to come.                                                       |
| Software Development and Maintenance Plan       | Software Developer            | Giving product-specific information on the tools, resources and methods to be used for software development. Helpful for developer teams to align regarding the development setup. |
| Change Evaluation List                          | QA/RA Manger                  | Listing and assessing gaps between the last and the upcoming software version. Follows criteria from MDCG 2020-3. Not needed for the very first release.                           |
| Risk Management Plan and Risk Acceptance Matrix | Risk Manager                  | Specifies the methods for assessing risks to be used for the product at hand. Defines probability and severity categories and acceptable ranges.                                   |
| Clinical Evaluation Plan                        | Clinician / Scientific Person | Specifying the methodology that shall be used to assess the clinical benefits and risks of the product.                                                                            |

### PHASE 2: Specification

| Document                             | Author                               | Comment                                                                                                    |
|--------------------------------------|--------------------------------------|------------------------------------------------------------------------------------------------------------|
| User Needs List                      | Product Manager                      | This is a list of high-level requirements. Most of them will be implemented through Software Requirements. |
| User Needs Checklist                 | QA/RA Manager                        | Checking if the User Needs List makes sense.                                                               |
| Software Requirements List           | Developer-adjacent person            | Specifying how User Needs will be incorporated in the software. Describing the details of a feature.       |
| List of Hazard-Related Use Scenarios | Risk Manager                         | Identifying scenarios in which users could be prone to hazards.                                            |
| Risk Table                           | Risk Manager                         | Anticipating and assessing risks. Gathering input from various channels.                                   |
| Software Requirements Checklist      | QA/RA Manager                        | Checking if the Software Requirements List makes sense.                                                    |
| Software Test Plan                   | Software Developer                   | Defining tests for every Software Requirement and mapping them to each other.                              |
| Usability Test Plan                  | Product Manager / Usability Engineer | Specifying the methodologies to be used to conduct the Usability Test.                                     |

### PHASE 3: Development

| Document              | Author             | Comment                                                                                                         |
|-----------------------|--------------------|-----------------------------------------------------------------------------------------------------------------|
| SOUP List             | Software Developer | List of external libraries, frameworks and packages used in the product, incl. their assessment of criticality. |
| Software Architecture | Software Developer | Description/Graphic outlining the software components and their interaction.                                    |

The actual programming work takes place in this phase. It makes sense to create the SOUP list and the software
architecture immediately before programming begins and to adjust them if anything changes during code
creation. These documents should actually be created in advance, but due to the iterative nature of software
development, it will not be possible to plan everything before the actual work begins. Therefore, it makes
sense to create them in parallel with the programming.

### PHASE 4: Verification and Validation

| Document                   | Author                               | Comment                                                                                                                                                                           |
|----------------------------|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Software Test Results      | QA Tester                            | Results of the Software Tests: passed or failed?                                                                                                                                  |
| List of Known Anomalies    | Software Developer / Product Manager | List of known bugs and failed software tests. Justification why the software can still be released without impacting benefit/safety and a timeline when those bugs will be fixed. |
| Instructions For Use       | Person with the best overview        | The name says it all.                                                                                                                                                             |
| Usability Test Protocol    | Product Manager / Usability Engineer | Specifying the actual usability test cases: Testing User Needs, Hazard-Related Use Scenarios and Instructions for Use.                                                            |
| Usability Test Report      | Product Manager                      | Summary of the results of the Usability Test.                                                                                                                                     |
| Clinical Evaluation Report | Clinician / Scientific Person        | Analysing scientific data to prove the products safety and efficacy.                                                                                                              |
| Risk Management Report     | Risk Manager                         | Summary of the Risk Management Activities                                                                                                                                         |

### PHASE 5: Product Release

| Document                   | Author                                | Comment                                                                                                                                                             |
|----------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| GSPR List                  | QA/RA Manager                         | Checking if the "General Safety and Performance Requirements" are fulfilled.                                                                                        |
| PMS (/PMCF) Plan           | QA/RA Manager                         | Planning the product-specific activities for Post-Market Surveillance. If the clinical data is not sufficient, also plan Post-Market Clinical Follow-Up activities. |
| Software Release Checklist | QA/RA Manager                         | Checking if all the requirements are fulfilled, if the documents are complete and if the product is safe to be used.                                                |
| Release Notes              | Product Manager OR Software Developer | Description of new features in the current release.                                                                                                                 |
| Declaration of Conformity  | QA/RA and CEO                         | Declaring the product's conformity with the regulations and standards.                                                                                              |

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
