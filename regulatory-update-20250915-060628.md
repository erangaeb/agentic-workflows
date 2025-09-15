## Topic
- Hungary e-invoicing updates.

## Document Metadata
- Jurisdiction/scope: Hungary. [Ref 1]
- Publishing authority: Hungarian Tax and Customs Administration (NAV). [Ref 1]

## Requirements / Specifications
- The official e-invoicing platform is Online Számla. [Ref 1]
- The technical requirements include FA(3) XML schema and API integration for real-time reporting. [Ref 1]
- Offline24 fallback is required for contingencies. [Ref 1]
- Invoices must be retained for 10 years. [Ref 1]

## Tax & VAT Compliance
- All VAT-registered businesses are required to report B2B and B2C invoices in real-time to NAV via the Online Számla platform since January 1, 2021. [Ref 1]
- Full e-invoicing is not mandatory for all transactions, but the energy sector is under full mandatory e-invoicing for B2B transactions since July 1, 2025. [Ref 1]
- VAT-registered foreign entities must comply with e-reporting obligations. [Ref 1]
- Non-residents using OSS for distance sales are exempt from full e-invoicing but must monitor other VAT-able flows carefully. [Ref 1]

## Penalties and risks for non-compliance
- Financial penalties can be up to HUF 1,000,000 per invoice for repeated non-compliance. [Ref 1]
- NAV issues warnings and allows for corrections before fines are applied. [Ref 1]
- Non-compliance may trigger VAT audits and deduction denials for buyers. [Ref 1]

## Implementation Impact
- Businesses should confirm VAT registration and fixed establishment (FE) status in Hungary. [Ref 1]
- Businesses should verify OSS participation for distance sales. [Ref 1]
- Businesses should identify applicable transaction types: B2B, B2C, B2G. [Ref 1]
- B2B invoices must be submitted via Online Számla. [Ref 1]
- B2C invoice data must be reported, and e-invoicing is optional. [Ref 1]
- Energy/Utilities sector has mandatory B2B e-invoicing from July 2025. [Ref 1]
- Businesses should map and validate the FA(3) XML schema. [Ref 1]
- Businesses should integrate with NAV API and configure Offline24 fallback for contingencies. [Ref 1]
- PEPPOL integration for future cross-border flows is planned. [Ref 1]
- Businesses should implement error correction workflows and re-submission processes. [Ref 1]
- Finance/IT teams should be trained on deadlines, reporting rules, and error handling. [Ref 1]

## Changes vs. Previous
- Since January 1, 2021, Hungary has required all VAT-registered businesses to report B2B and B2C invoices in real-time. [Ref 1]
- As of July 1, 2025, the energy sector is under full mandatory e-invoicing for B2B transactions. [Ref 1]

## Gaps/Unknowns
- Details on the specific data elements required in the FA(3) XML schema. [Ref 1]
- Specifics of the NAV API integration, including endpoints, authentication methods, and rate limits. [Ref 1]
- Detailed information on the Offline24 fallback procedure. [Ref 1]
- Precise details regarding PEPPOL integration for cross-border compliance. [Ref 1]

### Source References
- [Ref 1] Hungary e-Invoicing: RTIR, energy sector mandates and preparing for EU-wide VAT digitalization — https://www.globalvatcompliance.com/globalvatnews/hungary-e-invoicing-requirements-2025/
