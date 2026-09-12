# Accounts Payable

## 📘 Overview

Accounts Payable (AP) manages the financial transactions and outstanding liabilities related to vendors.

For Nikhil Manufacturing Pvt. Ltd., AP activities include vendor master data, invoice processing, payment processing and vendor account clearing.

---

## 🏢 Company Details

| Field | Details |
|---|---|
| **Company** | Nikhil Manufacturing Pvt. Ltd. |
| **Company Code** | NM01 |
| **Country** | India |
| **Currency** | INR |

---

## 🔄 Procure-to-Pay Finance Flow

**Purchase Requisition → Purchase Order → Goods Receipt → Invoice Receipt → Vendor Payment**

The Accounts Payable process mainly handles the financial impact of the invoice and payment stages.

---

## 👤 Vendor / Business Partner

In SAP S/4HANA, vendors are managed using the **Business Partner** approach.

Vendor-related information may include:

- Vendor name
- Address
- Bank details
- Payment terms
- Reconciliation account
- Tax information

---

## 🧾 Vendor Invoice Processing

When a vendor invoice is received, the invoice is recorded against the appropriate expense, inventory or other relevant account.

### Example

Vendor supplies raw materials worth INR 50,000.

Accounting impact:

**Debit:** Inventory / Raw Material – INR 50,000  
**Credit:** Accounts Payable – INR 50,000

This creates an outstanding liability for the vendor.

---

## 💰 Vendor Payment

When the invoice becomes due, the company processes the payment.

Example:

**Debit:** Accounts Payable – INR 50,000  
**Credit:** Bank – INR 50,000

The vendor open item is then cleared against the payment.

---

## 🔁 Vendor Clearing

Vendor clearing matches an outstanding vendor invoice with its corresponding payment or credit transaction.

Example:

**Vendor Invoice → Open Item → Payment → Clearing**

---

## 📋 Common AP Activities

- Create and maintain vendor / Business Partner data
- Process vendor invoices
- Review vendor open items
- Process vendor payments
- Clear vendor open items
- Handle vendor credit memos
- Review vendor account balances
- Support month-end closing activities

---

## 📚 Important SAP Concepts

- Accounts Payable
- Business Partner
- Vendor
- Vendor Invoice
- Vendor Credit Memo
- Payment Terms
- Reconciliation Account
- Open Item Management
- Vendor Clearing
- Outgoing Payment

---

## 🎯 Learning Objective

This section demonstrates understanding of the basic Accounts Payable process and how vendor transactions flow into the General Ledger.

---

## 📝 Important Note

This is a fictional SAP FICO / S/4HANA Finance learning and simulation project created for educational and portfolio purposes.
