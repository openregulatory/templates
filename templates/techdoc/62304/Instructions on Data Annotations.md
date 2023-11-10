# Instructions on Data Annotations

**Intended Purpose:**

The Instructions on Data Annotations specify the way in which datasets shall be annotated by medical experts to
apply labelling required for the training of the machine learning model. It provides a standard annotation
style, including the accuracy and form of annotations. Annotation requirements shall be specific enough to
enable any given third party to evaluate the quality of annotations. The guidelines shall als provide a
reasoning for the selection of labels and the methodology used to derive the ground truth for model
development.

**Relevant other documentation:**

* SOP Machine Learning Model Development
* Intended Use
* Instructions on Data Acquisitions

> Note: This is an example of content that could be considered for a specific use case. All content has to be
> replaced and customized to your specific product use case. You could also consider documenting this in
> format of a slides presentation in order to easily include helpful images.

### General Information

Annotation experts shall draw segmentations around the following findings:

* Tumors
* Other suspicious findings
* (...)

Annotation experts must make sure to segment all visible findings as missing a possible findings will lead to
an algorithmic classification as unsuspicious and decreased model performance.

Annotation experts shall NOT segment the following findings:

* Benign finding XYZ
* (...)

### Tumors

Annotation instructions:

* Ensure that the segmentation captures the entire tumor
* (...)

Document the following information:

* Tumor classification
* Biopsy information
* Confidence level
* (...)

### Other Suspicious Findings

Annotation instructions:

* Ensure that the segmentation captures the entire finding
* (...)

Document the following information:

* Type of suspicious finding
* Biopsy information
* Confidence level
* (...)
