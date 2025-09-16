## Topic
- Hungary e-invoicing updates.

## Document Metadata
- Jurisdiction/scope: Hungary. [Ref 1]
- Publishing authority: Global VAT Compliance. [Ref 1]
- Effective/compliance dates (incl. grace periods):
    - Real-time invoice reporting (RTIR) for B2B/B2C: January 1, 2021. [Ref 1]
    - Energy sector B2B e-invoicing: Mandatory since July 1, 2025. [Ref 1]
    - OSS exemptions continue: 2025–2026. [Ref 1]
    - Penalties enforced: NAV begins applying full penalties for non-compliance in 2026. [Ref 1]
    - EU ViDA integration: Anticipated in 2027. [Ref 1]

## Requirements / Specifications
- **Reporting Platform:** Online Számla is Hungary’s official e-invoicing platform for real-time invoice submission. [Ref 1]
- **Data Format:** FA(3) XML schema is required for technical implementation. [Ref 1]
- **Archiving:** Invoices must be retained for 10 years. [Ref 1]
- **Fallback Mechanism:** Offline24 fallback is required for contingencies. [Ref 1]

## Validation / Business Rules
- **Penalties:** Financial penalties can be up to HUF 1,000,000 per invoice for repeated non-compliance. [Ref 1]
- **Grace Period:** The Hungarian Tax and Customs Administration (NAV) issues warnings and allows for corrections before fines are applied. [Ref 1]
- **Risks:** Non-compliance may trigger VAT audits and deduction denials for buyers. [Ref 1]

## Tax & VAT Compliance
- **Reporting Obligation:** All VAT-registered businesses in Hungary are required to report B2B and B2C invoices in real-time to NAV via the Online Számla platform since January 1, 2021. [Ref 1]
- **B2B Transactions:** Mandatory real-time reporting of invoices via Online Számla. [Ref 1]
- **B2C Transactions:** Reporting invoice data is required; full e-invoicing is optional. [Ref 1]
- **B2G Transactions:** Public sector entities must accept e-invoices in compliance with EU Directive 2014/55/EU, but businesses are not mandated to issue e-invoices to public administrations. [Ref 1]
- **Non-residents:** VAT-registered foreign entities must comply with e-reporting obligations. [Ref 1]
- **OSS Participants:** Non-residents using the One Stop Shop (OSS) for distance sales are exempt from full e-invoicing but must monitor other VAT-able flows carefully. [Ref 1]
- **Sector-Specific Mandate:** The energy sector (electricity & gas) has a full mandatory e-invoicing requirement for B2B transactions, effective July 1, 2025. [Ref 1]

## Submission & Interfaces
- **Channels:** Real-time invoice submission is done via the Online Számla platform. [Ref 1]
- **API Integration:** API integration is required for real-time reporting. [Ref 1]
- **Future Interoperability:** PEPPOL integration is planned for future cross-border compliance. [Ref 1]

## Changes vs. Previous
- **RTIR Mandatory:** Real-time reporting for B2B/B2C invoices via Online Számla became mandatory on January 1, 2021. [Ref 1]
- **Energy Sector B2B E-Invoicing:** Mandatory e-invoicing for all B2B transactions in the energy sector (electricity & gas) became effective in July 2025. [Ref 1]
- **OSS Exemptions:** Non-resident sellers engaged in distance sales and registered for OSS are exempt from Hungarian e-reporting requirements, with these exemptions continuing through 2025–2026. [Ref 1]
- **Penalties Enforcement:** NAV will begin applying full penalties for non-compliance in 2026. [Ref 1]
- **EU ViDA Integration:** Full integration with EU-wide ViDA standards and PEPPOL interoperability is anticipated in 2027. [Ref 1]

## Implementation Impact
- **Registration & Scope:** Businesses need to confirm VAT registration and fixed establishment (FE) status in Hungary, verify OSS participation for distance sales, and identify applicable transaction types (B2B, B2C, B2G). [Ref 1]
- **Invoice Submission:**
    - B2B: All invoices must be submitted via Online Számla. [Ref 1]
    - B2C: Invoice data must be reported; e-invoicing is optional. [Ref 1]
    - B2G: Businesses have the possibility to issue e-invoices for public sector customers. [Ref 1]
- **Sector-Specific Preparation:** Businesses in the energy/utilities sector must prepare for mandatory B2B e-invoicing from July 2025. Telecom and financial services sectors should prepare for future EU ViDA compliance. [Ref 1]
- **Technical Setup:** Requires FA(3) XML schema mapping and validation, integration with NAV API, and configuration of Offline24 fallback. PEPPOL integration for future cross-border flows is planned. [Ref 1]
- **Archiving & Monitoring:** Implement archiving for 10 years and establish error correction workflows and re-submission processes. [Ref 1]
- **Staff & Strategic Readiness:** Train finance/IT teams on deadlines, reporting rules, and error handling. Align Hungarian compliance with EU ViDA strategy and cross-border harmonization, and continuously monitor NAV updates and sector-specific mandates. [Ref 1]
- **Strategic Opportunity:** Adopting automated workflows and preparing for sector-specific mandates can position businesses as leaders in digital VAT compliance, minimize risk, and future-proof VAT operations. [Ref 1]

## Gaps/Unknowns
- Specific details of the FA(3) XML schema (e.g., fields, data types, cardinality) are not provided. [Ref 1]
- Detailed API specifications (e.g., endpoints, authentication methods, rate limits) for Online Számla are not included. [Ref 1]
- Specific error codes and messages for non-compliance or submission failures are not detailed. [Ref 1]
- The exact scope of "energy sector" (e.g., specific types of energy, thresholds) beyond electricity and gas is not fully elaborated. [Ref 1]
- The specific timeline or roadmap for future mandates in telecom, finance, and other sectors is not provided. [Ref 1]

### Source References
- [Ref 1] Hungary e-Invoicing: RTIR, energy sector mandates and preparing for EU-wide VAT digitalization — https://www.globalvatcompliance.com/globalvatnews/hungary-e-invoicing-requirements-2025/