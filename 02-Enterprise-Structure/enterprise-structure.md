# Enterprise Structure

## 🏢 Overview

The enterprise structure defines the organizational units used by Nikhil Manufacturing Pvt. Ltd. for financial accounting, controlling, procurement, inventory and manufacturing activities.

This structure is designed for a fictional SAP S/4HANA Finance learning and simulation project.

---

## 🏗️ Organizational Structure

| Organizational Unit | Example | Purpose |
|---|---|---|
| Company | Nikhil Manufacturing Pvt. Ltd. | Represents the overall corporate entity |
| Company Code | NM01 | Main organizational unit for financial accounting |
| Controlling Area | NMCA | Supports management accounting and cost controlling |
| Plant | NM01 | Represents the manufacturing location |
| Storage Location | RM01 | Stores raw materials |
| Storage Location | FG01 | Stores finished goods |

---

## 1. Company

**Company Name:** Nikhil Manufacturing Pvt. Ltd.

The company represents the overall corporate entity used in this project.

It provides the overall organizational framework for the company's business and financial activities.

---

## 2. Company Code

**Company Code:** NM01

**Company Code Name:** Nikhil Manufacturing Pvt. Ltd.

**Country:** India

**Currency:** INR

The company code is the primary organizational unit for external financial accounting.

Financial transactions such as G/L postings, vendor invoices, customer invoices, payments and asset transactions are recorded for the company code.

A complete set of financial statements can be prepared at the company code level.

---

## 3. Controlling Area

**Controlling Area:** NMCA

**Controlling Area Name:** Nikhil Manufacturing Controlling Area

The controlling area is used for internal management accounting and cost controlling.

It supports activities such as:

- Cost Center Accounting
- Internal Orders
- Cost allocation
- Planning and analysis
- Monitoring business costs

---

## 4. Plant

**Plant:** NM01

**Plant Name:** Nikhil Manufacturing Plant

**Location:** Karnataka, India

The plant represents the company's manufacturing location.

The plant is used for activities such as:

- Procurement
- Inventory management
- Production
- Goods receipt
- Goods issue
- Finished goods management

---

## 5. Storage Locations

### Raw Material Storage

**Storage Location:** RM01

Used to store raw materials purchased from vendors.

### Finished Goods Storage

**Storage Location:** FG01

Used to store finished products manufactured by the company.

---

## 🔗 Organizational Relationships

Nikhil Manufacturing Pvt. Ltd.
│
├── Company Code: NM01
│   │
│   └── Plant: NM01
│       │
│       ├── RM01 - Raw Material Storage
│       │
│       └── FG01 - Finished Goods Storage
│
└── Controlling Area: NMCA

---

## 🔄 Finance and Business Process Integration

The organizational structure supports the major business processes used in this project.

### Procure-to-Pay (P2P)

**Vendor → Purchase Order → Goods Receipt → Invoice Receipt → Vendor Payment**

### Order-to-Cash (O2C)

**Customer → Sales Order → Delivery → Billing → Customer Payment**

### Record-to-Report (R2R)

**Business Transaction → G/L Posting → Reconciliation → Period-End Closing → Financial Reporting**

---

## 📚 Key SAP Concepts

### Company Code

The company code is the smallest organizational unit in SAP for which a complete set of financial statements can be created.

### Controlling Area

The controlling area is an organizational unit used for management accounting and internal cost controlling.

### Plant

A plant represents a location where materials are produced, stored or handled.

### Storage Location

A storage location represents a physical or logical subdivision within a plant where stock is managed.

---

## 🎯 Project Configuration Summary

| Parameter | Value |
|---|---|
| Company | Nikhil Manufacturing Pvt. Ltd. |
| Company Code | NM01 |
| Country | India |
| Currency | INR |
| Controlling Area | NMCA |
| Plant | NM01 |
| Raw Material Storage | RM01 |
| Finished Goods Storage | FG01 |

---

## 📝 Important Note

This organizational structure is created for a fictional SAP FICO / S/4HANA Finance learning project.

The organizational units, codes and business relationships are simulated for educational and portfolio purposes and do not represent an actual company's SAP system.
