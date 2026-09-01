# 🍔 FoodRush – Food Ordering & Analytics Platform

FoodRush is a full-stack food ordering web application built using **Python, Flask, MySQL, HTML, CSS, and JavaScript**. The project also includes a **Power BI dashboard** for analyzing food-ordering data and generating business insights.

---

## 📌 About the Project

FoodRush is designed as an online food ordering platform where users can browse food items, search for products, add items to their cart, manage their wishlist, apply coupons, place orders, make payments through the available payment interface, rate food items, and view their order history.

The project combines **web application development, database management, and business intelligence** into a single solution.

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

- Browse available food items
- Search food items
- View food item details
- Display food categories
- View food ratings

### 🛒 Shopping Cart

- Add food items to cart
- Update quantities
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
- Update ratings
- Calculate item ratings

### 💳 Payment

- Payment method selection
- Payment confirmation interface
- Payment information associated with orders

> **Note:** The payment functionality in this project is intended as a demonstration interface and is not a production payment gateway.

---

# 🛠️ Technologies Used

| Technology | Usage |
|---|---|
| **Python** | Backend programming |
| **Flask** | Web application framework |
| **MySQL** | Database management |
| **HTML5** | Web page structure |
| **CSS3** | Styling and responsive design |
| **JavaScript** | Frontend interaction |
| **Power BI** | Data analysis and visualization |
| **Git** | Version control |
| **GitHub** | Source code hosting |

---

# 🏗️ Application Architecture

```text
                   ┌─────────────────────┐
                   │    FoodRush User    │
                   │      Interface      │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │    HTML / CSS / JS  │
                   │      Frontend       │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │    Flask Backend     │
                   │       Python         │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │    MySQL Database    │
                   │                     │
                   │ Users               │
                   │ Food Items          │
                   │ Categories          │
                   │ Orders              │
                   │ Order Items         │
                   │ Wishlist            │
                   │ Coupons             │
                   │ Ratings             │
                   │ Payments            │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │       Power BI       │
                   │ Analytics Dashboard  │
                   └─────────────────────┘
📁 Project Structure
FoodRush/
│
├── app.py
├── data_sql.sql
├── FoodRush DB.sql
├── README.md
├── requirements.txt
├── .gitignore
├── .env.example
│
├── static/
│   └── ...
│
├── templates/
│   └── index.html
│
└── FoodRush - Dashboard.pbix
File Description
File / Folder	Description
app.py	Main Flask backend application
templates/	HTML templates
static/	CSS, JavaScript, images and static resources
data_sql.sql	SQL/database setup data
FoodRush DB.sql	FoodRush database SQL file
FoodRush - Dashboard.pbix	Power BI dashboard
requirements.txt	Python dependencies
.env.example	Example environment configuration
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

FoodRush includes a Power BI dashboard for analyzing the food-ordering data.

The dashboard provides a business analytics layer on top of the application database.

Analytics Areas

The dashboard can be used to analyze areas such as:

Sales performance
Order trends
Customer activity
Food-item performance
Category performance
Business KPIs
Power BI File
FoodRush - Dashboard.pbix

Open this file using Microsoft Power BI Desktop.

⚙️ Installation & Setup
1. Prerequisites

Make sure the following are installed on your computer:

Python 3.x
MySQL Server
MySQL Workbench
Git
Microsoft Power BI Desktop
2. Clone the Repository
git clone YOUR_GITHUB_REPOSITORY_URL

Move into the project directory:

cd FoodRush
3. Install Python Dependencies

Install the required Python packages:

pip install -r requirements.txt
4. Configure MySQL

Make sure your MySQL server is running.

Create the FoodRush database using the provided SQL file.

You can import the SQL file using MySQL Workbench or the MySQL command line.

5. Configure Environment Variables

Create a file named:

.env

inside the project directory.

Add:

MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=your_mysql_password
MYSQL_DATABASE=zomato
SECRET_KEY=your_secret_key

Replace the values with your local MySQL configuration.

Important

The .env file contains sensitive configuration information and should never be uploaded to GitHub.

The repository includes .env.example as a template.

6. Run the Application

Run the Flask application:

python app.py

The application will run locally.

Open your browser and visit:

http://127.0.0.1:5000
🔐 Security

Sensitive configuration values are stored using environment variables.

The project uses:

.env

for local configuration.

The following information should never be committed to a public GitHub repository:

MySQL passwords
Flask secret keys
API keys
Private credentials
Real customer information
Real payment credentials

The .gitignore file is used to prevent sensitive files from being uploaded.

🧪 Demo Data

The project uses database data for demonstrating the functionality of the FoodRush application.

When publishing the repository publicly, only demo or fictional data should be included.

Personal or sensitive customer information should not be included in the public repository.

🎯 Key Learning Outcomes

This project demonstrates practical experience in:

Python programming
Flask web development
MySQL database integration
SQL queries
CRUD operations
User authentication
Session management
Shopping cart implementation
Wishlist functionality
Coupon and discount logic
Order management
Rating functionality
Frontend development
Business intelligence
Power BI dashboard development
Git and GitHub
🚀 Future Enhancements

The following features could be added in future versions:

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

This makes the project a practical demonstration of both software development and data analytics.

👩‍💻 Author
Lakshmi Sundaramoorthy

FoodRush – Food Ordering & Analytics Platform

Developed as a full-stack web development and business intelligence project.

📄 License

This project is created for educational and portfolio purposes.