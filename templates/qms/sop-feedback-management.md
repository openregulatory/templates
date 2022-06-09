# SOP Feedback Management and Customer Complaints

| ISO 13485:2016 Section | Document Section |
|------------------------|------------------|
| 8.2.1.                 | All              |
| 8.2.2.                 | All              |

| IEC 62304:2006 Section | Document Section |
|------------------------|------------------|
| 6.2.1                  | All              |

## Summary

This SOP describes how to respond to feedback and complaints.

## General Considerations

> In this section, provide general information about how you intend to set up your company's feedback
> management system.
>
> Consider sub-sections that describe more specifically:
>
> * Customer support availability (typically e.g. 9am - 5pm CET Mon - Fri)
> * Customer support ticket system (if applicable, consider GDPR requirements for sensitive data)
> * Contact channels: describe the primary way to contact your customer support (e.g. support email address).
> * Think about the most commonly used contact channels for your product and organization. Also consider
>   channels independent from internet connection. Ideally, inquiries should be responded to in the same way of
>   communication as they were received by.
> * Feedback prioritization (*optional*, e.g. high - medium - low)

### Feedback Classification

All feedback is classified into one of the following categories. If the Operations team is not sure how to
classify a ticket, it consults the QMO.

| Feedback Category                                              | Feedback Description                                                                                                                                                                                                                                                                                                                                                                                               |
|----------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Support Inquiry                                                | Any request for help that can be resolved by providing the user with (usability) information.                                                                                                                                                                                                                                                                                                                      |
| Change Request                                                 | Any request to add, modify or remove product functionalities.                                                                                                                                                                                                                                                                                                                                                      |
| Customer Complaint                                             | Any complaint that can be related to our products or organization and which is not classified as an "issue with potential negative influence on patient health".                                                                                                                                                                                                                                                   |
| Issue with potential negative influence on the state of health | Any customer complaint related to:<br>problem with the medical device that could cause or may have caused or did in fact cause a death or serious deterioration in the state of health.<br>problem with the medical device that significantly impaired the performance criteria of the device (based e.g. on the information given in the intended use, user manual or marketing material). |

> Add more categories as required by your organization. For example: positive feedback (praise), data privacy inquiries, differentiate product complaints <> customer complaints (not product related), etc.

| Serious Deterioration of the State of Health                                                                                                                                                                                                                                                                                                                                                                                      |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A serious deterioration of the state of health includes at least one of the following:<br>life-threatening illness,<br>permanent impairment of a body function or permanent damage to a body structure,<br>a condition which requires medical or surgical intervention to prevent one of the above,<br>any indirect harm as a consequence of an incorrect diagnostic result when used within manufacturer's instructions for use. |

## Process Steps

### 1. Documentation of Feedback

The Operations team receives feedback through a contact channel, which automatically opens a respective ticket
in our system (see general considerations above). Based on the input, the Operations team then documents at
minimum the following information in the ticket:

* Date of feedback
* Description of the issue (e.g. software version, runtime environment, if available: screenshots / images)
* Affected users, contact details and customer locations
* Steps to reproduce the problem

| Participants    |
|-----------------|
| Operations team |

| Input                         | Output                                                |
|-------------------------------|-------------------------------------------------------|
| Received feedback / complaint | Structured documentation of feedback in ticket system |


### 2. Evaluation of Feedback

The Operations team classifies the feedback according to the categories outlined in the general considerations
of this process.  Depending on the feedback category it takes respective actions:

**Support Inquiry:**

The Operations team actively supports the customer / user in solving the issue by answering questions or
providing additional user training.

**Change Request:**

The feedback ticket is forwarded to the Product team to decide over implementation and potentially initiate the change management process.

**Customer Complaint:**

* If the customer complaint constitutes a persistent problem related to a medical device that cannot be
  resolved by providing user information or training (e.g. software bugs), it is forwarded to the Product team
  to initiate the problem resolution process.
* If the customer complaint is related to an organizational issue (e.g. sales and marketing efforts), the
  Operations team involves other teams of the organization where necessary to provide the customer / user with
  a satisfactory response.
* If the customer complaint may constitute a systematic issue, the feedback is additionally forwarded to the
  Quality Management Officer (QMO) to initiate the process for corrective and preventive actions (CAPA).

**Issue with a Potential Negative Impact on the State of Health:**

All issues with a potential negative impact on the state of health must be reported immediately, but no later
than on the same day, to the Medical Device Safety Officer / Person Responsible for Regulatory Compliance.

All product-related feedback shall be checked for a potential impact on the risk management file or product requirements of the respective device and shall be taken into consideration for device post-market surveillance.

| Participants    |
|-----------------|
| Operations team |

| Input               | Output                                      |
|---------------------|---------------------------------------------|
| Documented feedback | Classified feedback and decision on actions |

### 3. Validation of Actions

The Operations team proactively receives updates regarding the status of actions per ticket from other teams.

Once the actions are considered completed (e.g. for change requests: decision to implement a feature or not is
made), the Operations team informs the customer / user and validates if the actions taken are satisfying. If
so, the validation is documented in the ticket and the ticket is closed. If not, this process is re-initiated.

If a customer / user does not respond, validation is tried at least a second time before the ticket is closed.

| Participants    |
|-----------------|
| Operations team |

| Input               | Output                                  |
|---------------------|-----------------------------------------|
| Implemented actions | Validation of actions, ticket is closed |

> Optionally, depending on the features that your ticket system provides, consider adding a process step to
> assign each ticket a status (open, pending input, closed).
