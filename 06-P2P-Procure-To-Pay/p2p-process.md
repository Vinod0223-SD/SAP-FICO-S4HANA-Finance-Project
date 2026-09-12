# Procure-to-Pay (P2P) Process

## 📘 Overview

Procure-to-Pay (P2P) is an end-to-end business process that starts with the requirement for materials or services and ends with payment to the vendor.

For Nikhil Manufacturing Pvt. Ltd., the P2P process connects Procurement, Materials Management and Finance.

---

## 🔄 P2P Process Flow

**Purchase Requisition → Purchase Order → Goods Receipt → Invoice Receipt → Invoice Verification → Vendor Payment**

Each stage creates or updates relevant business and accounting information.

---

## 1. Purchase Requisition

A Purchase Requisition (PR) represents an internal requirement for materials or services.

Example:

The production department requires raw materials for manufacturing.

The requirement is raised through a purchase requisition.

**Purpose:**

- Identify material or service requirements
- Specify quantity and required date
- Initiate the procurement process

---

## 2. Purchase Order

A Purchase Order (PO) is created and sent to the selected vendor.

It contains information such as:

- Vendor
- Material or service
- Quantity
- Price
- Delivery date
- Payment terms

The PO represents a formal purchasing commitment.

---

## 3. Goods Receipt

When the materials are received, a Goods Receipt (GR) is recorded.

Example:

Raw materials worth INR 50,000 are received from the vendor.

For a stock-material scenario, the accounting impact can include:

**Debit:** Inventory – INR 50,000  
**Credit:** GR/IR Clearing – INR 50,000

The exact accounting entry depends on the material, valuation and configuration.

---

## 4. Invoice Receipt

The vendor sends an invoice for the materials supplied.

The invoice is verified against the purchasing documents.

This is commonly associated with **three-way matching**:

**Purchase Order ↔ Goods Receipt ↔ Vendor Invoice**

---

## 5. Vendor Liability

After the vendor invoice is posted, the amount payable to the vendor is recorded.

Example:

**Debit:** GR/IR Clearing – INR 50,000  
**Credit:** Accounts Payable – INR 50,000

This creates an outstanding vendor liability.

---

## 6. Vendor Payment

When the invoice becomes due, the company processes the vendor payment.

Example:

**Debit:** Accounts Payable – INR 50,000  
**Credit:** Bank – INR 50,000

The vendor open item is cleared after successful payment processing.

---

## 📋 P2P Finance Activities

Finance may be involved in:

- Vendor invoice processing
- Invoice verification
- Accounts Payable posting
- Payment processing
- Vendor open item review
- Vendor account clearing
- GR/IR reconciliation
- Month-end reconciliation

---

## 🔗 Integration with SAP Modules

P2P demonstrates integration between multiple SAP areas:

**MM → FI**

Materials Management activities such as purchasing and goods receipt can create financial impacts in Financial Accounting.

The process may also involve:

**MM → FI → CO**

Depending on the transaction, costs can also flow to relevant Controlling objects such as cost centers or internal orders.

---

## 📚 Important SAP Concepts

- Purchase Requisition
- Purchase Order
- Goods Receipt
- Invoice Receipt
- Three-Way Matching
- GR/IR Clearing
- Accounts Payable
- Vendor Open Items
- Vendor Clearing
- Automatic Account Determination
- MM-FI Integration

---

## 🎯 Learning Objective

This section demonstrates understanding of the complete P2P process and how procurement transactions can create financial impacts in SAP S/4HANA Finance.

---

## 📝 Important Note

This is a fictional SAP FICO / S/4HANA Finance learning and simulation project created for educational and portfolio purposes.
