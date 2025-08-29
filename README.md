<div align="center">
  <h3 align="center">SaaS LMS Application – Built with Next.js, Supabase & Stripe</h3>
  <div align="center">
    A modern Learning Management SaaS platform with authentication, subscriptions, AI voice agents, and more.
  </div>
</div>

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
5. [Assets](#assets)
6. [More](#more)

## 🚀 Introduction

This project is a SaaS Learning Management System (LMS) application built from scratch. It features user authentication, subscriptions, payments, AI voice agents, and a modern UI. The stack includes Next.js, Supabase, Stripe, Clerk, Vapi, and more.

If you need help or want to contribute, feel free to open an issue or pull request.

## ⚙️ Tech Stack

- **[Next.js](https://nextjs.org/)** – React framework for building fast, scalable web apps.
- **[Supabase](https://supabase.com/)** – Open-source backend-as-a-service (PostgreSQL, Auth, Storage, Realtime).
- **[Stripe](https://stripe.com/)** – Payment processing and subscription management.
- **[Clerk](https://clerk.com/)** – Authentication and user management.
- **[Vapi](https://vapi.com/)** – Voice AI platform for conversational agents.
- **[Tailwind CSS](https://tailwindcss.com/)** – Utility-first CSS framework.
- **[shadcn/ui](https://ui.shadcn.com/)** – Accessible, customizable UI components.
- **[TypeScript](https://www.typescriptlang.org/)** – Typed JavaScript for better code quality.
- **[Zod](https://zod.dev/)** – TypeScript-first schema validation.

## 🔋 Features

- **AI Voice Agents:** Interactive tutoring sessions with AI-powered voice agents.
- **Authentication:** Secure sign-up/sign-in with Clerk (supports Google and more).
- **Billing & Subscriptions:** Manage plans, upgrades, and payments with Stripe.
- **Bookmarks & Session History:** Organize learning and revisit previous sessions.
- **Reusable Components:** Modular codebase for efficient development.
- **Create a Tutor:** Build custom AI tutors by subject, topic, and style.
- **Responsive Design:** Works seamlessly across all devices.
- **Database Integration:** Real-time data and storage with Supabase.
- **Modern UI/UX:** Clean, responsive design using Tailwind CSS and shadcn/ui.
- **Scalable Architecture:** Built for production and easy scaling.
- **Search Functionality:** Quickly find tutors with robust filters and search.

## 🤸 Quick Start

**Prerequisites**

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Clone the Repository**

```bash
git clone https://github.com/your-username/your-saas-lms-app.git
cd your-saas-lms-app
```

**Install Dependencies**

```bash
npm install
```

**Set Up Environment Variables**

Create a `.env` file in the root directory and add:

```env
# Sentry (optional)
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

# Stripe
STRIPE_SECRET_KEY=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholders with your actual credentials from [Supabase](https://supabase.com/), [Clerk](https://clerk.com/), [Stripe](https://stripe.com/), and [Vapi](https://vapi.com/).

**Run the Project**

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

