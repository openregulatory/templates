# Instructions on Data Acquisition

The Instructions on Data Acquisition define what kind of data is collected and annotated (prepared) for
machine learning model development. The requirements for general data acquisition can be defined less
specific than the subset of data used for annotations as any additional data can be used for future
developments that are not specified yet.

**Relevant other documentation:**

* SOP Machine Learning Model Development
* Intended Use
* Instructions on data annotation
* Algorithm Validation Report

## Acquisition

### Use Context

|                    |                                                                                 |
|--------------------|---------------------------------------------------------------------------------|
| Use context:       | \<e.g. AI-based decision support in radiology\>                                 |
| Pathology:         | \<e.g. prostate cancer\>                                                        |
| Target numbers:    | For example: XXX tumor cases with biopsies, XXX benign cases, XXX healthy cases |
| Other information: | \<For example: Prefer images from certain manufacturers\>                       |
| (...)              | (...)                                                                           |

### Medical Specifications

|                              |                                                          |
|------------------------------|----------------------------------------------------------|
| Patient population:          | \<For example: European male\>                           |
| Contents of medical reports: | \<Applicable clinical scores, biopsy information, etc.\> |

### Technical Specifications

|               |                                                                 |
|---------------|-----------------------------------------------------------------|
| Manufacturer: | \<Enter hardware manufacturer, e.g. Siemens\>                   |
| Exclusions:   | For example: images other than MRI, no medical reports included |
| (...)         | (...)                                                           |

## Annotation Data

|                     |                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------|
| Inclusion criteria: | For example: male patients in Europe with certain diagnoses, (...)                                    |
| Exclusion criteria: | For example: tumors caused by metastasis of other cancers, implants e.g. for radiation therapy, (...) |

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
