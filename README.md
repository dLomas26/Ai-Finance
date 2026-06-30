<div align="center">

# 💰 Welth - AI Powered Personal Finance Platform

### Smart • Secure • AI-Driven Personal Finance Management

Manage your finances effortlessly with AI-powered insights, intelligent receipt scanning, budget tracking, recurring transactions, and beautiful analytics — all in one modern web application.

---

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?logo=prisma)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?logo=postgresql)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38BDF8?logo=tailwind-css)
![Gemini AI](https://img.shields.io/badge/Gemini-AI-blue)
![Clerk](https://img.shields.io/badge/Authentication-Clerk-purple)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

# 📖 Overview

**Welth** is a full-stack AI-powered finance management platform that helps users monitor their income, expenses, savings, and budgets with intelligent automation.

The platform leverages modern technologies including **Next.js 15**, **React 19**, **Prisma ORM**, **PostgreSQL**, **Gemini AI**, **Clerk Authentication**, **ArcJet Security**, **Inngest Background Jobs**, and **Tailwind CSS** to deliver a secure, scalable, and modern finance experience.

Whether you're tracking daily expenses, scanning receipts with AI, managing recurring payments, or receiving monthly financial reports, Welth provides everything you need in one place.

---

# ✨ Features

## 🔐 Authentication

- Clerk Authentication
- Secure Login & Signup
- Protected Routes
- Session Management

---

## 💳 Account Management

- Multiple Bank Accounts
- Balance Tracking
- Account Overview
- Account-wise Transactions

---

## 💸 Transaction Management

- Add Income & Expenses
- Edit Transactions
- Delete Transactions
- Filter Transactions
- Categorize Expenses
- Search Transactions

---

## 🤖 AI Features

- AI Receipt Scanner
- Automatic Transaction Extraction
- Smart Expense Categorization
- AI Financial Insights
- Monthly AI Reports

---

## 📊 Analytics Dashboard

- Expense Analytics
- Income Analytics
- Monthly Reports
- Interactive Charts
- Spending Trends
- Category Breakdown

---

## 📈 Budget Management

- Create Budgets
- Spending Limits
- Budget Tracking
- Budget Alerts
- Monthly Progress

---

## 🔄 Automation

- Recurring Transactions
- Automated Monthly Reports
- Background Jobs using Inngest
- Scheduled Email Reports

---

## 📧 Email Services

- Monthly Financial Reports
- Budget Notifications
- Transaction Alerts

---

## 🛡 Security

- Clerk Authentication
- ArcJet Rate Limiting
- Protected APIs
- Secure Server Actions
- Environment Variables

---

## 📱 Responsive UI

- Mobile Friendly
- Tablet Optimized
- Desktop Responsive
- Modern SaaS Design

---

# 🚀 Tech Stack

## Frontend

- Next.js 15
- React 19
- Tailwind CSS
- Shadcn UI
- Framer Motion
- Recharts

---

## Backend

- Next.js Server Actions
- Prisma ORM
- PostgreSQL
- Inngest
- ArcJet

---

## AI & Services

- Google Gemini API
- Clerk Authentication
- Resend Email API

---

## Database

- PostgreSQL
- Prisma ORM

---

# 📂 Project Structure

```bash
.
├── app/
│   ├── (auth)
│   ├── (main)
│   ├── api
│   ├── dashboard
│   ├── transaction
│   ├── account
│   └── layout.js
│
├── actions/
├── components/
│   ├── ui/
│   ├── dashboard/
│   ├── forms/
│   └── charts/
│
├── data/
├── hooks/
├── lib/
├── prisma/
├── public/
├── styles/
└── middleware.js
```
---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/dLomas26/Ai-Finance.git

cd Ai-Finance
```

---

## Install Dependencies

```bash
npm install
```

---

## Configure Environment Variables

Create a `.env` file in the project root.

```env
DATABASE_URL=

DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=

CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```

---

## Setup Database

```bash
npx prisma generate

npx prisma db push
```

or

```bash
npx prisma migrate dev
```

---

## Run Development Server

```bash
npm run dev
```

Open

```
http://localhost:3000
```

---

# 🌐 Environment Variables

| Variable | Description |
|-----------|-------------|
| DATABASE_URL | PostgreSQL Connection |
| DIRECT_URL | Direct PostgreSQL URL |
| NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY | Clerk Publishable Key |
| CLERK_SECRET_KEY | Clerk Secret Key |
| GEMINI_API_KEY | Google Gemini API |
| RESEND_API_KEY | Resend Email API |
| ARCJET_KEY | ArcJet Security API |

---

# 📊 Key Features

- AI Receipt Scanner
- AI Expense Categorization
- Smart Budget Tracking
- Interactive Charts
- Monthly Reports
- Automated Emails
- Secure Authentication
- Recurring Transactions
- Responsive Design
- Beautiful Dashboard

---

# 🔮 Future Enhancements

- Bank API Integration
- Investment Tracking
- OCR Improvements
- AI Financial Advisor
- Multi-Currency Support
- Export Reports (PDF & Excel)
- Mobile Application
- Expense Forecasting

---

# 👨‍💻 Author

## Deepanshu Lomas

- GitHub: https://github.com/dLomas26
- LinkedIn: https://linkedin.com/in/deepanshulomas
- Email: deepanshulomas@gmail.com

---

# ⭐ Support

If you found this project helpful:

⭐ Star this repository

🍴 Fork this repository

🐞 Report Issues

💡 Suggest Features

---

<div align="center">

### ⭐ If you like this project, don't forget to Star the repository ⭐

Made with ❤️ by **Deepanshu Lomas**

</div>


