# SOP Software Problem Resolution

| Classes | IEC 62304:2006 Section | Document Section |
|---------|------------------------|------------------|
| B, C    | 5.6.8                  | (All)            |
| A, B, C | 6.2.1.3                | 1                |
| A, B, C | 6.2.2                  | (All)            |
| A, B, C | 9.1                    | 1                |
| A, B, C | 9.2                    | 2                |
| A, B, C | 9.3                    | 3                |
| A, B, C | 9.5                    | 1                |
| A, B, C | 9.6                    | 2                |
| A, B, C | 9.7                    | 3                |

## Summary

This SOP describes how problems concerning our software product(s) are processed, evaluated and fixed.

|                                |                                                          |
|--------------------------------|----------------------------------------------------------|
| **Process Owner**              | *\<enter role of process owner\>*                        |
| **Key Performance Indicators** | *\<enter KPIs to be tracked for the Management Review\>* |

## Process Steps

### 1. New Problem Evaluation

New problems are entered as tickets into *\<your ticketing system\>*.

Reported problems can originate from customers, users or company employees. Examples include customer feedback
and bug reports.

For each problem report, the following must be entered:

 * Affected medical device and version
 * Severity classification (see below)
 * Problem description incl. instructions to reproduce

We classify the severity of problems in the following categories:

| Severity Classification | Description                                                      |
|-------------------------|------------------------------------------------------------------|
| High                    | Causes new or changed risks to patients which are unacceptable.  |
| Medium                  | May cause new or changed risks to patients which are acceptable. |
| Low                     | All other problems.                                              |

For all problems classified as "Medium" or higher the person responsible for regulatory compliance (PRRC) must
be informed who subsequently assesses it according to the SOP Vigilance.

| Participants                                 |
|----------------------------------------------|
| Head of product development                  |
| Person responsible for regulatory compliance |

| Input       | Output                                                  |
|-------------|---------------------------------------------------------|
| New problem | Problem report as *\<ticket in your ticketing system\>* |

### 2. Root Cause Analysis and Procedure

The root cause of the problem is determined (if possible) and a decision is made whether to fix it or not.

We also analyze whether similar problems have occurred in the past and any trends can be discerned. If this is
the case, it is noted in the problem report.

| Participants                 |
|------------------------------|
| Head of software development |
| Software developer           |


| Input          | Output                                          |
|----------------|-------------------------------------------------|
| Problem report | Problem report updated with cause and procedure |

### 3. Implementation and Verification

The bug fix is implemented. If the fix includes a change to an existing product, it is handled according to
SOP Change Management.

After the bug fix has been implemented, the problem report is reviewed whether it has been successfully fixed
and can be closed. Closing the problem report is equivalent to successful verification.

| Participants                                 |
|----------------------------------------------|
| Head of product development                  |
| Person responsible for regulatory compliance |

| Input              | Output                         |
|--------------------|--------------------------------|
| Problem report     | Resolved/closed problem report |
| Implemented change |                                |

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
