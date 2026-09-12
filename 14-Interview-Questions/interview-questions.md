# SAP FICO & S/4HANA Finance Interview Questions

## 📌 Purpose

This document contains important SAP FICO and S/4HANA Finance interview questions for entry-level and end-user roles.

The questions focus on SAP Finance concepts, business processes, accounting knowledge and practical scenarios.

---

# 1. SAP FICO Fundamentals

### Q1. What is SAP FICO?

**Answer:**

SAP FICO stands for Financial Accounting (FI) and Controlling (CO).

- **FI** is used for external financial accounting and reporting.
- **CO** is used for internal management accounting, cost controlling and analysis.

---

### Q2. What is SAP S/4HANA Finance?

**Answer:**

SAP S/4HANA Finance is the finance solution within SAP S/4HANA. It provides integrated financial accounting, controlling, reporting and analytics capabilities using the SAP HANA database.

---

### Q3. What is the difference between FI and CO?

**Answer:**

FI focuses mainly on external financial reporting, while CO focuses on internal management accounting and cost control.

**FI examples:**
- General Ledger
- Accounts Payable
- Accounts Receivable
- Asset Accounting

**CO examples:**
- Cost Center Accounting
- Internal Orders
- Cost Allocation

---

# 2. Enterprise Structure

### Q4. What is a Company Code?

**Answer:**

A company code is the organizational unit in SAP for which a complete set of financial statements can be prepared.

---

### Q5. What is a Controlling Area?

**Answer:**

A controlling area is an organizational unit used for management accounting and internal cost controlling.

---

### Q6. What is a Plant?

**Answer:**

A plant represents a location where materials are produced, stored or handled.

---

### Q7. What is a Storage Location?

**Answer:**

A storage location is a subdivision within a plant where inventory is managed.

---

# 3. General Ledger

### Q8. What is a General Ledger?

**Answer:**

The General Ledger contains the company's main accounting records and is used to prepare financial statements.

---

### Q9. What is a Chart of Accounts?

**Answer:**

A Chart of Accounts is a structured list of G/L accounts used by an organization for recording financial transactions.

---

### Q10. What is a G/L account?

**Answer:**

A G/L account is used to classify and record business transactions under specific accounting categories such as expenses, revenue, assets and liabilities.

---

### Q11. What is a document type?

**Answer:**

A document type identifies and classifies accounting documents. It can control characteristics such as the number range and permitted account types.

---

### Q12. What is a posting key?

**Answer:**

A posting key controls important characteristics of an accounting line item, including whether it is a debit or credit and which account type can be posted.

---

# 4. Accounts Payable

### Q13. What is Accounts Payable?

**Answer:**

Accounts Payable manages amounts that a company owes to its vendors.

---

### Q14. What is the basic vendor invoice process?

**Answer:**

A typical process is:

**Purchase → Goods Receipt → Invoice Receipt → Vendor Payment**

The exact steps depend on the business process and SAP configuration.

---

### Q15. What happens when a vendor invoice is posted?

**Answer:**

An accounting document is generated. The vendor liability is recorded and the relevant expense, inventory or other account is updated according to the transaction.

---

### Q16. What is vendor clearing?

**Answer:**

Vendor clearing is the process of matching and clearing open vendor items, such as invoices and payments.

---

# 5. Accounts Receivable

### Q17. What is Accounts Receivable?

**Answer:**

Accounts Receivable manages amounts that customers owe to the company.

---

### Q18. What is the basic customer collection process?

**Answer:**

A typical process is:

**Sales → Billing → Customer Receivable → Incoming Payment → Clearing**

---

### Q19. What is customer clearing?

**Answer:**

Customer clearing is the process of matching incoming payments with outstanding customer invoices or other open items.

---

# 6. P2P, O2C and R2R

### Q20. What is P2P?

**Answer:**

P2P stands for Procure-to-Pay. It covers the process from purchasing goods or services through vendor payment.

**Typical flow:**

**Purchase Requisition → Purchase Order → Goods Receipt → Invoice Receipt → Payment**

---

### Q21. What is O2C?

**Answer:**

O2C stands for Order-to-Cash. It covers the process from receiving a customer order through billing and collection.

**Typical flow:**

**Sales Order → Delivery → Billing → Customer Payment**

---

### Q22. What is R2R?

**Answer:**

R2R stands for Record-to-Report. It covers accounting activities from recording business transactions through reconciliation, period-end closing and financial reporting.

---

# 7. Asset Accounting

### Q23. What is Asset Accounting?

**Answer:**

Asset Accounting manages the financial information and transactions related to a company's fixed assets.

---

### Q24. What is depreciation?

**Answer:**

Depreciation is the systematic allocation of the depreciable value of a fixed asset over its useful life.

---

### Q25. What are common asset transactions?

**Answer:**

Common asset transactions include:

- Asset acquisition
- Depreciation
- Asset transfer
- Asset retirement
- Asset sale

---

# 8. Bank Accounting

### Q26. What is Bank Accounting?

**Answer:**

Bank Accounting manages bank-related financial transactions such as incoming payments, outgoing payments and bank reconciliation.

---

### Q27. What is bank reconciliation?

**Answer:**

Bank reconciliation is the process of comparing company accounting records with bank records and identifying or resolving differences.

---

# 9. Controlling

### Q28. What is a Cost Center?

**Answer:**

A cost center is an organizational unit used to collect, monitor and analyze costs associated with a particular area or responsibility.

---

### Q29. What is an Internal Order?

**Answer:**

An internal order is used to collect and monitor costs for a specific activity, event, project or temporary purpose.

---

### Q30. What is Cost Center Accounting?

**Answer:**

Cost Center Accounting helps organizations monitor and analyze costs incurred by different departments or areas of the business.

---

# 10. Practical Interview Scenarios

### Q31. A vendor invoice was posted to the wrong G/L account. What would you do?

**Answer:**

First, I would verify the accounting document and identify the incorrect G/L posting.

Depending on the situation and company process, I would either reverse the incorrect document and repost it correctly or use an appropriate correction process.

I would also verify the corrected posting and ensure the relevant open items are properly cleared.

---

### Q32. How would you handle an incorrect accounting document?

**Answer:**

I would first analyze the document and determine what is incorrect.

Then, based on the document status and business process, I would use the appropriate reversal or correction procedure. After correction, I would verify the accounting impact.

---

### Q33. What would you check before processing a vendor payment?

**Answer:**

I would check:

- Vendor account
- Open invoices
- Due dates
- Payment amount
- Payment terms
- Bank details according to company procedure
- Any payment blocks

---

### Q34. What would you check if a customer payment is not clearing an invoice?

**Answer:**

I would check:

- Customer account
- Open items
- Payment amount
- Reference information
- Assignment
- Currency
- Differences between payment and invoice

I would then determine the appropriate clearing or correction process according to company procedure.

---

### Q35. What happens during month-end closing?

**Answer:**

Month-end closing may include activities such as:

- Reviewing open items
- Account reconciliation
- Depreciation posting
- Accruals and adjustments
- Foreign currency valuation where applicable
- Cost allocations
- Reviewing financial postings
- Financial reporting

The exact activities depend on the organization's closing procedure.

---

# 11. S/4HANA Finance

### Q36. What is the Universal Journal?

**Answer:**

The Universal Journal is the central journal in SAP S/4HANA Finance that integrates financial accounting and controlling information in a common data structure.

---

### Q37. What is the significance of the Universal Journal?

**Answer:**

It provides an integrated source of financial and controlling information and reduces the need for separate data structures for many FI and CO postings.

---

### Q38. What is Business Partner in S/4HANA?

**Answer:**

Business Partner is the central master data concept used to manage customers and vendors in SAP S/4HANA.

---

# 12. End-User Interview Questions

### Q39. What is the role of an SAP Finance end user?

**Answer:**

An SAP Finance end user performs day-to-day business transactions in SAP according to defined business processes and company procedures.

Activities may include:

- Invoice processing
- Payment processing
- Customer receipt processing
- Accounting document verification
- Open item analysis
- Reconciliation support
- Master data-related activities
- Month-end closing support

---

### Q40. What would you do if you were unsure about a transaction?

**Answer:**

I would not process the transaction based on assumptions. I would first verify the business process, relevant documentation and company procedure. If necessary, I would consult the appropriate senior team member or process owner before posting.

---

# 🎯 Interview Preparation Tip

For an entry-level SAP Finance interview, focus on understanding **why a transaction is performed**, **which business process it belongs to**, and **what accounting impact it creates** rather than memorizing only transaction codes.

---

## 📝 Project Note

The questions and answers in this document are prepared for learning, practice and interview preparation based on the fictional **Nikhil Manufacturing Pvt. Ltd.** SAP FICO / S/4HANA Finance simulation project.
