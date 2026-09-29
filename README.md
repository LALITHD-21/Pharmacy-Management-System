<div align="center">

<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=💊%20Pharmacy%20Management%20System&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=A%20complete%20drug%20store%20management%20solution%20built%20with%20PHP%20%26%20MySQL&descAlignY=60&descSize=18" width="100%"/>

<!-- Badges -->
<p>
  <img src="https://img.shields.io/badge/PHP-7.4%2B-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-8.0%2B-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
  <img src="https://img.shields.io/badge/Twig-Template-009688?style=for-the-badge&logo=symfony&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
</p>

<p>
  <img src="https://img.shields.io/badge/MVC-Architecture-FF6B6B?style=flat-square"/>
  <img src="https://img.shields.io/badge/PHPMailer-Email%20Enabled-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/DomPDF-PDF%20Reports-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/DataTables-Integrated-green?style=flat-square"/>
</p>

<br/>

> **A powerful, feature-rich Pharmacy / Drug Store Management System** built with a clean MVC architecture in PHP. Designed to handle everything from medicine inventory and billing to HR, finance, and reporting — all from a single, beautiful admin dashboard.

<br/>

[🚀 Features](#-features) · [📸 Screenshots](#-screenshots) · [🛠 Tech Stack](#-tech-stack) · [📁 Project Structure](#-project-structure) · [⚙️ Installation](#️-installation) · [🔐 Security](#-security) · [📊 Reports](#-reports) · [🤝 Contributing](#-contributing)

</div>

---

## ✨ Features

<table>
  <tr>
    <td width="50%">

### 💊 Medicine & Inventory
- ✅ Add / Edit / Delete medicines with categories
- ✅ Track purchase orders from suppliers
- ✅ Real-time stock level monitoring
- ✅ Low-stock & out-of-stock alerts
- ✅ Batch-wise stock tracking
- ✅ Medicine categories management

    </td>
    <td width="50%">

### 🧾 Billing & Invoicing
- ✅ POS-style medicine billing
- ✅ Invoice generation with multiple PDF templates (5 styles)
- ✅ Tax & discount support
- ✅ Multiple payment method support
- ✅ Email invoices directly to customers
- ✅ Billing history & reprint

    </td>
  </tr>
  <tr>
    <td width="50%">

### 👥 Customer & Doctor Management
- ✅ Full customer profiles with history
- ✅ Doctor directory with prescription tracking
- ✅ Doctor search functionality
- ✅ Customer purchase history
- ✅ Customer profile view & management

    </td>
    <td width="50%">

### 💼 HR & Payroll
- ✅ Staff attendance tracking
- ✅ Salary template creation
- ✅ Manage salaries & payment history
- ✅ Salary slip PDF generation
- ✅ Payment scheduling & make payment module
- ✅ Noticeboard announcements for staff

    </td>
  </tr>
  <tr>
    <td width="50%">

### 💰 Finance & Accounting
- ✅ Income & expense tracking
- ✅ Expense categories (expense types)
- ✅ Account management with transactions
- ✅ Financial statement reports
- ✅ Tax management
- ✅ Payment method configuration

    </td>
    <td width="50%">

### 📧 Communication & Notifications
- ✅ Send individual & bulk emails
- ✅ Subscriber management
- ✅ Email templates management
- ✅ Full email logs history
- ✅ SMTP configuration support
- ✅ Automated invoice email delivery

    </td>
  </tr>
  <tr>
    <td width="50%">

### 📊 Reports & Analytics
- ✅ Medicine billing report
- ✅ Purchase report
- ✅ Inventory report
- ✅ Expense report
- ✅ Income vs expense report
- ✅ Account statement report
- ✅ Invoice report
- ✅ Salary report
- ✅ Out-of-stock report

    </td>
    <td width="50%">

### 🔐 System & Security
- ✅ Role-based access (Admin / Employee)
- ✅ Separate dashboards per role
- ✅ Secure login with session management
- ✅ Forgot password & reset workflow
- ✅ CSRF token protection
- ✅ Input validation & HTML purification
- ✅ Error log viewer (401, 403, 404)
- ✅ Media / file upload management

    </td>
  </tr>
</table>

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | PHP 7.4+ |
| **Database** | MySQL 8.0+ |
| **Templating** | Twig (Symfony) |
| **Frontend** | Bootstrap 5, jQuery, DataTables, SCSS |
| **PDF Generation** | DomPDF |
| **Email** | PHPMailer |
| **Input Sanitization** | HTML Purifier |
| **Routing** | Custom PHP Router |
| **Architecture** | MVC (Model-View-Controller) |
| **Icons** | Line Awesome Icon Set |
| **Charting** | Integrated Dashboard Charts |

---

## 📁 Project Structure

```
📦 Pharmacy-Management-System
├── 📂 app/
│   ├── 📂 http/
│   │   ├── 📂 controllers/          # All business logic controllers
│   │   │   ├── AccountController.php
│   │   │   ├── CustomerController.php
│   │   │   ├── DoctorController.php
│   │   │   ├── ExpenseController.php
│   │   │   ├── FinanceController.php
│   │   │   ├── InvoiceController.php
│   │   │   ├── MedicineController.php
│   │   │   ├── ReportController.php
│   │   │   ├── ManagesalaryController.php
│   │   │   ├── StaffattendanceController.php
│   │   │   ├── SenderController.php        # Email sender
│   │   │   ├── UploadController.php
│   │   │   └── ...more
│   │   └── 📂 models/               # Database models
│   │       ├── Medicine.php
│   │       ├── Invoice.php
│   │       ├── Customer.php
│   │       ├── Doctor.php
│   │       ├── Finance.php
│   │       ├── Expense.php
│   │       ├── Dashboard.php
│   │       └── ...more
│   ├── 📂 views/                    # Twig template files
│   │   ├── 📂 medicine/             # Medicine, billing, stock, purchase views
│   │   ├── 📂 invoice/              # Invoice views + 5 PDF templates
│   │   ├── 📂 dashboard/            # Admin & Employee dashboards
│   │   ├── 📂 customer/             # Customer management views
│   │   ├── 📂 doctor/               # Doctor directory views
│   │   ├── 📂 managesalary/         # Salary & payroll views
│   │   ├── 📂 report/               # All reporting views
│   │   ├── 📂 auth/                 # Login, forgot, reset password
│   │   └── 📂 common/               # Shared header, footer, modals
│   └── 📂 language/                 # Multi-language support
├── 📂 builder/
│   ├── 📂 core/                     # Router, App core
│   ├── 📂 library/                  # Database, Mailer library
│   ├── 📂 vendor/                   # Composer dependencies
│   └── routes.php                   # All application routes
├── 📂 config/
│   └── config.php                   # App configuration (DB, keys, URL)
├── 📂 install/                      # Web-based installer
├── 📂 public/
│   ├── 📂 css/                      # Compiled stylesheets
│   ├── 📂 js/                       # JavaScript files
│   ├── 📂 fonts/                    # Line Awesome & other fonts
│   ├── 📂 images/                   # Static images
│   ├── 📂 uploads/                  # User-uploaded media
│   └── 📂 sass/                     # SCSS source files
├── index.php                        # Application entry point
├── Upload.zip                       # Full project source archive
├── Documentation.zip                # Project documentation
└── README.md                        # This file
```

---

## ⚙️ Installation

### 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **PHP** `>= 7.4` (with extensions: `pdo`, `pdo_mysql`, `mbstring`, `openssl`, `fileinfo`, `gd`)
- **MySQL** `>= 5.7` or **MariaDB** `>= 10.3`
- **Apache** or **Nginx** web server
- **Composer** (for dependency management)

---

### 🚀 Quick Setup

#### Step 1 — Clone the Repository

```bash
git clone https://github.com/LALITHD-21/Pharmacy-Management-System.git
cd Pharmacy-Management-System
```

#### Step 2 — Extract the Project Files

```bash
# Extract the main project files
unzip Upload.zip -d ./app-source
```

#### Step 3 — Set Up Your Web Server

Copy the extracted files to your web server's document root:

```bash
# For XAMPP (Windows)
cp -r ./app-source/Upload/* C:/xampp/htdocs/pharmacy/

# For LAMP (Linux)
cp -r ./app-source/Upload/* /var/www/html/pharmacy/
```

#### Step 4 — Create Database

```sql
-- Log into MySQL and run:
CREATE DATABASE pharmacy_db CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

#### Step 5 — Configure the Application

Open `config/config.php` and update the following:

```php
define('NAME', 'Your Drug Store Name');       // Store name
define('URL', 'http://localhost/pharmacy');    // Your app URL

define('DB_HOSTNAME', 'localhost');            // Database host
define('DB_USERNAME', 'your_db_user');         // Database username
define('DB_PASSWORD', 'your_db_password');     // Database password
define('DB_DATABASE', 'pharmacy_db');          // Database name
define('DB_PREFIX', 'ds_');                    // Table prefix
```

#### Step 6 — Run the Web Installer

Open your browser and navigate to:

```
http://localhost/pharmacy/install
```

Follow the on-screen steps to complete installation and create your admin account.

#### Step 7 — Delete the Install Directory

> ⚠️ **Important Security Step!** After installation, delete the `/install` folder:

```bash
rm -rf /var/www/html/pharmacy/install
```

---

### 🐧 Linux File Permissions

```bash
chmod -R 755 /var/www/html/pharmacy
chmod -R 777 /var/www/html/pharmacy/public/uploads
chmod -R 777 /var/www/html/pharmacy/builder/storage
```

---

## 🔐 Security

This system includes multiple layers of security out of the box:

| Security Feature | Status |
|-----------------|--------|
| CSRF Token Protection | ✅ Enabled |
| Session-based Authentication | ✅ Enabled |
| Role-based Access Control (Admin/Employee) | ✅ Enabled |
| HTML Input Purification (HTMLPurifier) | ✅ Enabled |
| Cryptographic Auth Keys & Salts | ✅ Pre-configured |
| Password Hashing | ✅ Enabled |
| SQL Prepared Statements (PDO) | ✅ Enabled |
| 401 / 403 / 404 Error Handling | ✅ Enabled |

> 🔒 **Recommendation**: Change all cryptographic keys in `config/config.php` (`AUTH_KEY`, `LOGGED_IN_SALT`, `TOKEN`, `TOKEN_SALT`) before deploying to production.

---

## 📊 Reports

The system provides **11 detailed reports** with export capabilities:

| Report | Description |
|--------|-------------|
| 🧾 **Billing Report** | Medicine sales and billing history |
| 🛒 **Purchase Report** | Medicine purchase orders from suppliers |
| 📦 **Inventory Report** | Current stock levels for all medicines |
| 💸 **Expense Report** | All business expenses by category |
| 📈 **Income vs Expense** | Profit & loss comparison |
| 🏦 **Account Statement** | Bank/account transaction statements |
| 📄 **Invoice Report** | All customer invoices |
| 💰 **Salary Report** | Staff salary payment history |
| ❌ **Out-of-Stock Report** | Medicines that are out of stock |
| 📋 **General Reports** | Configurable general reports dashboard |
| 💳 **Finance Summary** | Payment method and tax reports |

---

## 👥 User Roles

### 🛡️ Admin
Full access to all system features including:
- All medicine, billing & stock operations
- HR management (salary, attendance, noticeboard)
- Finance & accounting
- Email sending & communication
- System settings & configurations
- All reports

### 👤 Employee
Limited access to:
- Medicine billing
- Stock viewing
- Personal profile
- Noticeboard viewing

---

## 📧 Email Configuration

Configure SMTP settings from the admin panel under **Settings → Email Settings**:

```
SMTP Host:      smtp.gmail.com (or your provider)
SMTP Port:      587
Encryption:     TLS
Username:       your@email.com
Password:       your_app_password
```

> 💡 For Gmail, use an **App Password** instead of your regular password.

---

## 🌐 Routes Overview

The application uses a clean custom router. Key route groups:

| Module | Example Routes |
|--------|---------------|
| **Authentication** | `/login`, `/forgot`, `/reset-password` |
| **Dashboard** | `/dashboard` |
| **Medicine** | `/medicines`, `/medicine/add`, `/medicine/edit`, `/medicine/billing` |
| **Stock** | `/medicine/stock`, `/medicine/purchase` |
| **Customers** | `/customers`, `/customer/add`, `/customer/view` |
| **Doctors** | `/doctors`, `/doctor/add`, `/doctor/search` |
| **Invoices** | `/invoices`, `/invoice/add`, `/invoice/pdf` |
| **Expenses** | `/expenses`, `/expense/add`, `/expensetype` |
| **Salary** | `/salarytemplate`, `/managesalary`, `/makepayment` |
| **Reports** | `/reports` |
| **Email** | `/send/email`, `/sendbulk/email`, `/emaillogs` |
| **Settings** | `/suppliers`, `/paymentmethod`, `/tax`, `/emailtemplate` |

---

## 📄 PDF Invoice Templates

The system ships with **5 beautifully designed invoice templates**:

```
📄 invoice_pdf_1.twig  →  Classic Style
📄 invoice_pdf_2.twig  →  Modern Minimal
📄 invoice_pdf_3.twig  →  Professional Blue
📄 invoice_pdf_4.twig  →  Compact Style
📄 invoice_pdf_5.twig  →  Detailed Extended
```

You can select your preferred template from the admin settings panel.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add some amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

Please read our contributing guidelines before submitting PRs.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

<div align="center">

**LALITH D**

[![GitHub](https://img.shields.io/badge/GitHub-LALITHD--21-181717?style=for-the-badge&logo=github)](https://github.com/LALITHD-21)

</div>

---

<div align="center">

**⭐ If this project helped you, please give it a star! It means a lot. ⭐**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
