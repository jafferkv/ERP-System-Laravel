# **ERP Management System – Laravel **

A fully customized ERP solution integrating RTA APIs, real-time dashboards, RFID-based payments, and enterprise modules for Job Cards, Finance, HR, ESS, and Administration. Built with scalable backend architecture and responsive frontend interfaces.

---

## 📌 **Objective**
To provide a centralized ERP platform that automates daily operations across Job Cards, Finance, HR, Sales, and ESS while ensuring real-time reporting, secure access control, and integration with external services such as RTA Dubai APIs.

---

## 🧩 **Key Modules & Features**

### **1. Dashboard**
- Sales charts by cost centers and branches  
- Employee, customer, job card, and department KPIs  
- Separate dashboards for admin and employees  

### **2. Job Cards**
- Create job tokens and select vehicle services  
- Multi-payment support:
  - RFID Mutakamela Card  
  - Cash, Card, Company Payment, Staff Payment  
- Auto-updated customer ledger  

### **3. Job Card Reports**
- Daily collection (cashier-wise, payment type, VAT, totals)  
- Sales Summary / Detailed Reports  
- Manager Target Report  
- Money Journey Report  
- VAT, RTA Sales, DM Sales Reports  
- Staff Credit Report  

### **4. Finance Module**
- Account, group, and ledger setup  
- Voucher entry + Tally voucher import  
- **Finance Reports:**
  - Chart of Accounts  
  - General Ledger  
  - Trial Balance  
  - Profit & Loss  
  - Receivable/Payable Aging  
  - Balance Sheet  
  - Payment Reversal  

### **5. HR Module**
- Employee registration & master data  
- Attendance register, time shift, holiday master  
- Leaves, vacations, lapse management  
- Bank & WPS details  
- Employee promotions, transfers, demotions  
- Interview & probation tracking  
- Payroll  
- Daily & monthly attendance reports  

### **6. ESS (Employee Self Service)**
- Leave request  
- Payslip view  
- Profile & document management  

### **7. Mutakamela RFID Card**
- Register multiple cards per customer  
- Recharge & credit limit management  
- RFID reader for payments  
- Real-time account reflection  

### **8. Product Setup**
- Category, service & package setup  
- VAT configuration  
- Pricing management  

### **9. Administrator**
- User Accounts, Roles, Job Card Roles  
- Company & Cost Center setup  
- Modules & Permissions  
- Payment Methods  
- Locations & Access Groups  

### **10. Extra Modules**
- Store Management  
- Import Vouchers  
- Import Ledgers  
- Import Card Accounts  

---

## 🖼️ **Screenshots**


### Dashboard  
![Dashboard](screenshots/dashboard.png)

### Job Card  
![Job Card](screenshots/jobcard.png)

### Finance  
![Finance](screenshots/finance.png)

### HR Module  
![HR Module](screenshots/hr.png)

### ESS  
![ESS](screenshots/ess.png)

---

## ⚙️ **Tech Stack**

### **Backend**
- PHP 8+  
- Laravel  
- Node.js / Express.js  
- REST API architecture  
- MSSQL & MySQL Databases  

### **Frontend**
- React.js  
- Next.js  
- Laravel Blade Templates  
- Bootstrap, Tailwind CSS  
- HTML, CSS, JavaScript, jQuery  

### **Real-Time & Background Processing**
- Pusher  
- Laravel Queues, Jobs, Events  
- Notifications  

### **Integrations & Libraries**
- RTA Dubai APIs  
- Spatie Permission  
- Maatwebsite/Excel  
- dompdf  

### **Tools**
- Git, GitHub  
- Composer, NPM  
- Postman  
- VS Code / PHPStorm  
- Docker (Optional)  

---

## 🗄️ **Database**
- MSSQL (Primary ERP operations)  
- MySQL (Secondary modules)  
- Optimized stored procedures  
- Normalized relational structure  

---

---

## 🔐 Authentication
- **Session-based login**
- **Role & Permission Management (Spatie Permission)**
- **API Token Security** for external services and third-party integrations

---

## 📊 Reporting
- **Excel Export** using *Maatwebsite/Excel*
- **PDF Export** using *dompdf*
- **Real-time Charts & Updates** via WebSockets (Pusher)
- **Auto-generated Reports**, including:
  - **RTA Reports**
  - **Dubai Municipality Reports**
  - **VAT Reports**
  - **Sales Summary & Detailed Reports**

---

## 🛡️ Security
- **CSRF Protection**
- **Strict Input Validation**
- **Sanitization for All User Inputs**
- **Encrypted RFID Card Data** for Mutakamela Payment System

---

## ✨ Future Enhancements
- **Mobile App** (React Native / Flutter)
- **AI-Driven Analytics**
- **Multi-Tenant SaaS Version**
- **Advanced Dashboards** using BI Tools (Power BI / Metabase)

---

