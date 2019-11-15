# cdm
Non-Profit Common Data Model - start with the wiki (https://github.com/TrueGivers/cdm/wiki)

# Overview
The Non-Profit Common Data Model (CDM) is our version of what it should look like.  We've been working with CRMs, homegrown systems, Excel spreadsheets, Google docs, and many other data sources over the past decade.  We also reivewed the Microsoft https://github.com/Microsoft/Dynamics-365-Industry-Accelerators/tree/master/nfp model and thought we would throw our hat in the ring for review.

We've also made every attempt to not make this too data-centric, meaning over-normalized and with strict data types.  We've also left off a number of globalization pieces, but have attempted to provide extensions wherever possible to account for LTR/RTL languages and other text encoding.

Some of the implementation details are sector-specific, this often causes problems with custom fields, workflows, and compliance.  To address these issues, we have extensions for each of the following sectors:

- Arts, Culture, and Humanities - A
- Education - B
- Environment and Animals - C, D
- Health - E, F, G, H
- Human Services - I, J, K, L, M, N, O, P
- International, Foreign Affairs - Q
- Public, Societal Benefit - R, S, T, U, V, W
- Religion Related - X
- Mutual/Membership Benefit - Y
- Unknown, Unclassified - Z

(https://nccs.urban.org/classification/national-taxonomy-exempt-entities)

The goals of the CDM are as follows:
- Provide a standard for organizations to discuss data
- Provide a standard for organizations to share and integrate data
- Provide a standard for designing systems related to the industry
