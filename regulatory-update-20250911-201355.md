## Topic
- Sweden e-invoicing updates.

## Document Metadata
- Jurisdiction/scope: Sweden [Ref 1][Ref 2][Ref 3].
- Publishing authority: Swedish Agency for Digital Government (DIGG) [Ref 1][Ref 2].
- Version/document date: The mandate for B2B e-invoicing was proposed in 2023 [Ref 1]. The current B2G mandate has been in effect since April 1, 2019 [Ref 1][Ref 2][Ref 3].
- Effective/compliance dates (incl. grace periods):
    - B2G e-invoicing mandate: April 1, 2019 [Ref 1][Ref 2][Ref 3].
    - Proposed B2B e-invoicing mandate: Expected to be implemented in 2026 [Ref 1].

## Requirements / Specifications
- Formats:
    - For B2G transactions, the primary format is Peppol BIS Billing 3.0 [Ref 1][Ref 2][Ref 3].
    - Other formats like Svefaktura 1.0 are also accepted for B2G, but Peppol BIS Billing 3.0 is preferred [Ref 2].
    - The proposed B2B mandate is expected to align with the Peppol network and Peppol BIS Billing 3.0 [Ref 1].
- Standard: The European standard EN 16931 is the basis for e-invoicing in Sweden [Ref 1][Ref 2]. Peppol BIS Billing 3.0 is an implementation of this standard [Ref 1].

## Tax & VAT Compliance
- CTC/RTIR/e-reporting obligations:
    - Sweden currently has a post-audit model for VAT reporting, meaning there is no real-time or continuous transaction control (CTC) system for e-invoicing [Ref 1].
    - The proposed B2B e-invoicing mandate aims to combat VAT fraud and improve tax compliance [Ref 1]. It is expected to be a clearance model, requiring invoices to be sent through a central platform or network (like Peppol) for validation before being sent to the recipient [Ref 1].
- Platforms/portals named: The Peppol network is the primary infrastructure for e-invoicing in Sweden for both B2G and the proposed B2B mandate [Ref 1][Ref 2][Ref 3].

## Submission & Interfaces
- Channels/API endpoints: E-invoices are exchanged via the Peppol network [Ref 1][Ref 2][Ref 3]. This requires businesses to connect to the Peppol network through an Access Point [Ref 1].
- Mandate scope:
    - **B2G (Business-to-Government)**: Mandatory for all public sector entities and their suppliers since April 1, 2019 [Ref 1][Ref 2][Ref 3]. This applies to all purchases made by public sector organizations [Ref 2].
    - **B2B (Business-to-Business)**: A proposal for a mandatory B2B e-invoicing system was submitted to the Swedish Ministry of Finance in 2023 [Ref 1]. This proposal suggests a clearance model using the Peppol network [Ref 1].
    - **B2C (Business-to-Consumer)**: No current or proposed mandate for B2C e-invoicing [Ref 1].

## Changes vs. Previous
- **New B2B Mandate Proposal**: The most significant update is the proposal for a mandatory B2B e-invoicing system [Ref 1].
    - This proposal, submitted by the Swedish Agency for Digital Government (DIGG) in 2023, aims to combat VAT fraud and align with EU trends [Ref 1].
    - It suggests a clearance model, where invoices are validated via the Peppol network before reaching the recipient [Ref 1].
    - The expected implementation date for this B2B mandate is 2026 [Ref 1].
- **Shift from Post-Audit to Clearance**: If the B2B proposal is adopted, Sweden would transition from a post-audit VAT reporting model to a clearance model for B2B transactions, which is a significant change [Ref 1].

## Implementation Impact
- **For Businesses**:
    - Businesses currently only dealing with B2G transactions are already compliant if using Peppol [Ref 1].
    - Businesses engaged in B2B transactions will need to adapt their systems to send and receive e-invoices via the Peppol network if the proposed mandate is enacted [Ref 1]. This includes connecting to a Peppol Access Point [Ref 1].
    - The shift to a clearance model for B2B will require real-time or near real-time processing of invoices for validation [Ref 1].
- **For Public Sector**: Public sector entities are already required to receive e-invoices via Peppol [Ref 2].

## Gaps/Unknowns
- Specific details on the B2B mandate's implementation, such as exact technical specifications beyond Peppol BIS Billing 3.0, grace periods, or penalties for non-compliance, are not yet available as it is still a proposal [Ref 1].
- The exact scope of the B2B mandate (e.g., thresholds, specific industries) is not detailed in the provided sources [Ref 1].

### Source References
- [Ref 1] Sweden: Mandatory B2B e-invoicing proposed for 2026 — https://www.vatcalc.com/news/sweden-mandatory-b2b-e-invoicing-proposed-for-2026/
- [Ref 2] E-invoicing in Sweden: What you need to know — https://www.pagero.com/blog/e-invoicing-in-sweden-what-you-need-to-know/
- [Ref 3] E-invoicing in Sweden: The Ultimate Guide — https://www.storecove.com/blog/e-invoicing-sweden/