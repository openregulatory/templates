# 1. General Information

This SOP describes how we carry out the development, training and update of machine learning (ML) models for
the purpose of integration in our medical devices. By following this process, we aim to ensure that the ML
models are implemented and updated in the intended way.

|                                   |     |
|-----------------------------------|-----|
| Process Owner:                    | CTO |
| Key Performance Indicators (KPI): |     |

**Regulatory references:**

ISO 13485:2016 Chapter 7.5

**Relevant other documentation:**

* SOP Integrated Software Development
* Intended use
* Instructions on data acquisition
* Instructions on data annotation
* List of software requirements
* List of applicable regulations
* List of medical devices
* Algorithm Validation Report

## 1.1. Development and Integration Requirements

When defining the ML model requirements, it is essential to take into account overall medical device
requirements:

* **General Medical Device Information**\
  For example: intended use and initial device description
* **List of Software Requirements**\
  Defines key functionalities for the ML model, e.g. minimum latency and response time, accuracy etc.
* **Software Development and Maintenance Plan**\
  Defines hardware limitations and standards for interoperability to consider.
* **List of Applicable Regulations**\
  May define data privacy, IT security and compliance requirements to adhere to.

## 1.2. Project Management Tool

\<Project Management Tool\> is used to keep track of the integration process and version control for ML
projects.  It is also used to maintain detailed documentation of the ML model architecture,
e.g. hyperparameters and evaluation metrics.

# 2. Process Overview

## 2.1. Configuration of Development Environment

The development environment is where the ML model creation, refinement and validation testing takes place. It
must be separated from the production environment. The clear separation between development and production
server allows for a controlled deployment process which includes the evaluation, testing, refinement and
release of reliable and robust models.

Additionally, the development server is set up. It serves as a sandbox for developers and data scientists when
experimenting with changes like new ML features, which are first deployed on the development server for
validation testing.

|              |                                                       |
|--------------|-------------------------------------------------------|
| Participants | ML developer                                          |
| Input        | ML development infrastructure<br/>(e.g. cloud server) |
| Output       | Configured development environment                    |

## 2.2. Define Instructions on Data Acquisition and Annotation

Based on the initial device description defined as part of the SOP Integrated Software Development, the
Medical team collects and documents required medical background information.

**Instructions Data Acquisition**

The Operations team and the Machine Learning Team then define the Instructions on Data Acquisition required to
obtain relevant data for ML model training and development. At minimum, these include:

* Data type (e.g. patient population, medical modality, data format etc.)
* Data volume incl. appropriate backup
* Data sources (e.g. outpatient clinics, hospital information systems, etc.)

The Instructions on Data Acquisition provide specifications of dataset composition, dataset size and other
technical requirements, including reasoning for why these specifications are deemed appropriate for model
development. The Instructions on Data Acquisition shall be specific enough both to enable employees to acquire
the correct data and to serve as evidence if the correct data has been acquired. They must be approved by the CTO.

**Instructions on Data Annotation**

The Medical team and the Machine Learning team compile Instructions on Data Annotation. The instructions shall
specify the way in which datasets must be annotated by medical experts to apply labelling required for the
training of the ML model. It shall provide a standard annotation style, incl. the accuracy and form of annotation.
Annotation requirements shall be specific enough both to serve as instructions and as evidence to evaluate the
quality of annotation. They shall also provide a reasoning for the selection of labels and the methodology used
to derive the ground truth for later model development. The Instructions on Data Annotation must be approved at
minimum by the CTO, QMO and a medical expert.

Both the Instructions on Data Acquisition and Annotation shall be continuously monitored for
adequacy and completeness and updated when necessary.

|              |                                                                        |
|--------------|------------------------------------------------------------------------|
| Participants | Operations team<br/>Medical team<br/>ML team                           |
| Input        | Device description                                                     |
| Output       | Instructions on Data Acquisition<br/>Instructions on Data Annotation |

## 2.3. Collection and Annotation of Data

The Operations team is responsible to obtain the required data according to the Instructions on Data Acquisition
from relevant partner organizations.

The Operations team is also responsible to ensure that all partners are informed about legal and data privacy
considerations.

Data exports must receive prior approval by the data protection officer of both the donating and receiving
organization.

In case the exported data has been annotated already, the annotation are reviewed against the annotation
requirements described in the Instructions on Data Annotation. Data with unqualified annotation is discarded.
If the exported data consists of raw data, the Operations team is responsible to hire medical experts which
provide the necessary data annotation according to the requirements of the Instructions on Data Annotation.
Annotation workforce must be contracted following the organization's purchasing process.

|              |                                                                                                        |
|--------------|--------------------------------------------------------------------------------------------------------|
| Participants | Operations team                                                                                        |
| Input        | Instructions on Data Acquisition<br/>Instructions on Data Annotation<br/>If applicable: SOP Purchasing |
| Output       | Acquisition of annotated data                                                                          |

## 2.4. Data Pre-Processing

Once data acquisition is completed, the Machine Learning team is responsible to apply necessary preprocessing
steps such as data cleaning, normalization and/or feature extraction to achieve a refined dataset according to
the Instructions on Data Acquisition. Detailed steps may include:

* Exploratory data analysis (EDA) to gain insight into data distribution, missing values, outliers and other
  potential dataset deficiencies.
* Missing data is addressed through imputation or removal, taking into account the impact on both patient
  privacy and data integrity.
* Outliers and anomalies are addressed using appropriate statistical methods and domain-specific knowledge.
* Data can be normalized or scaled to ensure consistent domains and to minimize the impact of different
  feature scales.

The final dataset is divided into training, validation and test datasets that are stored in separate
locations. Split ratio and the location of the datasets are documented in \<project management tool\> for the
purpose of possible replication.

|              |                                        |
|--------------|----------------------------------------|
| Participants | Machine Learning team                  |
| Input        | Annotated data                         |
| Output       | Complete dataset for model development |

## 2.5. ML Model Development

The ML team choses appropriate ML algorithms and techniques based on the general development and integration
requirements described above.

Factors such as interpretability, robustness and performance must be considered in this step.

The model is trained using the training dataset. The model is evaluated using the validation dataset, taking
into account relevant metrics such as accuracy, precision, recall or F1 score. The model development is
iterated by adjusting algorithms, features or hyperparameters based on evaluation results to optimize model
performance.

Final testing of model performance is performed on an independent training dataset or through cross-validation
techniques. Pass and fail criteria are defined prior to the testing. Additional evaluations, such as
cross-validation or external validation, may be conducted to ensure generalizability and robustness of the
models.

The best-performing ML model is selected based on the evaluation metrics, considering factors such as
accuracy, interpretability and clinical relevance. The Machine Learning team then compiles the Algorithm
Validation Report, which includes at minimum:

* Description of development resources (e.g. developer team qualification, infrastructure, SOUP and frameworks
  used)
* Description of dataset (acquisition, annotation, pre-processing)
* Description of the final ML model, incl. architecture, hyperparameters, evaluation metrics as well as
  limitations.

|              |                                     |
|--------------|-------------------------------------|
| Participants | Machine Learning team               |
| Input        | Final dataset for model development |
| Output       | Algorithm Validation Report         |

## 2.6. Production Deployment of ML Model

The final ML model is prepared for deployment and integration in the medical device, taking into account
memory, processing power and real-time requirements to ensure compatibility.

The ML team sets up the production environment. The production environment hosts the final ML models which are
released for processing real-time data as part of the medical device. SOP Deployment is following for detailed
instructions.

|              |                                                       |
|--------------|-------------------------------------------------------|
| Participants | ML developer                                          |
| Input        | ML development infrastructure<br/>(e.g. cloud server) |
| Output       | Configured production environment                     |

## 2.7. Handling of Updates

The need for ML model udpates is initiated through the SOP Change Management and SOP Integrated Software
Development.

New data is continuously collected and analyzed to improve the model's adequacy in comparison with the state
of technology.

ML model performance is continuously updated and evaluated by repeating the steps described above.

|              |                               |
|--------------|-------------------------------|
| Participants | Machine Learning team         |
| Input        | Updated ML model requirements |
| Output       | Updated ML model              |

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
