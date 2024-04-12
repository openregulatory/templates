# 1. General Information

This SOP describes how we support the initial integration and update of integrations of our medical devices
into the IT systems of our customers. Furthermore, it covers user management and user training. By following
this process, we want to make sure that our customers receive our medical devices or services the intended
way.

> Obvious disclaimer!
>
> The deployment process should be very much customized to the context of your specific product. Are you
> deploying your product web-based? Are you integrating with local healthcare providers' IT systems? Depending
> on those questions, you will have to write each single process step of this template. Sorry to disappoint
> you! Hope the structure helps you at least to get an idea of the regulatory requirements.

|                                |                                                          |
|--------------------------------|----------------------------------------------------------|
| **Process Owner**              | *\<enter role of process owner\>*                        |
| **Key Performance Indicators** | *\<enter KPIs to be tracked for the Management Review\>* |

**Regulatory references:**

* ISO 13485:2016 Chapter 7.5

**Relevant other documentation:**

* Integration Evaluation Checklist (IECL)
* Integration Validation Checklist (IVCL)
* Software Requirement Specifications
* List of Medical Devices (PROD)
* User Training Strategy
* Template User Training Record
* User Consent Form (if applicable)

## 1.1. Integration Specifications

Integration Specifications are the technical requirements defined in the instructions for use as part of the
technical documentation of medical devices.

## 1.2. Integration Checklists

The Integration Specifications are used to compile the Integration Evaluation Checklist. It is ensured that we
do not offer medical devices or services which cannot be delivered by filling out this checklist, for which
the Operations Team Representative is responsible. We fill out the Integration Validation Checklist after
concluding integration work in order to validate if all technical requirements for successful integration have
been completed.

## 1.3. Device Traceability

The operations team ensures that only released device versions are deployed to the customer
environment. Deployment of device versions is documented as part of the medical device list. This file must
contain at minimum:

* Use description (e.g. clinical use, test, etc.)
* Device description (e.g. device version, UDI, release date, identification number of the NB acc. to CE
  certificate)
* Company and contact data to a responsible person, deployment location

## 1.4. Project Management Tool

Optional:

\<enter name\> is used as the project management tool to coordinate integration work.

# 2. Process Overview

## 2.1. Evaluation of Integration Requirements per Customer

> Possible contents of this process step:
>
> * Following the draft of an offer / contract with a customer, the sales team reaches out to the technical
>   operations team to evaluate if technical requirements are met.
> * In coordination with competent staff on the customer’s side, the technical operations team gathers
>   relevant information to fill out the integration evaluation checklist.
> * If evaluation output does not allow for integration, the Operations team assesses other integration
>   possibilities or recommends to not further pursue the customer contract.
> * The operations team communicates the result of the evaluation to the sales team.

(...)

## 2.2. Integration Coordination

> Possible contents of this process step:
>
> * Following integration evaluation and the conclusion of a new customer contract, the operations team is
>   responsible to coordinate overall integration efforts.
> * The operations team communicates to the customer (technical department) appropriate technical information
>   and guidance for the integration.
> * If integration problems occur, the operations team is responsible to (a) amend the integration evaluation
>   checklist in order to prevent similar problems with future customers. (b) initiate the change management
>   process in case the medical device itself needs to be changed.
> * Successful integration is validated by filling out the integration validation checklist. The operations
>   team obtains written confirmation of the customer setup after integration.
> * The operations team informs the sales team once integration is complete. It documents the deployment date,
>   deployed version of the device and customer information as part of the medical device list.

(...)

## 2.3. Algorithm Deployment and Configuration

> Optional for ML-driven devices: after integration and before go-live, test the algorithm on
> customer-specific live data (e.g. in the form of a “shadow mode” where algorithm results are not used in the
> clinical setting yet). Evaluate the results together with users.

(...)

## 2.4. User Administration

> Possible contents of this process step:
>
> * The operations team is responsible to activate users accounts according to the customer contract.
> * No user account is activated without / before
>   * Specification in the customer contract (e.g. number of seats?)
>   * Full completion of previous process steps (e.g. algorithm test)
>   * Optional to add here: user consent according to GDPR?

(...)

## 2.5. User Training

> Possible contents of this process step:
>
> * The operations team is responsible to provide users with the instructions for use / user manual. If not
>   part of the device, provision via email is sufficient.
> * The operations team conducts user training as defined in the user training strategy and documents every
>   training in the template for user training records.
> * The operations team informs the sales and regulatory team about successfully completed training.

(...)

## 2.6. Handling of Feedback

In case the operations team receives feedback (questions, complaints, praise, etc.) regarding the
organization’s medical devices and services, it proceeds as outlined in the SOP feedback management.

## 2.7. Handling of Updates

> Possible contents of this process step:
>
> * In case of a version update, the operations team verifies if the integration requirements change due to
>   the update and, if necessary, implements changes accordingly.
> * The operations team coordinates updates with the customer prior to deployment and, if applicable, notifies
>   the customer of potential product downtime according to the timeframe stated in customer contracts.
> * After deployment, the latest deployed version is documented in the medical device list.

(...)

## 2.8. Handling of Terminated Contracts

> Possible contents of this process step:
>
> * The sales team notifies the operations team in case of a terminated contract. Thereafter, the operations
>   team is responsible for deactivating respective user accounts.
> * The medical device list is updated accordingly.
> * If required, the operations team is responsible to support the customer with necessary data migration and
>   archives data related to the respective customer according to GDPR requirements (reference privacy policy
>   or similar here).

(...)

---

Template Copyright [openregulatory.com](https://openregulatory.com). See [template
license](https://openregulatory.com/template-license).

Please don't remove this notice even if you've modified contents of this template.
