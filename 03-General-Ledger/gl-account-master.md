# G/L Account Master

## 📘 Overview

The G/L Account Master contains the basic information and control settings used for individual General Ledger accounts.

In SAP S/4HANA Finance, G/L accounts are used to record business transactions and support financial reporting.

This document defines sample G/L accounts for the fictional company Nikhil Manufacturing Pvt. Ltd.

---

## 🏢 Company Details

| Field | Details |
|---|---|
| **Company** | Nikhil Manufacturing Pvt. Ltd. |
| **Company Code** | NM01 |
| **Chart of Accounts** | NMCA |
| **Country** | India |
| **Currency** | INR |

---

## 📊 Sample G/L Account Master

| G/L Account | Account Name | Account Type | Category |
|---:|---|---|---|
| 100000 | Cash | Balance Sheet | Asset |
| 110000 | Bank Account | Balance Sheet | Asset |
| 120000 | Accounts Receivable | Balance Sheet | Asset |
| 130000 | Inventory | Balance Sheet | Asset |
| 140000 | Machinery | Balance Sheet | Asset |
| 200000 | Accounts Payable | Balance Sheet | Liability |
| 210000 | Accrued Expenses | Balance Sheet | Liability |
| 300000 | Share Capital | Balance Sheet | Equity |
| 400000 | Sales Revenue | Profit & Loss | Revenue |
| 500000 | Raw Material Consumption | Profit & Loss | Expense |
| 510000 | Salaries and Wages | Profit & Loss | Expense |
| 520000 | Electricity Expense | Profit & Loss | Expense |
| 530000 | Depreciation Expense | Profit & Loss | Expense |

---

## 🔑 Important Master Data Concepts

### G/L Account Number

A unique number assigned to identify a G/L account within the Chart of Accounts.

### G/L Account Name

The description used to identify the purpose of the account.

### Account Type

The account type determines how the G/L account is used in SAP.

Examples include:

- Balance Sheet accounts
- Profit & Loss accounts

### Account Group

G/L accounts can be organized into account groups based on their nature and purpose.

Account groups help control the structure and presentation of G/L accounts.

### Reconciliation Account

A reconciliation account connects subledger accounting, such as Accounts Payable or Accounts Receivable, with the General Ledger.

For example:

**Vendor Subledger → Accounts Payable Reconciliation Account → General Ledger**

---

## 🧾 Example: Expense Posting

Suppose the company receives an electricity bill of INR 10,000.

The accounting entry would be:

**Debit:** Electricity Expense – INR 10,000  
**Credit:** Accounts Payable – INR 10,000

The vendor liability can later be cleared through a payment transaction.

---

## 🔄 G/L Account Usage

G/L accounts are used throughout the major finance processes:

- General Ledger
- Accounts Payable
- Accounts Receivable
- Asset Accounting
- Bank Accounting
- Controlling
- Month-End Closing
- Financial Reporting

---

## 🎯 Learning Objective

This section helps demonstrate understanding of:

- G/L account structure
- Account classification
- Balance Sheet and Profit & Loss accounts
- Reconciliation accounts
- Basic accounting entries
- G/L master data concepts

---

## 📝 Important Note

The G/L accounts and examples in this document are fictional and created solely for SAP FICO / S/4HANA Finance learning and simulation purposes.
