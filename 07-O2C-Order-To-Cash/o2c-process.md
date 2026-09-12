# Order-to-Cash (O2C) Process

## 📘 Overview

Order-to-Cash (O2C) is an end-to-end business process that begins when a customer places an order and ends when the company receives and clears the customer payment.

For Nikhil Manufacturing Pvt. Ltd., the O2C process connects Sales, Delivery, Billing and Finance activities.

---

## 🔄 O2C Process Flow

**Customer Order → Sales Order → Delivery → Goods Issue → Billing → Customer Payment → Clearing**

Each stage contributes to the overall sales and financial process.

---

## 1. Sales Order

A Sales Order (SO) records the customer's requirement for products or services.

It may contain:

- Customer
- Material
- Quantity
- Price
- Delivery date
- Payment terms

The sales order represents the customer's confirmed requirement.

---

## 2. Delivery

After the sales order is processed, the required finished goods are prepared for delivery.

The delivery document contains information such as:

- Customer
- Material
- Quantity
- Delivery date
- Shipping information

---

## 3. Goods Issue

When the goods leave the company's inventory, a Goods Issue (GI) is recorded.

For a stock-material scenario, the accounting impact can include:

**Debit:** Cost of Goods Sold  
**Credit:** Inventory

The exact accounting impact depends on material valuation and system configuration.

---

## 4. Billing

After delivery, a customer billing document is created.

Example:

Finished goods are sold to a customer for INR 75,000.

The billing transaction creates the customer receivable and sales revenue impact.

**Debit:** Accounts Receivable – INR 75,000  
**Credit:** Sales Revenue – INR 75,000

This creates an outstanding amount receivable from the customer.

---

## 5. Customer Payment

When the customer pays the outstanding amount, the incoming payment is recorded.

Example:

**Debit:** Bank – INR 75,000  
**Credit:** Accounts Receivable – INR 75,000

The customer's outstanding item can then be cleared against the payment.

---

## 6. Customer Clearing

Customer clearing matches the outstanding customer invoice with the corresponding incoming payment.

Example:

**Customer Invoice → Open Item → Incoming Payment → Clearing**

After successful clearing, the customer invoice is no longer an outstanding open item.

---

## 📋 O2C Finance Activities

Finance may be involved in:

- Customer master / Business Partner review
- Billing-related accounting
- Accounts Receivable posting
- Incoming payment processing
- Customer open item monitoring
- Customer account clearing
- Receivables reconciliation
- Month-end closing

---

## 🔗 Integration with SAP Modules

O2C demonstrates integration between Sales, Logistics and Finance.

**SD → FI**

Sales and billing activities can create financial accounting documents.

The process may also involve:

**SD → FI → CO**

Depending on the transaction and configuration, revenue and cost information can also flow to relevant Controlling objects.

---

## 📚 Important SAP Concepts

- Sales Order
- Delivery
- Goods Issue
- Billing
- Accounts Receivable
- Customer / Business Partner
- Customer Open Items
- Incoming Payment
- Customer Clearing
- Revenue Posting
- SD-FI Integration

---

## 🎯 Learning Objective

This section demonstrates understanding of the complete O2C process and how sales and customer transactions create financial impacts in SAP S/4HANA Finance.

---

## 📝 Important Note

This is a fictional SAP FICO / S/4HANA Finance learning and simulation project created for educational and portfolio purposes.
