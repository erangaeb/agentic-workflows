## Topic
- romania e-invoice updates

## Document Metadata
- Jurisdiction/scope: Romania. [Ref 2]
- Publishing authority: ANAF (indirectly, via reference to SPV platform). [Ref 2]
- Effective/compliance dates:
  - B2B e-invoicing mandatory for Romanian-established businesses and non-established VAT-registered taxpayers supplying goods/services with place of supply in Romania: Since January 1, 2024 [Ref 2]
  - B2C e-invoicing mandatory: January 1, 2025 [Ref 2]
  - B2G e-invoicing mandatory: Since 2022 [Ref 2]
  - Associations, foundations, farmers exempt until June 30, 2025, now included in scope [Ref 2]
  - B2B fines: In force since April 2025 [Ref 2]
  - B2C fines: In force since July 2025 [Ref 2]

## Requirements / Specifications
- Format: RO_CIUS (UBL/CII), aligned with EN 16931 [Ref 2]
- Platform: ANAF SPV portal or APIs [Ref 2]

## Tax & VAT Compliance
- B2B e-invoicing is mandatory for Romanian-established businesses and for non-established VAT-registered taxpayers supplying goods or services with place of supply in Romania [Ref 2].
- B2C invoices must also be routed via RO e-Factura since January 1, 2025 [Ref 2]. However, unlike B2B, the supplier must still deliver the invoice directly to the consumer, as buyers do not retrieve invoices from the system [Ref 2].
- Buyers are increasingly refusing invoices that are not issued via RO e-Factura, as these may jeopardise VAT deduction [Ref 2].

## Submission & Interfaces
- Submission deadline: 5 calendar days from issuance [Ref 2]
- Buyer retrieval: invoices available for 60 days [Ref 2]

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

## Implementation Impact
- Companies need pre-validation, reject-handling loops, and fallback PDFs to avoid cash collection delays [Ref 2].
- Master data cleanup is essential [Ref 2].
- Contracts should specify e-Factura responsibilities, particularly around buyer retrieval and invoice delivery [Ref 2].

## Changes vs. Previous
- Since January 1, 2024, B2B e-invoicing is mandatory for Romanian-established businesses and for non-established VAT-registered taxpayers supplying goods or services with place of supply in Romania [Ref 2].
- From January 1, 2025, the scope expanded to cover B2C transactions [Ref 2].

## Gaps/Unknowns
- Specific details on the API endpoints, authentication methods, rate limits, and retry mechanisms for the ANAF SPV portal are not provided in the sources [Ref 2].
- The exact data requirements for commodity codes and detailed transaction information are not specified [Ref 1].
- The specific error codes and messages returned by the RO e-Factura system, as well as their handling procedures, are not detailed [Ref 2].

### Source References
- [Ref 1] Romania’s SAF-T rollout: Lessons from a challenging transition — https://www.vatupdate.com/2025/08/27/romanias-saf-t-rollout-lessons-from-a-challenging-transition/
- [Ref 2] Romania’s e-invoicing reform: What matters for businesses in 2025–2026 — https://www.globalvatcompliance.com/globalvatnews/romania-e-invoicing-reform-2025/
