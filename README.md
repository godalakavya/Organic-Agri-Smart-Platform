# 🌾 Organic Agri Smart Platform
### A Web-Based Platform for Farmers & Buyers | Python Flask + MySQL + HTML/CSS

<div align="center">

![Banner](images/banner_girl.png)

</div>

---

## 📌 Project Overview
The **Organic Agri Smart Platform** is a web-based application designed to connect farmers and buyers directly. It helps farmers list their organic produce online and allows buyers to search and purchase products based on type, price, and location.

This platform removes middlemen, reduces travel costs for farmers, and promotes sustainable organic farming through knowledge sharing and modern digital tools.

---

## 🎯 Key Features

### 👨‍🌾 Farmer Features
- Secure registration and login
- Add organic products with price, description & images
- Update or delete products
- View customer orders
- Access farming categories & resources

### 🛒 Buyer Features
- Search organic products by:
  - Type
  - Location
  - Price
- View product details & farmer information
- Place purchase requests
- Verify product quality before buying

### 🛠 Admin Features
- Manage farmers
- Manage farming categories
- View triggers/logs for all operations
- View and manage all agro-products
- Secure authentication system

---

## 📚 Tech Stack Used
| Layer | Technologies |
|-------|--------------|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend** | Python Flask |
| **Database** | MySQL (SQLAlchemy ORM) |
| **Server** | XAMPP / Apache |
| **Other** | Flask-Login, Werkzeug Security |

---

## 🗂 Project Modules

### 🔹 Authentication
- Signup / Login
- Password encryption
- Role-based access

### 🔹 Product Management
- Add / Edit / Delete agro products
- Product search & filtering
- Product listing page

### 🔹 Farmer Module
- Add farmer details
- Manage farming types
- Farmer database management

### 🔹 Trigger Logging System
Tracks all farmer table events:
- Insert
- Update
- Delete

Stored inside **trig** table.

---

## 🏗 System Architecture
```
Frontend (HTML, CSS, JS, Bootstrap)
        |
Application Layer (Flask Business Logic)
        |
Database Layer (MySQL)
```
REST APIs ensure secure communication between layers.

---

## 💾 Database Tables
- `user`
- `register`
- `addagroproducts`
- `farming`
- `trig`

---

## 🚀 How to Run This Project
### **1️⃣ Install Dependencies**
```bash
pip install flask flask_sqlalchemy flask_login werkzeug
```

### **2️⃣ Start XAMPP**
- Start **Apache**
- Start **MySQL**
- Create a database named:
```
farmers
```

### **3️⃣ Run the Flask App**
```bash
python app.py
```

### **4️⃣ Open in Browser**
```
http://127.0.0.1:5000/
```

---

## 🧪 Testing Performed
- Unit Testing
- Integration Testing
- System Testing
- Security Testing (login & permissions)
- Performance & compatibility testing

---

## 📈 Future Enhancements
- Cloud database integration
- Online payment gateway
- Advanced analytics dashboard
- Real-time price predictions

---

## 🏁 Conclusion
The **Organic Agri Smart Platform** provides a modern, digital solution for farmers to sell their organic products directly and securely. It simplifies agricultural marketing, promotes sustainability, and empowers farmers with essential digital tools.

---

## 👨‍💻 Developed By
- **Godala Kavya**
- **Sreeja**
- **Nithish**
- **Nikitha**
