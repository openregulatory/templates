| Regulatory Requirement                                                                                                              | Document Section |
|-------------------------------------------------------------------------------------------------------------------------------------|------------------|
| MDR Annex I (General Safety and Performance Requirements), Annex IV (EU Declaration of Conformity), Art. 27, 29, 31 (UDI / Eudamed) | All              |
| MPDG §8, §96, §97                                                                                                                   | All              |
| ISO 13485:2015, Sections 4.2.3                                                                                                      | All              |

## Summary

This SOP describes how a medical device is brought to the market while observing applicable regulatory
requirements, including the compilation of a Technical Documentation and issuing a EU Declaration of
Conformity for the medical device.

|                                |                                                          |
|--------------------------------|----------------------------------------------------------|
| **Process Owner**              | *\<enter role of process owner\>*                        |
| **Key Performance Indicators** | *\<enter KPIs to be tracked for the Management Review\>* |

## Process Steps

### 1. Decision on New or Revised Medical Device

This process is initiated once the Management decides to place a new or updated medical device on the
market. Business input could be:

* Conversations with prospective customers
* Market opportunities
* Internal ideas

If applicable, a responsible Product Manager for a new device is appointed. Together with the QMO, they
determine the classification of a new device as part of the MDR Classification document.

|              |                                         |
|--------------|-----------------------------------------|
| Participants | Management, Product Manager, QMO        |
| Input        | Management decision on new device       |
| Output       | Completed medical device classification |

### 2. Application for Conformity Assessment by Notified Body

If necessary based on the medical device classification, a Notified Body is involved for the conformity
assessment for the new device.

> NOTE: a Notified Body must be involved in the conformity assessment of all medical devices except for class I.

|              |                               |
|--------------|-------------------------------|
| Participants | Product Manager               |
| Input        | Medical device classification |
| Output       | Contract with Notified Body   |

### 3. Compilation of Technical Documentation and Declaration of Conformity

The technical documentation for the medical device is compiled by following respective processes for
development (e.g. software development, risk management, usability testing). The Product Manager is
responsible to coordinate this process step with all relevant members of the organization. Documentation for
different versions of the device is kept separate.

The Product Manager maintains a Medical Devices List according to MDR Annex II Sec 1.2 that provides an
overview of:

* Installed product versions per customer site (if applicable)
* Previous device versions, incl. release and decommissioning date
* Similar devices

Prior to submission to the Notified Body for conformity assessment (if applicable), the QMO checks the
documentation for completeness according to the stipulations listed below. Compliance with EU legislation is
documented in the MDR General Safety and Performance Requirements Checklist.

* MDR General Safety and Performance Requirements (Annex I)
* MDR EU Declaration of Conformity (Annex IV)

After successful approval by the Notified Body, the Management signs the declaration of conformity. A product
(version) is considered released and placed on the market with the release of its declaration of conformity.

|              |                                                                                                                          |
|--------------|--------------------------------------------------------------------------------------------------------------------------|
| Participants | Product Manager, QMO                                                                                                     |
| Input        | Technical documentation                                                                                                  |
| Output       | Approval by Notified Body<br>Signed EU Declaration of Conformity<br>Updated List of Medical Devices and Product Versions |

### 4. Registration of Medical Device (UDI)

Country-specific requirements for registration are observed before making a new medical device (version)
available in a market. For the European market, the Product Manager follows the requirements set out in
Art. 29 and Annex VI MDR by registering the device’s Unique Device Identifier (UDI) in the European Database
for Medical Devices (Eudamed).

For the implementation of product changes, the Product Manager applies for a new UDI-DI if the changes entail
one of the following:

* A significant change based on the Change Evaluation List
* Changed intended use
* New product features
* Changes in product interoperability, new interface or connected systems
* Non-trivial change to the user interface
* New supported operating system
* New programming language
* New algorithm model
* Non-trivial change to the software or database architecture

The Product Manager assigns a new UDI-PI for modifications such as:

* Bug fixes
* Security patches
* User interfaces (limited to usability and excluding security improvements)

The UDI-PI is determined by the manufacturer. Typically, the device version number serves as the UDI-PI (see
SOP Software Development).

> NOTE:
>
> * The **Basic UDI-DI** (or: BUDI-DI) is assigned by UDI providers and identifies a **group of medical
>   devices with the same purpose, risk class, comparable design and manufacturing features.**
> * The **UDI-DI** is assigned by UDI providers **for each medical device product type** and is revised for
>   any major modifications (substantial updates) to the device.
> * The **UDI-PI** you can assign yourself as a manufacturer **for every single product** and is revised for
>   minor modifications (non-substantial updates).

> **Example:**
>
> * Basic UDI-DI: Wrist-band health tracking device
> * UDI-DI: different code based on color and packaging (white/blue/red; single-/double-pack)
> * UDI-PI: different code based on series/batch/version, expiration date, etc.
>
> NOTE: As of early 2021, the European Commission has designated four entities to issue UDI codes: GS1, HIBCC,
> ICCBBA and IFA. As long as Eudamed is not set up for registration, national registration requirements
> apply. For Germany, consider §96 and §97 of the MPDG. At OpenReg, we recommend obtaining a UDI already to be
> prepared for the regulatory transition.
>
> NOTE: As part of the registration process, authorities in non-EU countries may require the documentation to
> be provided in other languages. Consider norms and regulations for the translation of medical device
> documentation.

|              |                                                  |
|--------------|--------------------------------------------------|
| Participants | Product Manager                                  |
| Input        | Released Declaration of Conformity               |
| Output       | Updated or new UDI Completed device registration |

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
