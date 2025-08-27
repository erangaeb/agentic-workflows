## Topic
- romania e-invoice updates

## Document Metadata
- Jurisdiction/scope: Romania. [Ref 2]

## Requirements / Specifications
- Format: RO_CIUS (UBL/CII), aligned with EN 16931. [Ref 2]

## Tax & VAT Compliance
- B2B e-invoicing is mandatory for Romanian-established businesses and non-established VAT-registered taxpayers supplying goods or services with a place of supply in Romania since January 1, 2024 [Ref 2].
- B2C e-invoicing is mandatory for established suppliers since January 1, 2025 [Ref 2]. The supplier must still deliver the invoice directly to the consumer [Ref 2].
- B2G e-invoicing has been mandatory since 2022 [Ref 2].
- Associations, foundations, and farmers were exempt until June 30, 2025, but are now included in the scope [Ref 2].
- Buyers are increasingly refusing invoices not issued via RO e-Factura, as these may jeopardize VAT deduction [Ref 2].

## Submission & Interfaces
- Platform: ANAF SPV portal or APIs. [Ref 2]
- Submission deadline: 5 calendar days from issuance. [Ref 2]
- Buyer retrieval: invoices available for 60 days. [Ref 2]

## Validation / Business Rules
- Invalid VAT IDs or addresses now block invoice validation [Ref 2].

## Penalties and enforcement
- Fine bands for late or missing transmission (RON):
    - 5,000–10,000 for large taxpayers [Ref 2]
    - 2,500–5,000 for medium taxpayers [Ref 2]
    - 1,000–2,500 for small taxpayers [Ref 2]
- B2B fines are in force since April 2025 [Ref 2].
- B2C fines are in force since July 2025 [Ref 2].
- The bigger risk is non-deductible VAT for buyers and payment delays for suppliers [Ref 2].

## Changes vs. Previous
- Since January 1, 2025, B2C transactions are also required to be routed via RO e-Factura [Ref 2].
- Associations, foundations, and farmers are now included in the scope, their temporary carve-out having ended on June 30, 2025 [Ref 2].

## Implementation Impact
- Companies need pre-validation, reject-handling loops, and fallback PDFs to avoid cash collection delays [Ref 2].
- Master data cleanup is essential [Ref 2].
- Contracts should specify e-Factura responsibilities, particularly around buyer retrieval and invoice delivery [Ref 2].

## Gaps/Unknowns
- Details on the specific API endpoints, authentication methods, rate limits, retries, and acknowledgement/receipt mechanisms are not provided in the source documents [Ref 2].
- Specific error codes/messages and handling procedures are not detailed [Ref 2].
- Specific commodity codes that need to be reported are not listed [Ref 1].

### Source References
- [Ref 1] Romania’s SAF-T rollout: Lessons from a challenging transition — https://www.vatupdate.com/2025/08/27/romanias-saf-t-rollout-lessons-from-a-challenging-transition/
- [Ref 2] Romania’s e-invoicing reform: What matters for businesses in 2025–2026 — https://www.globalvatcompliance.com/globalvatnews/romania-e-invoicing-reform-2025/