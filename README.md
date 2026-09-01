# 🍔 FoodRush – Food Ordering & Analytics Platform

FoodRush is a full-stack food ordering web application built using **Python, Flask, MySQL, HTML, CSS, and JavaScript**. The project also includes a **Power BI dashboard** for analyzing food-ordering data and generating business insights.

---

## 📌 About the Project

FoodRush is an online food ordering platform where users can browse food items, search for food, add items to their cart, manage their wishlist, apply coupons, place orders, select payment methods, rate food items, and view their order history.

The project combines **full-stack web development, database management, and business intelligence** into one practical application.

### Main Components

- 🍔 Food ordering web application
- 🐍 Flask backend
- 🗄️ MySQL database
- 🌐 HTML, CSS & JavaScript frontend
- 📊 Power BI analytics dashboard

---

## ✨ Features

### 👤 User Management

- User registration
- User login and logout
- Session-based authentication
- Profile management
- Password change functionality

### 🍽️ Food Browsing

- Browse food items
- Search food items
- View food item details
- Browse food categories
- View food ratings

### 🛒 Shopping Cart

- Add food items to cart
- Update item quantities
- Remove items from cart
- Calculate order totals
- Checkout functionality

### ❤️ Wishlist

- Add food items to wishlist
- Remove food items from wishlist
- View saved food items

### 🎟️ Coupon System

- Apply coupon codes
- Validate minimum order requirements
- Calculate percentage-based discounts
- Apply maximum discount limits

### 📦 Order Management

- Place food orders
- Store order details in MySQL
- Store order items
- View order history
- View order information

### ⭐ Rating System

- Rate food items
- Update existing ratings
- Calculate food-item ratings

### 💳 Payment

- Select payment methods
- Payment confirmation interface
- Store payment information associated with orders

> **Note:** The payment functionality is implemented as a demonstration interface and is not connected to a production payment gateway.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| MySQL | Database management |
| HTML5 | Frontend structure |
| CSS3 | Frontend styling |
| JavaScript | Frontend functionality |
| Power BI | Data analysis and visualization |
| Git | Version control |
| GitHub | Source code hosting |

---

## 🏗️ Application Architecture

```text
FoodRush User
     ↓
HTML / CSS / JavaScript
     ↓
Flask Backend
     ↓
MySQL Database
     ↓
Order & Customer Data
     ↓
Power BI Dashboard

📁 Project Structure
FoodRush/
│
├── static/
│   └── food images and static resources
│
├── templates/
│   └── index.html
│
├── app.py
├── data_sql.sql
├── FoodRush - Dashboard.pbix
├── README.md
├── requirements.txt
└── .gitignore

File Description
File / Folder	Description
app.py	Main Flask backend application
templates/	HTML templates
static/	Images and static frontend resources
data_sql.sql	Database schema and seed data
FoodRush - Dashboard.pbix	Power BI dashboard
requirements.txt	Required Python packages
.gitignore	Files excluded from GitHub
README.md	Project documentation
🗄️ Database

FoodRush uses MySQL as the backend database.

The database manages information related to:

Users
Food categories
Food items
Orders
Order items
Wishlist
Coupons
Ratings
Payments

The Flask application connects to MySQL to retrieve and update application data.

📊 Power BI Dashboard

FoodRush includes a Power BI dashboard for analyzing food-ordering data.

The dashboard provides a business analytics layer on top of the application database.

Analytics Areas

The dashboard can be used to analyze:

Sales performance
Order trends
Customer activity
Food-item performance
Category performance
Business KPIs
Power BI File

FoodRush - Dashboard.pbix

Open the .pbix file using Microsoft Power BI Desktop.

⚙️ Installation & Setup
1. Prerequisites

Install the following:

Python 3.x
MySQL Server
MySQL Workbench
Microsoft Power BI Desktop
2. Clone the Repository
git clone YOUR_GITHUB_REPOSITORY_URL

Move into the project directory:

cd FoodRush-Food-Ordering-System
3. Install Python Dependencies

Install the required Python packages:

pip install -r requirements.txt
4. Configure MySQL

Make sure your MySQL Server is running.

Import the provided SQL file:

data_sql.sql

You can import the SQL file using MySQL Workbench or the MySQL command line.

5. Configure Environment Variables

Create a .env file inside the project directory.

Add your local MySQL configuration:

MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=your_mysql_password
MYSQL_DATABASE=zomato
SECRET_KEY=your_secret_key

Replace the values with your own local configuration.

Important: Never upload .env to GitHub because it can contain passwords and secret keys.

6. Run the Application

Start the Flask application:

python app.py

The application will run locally at:

http://127.0.0.1:5000

Open the address in your browser.

🔐 Security

Sensitive configuration values are stored using environment variables.

The following information should never be published in a public repository:

MySQL passwords
Flask secret keys
API keys
Private credentials
Real customer information
Real payment credentials

The .gitignore file is used to prevent sensitive files such as .env from being uploaded.

🧪 Demo Data

The project uses database data for demonstrating the functionality of the FoodRush application.

Only demo or fictional data should be included in the public repository.

Real personal, customer, payment, or confidential information should not be published.

🎯 Key Learning Outcomes

This project demonstrates practical experience with:

Python programming
Flask web development
MySQL database integration
SQL queries
CRUD operations
User authentication
Session management
Shopping cart functionality
Wishlist functionality
Coupon and discount logic
Order management
Rating functionality
Frontend development
Business intelligence
Power BI dashboard development
Git and GitHub
🚀 Future Enhancements

Possible future improvements include:

Online payment gateway integration
Admin dashboard
Restaurant/vendor management
Real-time order tracking
Email notifications
SMS notifications
Cloud deployment
REST API
Mobile application
Advanced customer analytics
Improved authentication and authorization
📌 Project Highlights

FoodRush combines full-stack web development with business intelligence.

Python
   ↓
Flask
   ↓
MySQL
   ↓
Food Ordering Application
   ↓
Order & Customer Data
   ↓
Power BI
   ↓
Business Insights

This project demonstrates how a web application can be connected to a relational database and then used to generate meaningful business insights through Power BI.

👩‍💻 Author
Lakshmi Sundaramoorthy

FoodRush – Food Ordering & Analytics Platform

A full-stack web deelopment and business intelligence project created for educational and portfolio purposes.
