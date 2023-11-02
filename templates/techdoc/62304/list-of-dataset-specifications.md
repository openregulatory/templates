# List of Dataset Specifications

In this document we define what kind of data we obtain from partners (“acquisition”) and what we then use for annotation (“annotation data”).
Acquisition requirements are less specific because we might use such data for future developments which are not specified yet.

**Relevant other documentation:**

* SOP Machine Learning Model Development
* Intended Use
* Annotation Manual
* Algorithm Validation Report

## Acquisition

### Use Context

|                    |                                                                                 |
| ------------------ | ------------------------------------------------------------------------------- |
| Use context:       | \<e.g. AI-based decision support in radiology>                                  |
| Pathology:         | \<e.g. prostate cancer>                                                         |
| Target numbers:    | For example: XXX regular cases, XXX biopsy-proven cases                         |
| Other information: | \<For example: biopsy-proven cases are preferred image data>                    |
| (...)              | (...)                                                                           |

### Medical Specifications

|                              |                                                                            |
| ---------------------------- | -------------------------------------------------------------------------- |
| Patient population:          | \<For example: European male>                                              |
| Contents of medical reports: | For example: incl. PIRADS score and if available, incl. biopsy information |

### Technical Specifications

|               |                                                                 |
| ------------- | --------------------------------------------------------------- |
| Manufacturer: | \<Enter hardware manufacturer, e.g. Siemens>                    |
| Exclusions:   | For example: images other than MRI, no medical reports included |
| (...)         | (...)                                                           |

## Annotation Data

|                     |                                                                                                       |
| ------------------- | ----------------------------------------------------------------------------------------------------- |
| Inclusion criteria: | For example: male patients in Europe, biopsy-proven cancer findings, (...)                            |
| Exclusion criteria: | For example: tumors caused by metastasis of other cancers, implants e.g. for radiation therapy, (...) |
