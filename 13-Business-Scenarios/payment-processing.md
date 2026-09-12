# Business Scenario — Payment Processing

## 📘 Scenario Overview

Payment processing involves recording and clearing financial payments made by customers and payments made by the company to vendors.

For Nikhil Manufacturing Pvt. Ltd., payment processing is an important part of both Accounts Receivable and Accounts Payable.

This is a fictional scenario created for SAP FICO / S/4HANA Finance practice.

---

## 🏢 Scenario Details

| Field | Details |
|---|---|
| **Company** | Nikhil Manufacturing Pvt. Ltd. |
| **Company Code** | NM01 |
| **Currency** | INR |
| **Customer Payment** | INR 75,000 |
| **Vendor Payment** | INR 50,000 |

---

## 1. Incoming Customer Payment

The company receives INR 75,000 from a customer against an outstanding invoice.

### Accounting Entry

**Debit:** Bank – INR 75,000  
**Credit:** Accounts Receivable – INR 75,000

The customer invoice can then be cleared against the incoming payment.

---

## 2. Customer Clearing

The Finance team identifies the relevant customer open item and matches it with the incoming payment.

Process:

**Customer Invoice → Open Item → Incoming Payment → Clearing**

After successful clearing, the invoice no longer remains outstanding.

---

## 3. Outgoing Vendor Payment

The company pays INR 50,000 to a vendor against an outstanding invoice.

### Accounting Entry

**Debit:** Accounts Payable – INR 50,000  
**Credit:** Bank – INR 50,000

The vendor invoice can then be cleared against the payment.

---

## 4. Vendor Clearing

The Finance team identifies the relevant vendor open item and matches it with the outgoing payment.

Process:

**Vendor Invoice → Open Item → Outgoing Payment → Clearing**

After successful clearing, the vendor invoice no longer remains outstanding.

---

## 📊 Payment Summary

| Transaction | Debit | Credit |
|---|---|---|
| Customer Payment | Bank | Accounts Receivable |
| Vendor Payment | Accounts Payable | Bank |

---

## 🔄 Payment Processing Flow

### Customer
