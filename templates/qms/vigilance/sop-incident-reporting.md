# SOP Vigilance

| ISO 13485:2016 Section | Document Section |
|------------------------|------------------|
| 8.2.3                  | All              |

| Medical Device Regulation | Document Section |
|---------------------------|------------------|
| Art. 87                   | All              |

> Regulatory references: check MEDDEV 2.12./1 for guidance on this topic. As a German manufacturer, you are
> also subject to national law which lays out more specific requirements (note that in preparation for MDR,
> the Medizinproduktegesetz (MPG) was replaced by the Medizinprodukte-Durchführungsgesetz (MPDG) and the
> Medizinprodukte-EU-Anpassungsverordnung (MPEUAnpV) replaced the old
> Medizinprodukte-Sicherheitsplanverordnung (MPSV)).

## Summary

This SOP describes how we handle (potential) incidents. Specifically, it outlines how we follow the
requirements for the reporting of and necessary immediate action for adverse events.

## General Considerations

### Reportable Incident

Any incident that our organization becomes aware of is reportable, if one of our medical devices could be its
cause and if it fulfills the definition of an incident as outlined in this process. Potential incidents are
assessed based on our respective template form for incident assessment [reference document ID here].

A medical device incident is defined as "any malfunction or deterioration in the characteristics and/or
performance of a device, as well as any inadequacy in the labelling or the instructions for use which,
directly or indirectly, **might lead to or might have led** to the death of a patient, user or other person or
to a serious deterioration in their state of health" (see MEDDEV 2.12./1). Examples are (non-exclusively):

* malfunctioning (e.g. a software bug) of one of our medical devices
* incorrect labelling, instruction for use or advertising material
* usability deficiency causing a misuse

A serious deterioration in state of health includes at least one of the following:

* life-threatening illness
* permanent impairment of a body function or permanent damage to a body structure
* a condition which requires medical or surgical intervention to prevent one of the above
* any indirect harm as a consequence of an incorrect diagnostic result when used within manufacturer's
  instructions for use

> Note that: not all incidents lead to death or serious deterioration in health. The non-occurrence of such a
> result might have been due to fortunate circumstances or to the intervention of healthcare personnel. It is
> sufficient that: (a) an incident associated with a device happened, and (b) the incident was such that, if
> it occurred again, it might lead to death or serious deterioration in health.

### Field Safety Corrective Action (FSCA)

A field safety corrective action (FSCA) is an action taken to reduce a risk of death or serious deterioration
in the state of health associated with a device that is already placed on the market. Such actions, whether
related to direct or indirect harm, should be reported and informed about via a field safety notice. FSCAs can
include (non-exclusively):

* the return of a medical device to the manufacturer (recall)
* modification of a medical device, which can include: design changes (e.g. software update), permanent or
  temporary changes to the labelling or the instructions for use, changes to make device temporarily not
  available to users (software lock)
* advice provided by the manufacturer regarding the use or operation of the device

### Reporting Timescale

* In the event of imminent danger:
    * **Immediately** (without any delay that could not be justified)
* In the event of a serious public health threat:
    * **Immediately** after a link was established between the device and the event, **but no later than 2 elapsed calendar days** following the date of awareness of the event.
* Death or serious deterioration in state of health:
    * **immediately** after a link was established between the device and the event, **but no later than 10 elapsed calendar days** following the date of awareness of the event.
* Other reportable incidents:
    * **Immediately** after a link was established between the device and the event, **but not later than 15 elapsed calendar days** following the date of awareness of the event.
* Field Safety Corrective Action (FSCA):
    * **Immediately**, at latest with the beginning of the implementation of actions.

All report times refer to when the national responsible authority must first be notified. In case of uncertainty whether the incident has to be reported or not, it is reported within the above deadlines.

### Responsible Authorities

Incidents are reported to the authority of the country in which the reportable incident occurred:

**Germany:**

* [Federal Institute for Drugs and Medical Devices (BfArM)][bfarm]
* Email: [medizinprodukte@bfarm.de][bfarm-email]; Phone: +49 228 207 5355
* [Form for incident reporting][bfarm-form]

**Spain:**

* [Spanish Agency for Drugs and Medical Products (AEMPS)][aemps]
* Email: [sgps@aemps.es][aemps-email]; Phone: +34918225274

**Netherlands:**

* [CIBG-Farmatec][netherlands]
* Email: [medische_hulpmiddelen@minvws.nl][netherlands-email]

**Poland:**

* [Office for the Registration of Medical Products (URPLWMiPB)][poland]
* Email: [incydenty@urpl.gov.pl][poland-email]; Phone:+48 22 492 11 90

**Other national authorities:**

More contact data can be found under [this link on the website of the European Commission][other-authorities].

FSCA is reported to the authorities in the countries in which the FSCA is carried out, including incidents
which occurred outside of the European Economic Area (EEA) but resulted in a recall within European countries.

In parallel to reporting incidents to responsible authorities, our Notified Body is informed where applicable
in respect to the applied conformity assessment procedure.

## Process Steps

### 1. Documentation, Investigation and Evaluation of Incidents

Any employee of the company that obtains knowledge of an event with a potentially negative impact on the state
of health shall immediately notify the Person Responsible for Regulatory Compliance (PRRC) to initiate this process.

In a first step, the PRRC investigates the root causes of the event to determine if there is a causal
relationship between the use of the medical device and the event. The investigation is documented as a
CAPA. If there is no causal relationship, the event is not considered a reportable incident.

If there is a relationship, the PRRC secondly evaluates if the event qualifies as a reportable incident
by filling out our template form for incident assessment [reference document ID here].

In the case of uncertainty, the event is reported as a reportable incident.

| Participants                                              |
|-----------------------------------------------------------|
| Person Responsible for Regulatory Compliance (MDSO / PRRC)|

| Input                                                           | Output                                              |
|-----------------------------------------------------------------|-----------------------------------------------------|
| Event with a potentially negative impact on the state of health | Completed investigation and evaluation of the event |

### 2. Reporting of Incidents

Within the applicable reporting timescale (see general considerations above), the PRRC informs the
responsible national authority about the event using respective reporting forms. S/he compiles and provides a
report with all information required and available at the time.

If applicable, a copy of the report is sent to the Notified Body involved in the conformity assessment
procedure of the device.

| Participants                                               |
|------------------------------------------------------------|
| Person Responsible for Regulatory Compliance (MDSO / PRRC) |

| Input                                                  | Output                                                 |
|--------------------------------------------------------|--------------------------------------------------------|
| Completed investigation and evaluation of the incident | Completed reporting to authorities (and Notified Body) |

### 3. Decision on Immediate Action (FSCA)

Based on a risk and root cause analysis of the event, the PRRC decides if field safety corrective actions (FSCA) are required to reduce existing risks. Possible FSCAs are described as part of the general considerations of this process.

Before actions are taken, we inform users / customers about such as part of a field safety notice (FSN). The FSN is written in the language of the respective country and must at minimum include:

* Subject: **Safety Alert**
* Manufacturer information (e.g. contact details)
* Information to identify the affected devices (e.g. device name and software version)
* Description of the incident problem including resulting risks and the reasons for FSCA
* If applicable, actions recommended to the user / customer. For example, this could include actions to
  restore the safety or recommended clinical investigations.

All FSCAs are documented as part of the CAPA. A copy of the FSN shall be archived. Customers confirm the receipt
of FSNs as well as the implementation of recommended actions. All customer communication must be documented in writing (e.g. email follow-up after phone conversation). If a customer does not respond, at least three attempts for delivery should be made. It is also documented as part of the CAPA if all attempts to inform a customer were unsuccessful.

> You may want to consider a separate process regarding the handling of non-conforming products. This process
> would entail labeling instructions for respective product code and instructions for employees handling those
> products.


| Participants                                               |
|------------------------------------------------------------|
| Person Responsible for Regulatory Compliance (MDSO / PRRC) |

| Input                         | Output                          |
|-------------------------------|---------------------------------|
| Risks resulting from incident | Implemented FSCA, including FSN |

### 4. Verification and Evaluation of Effectiveness

The effectiveness of implemented FSCAs is evaluated as part of the CAPA. As soon as the CAPA is closed, a final
report is sent to the responsible authorities to verify that all actions taken are deemed sufficient for
completion.

All incident records shall be archived as part of the QMS.

| Participants                                               |
|------------------------------------------------------------|
| Person Responsible for Regulatory Compliance (MDSO / PRRC) |

| Input                  | Output                                |
|------------------------|---------------------------------------|
| Implementation of FSCA | Final incident report and closed CAPA |


<!-- Links -->

[bfarm]: https://www.bfarm.de
[bfarm-email]: mailto:medizinprodukte@bfarm.de
[bfarm-form]: https://www.bfarm.de/DE/Service/Formulare/functions/Medizinprodukte/_node.html
[aemps]: https://www.aemps.gob.es
[aemps-email]: mailto:sgps@aemps.es
[netherlands]: https://www.igj.nl
[netherlands-email]: mailto:medische_hulpmiddelen@minvws.nl
[poland]: http://www.urpl.gov.pl/en
[poland-email]: mailto:incydenty@urpl.gov.pl
[other-authorities]: https://ec.europa.eu/health/md_sector/contact_en
