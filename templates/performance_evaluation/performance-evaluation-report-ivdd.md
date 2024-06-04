# Performance Evaluation Report (IVDD)

The Performance Evaluation Report contains the methods and results regarding scientific validity, analytical
performance and clinical performance.

> There's a separate standard available for that: EN 13612:2002. It's very short and doesn't contain a whole
> lot of information. Additionally, there are three IMDRF guidance documents:
>
> * [GHTF/SG5/N6:2012][imdrf-1]
> * [GHTF/SG5/N7:2012][imdrf-2]
> * [GHTF/SG5/N8:2012][imdrf-3]

## Product

 * Name: *\<product name\>*
 * Version: *\<product version\>*
 * Basic UDI-DI: *\<insert UDI-DI, if/when available\>*

## Mapping of Requirements to Document Sections

| EN 13612:2002 Section                                    | Document                                 | Section |
|----------------------------------------------------------|------------------------------------------|---------|
| 3.1 Responsibilities and Resources                       | Performance Evaluation Plan              |         |
| 3.2 Documentation                                        | Performance Evaluation Plan              |         |
| 3.3 Final Assessment and Review                          | Performance Evaluation Report (this one) | 10      |
| 4.1 Preconditions                                        | Performance Evaluation Report (this one) | 7, 8, 9 |
| 4.2 Evaluation Plan                                      | Performance Evaluation Plan              |         |
| 4.3 Sites and Resources                                  | Performance Evaluation Plan              |         |
| 4.4 Basic Design Information                             | Performance Evaluation Plan              |         |
| 4.5 Experimental Design                                  | Performance Evaluation Plan              |         |
| 4.6 Performance Study Records                            | Performance Evaluation Plan              |         |
| 4.7 Observations and Unexpected Outcomes                 | Performance Evaluation Plan              |         |
| 4.8 Evaluation Report                                    | Performance Evaluation Report (this one) | (all)   |
| 5. Modifications During the Performance Evaluation Study | Performance Evaluation Plan              |         |
| 6. Re-evaluation                                         | Performance Evaluation Plan              |         |
| 7. Protection and Safety of Probands                     | Performance Evaluation Plan              |         |

## 1. List of Abbreviations

| Abbreviation | Explanation                        |
|--------------|------------------------------------|
| IVD MD       | In-vitro diagnostic medical device |

## 2. Product

 * Name: *\<product name\>*
 * Version: *\<product version\>*
 * Basic UDI-DI: *\<insert UDI-DI, if/when available\>*
 * UMDNS-Code:
 * GMDN-Code:

## 3. Relevant Documents

 * SOP Performance Evaluation
 * Performance Evaluation Plan

## 4. Intended Use

> Copy-paste the intended use of your device here.

## 5. Risk Analysis

> Copy-paste the summary of your Risk Analysis Report here.

## 6. Medical Context and State of the Art

### 6.1 Medical Context

> Summarize in which medical context your IVD is used. If it's an HIV test, it may be used for screening, or
> maybe only for people who think they've recently gotten infected with HIV.

### 6.2 State of the Art

> Describe how this is currently done. Continuing the example above: What happens currently to those patients
> who are screened for HIV, or those who think they've gotten infected? Are there any specific tests out there
> or is the state-of-the-art procedure another one, like (random example) doing a chest x-ray?

## 7. Scientific Validity

> This is generally based on literature research. Whatever your IVD is measuring, the current scientific
> knowledge has some sort of (valid) reason for this, because it is associated with some sort of condition. Can
> you still follow?
>
> Here's an example: You've developed an HIV test. Based on current scientific knowledge, it makes sense to do
> HIV tests on people because it's established that HIV is a non-benign disease which will lead to AIDS some
> time in the future. Early detection is useful because early treatment leads to favourable
> outcomes. Therefore, it's scientifically valid to do HIV tests.

### 7.1 Scientific Validity: Literature Search Methods

> Describe your methods for your literature research for scientific validity. You'll probably have a list of
> keywords which you'll be entering in certain databases (or other literature sources).
>
> Some example literature sources from guidance document GHTF/SG5/N7:2012:
>
> * Scientific databases – bibliographic (e.g., MEDLINE, EMBASE);
> * Specialized databases (e.g., MEDION);
> * Systematic review databases (e.g., Cochrane Collaboration);
> * Clinical trial registers (e.g., CENTRAL, NIH);
> * Adverse event report databases (e.g., MAUDE, IRIS);
> * Scientific databases – bibliographic (e.g., MEDLINE, EMBASE);
> * Specialized databases (e.g., MEDION);
> * Systematic review databases (e.g., Cochrane Collaboration);
> * Clinical trial registers (e.g., CENTRAL, NIH);
> * Adverse event report databases (e.g., MAUDE, IRIS);
> * Reference texts

### 7.2 Scientific Validity: Literature Search Results

> Describe your search results from your literature research

| Database | Search term | # Hits | # Evaluated Abstracts | # Potential Relevant Publications |
|----------|-------------|--------|-----------------------|-----------------------------------|
|          |             |        |                       |                                   |

| Database | Title | Author | Year | Summary | Relevant? Why? |
|----------|-------|--------|------|---------|----------------|
|          |       |        |      |         |                |

### 7.3 Scientific Validity: Literature Search Conclusion

> This is a bit like the "discussion" section in a scientific paper. You reach some sort of conclusion, based
> on your literature search. In the HIV test example, this would be something like "testing for HIV is useful
> because HIV is the disease which subsequently leads to AIDS, and early detection of that is good".

## 8. Analytical Performance

> Pretty simple. Describe the metrics by which your IVD detects whatever it should detect.
>
> In the HIV test example, those could be sensitivity / specificity values, in other words: If I use this test
> on 100 blood samples from different patients, what sort of analytical performance can I expect?
>
> This will require you to run your test on some sort of test set and do some analysis of those results.

### 8.1 Analytical Performance: Methods

> Describe your methods. If you have a Machine Learning model, you could describe your test set and why you
> chose that specific dataset as a test set. You could also describe the metrics by which you evaluate the
> performance of your ML model.

### 8.2 Analytical Performance: Results

> Describe your results. Again, similar to a peer-reviewed paper.

## 9. Clinical Performance

> Slightly harder to comprehend and a bit similar to Scientific Validity. These are the performance metrics of
> your product in its intended patient population.
>
> So, for the HIV test: You'll have some numbers for the analytical performance, but that's only on the
> "reagent" level. What are the metrics when you actually use that test on real people? There's probably a
> different sensitivity / specificity. Maybe certain comorbidities (like other viral diseases) may lead to
> false-positive test results. So, this is like analytical performance, but in the real world, on real
> patients.
>
> You can also do a literature research for this, or do a clinical performance study.

### 9.1 Clinical Performance: Methods

> Describe the methods of your clinical performance evaluation.

### 9.2 Clinical Performance: Results

> Describe your results.

## 10. Conclusion

> Conclude why your IVD is safe and effective to use. It makes sense to refer to your intended use, the risks
> in your risk analysis, and the scientific validity, analytical performance and clinical performance.

## 11. Dates and Signatures

> Date and sign the plan. If your document management system supports it, you can digitally sign by typing
> e.g., your initials in the "Signature" field. Otherwise, you can still sign it the old-school way (print it
> and sign the sheet of paper, ugh).

| Activity | Name | Signature |
|-----------|------|-----------|
| Creation  |      |           |
| Review    |      |           |
| Approval  |      |           |

## 12. Qualification of the Responsible Evaluators

> Attach CVs of the people who were involved in writing the Performance Evaluation. They must be "adequately
> skilled and trained".


<!-- Links -->

[imdrf-1]: http://www.imdrf.org/docs/ghtf/final/sg5/technical-docs/ghtf-sg5-n6-2012-clinical-evidence-ivd-medical-devices-121102.pdf
[imdrf-2]: http://www.imdrf.org/docs/ghtf/final/sg5/technical-docs/ghtf-sg5-n7-2012-scientific-validity-determination-evaluation-121102.pdf
[imdrf-3]: http://www.imdrf.org/docs/ghtf/final/sg5/technical-docs/ghtf-sg5-n8-2012-clinical-performance-studies-ivd-medical-devices-121102.pdf

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
