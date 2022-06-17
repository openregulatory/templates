# SOP Document and Record Control

| ISO 13485:2016 Section | Document Section |
|------------------------|------------------|
| 4.2.4                  | (All)            |
| 4.2.5                  | (All)            |

## Summary

This SOP describes how documents and records are handled. The goal is to understand how documents are
typically structured and in what states they can be as they move from draft to release. It's similarly
important to always have the most recent document available at the specified location while ensuring that
changes to documents can be traced.

## General Considerations

> This whole template assumes that you're using Google Drive and Google Docs for your QMS. If you're using
> something else, then.. good luck. Just kidding. You need to customize it, of course. There's specialized QMS
> software out there which makes some of these tasks easier and lots of other tasks harder :)
> Make sure to describe somewhere (ideally in this first paragraph), in which tool your QMS documents will be managed and stored.

**Documents** are expected to change over time, whereas **records** are created once and not altered
significantly afterwards.

All documents are written in English.

### Document and Record Labeling

Documents are named according to this schema:

`ASSOCIATED PROCESS-TYPE-NAME`

Where "associated process" can be abbreviated in capital letters and "type" refers to an abbreviation of the
document type (see below).  "Name" refers to the actual file name. An example would be:

`SWD-SOP-Integrated Software Development`

For released documents, we add a "-a" suffix (as in: approved) to the document name. An example would be:

`SWD-SOP-Integrated Software Development-a`

For archived documents, we add a "-archived_ARCHIVE DATE" suffix to the document name. An example would be:

`SWD-SOP-Integrated Software Development-archived_2021-03-01`

Product records are ideally labeled with a device number and device version; for instance:

`PR1-V1.2-ESW-SWDP-Software Development Plan`

### Document Type Abbreviations

> There probably will be more types in the future when I add more templates. For now, this covers all types of
> the templates on openregulatory.com.

| Abbreviation | Description                                        |
|--------------|----------------------------------------------------|
| AM           | Attachment                                         |
| LIS          | List                                               |
| SD           | Supporting Documentation                           |
| SOP          | Standard Operating Procedure (Process Description) |
| TPL          | Template                                           |


### Retention Periods

QMS documents and records shall be stored for at least 10 years after their archival date.

Technical Documentation shall be stored for at least 10 years after the lifecycle of the respective device has
ended.

### Review Periods

We review our QMS documents typically once per year to ensure they remain up to date.

Our core and safety processes as defined in the quality management manual must be reviewed at minimum once per
year.

All other processes and associated documents can be reviewed every three years once they have been reviewed
before without any findings.

In case of audit findings or related corrective action, it is up to the discretion of the QMO to apply shorter
review periods (e.g. 6 months).

### QMS Document List

We keep an overview list of all QMS documents, including document type, release date, next review date and
respective process owners.

## Process Steps

### Handling of Documents

#### 1. Creation of Documents

> This assumes you have three folders in your GDrive: "drafts", "under review" and "released".

All documents are saved in the Quality Management System (QMS) which is a folder in Google Drive.

New documents can be created by anyone in the company in the "drafts" folder. Naming of documents follows the
general considerations of this SOP (see above). Standard Operating Procedures (SOP) should specify a process
owner responsible for typically updating, reviewing and releasing all associated documents.

| Participants |
|--------------|
| Any employee |

| Input   | Output               |
|---------|----------------------|
| Content | New Document (draft) |

#### 2. Documents Ready for Review

Once a document is ready for review, its author moves it to the "under review" folder. Importantly, the author
selects appropriate reviewers and approvers and notes them at the bottom of the document.

| Participants |
|--------------|
| Any employee |

| Input            | Output                  |
|------------------|-------------------------|
| Document (draft) | Document (under review) |

#### 3. Review of Documents

The respective reviewer(s) and approver(s) review the document. If changes are required, they create comments
in the Google Doc and/or suggest changes. If the review is successful, they sign their initials at the bottom
of the document.

| Participants                                                |
|-------------------------------------------------------------|
| Process owner and/or designated reviewer(s) and approver(s) |

| Input                   | Output                       |
|-------------------------|------------------------------|
| Document (under review) | Document (review successful) |

#### 4. Release of Documents

The Process Owner moves the document to the "released" folder and assigns "-a" to the document name as
outlined by the general considerations for document naming.

Access to the "released" folder is restricted to prevent unauthorized changes to released documentation.

The QMO (and, if applicable, the process owner) decide if employee training is required. In general,
training for minor changes/corrections is not necessary.

| Participants                |
|-----------------------------|
| QMO, Process Owner          |

| Input                        | Output              |
|------------------------------|---------------------|
| Document (review successful) | Document (released) |

#### 5. Changes to Documents

If changes need to be made to a document, any employee with knowledge about the document and those changes can
perform them. For that, the currently-released document is copied to the "drafts" folder and edited by the
employee. After finishing the edit, it moves to the **Document Ready for Review** stage (step 2), following
the same steps as above.

A QMS change can trigger a substantial change. Before release, it shall be checked whether it may impact the
organization's process landscape and hence, overall organizational conformity with regulatory
requirements. The QMO is responsible to evaluate such potentially major changes as part of the Change
Evaluation List (reference change management process).


| Participants      |
|-------------------|
| QMO, any employee |

| Input               | Output                |
|---------------------|-----------------------|
| Document (released) | Document Copy (draft) |

#### 6. Archiving of Documents

Documents get archived if they become obsolete or a newer released version becomes available. For that, the
Process Owner removes the "-a" suffix, moves the document to the "archive" folder and assigns a respective
archiving date following the general considerations for document naming in this SOP. We observe retention
periods as outlined in this SOP and delete documents as soon as the retention period expired.

| Participants           |
|------------------------|
| Process Owner          |

| Input               | Output              |
|---------------------|---------------------|
| Document (released) | Document (archived) |

### Handling of Records

#### 1. Creation of Records

We create records as required by our processes. If available, we use templates and checklists for the creation
of records.  Naming conventions as outlined for documents do not apply. Records should include an author's name
and the date of creation.

| Participants |
|--------------|
| Any employee |

| Input                                      | Output     |
|--------------------------------------------|------------|
| Content, Template Document (if applicable) | New Record |

#### 2. Review and Release of Records

Unless specified differently in a template or SOP, records do not typically require a review and release
process.

| Participants                           |
|----------------------------------------|
| Designated reviewer(s) and approver(s) |

| Input                 | Output                     |
|-----------------------|----------------------------|
| Record (under review) | Record (review successful) |

#### 3. Storage of Records

Records are not necessarily stored in our QMS folder. They also may reside in other applications as specified
per respective processes. This is where records are typically stored:

> Add all your tools which stores data which is mentioned in your QMS.

 * *GitHub (Issues, Pull Requests)*
 * *ZenDesk (Customer Support Tickets)*


#### 4. Changes to Records

Records are not significantly altered after creation / release. Where significant changes are required, we
rather create a new record and archive the old one. Non-substantial changes (e.g. spelling mistakes) are
considered corrections only, assessed and added on a case-by-case basis.

| Participants |
|--------------|
| Any employee |

| Input             | Output           |
|-------------------|------------------|
| Record (released) | Record (updated) |

#### 5. Archiving of Records

Records are archived if they become obsolete or a new released version becomes available. For that, the
process owner moves the records to a respective archiving location. If possible, we follow the general
considerations for document names and add the archiving date to the record name. We observe retention periods
as outlined in this SOP and delete records as soon as the retention period expired.

| Participants           |
|------------------------|
| Process Owner          |

| Input             | Output            |
|-------------------|-------------------|
| Record (released) | Record (archived) |
