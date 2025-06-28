# 📚 Library Management System (Java Console + JSP + MySQL)

A user-friendly **Library Management System** developed in **Core Java, JSP, and MySQL**. This system allows users to register or log in, browse available books, borrow books, and receive receipts upon checkout. It also features an **Admin (Librarian) Panel** to manage inventory and track borrowing history.

---

## 🔧 Technologies Used

- **Java (JSP & Servlets)**
- **JDBC (Java Database Connectivity)**
- **MySQL**
- **HTML/CSS/Bootstrap (for UI)**
- **Apache Tomcat**

---

## 👥 User Roles

### 🧑‍💼 Librarian (Admin):
- Add new books
- Remove existing books
- Update book quantity and price
- View all available books
- View borrowing/selling history

### 🙋 User:
- Register or log in
- Browse the book catalog
- Select book(s) and quantity
- Borrow books
- View and print receipt
- View borrowing history

---

## 🗂️ Modules and Features

| Module       | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| Authentication | Secure login & registration for users and admin                          |
| Book Catalog   | Users can view book listings with prices and availability                 |
| Borrowing Flow | Users can add books to cart and confirm borrowing                         |
| Admin Panel    | Full control over inventory and borrow history                            |
| Receipt System | After borrowing, users receive a summary receipt (simulated payment)       |
| History Log    | Borrowing records maintained for future reference                         |

---

## 💾 Database Schema

- `users` – stores user credentials and roles
- `books` – stores book details, price, and quantity
- `orders` – stores borrowing transactions
- `order_items` – items associated with each borrow
  
SQL schema available in:  
📄 `setup/CreateDatastore.sql`

---

## 🏁 How to Run This Project

1. **Clone this repository**:
   ```bash
   git clone https://github.com/abhi8618404/library-management-system.git
