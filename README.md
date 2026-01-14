# Dynamics 365 Business Central ERP for SMBs

## Overview
This project is an implementation of **Microsoft Dynamics 365 Business Central** designed specifically for **Small and Medium Businesses (SMBs)**.  
The ERP solution integrates key business processes into a single, scalable system to improve operational efficiency, financial visibility, and decision-making.

The system covers end-to-end workflows across sales, finance, procurement, and inventory management.

---

## Business Objectives
- Centralize business operations into a single ERP platform
- Improve financial control and reporting
- Streamline sales and procurement processes
- Enhance inventory visibility and stock accuracy
- Support scalability as the business grows

---

## Core Modules

### 1. Sales Management
- Customer and contact management  
- Sales quotes and sales orders  
- Invoicing and credit memos  
- Pricing and discounts  
- Sales reporting and analytics  

### 2. Finance Management
- General Ledger  
- Accounts Receivable & Payable  
- Bank and cash management  
- VAT / tax setup and reporting  
- Financial statements and compliance  

### 3. Procurement
- Vendor management  
- Purchase requisitions and orders  
- Approval workflows  
- Cost and expense tracking  
- Vendor performance reporting  

### 4. Inventory & Stock Management
- Item and SKU management  
- Inventory tracking and valuation  
- Stock transfers and adjustments  
- Warehouse and location management  
- Reorder points and availability insights  

---

## Target Audience
- Small and Medium Enterprises (SMEs)
- Finance teams
- Operations and supply chain teams
- Business Central consultants and developers
- Microsoft Partners implementing ERP solutions

---

## Technology Stack
- **ERP Platform:** Microsoft Dynamics 365 Business Central  
- **Programming Language:** AL (Application Language)  
- **Database:** Azure SQL (Cloud) / SQL Server (On-Premises)  
- **Reporting:** Built-in Business Central reports / Power BI integration  
- **Deployment:**  
  - Business Central Online (SaaS)  
  - Business Central On-Premises  

---

## System Architecture
- Modular ERP architecture based on Business Central extensions  
- Customizations developed using AL extensions  
- Integration-ready with Microsoft ecosystem (Power Platform, Office 365, Azure)

---

## Installation & Setup

### Prerequisites
- Microsoft Dynamics 365 Business Central environment  
- Valid Microsoft license for Business Central  
- Visual Studio Code  
- AL Language Extension for VS Code  

### Setup Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/muchumi/BC260-SMB.git

# Recommended Repository Structure
text
```bash
business-central-erp/
├── src/
│   └── extensions/
│       ├── sales/
│       ├── finance/
│       ├── procurement/
│       └── inventory/
│
├── shared/
│
├── docs/
│   ├── functional/
│   │   ├── sales.md
│   │   ├── finance.md
│   │   ├── procurement.md
│   │   └── inventory.md
│   │
│   ├── technical/
│   │   ├── architecture.md
│   │   ├── al-development.md
│   │   └── deployment.md
│   │
│   ├── integrations/
│   │   └── power-bi.md
│   │
│   └── user-guides/
│       ├── sales-users.md
│       ├── finance-users.md
│       └── inventory-users.md
│
├── README.md
└── LICENSE




















