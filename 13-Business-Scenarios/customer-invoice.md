# Business Scenario — Customer Invoice

## 📘 Scenario Overview

Nikhil Manufacturing Pvt. Ltd. sells finished products to a business customer.

After the goods are delivered, the customer is billed. The Finance team records the customer receivable and recognizes the sales revenue.

This is a fictional scenario created for SAP FICO / S/4HANA Finance practice.

---

## 🏢 Scenario Details

| Field | Details |
|---|---|
| **Company** | Nikhil Manufacturing Pvt. Ltd. |
| **Company Code** | NM01 |
| **Customer** | XYZ Industrial Solutions Pvt. Ltd. |
| **Material** | Finished Goods |
| **Invoice Amount** | INR 75,000 |
| **Currency** | INR |
| **Payment Terms** | 30 Days |

---

## 🔄 Business Process

**Sales Order → Delivery → Goods Issue → Billing → Accounts Receivable → Customer Payment**

---

## 1. Sales Order

The Sales team receives an order from the customer for finished products worth INR 75,000.

The Sales Order contains information such as:

- Customer
- Material
- Quantity
- Price
- Delivery information
- Payment terms

---

## 2. Delivery

The finished goods are prepared and delivered to the customer.

The delivery document records information related to the shipment.

---

## 3. Goods Issue

When the goods leave the company's inventory, a Goods Issue is recorded.

For a stock-material scenario, the accounting impact can include:

**Debit:** Cost of Goods Sold  
**Credit:** Inventory

The exact accounting impact depends on material valuation and system configuration.

---

## 4. Customer Billing

After delivery, a billing document is created for INR 75,000.

A simplified accounting impact is:

**Debit:** Accounts Receivable – INR 75,000  
**Credit:** Sales Revenue – INR 75,000

This creates an outstanding receivable from the customer.

---

## 5. Customer Open Item

The customer invoice appears as an open item in Accounts Receivable.

The Finance team can review:

- Customer
- Invoice amount
- Posting date
- Due date
- Payment terms
- Outstanding balance

---

## 6. Customer Payment

When the customer pays the outstanding amount, the incoming payment is recorded.

Simplified accounting entry:

**Debit:** Bank – INR 75,000  
**Credit:** Accounts Receivable – INR 75,000

The customer invoice can then be cleared against the payment.

---

## 📊 Accounting Summary

| Transaction | Debit | Credit |
|---|---|---|
| Goods Issue | Cost of Goods Sold | Inventory |
| Customer Billing | Accounts Receivable | Sales Revenue |
| Customer Payment | Bank | Accounts Receivable |

---

## 🔗 SAP Integration

This scenario demonstrates integration between:

**SD → FI**

Sales and billing activities can create financial accounting impacts.

The process also involves:

**Customer / Business Partner → Accounts Receivable → General Ledger → Bank**

---

## 📚 Key Concepts Demonstrated

- Sales Order
- Delivery
- Goods Issue
- Billing
- Accounts Receivable
- Customer / Business Partner
- Customer Open Item
- Incoming Payment
- Customer Clearing
- SD-FI Integration

---

## 🎯 Interview Explanation

**Question:** Explain how a customer invoice is processed in SAP.

**Answer:**

The process generally starts with a Sales Order followed by delivery and Goods Issue. After the goods are delivered, billing is created. The billing transaction creates a customer receivable and recognizes sales revenue. The invoice remains as an open item until the customer makes the payment. The incoming payment is then posted and the customer invoice is cleared.

---

## 📝 Important Note

This is a fictional SAP FICO / S/4HANA Finance practice scenario created for educational and portfolio purposes.
