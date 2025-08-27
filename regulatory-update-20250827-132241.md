## Document Metadata
- Jurisdiction / scope: Various (Romania, Netherlands, Pakistan, Côte d’Ivoire, Nigeria, Finland, Singapore, Cyprus, Hungary, Italy, Paraguay, Uruguay, Bulgaria, Türkiye, Lithuania, Greece, Croatia, Cambodia, Malaysia, Belgium, Hungary, South Africa, North Macedonia, France, Vanuatu, EU). [Ref 1] [Ref 2] [Ref 3] [Ref 4] [Ref 5] [Ref 6] [Ref 7] [Ref 8] [Ref 9] [Ref 10] [Ref 11] [Ref 12] [Ref 13] [Ref 14] [Ref 15] [Ref 16] [Ref 17] [Ref 18] [Ref 19] [Ref 20] [Ref 21] [Ref 22] [Ref 23] [Ref 24]
- Publishing authority: Federal Board of Revenue (FBR) of Pakistan [Ref 3], Nigerian government [Ref 5], Public Revenue Office of North Macedonia [Ref 23], France's tax authority [Ref 24], Romania's ANAF [Ref 12].
- Version / document date: August 2025 (various dates). [Ref 1] [Ref 2] [Ref 3] [Ref 4] [Ref 5] [Ref 6] [Ref 7] [Ref 8] [Ref 9] [Ref 10] [Ref 11] [Ref 12] [Ref 13] [Ref 14] [Ref 15] [Ref 16] [Ref 17] [Ref 18] [Ref 19] [Ref 20] [Ref 21] [Ref 22] [Ref 23] [Ref 24]
- Effective / compliance dates (incl. grace periods):
  - **Romania:** B2B e-invoicing mandatory since January 1, 2024 for Romanian-established businesses and non-established VAT-registered taxpayers supplying goods/services with place of supply in Romania [Ref 12]. B2C e-invoicing mandatory since January 1, 2025 [Ref 12]. B2G mandatory since 2022 [Ref 12]. Soft-landing period ended March 31, 2025 [Ref 12]. B2C penalty regime applies from July 1, 2025 [Ref 12]. Associations, foundations, farmers exempt until June 30, 2025 [Ref 12].
  - **Pakistan:** Phased rollout from September to December 2025 [Ref 3]: September 1, 2025 for public companies, importers, and companies with turnover over PKR1bn [Ref 3]; October 1, 2025 for companies and individuals/associations with turnover over PKR100m [Ref 3]; November 1, 2025 for companies with turnover below PKR100m [Ref 3]; December 1, 2025 for all other registered persons [Ref 3].
  - **Côte d’Ivoire:** Full compliance by September 1, 2025 [Ref 4]. Physical invoices allowed until September 2, 2025 [Ref 4].
  - **Nigeria:** Extended to November 2025 for large taxpayers [Ref 5].
  - **Singapore:** Mandatory from November 1, 2025, for newly incorporated voluntary GST registrants and from April 1, 2026, for all new voluntary registrants [Ref 6].
  - **Hungary:** Effective July 1, 2025, Hungary mandates e-invoicing for B2B transactions involving electricity and natural gas traders [Ref 6].
  - **Greece:** Mandatory B2B e-invoicing set to start on July 1, 2025, but the Greek government has yet to finalize the implementation timeline [Ref 6].
  - **Croatia:** As of January 1, 2026, mandatory e-invoicing will apply to all domestic B2B transactions for VAT-registered businesses [Ref 6]. Non-VAT registered businesses must accept e-invoices from this date and will be required to issue them starting January 1, 2027 [Ref 6].
  - **Belgium:** Mandatory B2B e-invoicing for all VAT-registered entities from January 1, 2026 [Ref 11]. Near-real-time e-reporting set for 2028 [Ref 11].
  - **North Macedonia:** Pilot testing starts January 1, 2026, with selected businesses [Ref 23]. Mandatory compliance for all taxpayers begins in Q3 2026 [Ref 23].
  - **EU (ViDA):** Mandatory E-Invoicing for intra-EU B2B and B2G transactions starting 1 July 2030 [Ref 7].
  - **Vanuatu:** Rollout of VSMS planned between August 2025 and January 2026 [Ref 9].
  - **Hungary:** Stricter validation rules in NAV Online Invoice System from September 2025 [Ref 10]. New rules can be tested from September 1, 2025 [Ref 10].

## Format Requirements
- **Romania:** RO_CIUS (UBL/CII), aligned with EN 16931 [Ref 12].
- **EU (ViDA):** Structured e-invoices must follow a common EU format (e.g., EN16931) [Ref 7].

## Validation Rules
- **Hungary:** Stricter validation rules for the NAV Online Invoice system from September 2025 [Ref 10]. New WARN messages introduced, some existing WARN messages removed, and some WARN messages converted to ERROR messages [Ref 10]. NAV has specified which warnings will become blocking errors, such as issues with performance period dates, missing elements in XML, and incorrect tax markings [Ref 10].

## Tax & VAT Compliance
- **Romania:** Buyers are increasingly refusing invoices that are not issued via RO e-Factura, as these may jeopardise VAT deduction [Ref 12].

## Submission & Reporting
- **Romania:** Submission deadline is 5 calendar days from issuance [Ref 12]. Invoices available for buyer retrieval for 60 days [Ref 12].
- **EU (ViDA):** 10-day issuance rule: e-invoices must be issued within 10 days of supply or payment [Ref 7]. Customer reporting: Customers may also need to report received invoices within 5 days, unless waived [Ref 7].

## Regulatory Changes (Diff vs. previous)
- **Romania:** From adoption to enforcement [Ref 12].
- **Hungary:** Changes necessitate a review of invoicing processes [Ref 10].

## Implementation Impact
- **Romania:** Companies need pre-validation, reject-handling loops, and fallback PDFs to avoid cash collection delays [Ref 12].
- **Pakistan:** Companies are advised to assess their categories based on turnover, upgrade their systems for FBR integration, utilize the testing phase to resolve issues, and train staff on new processes to ensure a smooth transition before the deadlines [Ref 3].
- **Côte d’Ivoire:** Companies must choose their issuance channels (API, web portal, mobile app, or electronic payment terminals) and ensure compliance through proper data mapping, testing, and stakeholder training to avoid common pitfalls [Ref 4].
- **North Macedonia:** Companies can connect via APIs for integration with existing systems [Ref 23]. Businesses should prepare for the implementation timeline and adapt their invoicing systems [Ref 23].
- **Hungary:** Changes necessitate a review of invoicing processes [Ref 10].

## Gaps/Unknowns
- Specifics of the interoperability framework in South Africa [Ref 8].
- Details of the penalties for non-compliance in Nigeria [Ref 5].
- Specifics of the e-invoicing frameworks and technical requirements in South Africa [Ref 8].
- Implementation timelines and requirements to connect to approved service providers in South Africa [Ref 8].
- Details on how the Greek government will finalize the implementation timeline for mandatory B2B e-invoicing [Ref 6].
- Specifics of the "expanded scope" expected in 2025 for Greece's B2G e-invoicing [Ref 6].
- Details of the new standards that public entities in France need to comply with [Ref 24].

### Source References
[Ref 1] Romania’s SAF-T rollout: Lessons from a challenging transition — https://www.vatupdate.com/2025/08/27/romanias-saf-t-rollout-lessons-from-a-challenging-transition/
[Ref 2] E-invoicing obligation in the Netherlands: where does The Hague really stand? — https://www.vatupdate.com/2025/08/27/e-invoicing-obligation-in-the-netherlands-where-does-the-hague-really-stand/
[Ref 3] Pakistan’s New Electronic Invoicing Timeline: Phased Rollout from September 2025 — https://www.vatupdate.com/2025/08/27/pakistan-announces-new-deadlines-for-mandatory-electronic-invoicing-starting-september-2025/
[Ref 4] Côte d’Ivoire’s 2025 E-Invoicing Reform: A Guide to FNE and RNE Implementation — https://www.vatupdate.com/2025/08/27/cote-divoires-2025-e-invoicing-reform-a-guide-to-fne-and-rne-implementation/
[Ref 5] Nigeria Extends E-Invoicing Compliance Deadline for Large Nigerian Taxpayers to November 2025 — https://www.vatupdate.com/2025/08/27/nigeria-extends-e-invoicing-compliance-deadline-for-large-nigerian-taxpayers-to-november-2025/
[Ref 6] E–invoicing Developments Tracker — https://www.vatupdate.com/2025/08/27/e-invoicing-developments-tracker/
[Ref 7] All you need to know about VAT in the Digital Age (ViDA) — https://www.vatupdate.com/2025/08/27/all-you-need-to-know-about-vat-in-the-digital-age-vida/
[Ref 8] South Africa Proposes New Regulations for E-Invoicing and E-Reporting in Draft Bill — https://www.vatupdate.com/2025/08/27/south-africa-proposes-new-regulations-for-e-invoicing-and-e-reporting-in-draft-bill/
[Ref 9] Vanuatu’s E-Invoicing Revolutionizes Tax Compliance, Tackles Grey Economy with Digital Precision — https://www.vatupdate.com/2025/08/27/vanuatus-e-invoicing-revolutionizes-tax-compliance-tackles-grey-economy-with-digital-precision/
[Ref 10] Stricter Validation Rules in NAV Online Invoice System from September 2025 — https://www.vatupdate.com/2025/08/27/stricter-validation-rules-in-nav-online-invoice-system-from-september-2025/
[Ref 11] Webinar: Ready or Not? Belgium’s e-Invoicing Mandate is Coming – Sept 4 — https://www.vatupdate.com/2025/08/27/webinar-eezi-ready-or-not-belgiums-e-invoicing-mandate-is-coming-sept-4/
[Ref 12] Romania’s e-invoicing reform: What matters for businesses in 2025–2026 — https://www.globalvatcompliance.com/globalvatnews/romania-e-invoicing-reform-2025/
[Ref 13] North Macedonia Mandates E-Invoicing with e-Faktura Project for Tax Compliance by 2026 — https://www.vatupdate.com/2025/08/26/north-macedonia-mandates-e-invoicing-with-e-faktura-project-for-tax-compliance-by-2026/
[Ref 14] Chorus Pro Confirmed as Official E-Invoicing Platform for French Public Sector Post-2026 — https://www.vatupdate.com/2025/08/26/chorus-pro-confirmed-as-official-e-invoicing-platform-for-french-public-sector-post-2026/