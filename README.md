# 🍽️ Restaurant Review Platform

A PHP-based web application that allows users to browse, review, and interact with restaurants through a structured account system. The platform includes functionality for clients, restaurateurs, and moderators, with a relational database backing the core features.

## 🔧 Features

### 👤 User Roles
- **Clients**: Can create accounts, browse restaurants, leave detailed reviews (including delivery/service ratings), and view statistics.
- **Restaurateurs**: Register their restaurants, define menus, opening hours, cuisine type, price range, and manage their public page.
- **Moderators**: Review and moderate client comments. Offensive or misleading content can be removed with a logged justification.

### 📝 Review System
- Clients can rate restaurants on a 5-star scale and leave comments with tags like “Recommended”, “Not Recommended”, or “Avoid Urgently”.
- Support for evaluating both dine-in and delivery experiences.
- Detailed review data includes visit time, items consumed, and total paid.

### 🍽 Menu Management
- Restaurants manage menus with dishes, prices, and allergen listings.
- Support for various cuisine types (e.g., Asian, Mexican, etc.).

### 📊 Data Queries & Insights
The backend supports advanced data queries and filters such as:
- Restaurants with average ratings supperior to a choosen value.
- The restaurant with the most and least expensive dish.
- Clients who consumed the most type of dishes.
- Analysis of cuisine types by rating range.

Queries were implemented using SQL and in some cases formal relational algebra/tuple calculus as demonstrated in the project report.

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS  
- **Backend**: PHP  
- **Database**: SQL   
- **Tools**: XAMPP/LAMP stack

## 📁 Project Structure

- `php/setup_database.php`: Database initialization and data import
- `php/`: All server-side logic
- `assets/`: Static content (CSS, images)
- `index.php`: Landing page

