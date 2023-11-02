# Annotation Manual

**Intended Purpose:**
The annotation manual specifies the way in which datasets shall be annotated by medical experts to apply labelling required for the training of the machine learning model. It provides a standard annotation style, including the accuracy and form of annotations. Annotation requirements shall be specific enough to enable any given third party to evaluate the quality of annotations. The manual shall also provide a reasoning for the selection of labels and the methodology used to derive the ground truth for model development.

**Relevant other documentation:**

* SOP Machine Learning Model Development
* Intended Use
* List of Dataset Specifications

> Note: This is an example of content that could be considered for a specific use case. All content has to be replaced and customized to your specific product use case. You could also consider documenting this in format of a slides presentation in order to easily include helpful images.

### General Information

Annotation experts shall draw polygons around the following findings:

* Masses
* Asymmetries
* (...)
* Other findings

Annotation experts must make sure to draw polygons around all visible findings as missing a possible findings will lead to an algorithmic classification as unsuspicious tissue and decreased model performance.

Annotation experts shall NOT draw polygons around the following findings:

* Benign tissue XYZ
* (...)

### Masses

Annotation instructions:

* Ensure that the polygon captures the entire mass
* Annotate both benign and maligne masses
* (...)

Document the following information:

* Classification on medical score XYZ
* Density of the mass according to medical score XYZ
* Biopsy information
* Annotator confidence level
* (...)

### Asymmetries

Annotation instructions:

* Ensure annotation in comparative view
* (...)

Document the following information:

* Classification on medical score XYZ
* Biopsy information
* Annotator confidence level
* (...)

### Other Information

Annotation instructions:

* Ensure to also annotate any other finding to the best of your knowledge (e.g. skin lesion, thickening, etc.)

Document the following information:

* Type of finding
* Biopsy information
* Annotator confidence level
* (...)
