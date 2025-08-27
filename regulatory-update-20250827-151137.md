## Document Metadata
- Jurisdiction / scope: Romania. [Ref 1]
- Publishing authority: Not specified in the provided text.
- Version / document date: Not specified in the provided text.
- Effective / compliance dates (incl. grace periods):
    - B2B e-invoicing mandatory for Romanian-established businesses and non-established VAT-registered taxpayers: Since January 1, 2024. [Ref 1]
    - B2C e-invoicing mandatory for established suppliers: Since January 1, 2025. [Ref 1]
    - B2G e-invoicing mandatory: Since 2022. [Ref 1]
    - Associations, foundations, farmers exempt until June 30, 2025. [Ref 1]
    - B2B fines in effect: Since April 2025. [Ref 1]
    - B2C fines in effect: Since July 2025. [Ref 1]

## Format Requirements
- Format: RO_CIUS (UBL/CII), aligned with EN 16931. [Ref 1]

## Validation Rules
- Invalid VAT IDs or addresses now block invoice validation. [Ref 1]

## Tax & VAT Compliance
- Buyers are increasingly refusing invoices that are not issued via RO e-Factura, as these may jeopardise VAT deduction. [Ref 1]
- The bigger risk is non-deductible VAT for buyers and payment delays for suppliers. [Ref 1]

## Submission & Reporting
- Platform: ANAF SPV portal or APIs. [Ref 1]
- Submission deadline: 5 calendar days from issuance. [Ref 1]

## Regulatory Changes (Diff vs. previous)
- Since January 1, 2024, B2B e-invoicing is mandatory for Romanian-established businesses and for non-established VAT-registered taxpayers supplying goods or services with place of supply in Romania. [Ref 1]
- From January 1, 2025, the scope expanded to cover B2C transactions. [Ref 1]
- Associations, foundations, farmers exempt until June 30, 2025, now included in scope. [Ref 1]

## Implementation Impact
- Companies need pre-validation, reject-handling loops, and fallback PDFs to avoid cash collection delays. [Ref 1]
- Master data cleanup is essential. [Ref 1]
- Contracts should specify e-Factura responsibilities, particularly around buyer retrieval and invoice delivery. [Ref 1]

## Gaps/Unknowns
- Specific mandatory fields for RO_CIUS format are not listed. [Ref 1]
- Data types, value domains, cardinality, and patterns (regex) for RO_CIUS are not specified. [Ref 1]
- Namespaces and encoding details for the file format are not provided. [Ref 1]
- Details on signatures/hashes are missing. [Ref 1]
- Minimal example fragments of RO_CIUS are not included. [Ref 1]
- Specific field validations, cross-field dependencies, and conditionals are not detailed. [Ref 1]
- Error codes/messages and handling procedures are not specified. [Ref 1]
- VAT rates, exemptions, and special schemes are not detailed. [Ref 1]
- Specific reporting obligations (CTC/RTIR), thresholds, and frequency are not provided. [Ref 1]
- Transport/API endpoints, authentication methods, and rate limits are not specified. [Ref 1]
- Deadlines, retries, and acknowledgements/receipts for submissions are not detailed. [Ref 1]
- Specific added/removed/modified fields or rules compared to previous versions are not listed. [Ref 1]
- Deprecated elements and timelines are not specified. [Ref 1]
- Detailed required system changes (models, validations, integrations) are not provided. [Ref 1]
- Specific risks/edge cases and testing requirements are not detailed. [Ref 1]

### Source References
- [Ref 1] Romania’s e-invoicing reform: What matters for businesses in 2025–2026 — https://www.globalvatcompliance.com/globalvatnews/romania-e-invoicing-reform-2025/