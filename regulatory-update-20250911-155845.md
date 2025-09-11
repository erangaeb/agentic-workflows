## Topic
- e-invoice regulatory updates poland

## Document Metadata
- Jurisdiction/scope: Poland [Ref 1].
- Publishing authority: Ministry of Finance and Economy [Ref 1], Ministry of Finance [Ref 3][Ref 5][Ref 6].
- Version/document date: The latest draft regulation on KSeF is undergoing public consultations and inter-ministerial agreements [Ref 1].
- Effective/compliance dates (incl. grace periods):
    - Mandatory KSeF implementation for Polish VAT taxpayers: February 2026 [Ref 1].
    - Full transition to KSeF 2.0: February 1, 2026 [Ref 4][Ref 6].
    - KSeF 1.0 test environment shut down: September 1, 2025 [Ref 4].
    - KSeF 2.0 test environment launch: September 30, 2025 [Ref 4][Ref 6].
    - KSeF 2.0 pre-production environment availability: October 15, 2025 [Ref 4].
    - New permissions and certificate downloads for KSeF 2.0 via MCU: From November 1, 2025 [Ref 6].
    - KSeF 1.0 production environment end: Late January 2026 [Ref 4].
    - KSeF 1.0 available until technical break: January 26-31, 2026 [Ref 6].

## Requirements / Specifications
- Formats: Structured XML invoices [Ref 5].
- Data structure: Uniform data structure defined by the Ministry of Finance [Ref 5].
- Invoice structure: New invoice structure FA3 for KSeF 2.0 [Ref 6].
- Data fields: Essential transaction details such as seller and buyer information, transaction dates, item descriptions, VAT rates, and totals [Ref 5].
- Verification code: Invoices outside the KSeF system must include a verification code, often a QR code [Ref 5].
- Visualization: While the XML file is the official document, accounting systems can generate a readable table-like preview or a PDF visualization for informational purposes [Ref 5].

## Validation / Business Rules
- Invoice correction:
    - Incorrect NIP (Tax Identification Number) on an invoice should be corrected to zero and the invoice reissued with the correct NIP [Ref 3].
    - Other errors on an invoice should be corrected through an invoice correction [Ref 3].
    - There will be no corrective notes in KSeF [Ref 3].
- System assignment: The system assigns a unique KSeF identification number and timestamp upon submission, marking the invoice as officially issued and delivered [Ref 5].

## Tax & VAT Compliance
- CTC/RTIR/e-reporting obligations: Mandatory invoicing will be conducted through the National e-Invoice System (KSeF) [Ref 1].
- Platforms/portals named: National e-Invoice System (KSeF) [Ref 1].

## Submission & Interfaces
- Channels/API endpoints: KSeF 2.0 features an improved API for better integration [Ref 6].
- Authentication: The new regulation will cover authentication methods [Ref 1]. New permissions and certificate downloads for KSeF 2.0 are available via MCU from November 1, 2025 [Ref 6]. The KSeF 2.0 test environment allows checking authentication and access management [Ref 6].
- Integration: Integration with the KSeF 2.0 test environment is required [Ref 6]. Documentation for KSeF 2.0 integration is available online [Ref 6]. The Ministry provides documentation, code examples, and training [Ref 6].

## Changes vs. Previous
- KSeF 1.0 vs KSeF 2.0:
    - KSeF 1.0 and KSeF 2.0 APIs are not compatible [Ref 6].
    - Only invoices and ownership rights migrate from KSeF 1.0 to KSeF 2.0 [Ref 6].
    - KSeF 1.0 production version will not be further developed [Ref 6].
    - New functionalities were added to KSeF 1.0 after consultations [Ref 6].
    - KSeF 2.0 introduces a new invoice structure (FA3) and an improved API [Ref 6].

## Implementation Impact
- Required system/process changes: Businesses need to build capacity for invoice generation and transmission [Ref 7]. Systems must be adapted to capture new mandatory data fields [Ref 7].
- Integration impacts: Companies need to integrate with the KSeF 2.0 test environment [Ref 6].
- Risks/edge cases: Businesses should plan for offline scenarios in case of system downtime [Ref 7]. Delaying preparation can lead to compliance risks and costs [Ref 7]. Compliance risks include discrepancies and VAT deduction issues [Ref 7].
- Testing: The KSeF 2.0 test environment allows companies to verify system compliance and optimize invoicing processes [Ref 6].
- Organizational impact: E-invoicing readiness involves accounting, IT, and logistics departments [Ref 7].
- Controls: Businesses should strengthen controls and validation processes for compliance [Ref 7]. Implement invoice checks and identifier systems [Ref 7]. Validate employee expenses and ensure data alignment [Ref 7].

## Gaps/Unknowns
- Specific details of the new invoice structure FA3 are not provided [Ref 6].
- Detailed technical specifications for the KSeF 2.0 API (e.g., specific endpoints, data types, request/response formats) are not included in the sources, though documentation is stated to be available online [Ref 6].
- Specific authentication methods beyond "permissions and certificates" are not detailed [Ref 1][Ref 6].
- Error codes and messages for KSeF 2.0 are not specified [Ref 6].

### Source References
- [Ref 1] How to Use KSeF from February 2026: Permissions, Authentication, Invoices, Technical Requirements Explained — https://www.vatupdate.com/2025/09/10/how-to-use-ksef-from-february-2026-permissions-authentication-invoices-technical-requirements-explained/
- [Ref 2] Interactive Webinar: Navigating KSeF Implementation Challenges and Solutions for 2026 — https://www.vatupdate.com/2025/09/10/interactive-webinar-navigating-ksef-implementation-challenges-and-solutions-for-2026/
- [Ref 3] Ministry of Finance Explains How to Correct Errors in KSeF Invoices — https://www.vatupdate.com/2025/09/10/ministry-of-finance-explains-how-to-correct-errors-in-ksef-invoices/
- [Ref 4] Poland Transitions to KSeF 2.0: Key Dates and Roadmap for E-Invoicing Shift — https://www.vatupdate.com/2025/09/10/poland-transitions-to-ksef-2-0-key-dates-and-roadmap-for-e-invoicing-shift/
- [Ref 5] Structured VAT Invoice in 2026: Visualization, Data Scope, and QR Codes Explained — https://www.vatupdate.com/2025/09/10/structured-vat-invoice-in-2026-visualization-data-scope-and-qr-codes-explained/
- [Ref 6] Transition to KSeF 2.0: New Features, Testing Environment, and Integration Guidelines — https://www.vatupdate.com/2025/09/10/transition-to-ksef-2-0-new-features-testing-environment-and-integration-guidelines/
- [Ref 7] Urgent Steps for Businesses: Preparing for Poland’s 2026 B2B eInvoicing Mandate — https://www.vatupdate.com/2025/09/10/urgent-steps-for-businesses-preparing-for-polands-2026-b2b-einvoicing-mandate/