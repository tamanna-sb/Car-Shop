# 🚗 Car Shop E-Commerce Platform

## Overview
Car Shop is a modern **e-commerce platform** designed for buying and selling cars. It is built using **C#, ASP.NET Core MVC, Razor Pages, SQL Server, Entity Framework, and AWS**. The platform features **secure authentication with Two-Factor Authentication (2FA)**, an intuitive **Admin Dashboard**, and a **user-friendly shopping experience** with features like product search, user management, and payment processing.

---

## 📌 Features

### 🔐 Authentication & Security
- **User Authentication** (Register/Login)
- **Two-Factor Authentication (2FA)** for enhanced security
- **Role-based access control** (Admin, Dealer, Customer)

### 🛠️ Admin Dashboard
- **User Management**: Modify user roles (Admin, Dealer, Customer)
- **Brand & Dealer Management**: Add, update, or remove brands and dealers
- **Product Management**: Add, update, or remove cars from the platform
- **Order Management**: View and manage customer orders

### 🛒 Shopping & Orders
- **Search & Filter**: Browse cars by brand, model, price, etc.
- **Add to Cart**: Users can add cars to their shopping cart
- **Checkout & Payment**: Secure payment processing integration

### ☁️ Cloud & Database
- **Hosted on AWS**
- **SQL Server Database** using Entity Framework

---

## 🏗️ Tech Stack
- **Backend**: C#, ASP.NET Core MVC, Razor Pages
- **Frontend**: Razor Pages, HTML, CSS, JavaScript
- **Database**: SQL Server, Entity Framework
- **Cloud**: AWS
- **Security**: 2FA, Role-based access control

---

## 🚀 Installation & Setup

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/tamanna-sb/Car-Shop
cd car-shop
```

### 3️⃣ Configure the Database
- Install **SQL Server** and update the connection string in `appsettings.json`.
- Apply migrations:
```sh
dotnet ef database update
```

### 4️⃣ Run the Application
```bash
dotnet run
```
The application will be available at `http://localhost:5000`.

---

## 📝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License
This project is licensed under the **MIT License**.


