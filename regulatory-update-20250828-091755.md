## Topic
- romania e-invoice updates

## Document Metadata
- Jurisdiction/scope: Romania [Ref 1].
- Effective/compliance dates:
  - B2B e-invoicing mandatory for Romanian-established businesses and non-established VAT-registered taxpayers since January 1, 2024 [Ref 1].
  - B2C e-invoicing mandatory since January 1, 2025 [Ref 1].
  - B2G invoicing mandatory since 2022 [Ref 1].
  - B2B fines in force since April 2025 [Ref 1].
  - B2C fines in force since July 2025 [Ref 1].
  - Associations, foundations, farmers exempt until June 30, 2025 [Ref 1].

## Requirements / Specifications
- Format: RO_CIUS (UBL/CII), aligned with EN 16931 [Ref 1].
- Submission deadline: 5 calendar days from issuance [Ref 1].
- Archiving: mandatory 10 years [Ref 1].
- Consumer IDs can be replaced with zeros [Ref 1].

## Validation / Business Rules
- Invalid VAT IDs or addresses now block invoice validation [Ref 1].

## Tax & VAT Compliance
- Buyers are increasingly refusing invoices not issued via RO e-Factura, as these may jeopardise VAT deduction [Ref 1].
- Non-established companies in Romania must submit the D406 Standard Audit File for Tax (SAF-T) starting January 1, 2025 [Ref 2].
- New data requirements for SAF-T exceed typical VAT reporting capabilities, especially for businesses with infrequent transactions in Romania [Ref 2].
- SAF-T reporting requires commodity codes and detailed transaction information [Ref 2].
- SAF-T reporting requires navigating complex adjustment and exchange rate rules [Ref 2].

## Submission & Interfaces
- Platform: ANAF SPV portal or APIs [Ref 1].
- Buyer retrieval: invoices available for 60 days [Ref 1].

## Changes vs. Previous
- Since January 1, 2025, B2C invoices must also be routed via RO e-Factura, including simplified invoices [Ref 1].
- B2B e-invoicing has been mandatory for both established and non-established suppliers with Romanian transactions since July 1, 2024 [Ref 1].

## Implementation Impact
- Companies need pre-validation, reject-handling loops, and fallback PDFs to avoid cash collection delays [Ref 1].
- Master data cleanup is essential [Ref 1].
- Contracts should specify e-Factura responsibilities, particularly around buyer retrieval and invoice delivery [Ref 1].
- Need to ensure infrastructure readiness before enforcing digital tax compliance [Ref 2].

## Penalties and enforcement
- Fine bands for late or missing transmission (RON) [Ref 1]:
  - 5,000–10,000 for large taxpayers [Ref 1].
  - 2,500–5,000 for medium taxpayers [Ref 1].
  - 1,000–2,500 for small taxpayers [Ref 1].
- The bigger risk is non-deductible VAT for buyers and payment delays for suppliers [Ref 1].

## Gaps/Unknowns
- Details on the specific API endpoints, authentication methods, rate limits, and retry policies for the ANAF SPV portal are not provided [Ref 1].
- Specific error codes/messages and handling procedures for rejected e-invoice submissions are not detailed [Ref 1].
- Specifics on how to implement the "AUTOFACTURA flag" for self-billing are not provided [Ref 1].
- The exact format and technical specifications for the D406 SAF-T are not detailed [Ref 2].

### Source References
- [Ref 1] Romania’s e-invoicing reform: What matters for businesses in 2025–2026 — https://www.globalvatcompliance.com/globalvatnews/romania-e-invoicing-reform-2025/
- [Ref 2] Romania’s SAF-T rollout: Lessons from a challenging transition — https://www.vatupdate.com/2025/08/27/romanias-saf-t-rollout-lessons-from-a-challenging-transition/
