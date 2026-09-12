# Business Scenario — Vendor Invoice

## 📘 Scenario Overview

Nikhil Manufacturing Pvt. Ltd. purchases raw materials from a vendor for its manufacturing operations.

The vendor supplies materials and sends an invoice to the company. The Finance team processes the invoice and records the vendor liability.

This is a fictional scenario created for SAP FICO / S/4HANA Finance practice.

---

## 🏢 Scenario Details

| Field | Details |
|---|---|
| **Company** | Nikhil Manufacturing Pvt. Ltd. |
| **Company Code** | NM01 |
| **Vendor** | ABC Raw Materials Pvt. Ltd. |
| **Material** | Raw Materials |
| **Invoice Amount** | INR 50,000 |
| **Currency** | INR |
| **Payment Terms** | 30 Days |

---

## 🔄 Business Process

**Purchase Order → Goods Receipt → Vendor Invoice → Invoice Verification → Accounts Payable → Vendor Payment**

---

## 1. Purchase Order

The Procurement team creates a Purchase Order for raw materials worth INR 50,000.

The PO contains:

- Vendor
- Material
- Quantity
- Price
- Delivery information
- Payment terms

---

## 2. Goods Receipt

The raw materials are received at the company's plant.

A Goods Receipt is recorded to confirm that the materials have been received.

For a stock-material scenario, the accounting impact can include:

**Debit:** Inventory – INR 50,000  
**Credit:** GR/IR Clearing – INR 50,000

The exact accounting impact depends on material valuation and system configuration.

---

## 3. Vendor Invoice

The vendor sends an invoice for INR 50,000.

The invoice is checked against the Purchase Order and Goods Receipt.

This is part of the three-way matching process:

**Purchase Order ↔ Goods Receipt ↔ Vendor Invoice**

---

## 4. Invoice Posting

After successful verification, the vendor invoice is posted.

A simplified accounting entry may be:

**Debit:** GR/IR Clearing – INR 50,000  
**Credit:** Accounts Payable – INR 50,000

This creates an outstanding liability for the vendor.

---

## 5. Vendor Open Item

The vendor invoice appears as an open item in Accounts Payable.

The Finance team can review:

- Vendor
- Invoice amount
- Posting date
- Due date
- Payment terms
- Open balance

---

## 6. Vendor Payment

After the payment due date is reached, the company processes the vendor payment.

Simplified accounting entry:

**Debit:** Accounts Payable – INR 50,000  
**Credit:** Bank – INR 50,000

The vendor invoice can then be cleared against the payment.

---

## 📊 Accounting Summary

| Transaction | Debit | Credit |
|---|---|---|
| Goods Receipt | Inventory | GR/IR Clearing |
| Vendor Invoice | GR/IR Clearing | Accounts Payable |
| Vendor Payment | Accounts Payable | Bank |

---

## 🔗 SAP Integration

This scenario demonstrates integration between:

**MM → FI**

Procurement and goods receipt activities can create financial impacts in Financial Accounting.

The process also involves:

**Vendor / Business Partner → Accounts Payable → General Ledger → Bank**

---

## 📚 Key Concepts Demonstrated

- Purchase Order
- Goods Receipt
- Vendor Invoice
- Three-Way Matching
- GR/IR Clearing
- Accounts Payable
- Vendor Open Item
- Vendor Payment
- Vendor Clearing
- MM-FI Integration

---

## 🎯 Interview Explanation

**Question:** Explain how you would process a vendor invoice in SAP.

**Answer:**

A vendor invoice is received after the goods or services are provided. I would first ensure that the invoice is matched with the relevant purchasing documents, such as the Purchase Order and Goods Receipt. After verification, the invoice is posted to Accounts Payable, creating a vendor open item. When the invoice becomes due, the payment is processed and the vendor item is cleared.

---

## 📝 Important Note

This is a fictional SAP FICO / S/4HANA Finance practice scenario created for educational and portfolio purposes.
