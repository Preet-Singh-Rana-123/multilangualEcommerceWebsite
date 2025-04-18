# 🍏 GlobalGrocers Admin Panel

A simple PHP-based admin panel for managing a grocery e-commerce platform. Features include user authentication, product management, and order tracking.

---

## 🛠️ 1. Features
- Admin login/logout
- Manage products, categories, users, and orders
- Responsive UI with basic CSS
- Dynamic content via PHP and JavaScript
- Session management for security

---

## ⚙️ 2. Configure your environment
Make sure you have **PHP** and **MySQL** installed (e.g., using **XAMPP**, **MAMP**, or **LAMP**).

1. Create a MySQL database named:
   ```
   GroceriesDB
   ```
2. Import the `GroceriesDB.sql` file provided in the root directory into your MySQL server.

3. Update database credentials in `db_connection.php` if needed:
   ```php
   $conn = mysqli_connect("localhost", "root", "", "GroceriesDB");
   ```

---

## 🚀 3. Run the Project
1. Place the entire `FINAL_GROCERY_ADMIN` folder inside your web server directory, e.g.:
   ```
   /Applications/XAMPP/htdocs/
   ```

2. Start your Apache and MySQL services via XAMPP.

3. Open your browser and go to:
   ```
   http://localhost/FINAL_GROCERY_ADMIN/index.php
   ```

---

## 📁 4. Project Structure
```
FINAL_GROCERY_ADMIN/
├── admin/
│   ├── admin_categories.php
│   ├── admin_login.php
│   ├── admin_logout.php
│   ├── admin_logs.php
│   ├── admin_orders.php
│   ├── admin_products.php
│   ├── admin_users.php
│   ├── admin.php
│   └── db_connection.php
├── css/
│   ├── admin.css
│   ├── auth.css
│   ├── login.css
│   ├── main.css
│   ├── responsive.css
│   └── styles.css
├── images/
├── js/
│   ├── auth.js
│   ├── cart.js
│   ├── categories.js
│   ├── language.js
│   ├── main.js
│   ├── products.js
│   └── translate.js
├── pages/
│   ├── about.php
│   ├── cart.php
│   ├── category.php
│   └── products.php
├── uploads/
│   └── cart.php
├── GroceriesDB.sql
├── db_connection.php
├── index.php
├── login.php
├── logout.php
├── profile.php
├── README.md
├── register.php
└── trailMix.jpg
```

---

## 🙋 Team
- **Preet Rana** – Backend Developer
- **Aman Kumar Yadav** – Frontend Developer
- **Prince Yadav** – UI/UX Design

---

## 📌 Future Improvements
- Add product reviews and ratings system
- Real-time cart update with AJAX
- Payment integration (e.g., Razorpay, Stripe)
- Inventory management for admins
- API endpoints for mobile apps

---

> Feel free to fork, clone, and build upon this project for your own use!
