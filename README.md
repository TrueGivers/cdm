# cdm
Non-Profit Common Data Model

# Overview
The Non-Profit Common Data Model (CDM) is our version of what it should look like.  We've been working with CRMs, homegrown systems, Excel spreadsheets, Google docs, and many other data sources over the past decade.  We also reivewed the Microsoft https://github.com/Microsoft/Dynamics-365-Industry-Accelerators/tree/master/nfp model and thought we would put our hat in the ring for review.

We've also made every attempt to not make this too data-centric, meaning over-normalized and with strict data types.  We've also left off a number of globalization pieces, but have attempted to provide extensions wherever possible to account for LTR/RTL languages and other text encoding.

Some of the implementation details are sector-specific, this often causes problems with custom fields, workflows, and compliance.  To address these issues, we have extensions for each of the following sectors:

I.    Arts, Culture, and Humanities - A
II.   Education - B
III.  Environment and Animals - C, D
IV.   Health - E, F, G, H
V.    Human Services - I, J, K, L, M, N, O, P
VI.   International, Foreign Affairs - Q
VII.  Public, Societal Benefit - R, S, T, U, V, W
VIII. Religion Related - X
IX.   Mutual/Membership Benefit - Y
X.    Unknown, Unclassified - Z

(https://nccs.urban.org/classification/national-taxonomy-exempt-entities)

The goals of the CDM are as follows:
- Provide a standard for organizations to discuss data
- Provide a standard for organizations to share and integrate data
- Provide a standard for designing systems related to the industry

# Usage
There is no specific usage implementation for this repository, other than to enable other software developers to not forget stuff when building their applications.

# Entities
The data entities covered by the CDM include the following:
- Donor
  - Individual
  - Organization
  - Corporation
  - Foundation
  - Government
- Relationships
  - Household
  - Employee
  - Colleague
  - Student
- Contact mechanism
  - Email addresse
  - Mailing addresse
  - Phone number
- Social profile
- Pledge
- Donation
- Communication Preference
- Tag
- Category

The entities that are beyond the scope of this CDM are:
- Events
- E-commerce
