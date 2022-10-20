# Clinical Evaluation Report

The Clinical Evaluation Report states the clinical benefits and safety characteristics of the device, based on
clinical data. It is the output of the Clinical Evaluation Plan.

> While the content of the Clinical Evaluation is simple, writing it, coming up with the right structure and
> forming a sensible line of reasoning (equivalence) can be a bit tricky.
>
> These are the guidance documents on Clinical Evaluation. If you're the person writing it, you should read
> them:
>
>  * MDCG 2020-1, 2020-5, 2020-6
>  * MDCG 2020-13: Quite helpful as it gives you an idea of the structure.
>  * MEDDEV 2.7/1 Rev. 4. (mostly for MDD, but still a good starting point; especially the list of proposed
>    headings for a report at the end of the document).
>
> Finally, this Clinical Evaluation Report is for Medical Devices. If you are an IVD manufacturer you will
> write a Performance Evaluation Report which has many similarities but some essential parts are different,
> e.g., Post-Market Performance Follow-Up and procedural descriptions of evaluation and validation).

## Table of Contents

> A list of the sections is presented below. You have to update this manually when you edit headings as this
> is a markdown file (sorry - guilty dog face).

 1. List of Abbreviations
 2. Product
 3. Relevant Documents
 4. Scope of the Clinical Evaluation
 5. Device
 6. Clinical Background, Current Knowledge, State of the Art
 7. Type of Evaluation
 8. Literature Search
 9. Clinical Data
 10. Post-Market Activities
 11. Conclusions
 12. Date of the Next Clinical Evaluation
 13. Dates and Signatures
 14. Qualification of the Responsible Evaluators
 15. References

## 1. List of Abbreviations

| Abbreviation | Explanation                                            |
|--------------|--------------------------------------------------------|
| AE           | Adverse Event                                          |
| BfArM        | German Federal Institute for Drugs and Medical Devices |
| CE           | Communauté Européenne                                  |
| CER          | Clinical Evaluation Report                             |
| CI           | Confidence interval                                    |
| DHF          | Design History File                                    |
| DMR          | Device Master Record                                   |
| EUDAMED      | European Database for Medical Devices                  |
| FDA          | Food and Drug Administration (US)                      |
| IFU          | Instruction for Use                                    |
| LoE          | Level of Evidence                                      |
| MAUDE        | Manufacturer and User Facility Device Experience       |
| MEDDEV       | Guideline for Clinical Evaluation of Medical Devices   |
| MDD          | Medical Device Directive, European Directive 93/42/EEC |
| MDR          | Medical Device Regulation (EU) 2017/745                     |
| PMS          | Post Market Surveillance                               |
| PMCF         | Post Market Clinical Follow Up                         |
| Rev          | Revision                                               |
| SOP          | Standard Operation Procedure                           |
| T            | Tendency                                               |
| C            | Comparability                                          |
| WHO          | World Health Organization                              |

## 2. Product

 * Name: *\<product name\>*
 * Version: *\<product version\>*
 * Basic UDI-DI: *\<insert UDI-DI, if/when available\>*
 * UMDNS-Code: *\<insert UMDNS-Code, if/when available\>*
 * GMDN-Code: *\<insert GMDN-Code, if/when available\>*

The classification is based on the following criteria:

> Select one of these two, based on whether you're going for MDD or MDR compliance.

 * Annex IX of the European Directive 93/42/EEC (MDD): *\<if applicable\>*.
 * Annex VIII, Section 6 (Active Devices) Rule *\<write the Rule number, e.g., 13\>* of the EU Regulation 2017/745 (MDR).

## 3. Relevant Regulatory References

Other relevant regulatory documents:

* SOP Clinical Evaluation
* Clinical Evaluation Plan
* Instructions for Use (IFU)

This clinical evaluation report serves as evidence of conformance with certain General Safety and Performance
Requirements pursuant to EU Regulation 2017/745 (MDR), Annex I.

Specifically, the following requirements were evaluated as part of this report:

* Chapter 1 (General Requirements), para. 1 and 8
* Chapter 2.8 (Software Devices), para. 17.2

## 4. Scope of the Clinical Evaluation

> Note: This section is copy-pasted from the Clinical Evaluation Plan.

> The following section can be part of the Clinical Evaluation Plan or pasted here with reference to the
> respective chapters. Remember that you can update the Clinical Evaluation Plan during your evaluation
> (e.g., your search criteria are not sufficient).
>
The approach according to the MEDDEV 2.7/1 Rev. 4 includes five logical procedural stages in order to
evaluate the performance and safety data of the medical device:

* Step 0 ("Scope")
* Step 1 ("Identification")
* Step 2 ("Appraisal")
* Step 3 ("Analysis")
* Step 4 ("Report")

During the working process, these five steps are iterative and influence each other. The report shows the
steps in a sequential way. In the present report (step 4), the steps 0 through 3 are corresponding to the
following chapters:

> List sections of the Clinical Evaluation Report here which cover the steps above.

## 5. Device

### 5.1 Device Description

> Copy-paste your Device Description here, which includes the Intended Use but also, User Profile, 
> Precautions/Safety Instructions, Contraindications, Use Environment, Operating Principle, 
> Variants/Accessories, Novelty, Design Requirements. If it's not done yet, remember to
> do it later :)

> Make sure to reference your Design Requirements Document of the stakeholder and software requirements here.

### 5.2 Clinical Benefits, Outcome Parameters

> Medical device claims are statements from accompanying documents, marketing material, your website,
> etc. that include information about the performance and safety of the medical device (information by the
> manufacturer). The clinical evaluation is done in order to determine whether those claims are confirmed by
> sufficient clinical evidence.
>
> So, if your website claims that your device cures back pain in 50% of patients after 14 days, here's the
> place to list that claim and show explain how you'll prove it.

Claims that have not been stated so far (e.g., in the IFU) are described below and sorted according to their
meaning for performance and safety. In this clinical evaluation, it was determined that the claims are
sufficiently supported by clinical data.

Performance-related product claims:
> * Claim 1, e.g., diagnosis for better treatment decision (performance)
> * Claim 2, e.g., xy % accuracy, xy % sensitivity, xy % specificity

### 5.3 Clinical Safety, Methods for Analysis

> Describe your safety parameters, i.e., which things should your product fulfil so that you consider it safe?
> And your methods, i.e., how will you prove that your product fulfils those safety parameters? A method could
> be a literature search for past studies, but you could additionally do a Post-Market Clinical Follow-Up to
> double-check whether that's actually true for your device.

> Also, make sure to mention that a risk management plan, risk assessment and risk management report were 
> undertaken according to the EN ISO 14971:2019 to evaluate all the known and foreseeable risks related to the product.

Safety-related product claims:
> * Claim 1, e.g., temporary worsening
> * Claim 2, e.g., placebo effect

### 5.4 Acceptability of Benefit-Risk-Ratio

> After you've defined your benefits and safety parameters, which combination of those is acceptable to you?
> In the case of most software devices (and apps), you'll probably have subtle benefits (e.g., better disease
> management, early detection of relapses) while low safety concerns (e.g., disease progression unlikely, not
> killing anyone). Thus, define criteria under which the benefit-risk profile is acceptable.

### 5.5. Risk Analysis <br>
> Copy-paste your Risk Management Report here. This is to prove that your medical device is safe.

### 5.6. Usability Testing <br>
> Copy-paste your Usability Evaluation Report here. This is to prove that your medical device is effective.

## 6. Clinical Background, Current Knowledge, State of the Art

> This chapter focus on literature  and guidelines that describe the current state of the art and
> other topics. It is similar to the literature / introduction chapter of papers.
>
> It makes sense to differentiate between "context" and "pivotal" data:
> * Context data describes the state of the art (commonly the introduction / literature part of papers)
> * Pivotal data is used for the appraisal, i.e., that's the data describing the actual study and
>   outcome(s). In the best case, the pivotal data is about the device(s) you're claiming similarity to.

### 6.1 Clinical Background & Current Knowledge

> Describe the clinical context of the disease you're treating. How are patients currently treated? Which
> symptoms do they have, which diagnostic modalities are being used to establish a diagnosis, which treatment
> options exist? What are the benefits and drawbacks of current treatment options?
>
> You can start with a definition of the disease and describe details about epidemiology, aetiology, pathophysiology, 
> investigation and diagnosis.

### 6.2 State of the Art incl. Alternative Treatments

> Given the current treatment options, what is the preferred, "state of the art" treatment? What are its
> benefits and drawbacks? Are there recent scientific achievements (studies, new technologies, software) which
> may be promising to improve this state-of-the-art treatment? Also, what are alternative treatments?
>
> You might want to consider adding a sub-section on digital therapeutics as well as organising this section into
> tables.

## 7. Type of Evaluation

> Note: This section is copy-pasted from the Clinical Evaluation Plan.
>
> Describe the type of Clinical Evaluation you'll be doing. Most probably, you'll be doing a literature search
> and review to come up with adequate clinical data.

## 8. Literature Search

### 8.1 Literature Search Methods

> Copy-paste from Clinical Evaluation Plan.

### 8.2 Literature Appraisal Criteria

> Copy-paste from Clinical Evaluation Plan.

### 8.3 Literature Search Protocol

> You can describe it as a flow chart, e.g.:
>
> 1. Initial search with all publications from the relevant databases. <br>
> 1.1 Potentially relevant papers (from the first skimming of article titles / abstracts) <br>
> 1.2 Irrelevant papers <br>
> 2. Potentially relevant papers found in irrelevant papers <br>
> 2.1 Relevant paper used for context <br>
> 2.2 Relevant paper used for a single appraisal (pivotal data) <br>

### 8.4 Literature Search Overview
> A table which lists your actual literature search results. For each entry, you should decide whether it's
> acceptable (based on your appraisal criteria) or not. I pre-wrote some tables to give you an idea of the
> structure below. You could separate the tables based on the database where you did the search (PubMed,
> Google Scholar).
>
> It could make sense to put this in a separate document (rather: a spreadsheet).

> Here are some bullet points from the guidance:
> * Literature search protocol provided
> * Literature search reports provided
> * Full list of retrieved articles provided
> * Full list of excluded articles provided, with reasons for exclusion Full text copies of relevant documents
>   available

#### Database Search Overview

| Database | Search term | # Hits | # Evaluated Abstracts | # Potential Relevant Publications |
|----------|-------------|--------|-----------------------|-----------------------------------|
|          |             |        |                       |                                   |

#### Database: PubMed

| Title | Author | Year | Summary | Relevant? Why?                          |
|-------|--------|------|---------|-----------------------------------------|
|       |        |      |         | *e.g., similar design, similar features* |

#### Database: Google Scholar

| Title | Author | Year | Summary | Relevant? Why? |
|-------|--------|------|---------|----------------|
|       |        |      |         |                |

#### Database: Cochrane

| Title | Author | Year | Summary | Relevant? Why? |
|-------|--------|------|---------|----------------|
|       |        |      |         |                |

### 8.5 Literature Search Report

> Briefly summarise how many studies you reviewed, how many you deemed acceptable and why you didn't include
> the unacceptable ones (probably because they didn't conform to the appraisal criteria).

> Describe a gap analysis which information could not be found during your search e.g., specific
> functionalities of your device, limited number of clinical data in publications.

### 8.6 Evaluation of Study Quality

#### 8.6.1  Level of Evidence (LoE)

> Take a sufficient classification to evaluate the quality of your study. You can use the LoE from MDCG 2020-6
> or from the American Heart Association.

#### 8.6.2 Tendency (T)

> The MEDDEV 2.7/1 Rev. 4 requires that literature is used that confirms as well as questions the suitability
> of the evaluated medical device.
>
>  * Positive: + (Confirms clinical suitability)
>  * Negative: - (Does not confirm clinical suitability)
>  * Indifferent: i (No statement to the clinical suitability possible)

#### 8.6.3 Comparability (C)

> For the consideration of the relevance of literature data for the clinical evaluation it is necessary to make
> a statement about the comparability to the medical device to be evaluated.

#### 8.6.4  Single Appraisal of Searched Clinical Studies

> This sub-section is highly important for medical device evaluation. Here you take all the publications from
> the literature search and evaluate them to prove equivalence with your device and prove the respective
> product claims. The latter can also be proven by other activities (e.g., PMS, equivalent device, usability
> testing, result of adverse events etc.).

#### 8.6.5 Literature Data on the Performance of the Medical Device

> Focus here on equivalent devices that support your performance claims.

> Do the paper description in the same way e.g.:
>
>  * First, describe the study with its main characteristics regarding the quality and relevance are made
>    (study design, patient number, mean age inclusion and exclusion criteria, used product, endpoint,
>    results of performance, conclusion of the author).
>  * Complications, side-effects, adverse events.
>  * A consideration of the study according to the criteria (LoE, T, C).

Herein, the selected literature references, which were categorised as "relevant" (appraisal), are
evaluated. This was done according to the following scheme:

#### 8.6.6 Literature Data about the Safety of the Medical Device

> Focus here on equivalent devices that support your Safety claims. So you do not need to describe the LoE
> since potential risks can also arise from case studies (which might have a low LoE). Were any side effects mentioned
> in any of the identified relevant studies?

## 9. Clinical Data

### 9.1 Clinical Data From Literature

> List all the clinical data you got from studies which matched your appraisal criteria,
> e.g., study design such as number of subjectives, age and any other relevant parameter considered, objectives, 
> disease severity, what the measured outcomes/endpoints were.
> 
> Feel free to organise this section into tables.


### 9.2 Clinical Data from Clinical Study Databases

> List all the clinical data you got from studies (clinical trials.gov, ANCTR, DRKS, WHO etc.).

### 9.3 Clinical Data From Adverse Event Databases

> List all the clinical data you got from studies which matched your appraisal criteria (BfArM, MAUDE, FDA
> Medical Device Recall, EUDAMED (when applicable)).

### 9.4 Summary and Appraisal of Clinical Data

> Summarise all the clinical data from above :)

### 9.5 Analysis of the Clinical Data

> Analyse the clinical data with a focus on whether your targets of clinical benefits and safety were
> fulfilled.

## 10. Post-Market Activities

> This chapter is used to summarise your PMS/ PMCF activities. During the clinical evaluation you evaluate
> the information of your safety and performance claims as well as general requirements on safety &
> performance. If you can not cover certain aspects you might need to add them to your PMS/ PMCF - Plan.

> Summarise your post-market activities. You can copy-paste a lot of those here. At the minimum, you'll have a
> Post-Market Surveillance Plan and Report. If this is your initial certification, your report may be empty as
> you haven't brought your device to the market yet.

> Additionally, you may have a Post-Market Clinical Follow-Up (PMCF) Plan and Report, which essentially have the
> content of "we'll be tracking some data to make sure that our claims of clinical benefits and safety are
> actually true".

> Here's what the guidance states about it: <br>
> Describe how the manufacturer will verify the presumption that there would be no clinically significant
> difference in the safety and clinical performance of the device under evaluation compared with the
> equivalent device by post market surveillance or post market clinical follow-up.

> * PMS Plan
> * PMS Report
> * PMCF Plan
> * PMCF Report
> * PSUR (if relevant)

## 11. Conclusions

> Your conclusion is whether the clinical data shows that your goals (benefit/ performance and safety) are
> fulfilled. Reference your claims you stated before.

## 12. Date of the Next Clinical Evaluation

> When will you be doing the next clinical evaluation and updating this report?

## 13. Dates and Signatures

> Date and sign the report. If your document management system supports it, you can digitally sign by typing
> e.g., your initials in the "Signature" field. Otherwise, you can still sign it the old-school way (print it
> and sign the sheet of paper, ugh).

| Activity | Name | Date | Signature |
|----------|------|------|-----------|
| Creation |      |      |           |
| Review   |      |      |           |
| Approval |      |      |           |

## 14. Qualification of the Responsible Evaluators

> Attach CVs of the people who were involved in writing the Clinical Evaluation. They must fulfil some
> criteria (it's complicated), so I'll just copy-paste MEDDEV 2.7/1 Rev. 4 here:

> * The manufacturer defines requirements for the evaluators that are in line with the nature of the device
>    under evaluation and its clinical performance and risks.
>  * The manufacturer should be able to justify the choice of the evaluators through reference to their
>    qualifications and documented experience, and present a declaration of interest for each evaluator.
>
> As a general principle, the evaluators should possess knowledge of the following:
>  * research methodology (including clinical investigation design and biostatistics); MEDDEV 2.7/1 revision 4
>    page 14 of 65
>  * information management (e.g., scientific background or librarianship qualification; experience with relevant
>    databases such as Embase and Medline);
>  * regulatory requirements; and
>  * medical writing (e.g., post-graduate experience in a relevant science or in medicine; training and
>    experience in medical writing, systematic review and clinical data appraisal).
>
> With respect to the particular device under evaluation, the evaluators should in addition have knowledge of:
>  * the device technology and its application;
>  * diagnosis and management of the conditions intended to be diagnosed or managed by the device, knowledge of
>    medical alternatives, treatment standards and technology (e.g., specialist clinical expertise in the
>    relevant medical speciality).
>
> The evaluators should have at least the following training and experience in the relevant field:
>  * a degree from higher education in the respective field and 5 years of documented professional experience;
>    or
>  * 10 years of documented professional experience if a degree is not a prerequisite for a given task.
>
> There may be circumstances where the level of evaluator expertise may be less or different; this should be
> documented and duly justified.

## 15. References

> Papers and other references which you cite go here.
