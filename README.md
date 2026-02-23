# 💰 Expense Tracker

A web-based personal finance application that helps users record and monitor their daily spending through a clean, mobile-friendly interface.

🔗 **Live Demo:** [https://faiz-alam.github.io/expense-tracker/](https://faiz-alam.github.io/expense-tracker/)

---

## 📌 Overview

The Expense Tracker is a **Sprint 1 frontend implementation** built using HTML, CSS, and JavaScript. All data is stored in the browser using **Local Storage** — no backend or internet connection is required.

The application consists of three pages connected using standard HTML anchor tag navigation:

1. **Landing Page** (`index.html`) — Introduces the app with a hero section, features summary, and a 'Get Started' button.
2. **Login / Signup Page** (`login.html`, `signup.html`) — Register and login with JavaScript form validation. Credentials are stored in Local Storage.
3. **Dashboard** (`dashboard.html`) — Core page where users add, view, filter, and delete expenses.

---

## ✨ Features

- 🔐 **User Registration & Login** — Form validation with inline error messages
- ➕ **Add Expenses** — Log category, item name, amount, and date
- 📋 **View Expenses** — All expenses displayed in a structured table
- 🗑️ **Delete Expenses** — Remove any entry instantly
- 🔍 **Category Filter** — Filter expenses by Food, Transport, Shopping, Bills, Entertainment, or Others
- 🧮 **Total Calculation** — Dynamically calculates total spending based on the active filter
- 🚪 **Logout** — Clears session from Local Storage and redirects to login
- 📱 **Responsive Design** — Mobile-first layout using Flexbox

---

## 🛠️ Built With

| Layer | Technology |
|-------|------------|
| Structure | HTML5 |
| Styling | CSS3 (Flexbox, Media Queries) |
| Logic | JavaScript ES6 (DOM, Local Storage) |

---

## 📁 Project Structure

```
expense-tracker/
├── index.html        # Landing page
├── login.html        # Login page
├── signup.html       # Signup / Register page
├── dashboard.html    # Main dashboard
├── images/           # Image assets
├── style/            # CSS files
└── index.js          # JavaScript logic
```

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/faiz-alam/expense-tracker.git
   ```
2. Open the project folder and launch `index.html` in your browser.

> No installation or setup required — it runs entirely in the browser.

---

## 📊 Data Stored in Local Storage

**User Info:**
- `username` — Name entered during registration
- `email` — Used as login identifier
- `pass` — Password (prototype-level storage)

**Expense Records:**
- `id` — Auto-generated unique identifier
- `category` — Food, Transport, Shopping, Bills, Entertainment, Others
- `itemName` — Name/description of the purchase
- `amount` — Price (positive number)
- `date` — Date of the expense
- `notes` — Optional remarks

---

## 🔮 Future Enhancements (Sprint 2)

- [ ] Rebuild frontend using **React.js** for component-based architecture
- [ ] Add backend using **Node.js** with **SQL database** for cloud storage
- [ ] Implement proper authentication with hashed passwords and session tokens
- [ ] Add **data visualization** using Chart.js (spending by category)
- [ ] Allow users to **edit** existing expense entries
- [ ] Set monthly **budget goals** with alerts when approaching the limit

---

## 👤 Author

**Mohd Faiz Alam**  
Student ID: AF05041897 | Batch: ANP-D3238  
Project Guide: Ms. Maseera Jamal Shaikh

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
