# Software Requirements List

> This document is related to your product. You somehow need to associate it with it. The easiest way would be
> to just put all product-related documents into a folder in your QMS so that the association is
> clear. Alternatively, you could mention the related product and version here, but then you'd have to update
> the version here any time you do a new release. Painful!

> This is a list of your software requirements. If you have multiple software systems (you probably have a
> backend and a frontend), you can use the "Software System" column. The categories are the 62304 categories
> from section 5.2.2. *Risk Control Measure?* is just a yes/no field. And the related risk IDs refer to the
> risk IDs from your risk table.

> Of course, you could also use your own tool like Jira or GitHub issues. Just ensure that the content (i.e.,
> the columns shown here) is roughly the same.

## Mapping of Standard Requirements to Document Sections

| Classes | IEC 62304:2006 Section | Document Section |
|---------|------------------------|------------------|
| A, B, C | 5.2.1, 5.2.2, 5.2.3    | 1                |

| ISO 13485:2016 Section | Document Section |
|------------------------|------------------|
| 7.2.1                  | (All)            |
| 7.3.3                  | (All)            |

| IEC 62366-1:2015 Section | Title                                                                              | Document Section |
|--------------------------|------------------------------------------------------------------------------------|------------------|
| 5.2                      | Identify User Interface characteristics related to Safety and potential Use Errors | 1                |
| 5.6                      | Establish User Interface Specification                                             | 1                |

## 1. Software Requirements

> While the 62034 "only" requires you to document Software Requirements, the 13485 also wants you to document
> higher-level customer requirements. You could solve that by having a two-stage hierarchy of requirements: On
> the first level, you'd have user stories (= the 13485 customer requirements), and beneath that, for each
> user story, you'd have more technical specifications (= 62304 software requirements).

> There's no great way to display this in a table, so for now, this table only solves the problem of defining
> software requirements. Feel free to create a second table for user stories, or just cram them into this one
> (good luck).

| ID | Software System | Category       | Description                        | Risk Control Measure? | Related Risk IDs |
|----|-----------------|----------------|------------------------------------|-----------------------|------------------|
| 1  | App             | Functional     | On first launch, show introduction | No                    |                  |
| 2  | App             | User Interface | Use user locale (language)         | No                    | 1 (Risk ID)      |
| 3  | App             | Functional     | Average CPU usage < 2%             | No                    |                  |
| 4  | Backend         | Security       | Store passwords as hashes          | Yes                   |                  |
| 5  | Backend         | Interface      | Expose a REST API, handle JSON     | No                    |                  |

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
