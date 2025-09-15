## Topic
- Hungary e‑invoicing updates.

## Document Metadata
- Jurisdiction/scope: Hungary. [Ref 1][Ref 2]
- Publishing authority: Hungarian Tax and Customs Administration (NAV). [Ref 2]

## Requirements / Specifications
- Real-time reporting of B2B and B2C invoices to NAV via the Online Számla platform is required for VAT-registered businesses [Ref 2].
- The technical requirements include FA(3) XML schema and API integration for real-time reporting [Ref 1][Ref 2].
- An Offline24 fallback is required for contingencies [Ref 1][Ref 2].
- Invoices must be retained for 10 years [Ref 1][Ref 2].

## Tax & VAT Compliance
- Since January 1, 2021, all VAT-registered businesses are required to report B2B and B2C invoices in real-time to NAV via the Online Számla platform [Ref 2].
- As of July 1, 2025, full mandatory e-invoicing for B2B transactions in the energy sector is in effect [Ref 1][Ref 2].
- Non-residents using OSS for distance sales are exempt from full e-invoicing but must monitor other VAT-able flows carefully [Ref 2].

## Submission & Interfaces
- Invoices are submitted via Hungary’s official e-invoicing platform, Online Számla [Ref 1][Ref 2].
- Integration with NAV API is required [Ref 2].
- Future cross-border compliance via PEPPOL integration is planned [Ref 1][Ref 2].

## Penalties and Risks for Non-Compliance
- Financial penalties can be up to HUF 1,000,000 per invoice for repeated non-compliance [Ref 1][Ref 2].
- NAV typically offers grace periods for corrections before fines are applied [Ref 1][Ref 2].
- Non-compliance may trigger VAT audits and deduction denials for buyers [Ref 2].

## Implementation Impact
- Businesses should confirm VAT registration and fixed establishment (FE) status in Hungary [Ref 2].
- Businesses should verify OSS participation for distance sales [Ref 2].
- Businesses should identify applicable transaction types: B2B, B2C, B2G [Ref 2].
- Businesses should map and validate the FA(3) XML schema [Ref 2].
- Businesses should train finance/IT teams on deadlines, reporting rules, and error handling [Ref 2].

## Changes vs. Previous
- As of July 1, 2025, mandatory e-invoicing is in effect for all B2B transactions in the energy sector (electricity & gas) [Ref 2].

## Gaps/Unknowns
- Details on the specific API endpoints, authentication methods, rate limits, and retry mechanisms for the Online Számla platform are not provided [Ref 2].
- Specific error codes/messages and handling procedures are not detailed [Ref 2].

### Source References
- [Ref 1] Hungary e-Invoicing: RTIR, Energy Sector Requirements, and EU VAT Digitalization Prep — https://www.vatupdate.com/2025/09/15/hungary-e-invoicing-rtir-energy-sector-requirements-and-eu-vat-digitalization-prep/
- [Ref 2] Hungary e-Invoicing: RTIR, energy sector mandates and preparing for EU-wide VAT digitalization — https://www.globalvatcompliance.com/globalvatnews/hungary-e-invoicing-requirements-2025/
