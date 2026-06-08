# Maareeye Business Management System 🚀

<img src="assets/Images/Maareeye%20Logo.jpg" width="250" alt="Maareeye Logo">

> **A comprehensive Point of Sale (POS), Inventory, and Business Management SaaS application.**

### 🔗 **[Test the Live App Here: maareeyeapp.com](https://maareeyeapp.com)**

---

## 💡 What Problem Does This Solve?
Running a modern business requires tracking sales, managing stock, and monitoring expenses simultaneously. Many small to medium businesses struggle with disconnected systems or manual paper tracking, leading to lost revenue and inventory shrinkage. 

**Maareeye** solves this by providing an all-in-one centralized platform. It empowers business owners to:
- Instantly process sales and generate digital receipts.
- Track real-time inventory and receive low-stock alerts.
- Monitor daily expenses, debts, and generate comprehensive financial reports.
- Manage customer and vendor accounts seamlessly.

---

## ✨ Core Features
- 🛒 **Point of Sale (POS):** Fast checkout, custom receipts, and multiple payment methods.
- 📦 **Inventory Management:** Live stock tracking, unit management, and bulk import/export.
- 👥 **Customer & Vendor Profiles:** Track debts, transaction history, and account balances.
- 📊 **Financial Reporting:** Beautiful, data-driven dashboards for daily/monthly profits, expenses, and growth.
- 🔒 **Role-Based Access Control:** Distinct permissions for Cashiers, Managers, and Super Admins.
- 📱 **Mobile Optimized:** Progressive Web App (PWA) support allowing users to manage their business on the go.

---

## 📸 Screenshots & Demo

Here is a look at the Maareeye Management System in action:

<details>
<summary>Click to view screenshots</summary>

| Showcase | App Interface |
|:---:|:---:|
| ![Showcase Image](assets/Images/maareye%20showcase%20image%201.png) | ![App Pic](assets/Images/Maareeyeapp%20app%20pic.png) |

</details>

---

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla & PWA Service Workers)
- **Backend:** PHP 8+
- **Database:** MySQL
- **Architecture:** Monolithic SaaS

---

## 🚀 How to Run Locally

1. **Prerequisites:** Install [XAMPP](https://www.apachefriends.org/index.html).
2. **Clone the Repo:**
   ```bash
   git clone https://github.com/yourusername/maareeyev1.git
   ```
3. **Move to XAMPP:** Place the folder inside `C:/xampp/htdocs/`.
4. **Database Setup:** 
   - Start Apache and MySQL in XAMPP.
   - Go to `http://localhost/phpmyadmin`.
   - Create a database named `maareeye_db`.
   - Import the `database-migration/` or `.sql` file.
5. **Configuration:** 
   - Rename `config/db.example.php` to `config/db.php` (if applicable) and add your local database credentials.
6. **Access:** Open `http://localhost/maareeyev1` in your browser.

---

*This project is built as a portfolio showcase to demonstrate full-stack PHP & MySQL capabilities.*
