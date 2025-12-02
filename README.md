# stock-trading-app

# 📈 Zerodha Clone – Full-Stack Trading Platform

A full-featured trading platform inspired by Zerodha, built for learning and development.
This project includes authentication, stock charts, dummy live price feed, order placement, and portfolio management — all in a clean and modern UI.

---

## 📚 Table of Contents

* About the Project
* Features
* Tech Stack
* Folder Structure
* Installation
* Environment Variables
* Running the Project
* API Routes
* Screenshots (Add your own)
* Future Enhancements
* Contributing
* License

---

# 🧩 About the Project

This is a **Zerodha-like stock trading platform clone**, created for educational purposes.
The goal is to understand how trading platforms work — UI, backend APIs, charts, portfolio, and order logic.

---

# 🚀 Features

### 🔐 Authentication

* Signup, Login
* JWT Token authentication
* Secure password hashing

### 📊 Market Dashboard

* Dummy live market feed
* Candlestick & line charts
* Top gainers & losers widget

### 💼 Portfolio

* Real-time portfolio updates
* Investment summary
* Profit / Loss calculation

### 🛒 Order System

* Buy & Sell stocks
* Market / Limit order
* Order history

### ⚙️ User Settings

* Update profile
* Dark / Light theme
* Logout

---

# 🧱 Tech Stack

### **Frontend**

* HTML, CSS, JavaScript
* React.js (optional)
* Chart.js / Recharts

### **Backend**

* Node.js
* Express.js
* MongoDB / MySQL
* JWT Authentication

### **Other Tools**

* Axios
* WebSockets (Optional)

---

# 📁 Folder Structure

```
/zerodha-clone
│── /client                 # Frontend
│   │── /src
│   │── package.json
│
│── /server                 # Backend
│   │── /routes
│   │── /models
│   │── /controllers
│   │── server.js
│   │── package.json
│
│── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/zerodha-clone.git
cd zerodha-clone
```

## 2️⃣ Install dependencies

### Frontend

```bash
cd client
npm install
npm start
```

### Backend

```bash
cd server
npm install
npm run dev
```

---

# 🔧 Environment Variables

Inside `/server`, create `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

(Optional for frontend)

```
REACT_APP_BACKEND_URL=http://localhost:5000
```

---

# ▶️ Running the Project

### **Start Backend**

```bash
cd server
npm run dev
```

### **Start Frontend**

```bash
cd client
npm start
```

Project will run on:

* Backend → [http://localhost:5000](http://localhost:5000)
* Frontend → [http://localhost:3000](http://localhost:3000)

---

# 🧪 API Routes

## **Auth Routes**

| Method | Route            | Description   |
| ------ | ---------------- | ------------- |
| POST   | /api/auth/signup | Register user |
| POST   | /api/auth/login  | Login user    |

## **Stock / Market Routes**

| Method | Route          | Description          |
| ------ | -------------- | -------------------- |
| GET    | /api/market    | Dummy market data    |
| GET    | /api/stock/:id | Single stock details |

## **Order Routes**

| Method | Route            | Description   |
| ------ | ---------------- | ------------- |
| POST   | /api/orders/buy  | Buy stock     |
| POST   | /api/orders/sell | Sell stock    |
| GET    | /api/orders      | Order history |

## **Portfolio Routes**

| Method | Route          | Description    |
| ------ | -------------- | -------------- |
| GET    | /api/portfolio | User portfolio |

---

# 📸 Screenshots

Add your images inside `/screenshots` folder:

```
/screenshots
    dashboard.png
    login.png
    portfolio.png
    place-order.png
```

Add them in README:

```
![Dashboard](./screenshots/dashboard.png)
```

---

# 🔮 Future Enhancements

* Real-time stock market API
* Mutual funds & F&O section
* Funds add / withdraw
* Notification alerts
* Mobile app (React Native)

---

# 🤝 Contributing

Pull Requests are welcome!
For major changes, please open an issue first to discuss your ideas.

---

# 📜 License

This project is created **only for educational purposes**.
It is **not intended for real trading or financial use**.
