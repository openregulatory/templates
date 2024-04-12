# SOP Change Management

| Classes | IEC 62304:2006 Section | Document Section |
|---------|------------------------|------------------|
| A, B, C | 6.2.3                  | 2                |
| A, B, C | 6.2.4                  | 2                |
| A, B, C | 6.2.5                  | 2                |
| A, B, C | 6.3.1                  | 3                |
| A, B, C | 6.3.2                  | 3                |
| A, B, C | 7.4.1                  | 2                |
| B, C    | 7.4.2                  | 2                |
| B, C    | 7.4.3                  | 2                |
| A, B, C | 8.2.1                  | 2                |
| A, B, C | 8.2.2                  | 3                |
| A, B, C | 8.2.3                  | 3                |
| A, B, C | 8.2.4                  | 3                |
| A, B, C | 9.4                    | (All)            |

## Summary

This SOP describes how we evaluate and make changes to our software after it’s released.

|                                |                                                          |
|--------------------------------|----------------------------------------------------------|
| **Process Owner**              | *\<enter role of process owner\>*                        |
| **Key Performance Indicators** | *\<enter KPIs to be tracked for the Management Review\>* |

## General Considerations

### Feedback Classification

Feedback is either classified as a **bug fix** or a **regular change request**:

* **Bug fixes:** By definition, bug fixes only constitute minor changes to the software code and complement
  existing device features instead of introducing new ones or removing existing ones. Bug fixes must
  not 1) Constitute significant changes to the medical device as defined by the criteria outlined in the
  change assessment list and 2) Introduce new risks or failure modes
* **Regular Change Requests:** All other changes that are not classified as a bug fix.

### Guidance Documents

The processing of changes is based on the following regulatory provisions and guidances:

* **Medical Device Regulation, Annex IX Chapter II Section 4.10:** *"Changes to the approved device shall
  require approval from the notified body which issued the EU technical documentation assessment certificate
  where such changes could affect the safety and performance of the device or the conditions prescribed for
  use of the device. Where the manufacturer plans to introduce any of the above-mentioned changes it shall
  inform the notified body which issued the EU technical documentation assessment certificate thereof. The
  notified body shall assess the planned changes and decide whether the planned changes require a new
  conformity assessment in accordance with Article 52 or whether they could be addressed by means of a
  supplement to the EU technical documentation assessment certificate. In the latter case, the notified body
  shall assess the changes, notify the manufacturer of its decision and, where the changes are approved,
  provide it with a supplement to the EU technical documentation assessment certificate."*
* **Medical Device Coordination Group (MDCG) Document 2020-03:** “Guidance on significant changes regarding
  the transitional provision under Article 120 of the MDR with regard to devices covered by certificates
  according to MDD or AIMDD”

## Process Steps

### 1. Creation of Change Request

Changes proposals can originate from various sources, e.g.:

* Internal design ideas
* Market research
* Customer feedback (see process for feedback management)
* Post-Market Surveillance (see process for post-market surveillance)
* Changes to the QMS

They can originate from anywhere inside the company.

The Product Manager creates a change request ticket in the company’s project management software with a
description of the proposed change.

| Participants                                 |
|----------------------------------------------|
| Anyone in the company with a change proposal |

| Input           | Output                                                   |
|-----------------|----------------------------------------------------------|
| Change proposal | Documented change request (ID per product version) |

### 2. Evaluation of Change

The Product Manager, together with a Regulatory Affairs Manager and the Head of Software Development, then
evaluates the proposed change. In a first step, it is assessed if the change constitutes a bug fix or not. In
case of a bug fix, the Product Manager directly proceeds with the evaluation as part of the bug fixes
documentation list (link here).

If the change does not constitute a bug fix but rather a regular change request, it is evaluated whether the
change:

1. Is a significant change (refer to e.g. MDCG 2020-03 for guidance)
2. Introduces any new risks and whether those are acceptable
3. Impacts any existing risk control measures
4. Is technically feasible
5. Makes sense for the product strategy of the company

The evaluation is documented as part of the Change Evaluation List and results in a decision on whether the change is implemented and whether the Notified Body needs to be involved if the change is significant. These two decisions are documented in the change request ticket.

If required, a Notified Body shall be informed before the implementation of changes.
Multiple proposed changes can be batched and discussed in one session.

If the change request relates to the change of parts of the QMS, the change is assessed with the second part of the change evaluation list for "organizational changes".

| Participants                 |
|------------------------------|
| Product Manager              |
| Head of Software Development |
| Regulatory Affairs Manager   |

| Input          | Output                      |
|----------------|-----------------------------|
| Change request | Completed change evaluation |

### 3. Implementation, Verification, Validation, Update of Documentation

Change requests result as input to the SOP Software Development and are implemented accordingly.

This includes verification, validation and release activities while ensuring traceability. The relevant
documentation is updated and released with an updated declaration of conformity.

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
