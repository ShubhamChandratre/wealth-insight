# 💸 AI Finance Platform

A full-stack AI-powered finance management platform built with **React 19**, **Next.js 15**, and **Shadcn UI**, featuring transaction tracking, budgeting, automation, and insightful dashboards. The project integrates modern tooling like **Supabase**, **Prisma**, **Clerk**, **Inngest**, and **Arcjet** to offer a secure, intelligent, and production-ready finance solution.

---

## 🚀 Features

- ✅ **User Authentication** – Seamless sign-in/signup with Clerk
- 💳 **Transaction Management** – Add, edit, delete, and view transactions
- 📊 **Dashboards** – Dynamic charts for expenses, budgets, and financial reports
- 🧠 **AI Receipt Scanner** – Extract transaction data from uploaded images
- 🔁 **Recurring Transactions** – Scheduled with Inngest functions
- 📬 **Budget Alerts** – Automated emails for budget overspending
- 📈 **Monthly Reports** – AI-generated financial summaries
- 🛡️ **Rate Limiting & Bot Protection** – Powered by Arcjet Shield

---

## 🧰 Tech Stack

**Frontend:**  
React 19, Next.js 15, Tailwind CSS, Shadcn UI  

**Backend & DB:**  
Supabase (PostgreSQL), Prisma ORM  

**Authentication & Automation:**  
Clerk, Inngest  

**Security & Infra:**  
Arcjet, Vercel  

**Dev Tools:**  
Git/GitHub, VS Code, Postman, Docker

---

## ⚙️ Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/ShubhamChandratre/wealth-insight.git
   cd wealth-insight

2. **Installing Dependencies
    ```bash
    npm install --legacy-peer-deps

3. Create a .env file and configure environment variables for Supabase, Clerk, Inngest, and Arcjet.
    ```bash
   # Connect to Supabase via connection pooling
   DATABASE_URL=""
   
   # Direct connection to the database. Used for migrations
   DIRECT_URL=""
   
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
   
   GEMINI_API_KEY=
   RESEND_API_KEY=
   ARCJET_KEY=

4. Run the development server
    ```bash
    npm run dev
