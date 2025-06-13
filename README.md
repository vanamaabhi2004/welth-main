# 💰 Finance Management App

A full-stack Finance Management App that helps you track expenses, monitor wealth, and analyze financial data. Built with modern authentication and database integration using Clerk and Supabase.

---

## 🚀 Features

- ✅ Income and expense tracking by category
- 📊 Financial analytics (monthly/yearly trends)
- 💼 Net worth & asset tracking
- 📅 Budget planning with visual insights
- 🔔 Alerts for spending, budgeting, and reminders
- 🌍 Multi-currency support
- 🔐 Secure authentication with Clerk

---

## 🛠️ Tech Stack

- **Frontend**: Next.js, Tailwind CSS, Clerk Auth
- **Backend**: API Routes, Supabase (PostgreSQL)
- **Auth**: Clerk (Hosted OAuth/Auth)
- **DB**: Supabase PostgreSQL
- **ORM**: Prisma

---

## 📦 Environment Variables

Create a `.env` file in the root of your project and add the following:

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Clerk Routing URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=sign-up

# Supabase - Connection Pooling (production)
DATABASE_URL=your_supabase_pooled_connection_url

# Supabase - Direct connection (migrations/dev)
DIRECT_URL=your_supabase_direct_connection_url

# Arcjet (optional security/observability)
ARCJET_KEY=your_arcjet_api_key
