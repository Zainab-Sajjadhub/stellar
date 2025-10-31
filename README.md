
# 🌟 Stellar - Personalized Skincare E-Commerce

> An AI-powered skincare shopping experience, built with PHP, MySQL, HTML, CSS, and JavaScript.


## 🧴 Project Overview

**Stellar** is a dynamic and intelligent e-commerce platform that provides personalized skincare product recommendations using AI. Users can browse, search, and shop products that are suitable for their unique skin needs, while interacting with GlamBot, a smart chatbot assistant.



## ✨ Features

- 🧠 **AI-Powered Chatbot (GlamBot)**: Personalized skincare guidance.
- 🛍️ **Shopping Cart**: Add/remove items, dynamic session-based cart.
- 🔎 **Live Search with Scroll-To Feature**: Search products and jump to results.
- 📷 **Product Display**: Images, prices, stock, reviews — all from a MySQL database.
- 📱 **Responsive UI**: Optimized for all screen sizes.
- 📦 **Inventory Management**: Real-time stock tracking.
- 🎨 **Modern Design**: Font Awesome, Google Fonts, and animations.
- 🔐 **Privacy Focus**: Foundation for future secure login and data handling.



### Prerequisites

To run Stellar locally, you’ll need:

- PHP >= 7.4
- MySQL Server
- Apache (via XAMPP, MAMP, WAMP, etc.)
- A web browser



## ⚙️ Installation

1. **Clone the Repository:**

```bash
git clone https://gitlab.cci.drexel.edu/cid/2425/ws1023/64/17/stellar.git
cd stellar
````

2. **Set Up the Database:**

* Open your MySQL interface (e.g., phpMyAdmin or MySQL CLI).
* Create a new database named: `my_products`
* Import the `my_products.sql` file from the `database/` folder.

3. **Update Database Credentials:**

In your `config.php` or database connection file:

```php
$host = 'localhost';
$db   = 'my_products';
$user = 'root';
$pass = ''; // Set your MySQL password if applicable
```

4. **Run the App:**

* Place the project folder inside your web server's root (`htdocs` for XAMPP).
* Start Apache and MySQL.
* Go to [http://localhost/stellar/index.php](http://localhost/stellar/index.php) in THE browser.




## 🧰 Tech Stack

| Language/Tool | Purpose                   |
| ------------- | ------------------------- |
| PHP           | Backend and server logic  |
| MySQL         | Product database          |
| HTML/CSS      | Structure and styling     |
| JavaScript    | Interactivity & search    |
| Font Awesome  | Icons                     |
| Google Fonts  | Typography                |
| Chatbot API   | AI product recommendation |



## 🙌 Authors

* Jalisa Wasima
* Faith Sarnor
* Zainab Sajjad
* Awo Asieduwaa Afranie-Adjei

---

## 📄 License

This project is for educational purpose.

---

## 📌 Project Status

✅ Functional, completed

