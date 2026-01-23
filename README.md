# 📦 Smart Warehouse Inventory System

A web-based application that helps warehouse managers monitor and control inventory levels with real-time visibility and intelligent automation.

## 🚀 Project Overview

The **Smart Warehouse Inventory System** provides tools to track inventory in real-time, audit stock discrepancies, and generate actionable insights through dashboards and predictive analytics. Built using MongoDB, Node.js, and plain HTML/CSS/JavaScript, it ensures a lightweight yet powerful solution.

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js
- **Database:** MongoDB
- **Real-Time Updates:** AJAX (Fetch API)
- **Visualization:** Chart.js (for dashboards)
- **Notifications:** JavaScript

## 🌟 Core Features

- **Real-Time Inventory Tracking**
  - Add/remove items dynamically with instant updates.
- **Automated Inventory Auditing**
  - Periodic checks to flag discrepancies between expected and actual stock levels.
- **Interactive Dashboards**
  - Visualize stock levels, turnover rates, and trends.

## 🔮 Extra Features

- **Predictive Restocking**
  - Suggests restocking based on historical usage data.
- **Automated Notifications**
  - Sends alerts when stock hits critical thresholds.

## 📂 Project Structure

```
Smart Warehouse System/
├── config/
│   ├── mongoCollections.js
│   ├── mongoConnection.js
│   └── settings.js
├── data/
│   ├── auditController.js
│   ├── dashboardController.js
│   ├── inventoryController.js
│   ├── logController.js
│   ├── reportController.js
│   └── userController.js
├── middlewares/
│   └── auth.js
├── public/
│   ├── css/
│   │   ├── dashboard.css
│   │   ├── inventory.css
│   │   ├── login.css
│   │   ├── logs.css
│   │   ├── main.css
│   │   ├── register.css
│   │   ├── reports.css
│   │   └── settings.css
│   ├── images/
│   │   └── swisLogo.png
│   └── js/
│       ├── main.js
│       └── dashboard.js
├── routes/
│   ├── auditRoutes.js
│   ├── dashboard.js
│   ├── index.js
│   ├── inventory.js
│   ├── reports.js
│   ├── settings.js
│   └── users.js
├── utils/
│   └── validations.js
├── views/
│   ├── layouts/
│   │   └── main.handlebars
│   ├── dashboard.handlebars
│   ├── error.handlebars
│   ├── inventory-admin.handlebars
│   ├── inventory-user.handlebars
│   ├── login.handlebars
│   ├── register.handlebars
│   ├── reports.handlebars
│   └── settings.handlebars
├── .gitignore
├── app.js
├── LICENSE
├── package.json
├── package-lock.json
├── README.md
└── seed.js
```

## ⚙️ Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/VaibhavGaneriwala/warehouse-inventory-system.git
```

```
cd warehouse-inventory-system/
```

### 2. Install Dependencies

```
npm install
```

### 3. Seed the database with seed file

```
npm run seed
```

### 4. Run the Application

```
npm start
```

Visit `http://localhost:3000` in your browser.

### 5. Username and Password to test the program.
```
Admin:
Username: lego
Password: Password@1

User:
Username: superman
Password: Superman@1
```

## 📈 Future Improvements

- Enhancing Automation
- Advanced Reporting & Analytics
- Integration with Other Systems

## 🤝 Contributors

- Vaibhav Ganeriwala
- Erik Bobinski
- Neha Sutariya
- Terynce Chan

## 📄 License

This project is licensed under the [MIT License](LICENSE).