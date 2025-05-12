# 🌾 Farming Produce Marketplace (MySQL Database)

This project is a relational database system for a Farming Produce Marketplace — a platform that connects farmers and buyers to list, discover, and order fresh farm products.

---

## 🧾 Project Description

This MySQL-based database manages:

- **User accounts** (farmers and buyers)
- **Produce listings**
- **Product categories**
- **Orders and order items**
- **Payment tracking**

It demonstrates how a digital agriculture system might be structured behind the scenes, using proper normalization, relationships, and constraints.

---

## 🏗️ Features

- Farmers can list multiple products
- Buyers can browse and place orders
- Orders can contain multiple items
- Categories organize product types
- Payments are tracked per order

---

## 🗃️ Database Tables

- `Users` – All users (farmers and buyers)
- `Categories` – Produce categories like fruits, grains, etc.
- `Products` – Produce listed by farmers
- `Orders` – Orders placed by buyers
- `Order_Items` – Junction table linking orders to products
- `Payments` – Payment tracking table

---

## 🚀 How to Set Up

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/farming-produce-marketplace.git
   cd farming-produce-marketplace
