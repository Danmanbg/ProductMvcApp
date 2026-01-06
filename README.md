ProductMvcApp 🛒

ProductMvcApp is a small ASP.NET Core MVC application demonstrating a product management system with categories, images, shopping cart, and orders. It uses Code First with SQL Server LocalDB and standard MVC architecture.

Features

Products & Categories: Add, edit, delete products and categories (1→many relationship).
Product Images: Store image URLs for products and display them.
Product Details: View full product info including category, price, and image.
Shopping Cart: Session-based cart without login; add products and adjust quantities.
Orders: Checkout from the cart, creating an order with multiple items.
MVC + Code First: Models → Controllers → Views; automatic database migrations.


How to Run
Open the solution in Visual Studio 2022.
Ensure SQL Server LocalDB is installed.

Apply migrations:

Add-Migration InitialCreate
Update-Database

Run the project (F5 / IIS Express).
Use the UI to manage categories, products, cart, and orders.
Tech Stack
ASP.NET Core MVC
C#
SQL Server LocalDB (Code First)
Razor Views
Session-based cart

Links
Repository: https://github.com/Danmanbg/ProductMvcApp
