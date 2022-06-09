# Failure Mode and Effects Analysis (FMEA): Risk Acceptance Matrix

This document defines under which circumstances risks are acceptable. It defines probabilities and severities
and each probability-severity combination is either acceptable or not, as shown in the risk acceptance matrix
at the bottom.

## Risk Policy

> Generally, describe what your company's risk policy is. Most likely, that's something along the lines of "our
> products are generally safe and shouldn't cause more harm than the next-best alternative". So, if you're in
> the business of predicting COVID-19 infections, maybe you'd compare yourself to people not using your software
> and doing a non-professional google research about their symptoms. Obviously, that's a worse alternative. In
> your clinical evaluation, you should collect data on those alternatives to be able to compare yourself to
> them :)

## Severity

> Define what can go wrong with your product here. Make the examples specific - chances are, your product
> can't cause skin lacerations. In all likelihood it also doesn't cause death. So, feel free to remove
> severity rows here. But most importantly, customize the definitions and examples so that they resemble the
> harms in your product.

| Severity         | Definition and Examples                                                                                   |
|------------------|-----------------------------------------------------------------------------------------------------------|
| S1: Negligible   | Minor, reversible damage, e.g. superficial skin irritation, delay of non-critical treatment               |
| S2: Marginal     | Minor, reversible damage with required medical intervention, e.g. skin laceration requiring stitches      |
| S3: Critical     | Major, irreversible damage with required medical intervention, e.g. irreversible deterioration of disease |
| S4: Catastrophic | Death                                                                                                     |

## Probability

> Define your probabilities. You can probably just use these definitions. The idea is that each probability
> row is 10^2 apart from adjacent ones.

> Also, change the "Estimated Maximum Event Count". That's the usage number you estimate for your (not yet
> released product) during its entire lifecycle (which you need to define). So, if you assume that your
> product will be on the market for 4 years and that it'll be used 100 times per day, that results in 146.100
> usages (100 usages/day * 365.25 days/year * 4 years). The numbers in the lower columns of "Estimated Maximum
> Event Count" are simply the total usage number multiplied by the upper limit probability of the same row,
> e.g. you want to know "how often can probability P3 occur if the product is being used 100 times per day?"

| Probability  | Upper Limit | Lower Limit | Estimated Maximum Event Count |
|--------------|-------------|-------------|-------------------------------|
| P5: Certain  | 1           | 10^-2       | 1000000 *(change this*)       |
| P4: Likely   | 10^-2       | 10^-4       | 10000                         |
| P3: Possible | 10^-4       | 10^-6       | 100                           |
| P2: Unlikely | 10^-6       | 10^-8       | 1                             |
| P1: Rare     | 10^-8       | 0           | 0                             |

## Risk Acceptance Matrix

> The most important part. You assess each severity-probability combination whether it's acceptable for you as
> a company. There are no definitive rules on what's deemed acceptable. It depends on your company's risk
> policy and, more importantly, the benefits of your product which you show in your clinical evaluation. So,
> for example, if your product saves 10 lives per day, it might be acceptable to cause one death per day. If
> your product doesn't save any lives, it might not be acceptable to cause any deaths. You get the idea, I
> hope.

| Probability  | S1: Negligible | S2: Marginal     | S3: Critical     | S4: Catastrophic | Estimated Maximum Event Count |
|--------------|----------------|------------------|------------------|------------------|-------------------------------|
| P5: Certain  | acceptable     | **unacceptable** | **unacceptable** | **unacceptable** | 1000000                       |
| P4: Likely   | acceptable     | **unacceptable** | **unacceptable** | **unacceptable** | 10000                         |
| P3: Possible | acceptable     | acceptable       | **unacceptable** | **unacceptable** | 100                           |
| P2: Unlikely | acceptable     | acceptable       | acceptable       | **unacceptable** | 1                             |
| P1: Rare     | acceptable     | acceptable       | acceptable       | acceptable       | 0                             |
