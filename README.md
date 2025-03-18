# Car Shop E-Commerce Platform

## Overview
Car Shop is a feature-rich e-commerce web application built using **C#, ASP.NET Core MVC, Razor Pages, SQL Server & Entity Framework**. It provides a seamless experience for users to browse, search, and purchase cars while offering an extensive admin panel for managing products, users, and system configurations.

## Features

### **User Features**
- **Car Search & Filtering:** Users can search for cars based on brand, model, price, and dealer.
- **Product Listings & Details:** View detailed car information, including specifications, images, and price.
- **User Authentication & Authorization:** Secure login and registration system with authentication via Identity.
- **Shopping Cart & Checkout:** Add cars to the cart, manage items, and complete purchases with integrated payment.

### **Admin Dashboard**
- **Role Management:** Assign and modify roles (Admin, Dealer, Customer) with different permission levels.
- **Brand & Dealer Management:** Create, update, and delete brands and dealers to keep inventory up-to-date.
- **Car Inventory Management:** Add, edit, and remove vehicles from the system.
- **Order Management:** Track, update, and process customer orders.

## Tech Stack
- **Frontend:** Razor Pages, HTML, CSS, JavaScript
- **Backend:** C#, ASP.NET Core MVC
- **Database:** SQL Server, Entity Framework
- **Cloud & DevOps:** AWS (for hosting and storage)
- **Authentication:** ASP.NET Identity

## Installation & Setup
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/tamanna-sb/Car-Shop
   cd Car-Shop
   ```
2. **Set Up Database:**
   - Install **SQL Server** and update the connection string in `appsettings.json`.
   - Apply migrations:
     ```sh
     dotnet ef database update
     ```
3. **Run the Application:**
   ```sh
   dotnet run
   ```
4. **Access the App:**
   - Open `http://localhost:5000` in your browser.
   - Login as Admin to access the dashboard.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for discussion.

## License
This project is licensed under the MIT License.


