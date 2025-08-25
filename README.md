# 💸 FinTrack - Personal Finance Management App

FinTrack is a full-stack web application that helps users efficiently manage their personal finances by tracking **income**, **expenses**, **budgets**, and analyzing financial trends with interactive visualizations.


## 🚀 Features

### 🔐 User Authentication
- Register and login using secure JWT-based authentication.
- Multiple user support

### 🔎Pagination
- Efficiently handles large datasets by displaying data in manageable chunks.
- Enhances user experience by enabling quick navigation between pages.

### 💰 Income Tracker
- Add multiple income sources (salary, freelancing, etc.).
- View and manage income history.

### 🧾 Expense Manager
- Add expenses with or without uploading receipts.
- Categorize expenses (e.g., food, travel, shopping).
- Upload PDF/image receipts (POS supported).

### 🎯 Budget Planning
- Set monthly budgets.
- Track budget utilization against expenses.

### 📊 Dashboard Insights
- Monthly income vs expenses overview.
- Financial summaries and spending categories.
- Visualizations with Pie and Bar charts.

### 🔎 Visual Analytics
- Dynamic data filtering and visualizations using Chart.js.
- Search historical income/expenses.

### 🌗 Dark Mode Support
- Toggle between light and dark themes for enhanced user experience.


### 🧾 Receipt Upload Support

- Accepts `.jpg`, `.jpeg`, `.png`, `.pdf` files.
- Files are stored via backend and linked to the related expense record.
- Fallback API available for expense creation without receipt upload.


### 🛠️ Tech Stack
- Frontend: React.js, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MySQL
- Authentication: JWT
- Chart: Charts.js

---
## 📁 Folder Structure
```bash
xpensify/
├── backend/
│ ├── routes/
│ ├── controllers/
│ ├── middleware/
│ ├── helper/
│ ├── server.js
│ └── .env
├── frontend/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── App.js
│ └── constants/index.js
├── screenshots/
│ ├── dashboard.png
│ ├── add-income.png
│ └── receipt.png
└── README.md

```
