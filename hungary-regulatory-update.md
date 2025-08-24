## Hungary E-Invoice Regulatory Update Summary (Generic Template)

### Format Requirements

*   **Mandatory Fields:**
    *   Supplier Name and Address
    *   Buyer Name and Address
    *   Invoice Number (Unique)
    *   Invoice Date
    *   Supply Date (if different from Invoice Date)
    *   VAT Identification Number (Supplier and Buyer, if applicable)
    *   Description of Goods or Services
    *   Quantity
    *   Unit Price
    *   Net Amount
    *   VAT Rate
    *   VAT Amount
    *   Gross Amount
    *   Currency Code
*   **Data Types and Structures:**
    *   Dates: YYYY-MM-DD (ISO 8601)
    *   Numbers: Decimal with specified precision (e.g., 2 decimal places for currency)
    *   Text: UTF-8 encoding, specific length restrictions may apply to certain fields
    *   VAT IDs: Specific format validation based on Hungarian VAT ID structure
*   **File Format Specifications:**
    *   XML (likely based on a specific schema, e.g., SAF-T or custom schema)
    *   Possible support for other formats (e.g., PDF/A-3 with embedded XML) - *Needs Verification*
    *   File Naming Convention: [Specific convention to be defined, e.g., based on invoice number and date]

### Validation Rules

*   **Validation Checks and Error Handling:**
    *   Mandatory fields must be present.
    *   Data types must conform to specified formats.
    *   VAT ID validation against a central database (if applicable).
    *   Mathematical accuracy (Net Amount * VAT Rate = VAT Amount; Net Amount + VAT Amount = Gross Amount).
    *   Schema validation (if XML).
*   **Consistency and Cross-Field Rules:**
    *   Currency code consistency throughout the invoice.
    *   Supply date must not be later than the invoice date.
    *   VAT rate must be valid for the specified goods/services and dates.
    *   Invoice number uniqueness check.

### Tax and VAT Compliance

*   **VAT Obligations:**
    *   Compliance with Hungarian VAT law.
    *   Accurate calculation and reporting of VAT.
    *   Use of correct VAT rates based on goods/services and customer location.
*   **Reporting Requirements:**
    *   Real-time or near real-time reporting of invoice data to the Hungarian Tax Authority (NAV).
    *   Data elements to be reported are defined by NAV.
    *   Reporting frequency (e.g., daily, weekly).
*   **Special Country-Specific Rules:**
    *   [Specific rules related to reverse charge mechanism, special VAT schemes, etc. - *Needs Verification*]
    *   [Rules regarding archiving and retention of e-invoices - *Needs Verification*]

### Submission and Reporting

*   **Filing Deadlines:**
    *   Real-time or near real-time reporting requirements. Specific deadlines to be confirmed.
*   **Submission Process and Timelines:**
    *   Submission via a designated online portal provided by NAV.
    *   Use of specific communication protocols (e.g., API).
    *   Confirmation of successful submission and error handling procedures.

### Regulatory Updates

*   **Changes Compared to Previous Versions:**
    *   [List of changes compared to the previous version of the e-invoicing regulation. - *Needs Verification*]
*   **Any Newly Introduced Compliance Measures:**
    *   [Description of any new compliance measures, such as new data elements, validation rules, or reporting requirements. - *Needs Verification*]