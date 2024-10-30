# Risk Management Report

The Risk Management Report contains the output and summary of risk management activities. The general planning
and methods are described in the Risk Management plan, while the actual risks are listed and analyzed in the
Risk Table.

The process and stages of risk analysis are described in the SOP Integrated Software Development.

## Mapping of Standard Requirements to Document Sections

| ISO 14971:2019 Section                | Document Section             |
|---------------------------------------|------------------------------|
| 4.5 Risk management file              | (all)                        |
| 7.4 Benefit-risk analysis             | 6                            |
| 7.6 Completeness of risk control      | (by review of this document) |
| 8 Evaluation of overall residual risk | 3, 5                         |
| 9 Risk management review              | (all)                        |

## 1. Relevant Processes and Documents

 * SOP Integrated Software Development
 * Risk Management Plan
 * Risk Acceptance Matrix
 * Risk Table

## 2. Risk Analysis

> The general idea about this section is that you simply summarize the amount of stuff you added to your Risk
> Table (a separate document).

### 2.1 Preliminary Hazards Analysis

*\<no. of hazards\>* hazards were identified based on the Intended Use and Usability Tests. They were further
analyzed in the Risk Table.

### 2.2 Failure Modes

*\<no. of failure modes\>* failure modes of software systems were identified. They were further analyzed in
the Risk Table.

### 2.3 Failure Mode and Effects Analysis (FMEA)

All preliminary hazards and potential failure modes of the software were analyzed. Annec C of ISO 14971 was reviewed for potentially applicable scenarios. In total, *\<no. of hazards\>* were identified. The hazardous situation(s) and harm(s) which they could lead to were analyzed, including intermediate probabilities (p1 and p2).

## 3. Risk Control Measures

Risks were reduced as far as possible (AFAP). If a risk was classified as "unacceptable" based on
the Risk Table, Risk Control Measures were implemented.

The following categories of Risk Control Measures were implemented in priority as listed below:

1. Inherent safety by design
2. Protective measures
3. Information for safety

In total, *\<no. of risk control measures\>* were implemented.

## 4. Risk Matrix

After implementation and verification of all Risk Control Measures, the count of risks in the Risk Acceptance
Matrix was as follows:

| Probability  | S1: Negligible | S2: Marginal        | S3: Critical        | S4: Catastrophic    | Estimated Maximum Event Count |
|--------------|----------------|---------------------|---------------------|---------------------|-------------------------------|
| P5: Certain  | acceptable: 0  | **unacceptable: 0** | **unacceptable: 0** | **unacceptable: 0** | 1000000                       |
| P4: Likely   | acceptable: 0  | **unacceptable: 0** | **unacceptable: 0** | **unacceptable: 0** | 10000                         |
| P3: Possible | acceptable: 0  | acceptable: 0       | **unacceptable: 0** | **unacceptable: 0** | 100                           |
| P2: Unlikely | acceptable: 0  | acceptable: 0       | acceptable: 0       | **unacceptable: 0** | 1                             |
| P1: Rare     | acceptable: 0  | acceptable: 0       | acceptable: 0       | acceptable: 0       | 0                             |

## 5. Summary of Risks and Unacceptable Risks

> If you don't have unacceptable risks (more likely), use this section:

After Risk Control Measures, no unacceptable risks remained. The software, therefore, fulfils the specifications
of the defined risk policy and is safe. A Benefit-Risk Assessment is not required.

> If you still have unacceptable risks, use this section:

After Risk Control Measures, *\<no. of unacceptable risks\>* unacceptable risks remained. They will be further
assessed in the Benefit-Risk Assessment below.

> Optionally, mention here your device's software safety classification according to IEC 62304, resulting from the worst possible risks found above.

## 6. Benefit-Risk Assessment

> Only use this whole section (Risk-Benefit Assessment) if you have unacceptable risks.

The *\<no. of unacceptable risks\>* remaining unacceptable risks are compared to the benefits resulting from
the Clinical Evaluation Report.

The benefits are as follows:

*\<Copy-paste benefits from Clinical Evaluation\>*

> Add a conclusion on whether the benefits outweigh the risks

Weighing the benefits against the risks, we conclude that...

## 7. Overall Residual Risk

> Take a look at your risk mitigating measures and assess whether the combination of them could lead to a risk that has not been taken care of yet, e.g., if one mitigation serves two or more risks at once.

The overall residual risk is estimated to have a probability of *\<probability of residual risk\>* and a severity of *\<severity of residual risk\>*. According to the Risk Acceptance Matrix the overall residual risk is assessed as *\<acceptable\>*.

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
