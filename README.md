# Product Management System

## Project Overview
This project is a Product and Category Management System built with ASP.NET Core and EF Core.  
It allows administrators to manage products and categories.

---

## Current Progress
1. **Data Models**
   - User
   - Product
   - Category
   - ProductCategory (many-to-many relationship)
2. **Database Connection**
   - SQL Server connection configured in `appsettings.json`
   - DbContext (`AppDbContext`) is set up

---

## Project Structure

 ProductManagementDashboard /
├──  ProductManagementDashboard.Api/ # API layer
└──  ProductManagementDashboard.Data/ # Data layer
├── Models/ # Entities
└── AppDbContext.cs
## Technologies Used
- ASP.NET Core Web API
- Entity Framework Core
- C#
- SQL Server

---

## Next Steps
- Implement API endpoints for CRUD operations
- Add image upload for products
- Enable filtering by categories/tags
- Add authentication for admin users