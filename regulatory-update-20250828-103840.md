## Topic
- romania e-invoice updates

## Document Metadata
- Jurisdiction/scope: Romania. [Ref 2]
- Effective/compliance dates:
  - B2B e-invoicing mandatory for Romanian-established businesses and non-established VAT-registered taxpayers supplying goods/services with place of supply in Romania since January 1, 2024. [Ref 2]
  - B2C e-invoicing mandatory since January 1, 2025. [Ref 2]
  - B2G e-invoicing mandatory since 2022. [Ref 2]
  - Associations, foundations, and farmers are exempt until June 30, 2025. [Ref 2]
  - B2B fines are in force since April 2025. [Ref 2]
  - B2C fines are in force since July 2025. [Ref 2]
  - Soft-landing period ended March 31, 2025. [Ref 2]

## Requirements / Specifications
- Format: RO_CIUS (UBL/CII), aligned with EN 16931. [Ref 2]
- Platform: ANAF SPV portal or APIs. [Ref 2]
- Self-billing: Supported (AUTOFACTURA flag). [Ref 2]
- Consumer IDs can be replaced with zeros for privacy. [Ref 2]

## Tax & VAT Compliance
- Buyers are increasingly refusing invoices not issued via RO e-Factura, as these may jeopardize VAT deduction. [Ref 2]
- Failure to issue compliant invoices risks delayed payments or disputes. [Ref 2]

## Submission & Interfaces
- Submission deadline: 5 calendar days from issuance. [Ref 2]
- Buyer retrieval: invoices available for 60 days. [Ref 2]
- Archiving: mandatory 10 years. [Ref 2]

## Validation / Business Rules
- Invalid VAT IDs or addresses now block invoice validation. [Ref 2]

## Penalties and enforcement
- Fine bands for late or missing transmission (RON): [Ref 2]
  - 5,000–10,000 for large taxpayers. [Ref 2]
  - 2,500–5,000 for medium taxpayers. [Ref 2]
  - 1,000–2,500 for small taxpayers. [Ref 2]
- The bigger risk is non-deductible VAT for buyers and payment delays for suppliers. [Ref 2]

## Implementation Impact
- Companies need pre-validation, reject-handling loops, and fallback PDFs to avoid cash collection delays. [Ref 2]
- Master data cleanup is essential. [Ref 2]
- Contracts should specify e-Factura responsibilities, particularly around buyer retrieval and invoice delivery. [Ref 2]
- Need to map ERP to RO_CIUS, including simplified invoices. [Ref 2]
- Implement robust API/portal flows with reject-handling and escalation. [Ref 2]
- Train AR/AP teams on the 5-day deadline and retrieval/delivery requirements. [Ref 2]
- Reconcile VAT returns with RO e-Factura invoice statuses. [Ref 2]

## Changes vs. Previous
- Since January 1, 2024, B2B e-invoicing is mandatory for Romanian-established businesses and for non-established VAT-registered taxpayers supplying goods or services with place of supply in Romania [Ref 2].
- From January 1, 2025, the scope expanded to cover B2C transactions [Ref 2].

## Gaps/Unknowns
- Details on the specific data requirements that exceed typical VAT reporting capabilities [Ref 1].

### Source References
- [Ref 1] Romania’s SAF-T rollout: Lessons from a challenging transition — https://www.vatupdate.com/2025/08/27/romanias-saf-t-rollout-lessons-from-a-challenging-transition/
- [Ref 2] Romania e-invoicing reform 2025: Key updates for B2B and B2C — https://www.globalvatcompliance.com/globalvatnews/romania-e-invoicing-reform-2025/