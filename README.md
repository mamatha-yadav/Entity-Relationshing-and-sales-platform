
# 📚 Online Bookstore Database Project

This project is a **relational database schema** designed for an **Online Bookstore Management System**. It is structured to handle the core operations of an e-commerce bookstore, including book listings, customer management, orders, payments, shipping, and wishlists.

---

## 📌 Project Features

- Store detailed information about **Books**, **Authors**, **Publishers**, and **Genres**
- Manage **Customers**, their **Shipping Addresses**, and **Purchase Histories**
- Enable **Order processing** with itemized details
- Maintain **Wishlists** for future purchases
- Track **Payments** and their statuses
- Support **many-to-many relationships** (Books ↔ Authors, Books ↔ Genres)

---

## 🗃️ Entity Tables

| Table Name         | Purpose                                    |
|--------------------|--------------------------------------------|
| `BOOK`             | Stores book information like title, ISBN, edition, etc. |
| `AUTHOR`           | Stores author names and biographies         |
| `PUBLISHER`        | Stores publisher details                   |
| `GENRE`            | Categorizes books into genres like Fiction, History, etc. |
| `CUSTOMER`         | Stores customer profiles                   |
| `SHIPPING_ADDRESS` | Stores customer shipping addresses         |
| `WISHLIST`         | Manages customer wishlist items            |
| `ORDERS`           | Stores order data                          |
| `ORDER_ITEM`       | Links individual books to orders (line items) |
| `PAYMENT`          | Stores payment details for orders          |

---

## 🔁 Junction Tables (Many-to-Many)

| Table Name        | Relationship Description                             |
|-------------------|------------------------------------------------------|
| `BOOK_AUTHOR`     | Links books with multiple authors                    |
| `BOOK_GENRE`      | Links books with multiple genres                     |

---

## 🛠️ Technologies Used

- **SQL** (MySQL-compatible syntax)
- Schema written for RDBMS (Relational Database Management Systems)




![image](https://github.com/user-attachments/assets/fd90474c-2eb3-455f-825d-6c1c4b3b4a04)
![image](https://github.com/user-attachments/assets/dbe033bc-4ec0-427a-a31f-af4940097c09)




