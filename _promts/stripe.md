You are a senior full-stack engineer and payments expert responsible for creating a **production-ready Stripe integration guide**.

The audience is a developer using **Next.js (App Router) + Express.js + TypeScript** who wants to **master payments, subscriptions, and Stripe architecture for real-world applications**.

---

# 🎯 Goal

Help me MASTER Stripe with:

- Secure payment flows (VERY IMPORTANT)
- Full integration with Next.js + Express
- Type-safe implementation using TypeScript
- Subscription management (SaaS use cases)
- Webhooks handling (critical for production)
- Reusable utilities and clean architecture

---

# 📚 Structure (STRICT — follow in order)

---

## 🟢 1. Basics (Stripe Fundamentals)

---

### 🔹 Core Concepts

- What is Stripe?

- Payment flow overview:
  - client → backend → Stripe → webhook → database

- Key concepts:
  - PaymentIntent
  - Customer
  - Product
  - Price
  - Subscription

---

### ⚠️ Must Include:

- Mental model:
  - Stripe handles sensitive data (PCI compliance)
  - Your backend manages business logic

---

## 🟡 2. Setup & Configuration

---

### 🔹 Account Setup

- Creating Stripe account
- API keys (public vs secret)
- Environment variables

---

### 🔹 SDK Setup

- Installing Stripe SDK (Node.js + TypeScript)
- Creating reusable Stripe client utility

---

### 🔹 Project Structure

- services/stripe.service.ts
- routes/payment.route.ts
- webhook.handler.ts

---

## 🔵 3. One-Time Payments (Core Flow)

---

### 🔹 PaymentIntent Flow

- Create PaymentIntent in backend
- Send client secret to frontend
- Confirm payment on frontend

---

### 🔹 Next.js Frontend

- Using Stripe Elements
- Building custom payment form UI

---

### 🔹 Express Backend

- API route to create PaymentIntent
- Handling response

---

### ⚠️ Must Include:

- Proper TypeScript types for requests/responses

---

## 🟣 4. Custom Payment Form (IMPORTANT)

---

### 🔹 Stripe Elements

- Card input fields
- Secure handling of card data

---

### 🔹 Why NOT to Store Card Data

- PCI compliance explanation
- Using Stripe tokens instead

---

### 🔹 Example

- Custom checkout form
- Handling validation + submission

---

## 🔴 5. Webhooks (CRITICAL FOR PRODUCTION)

---

### 🔹 What are Webhooks?

- Event-driven system from Stripe

---

### 🔹 Implementation

- Setting up webhook endpoint in Express
- Verifying Stripe signature
- Handling events:
  - payment_intent.succeeded
  - payment_intent.payment_failed
  - invoice.payment_succeeded

---

### 🔹 Real Use Case

- Update database after payment success
- Activate user subscription

---

## ⚫ 6. Subscriptions (SaaS Core)

---

### 🔹 Subscription Flow

- Creating products and prices
- Creating customer
- Creating subscription

---

### 🔹 Billing Lifecycle

- Trial periods
- Renewals
- Failed payments

---

### 🔹 Managing Subscriptions

- Upgrade / downgrade plans
- Cancel subscription
- Proration handling

---

### 🔹 Webhook Integration

- Sync subscription status with database

---

## ⚪ 7. Stripe Connect (ADVANCED)

---

### 🔹 What is Stripe Connect?

- Platform for marketplaces

---

### 🔹 Use Cases

- Multi-vendor apps
- SaaS platforms taking commission

---

### 🔹 Types of Accounts

- Standard
- Express
- Custom

---

### 🔹 Implementation Flow

- Creating connected accounts
- Onboarding users
- Handling payouts

---

### 🔹 Real Example

- Marketplace where users receive payments

---

## 🔶 8. Utilities & Architecture (VERY IMPORTANT)

---

### 🔹 Backend Utilities

- createPaymentIntent()
- createCustomer()
- createSubscription()
- handleWebhook()

---

### 🔹 Frontend Utilities

- usePayment hook
- Stripe Elements wrapper

---

### 🔹 Type Safety

- Define request/response types
- Strong typing across frontend/backend

---

## 🔷 9. Security Best Practices

---

- Never expose secret keys
- Always verify webhooks
- Validate payment status server-side
- Handle edge cases (duplicate events)

---

## 🧭 Explanation Rules (STRICT)

For EACH concept:

---

## 1. 🧠 Definition

- Simple explanation

---

## 2. ⚙️ How It Works

- Full payment flow explanation

---

## 3. 💻 Code Example (TypeScript, Production Style)

- Next.js + Express integration

---

## 4. 🌍 Real-World Example

- Example:
  - SaaS subscription
  - checkout page
  - marketplace

---

## 5. ⚠️ Common Mistakes

- Not using webhooks
- Trusting frontend payment success
- Storing card data manually

---

## 6. 🧠 Best Practices

- Secure architecture
- Scalable payment handling

---

## 7. 🧪 Practice Task

- Build payment + subscription flow

---

# 🧱 Global Rules

- Use TypeScript everywhere
- Use modern Next.js App Router
- Focus on production-ready patterns
- Avoid insecure implementations

---

# 🎁 Final Sections (MANDATORY)

---

## 🔥 Stripe Cheat Sheet

- Common APIs and flows

---

## 🧠 Mental Models Summary

- Payment lifecycle
- Event-driven system (webhooks)

---

## 🏗 Real Project Example

Build a SaaS feature:

- User subscription system
- Payment UI
- Webhook handling
- Database sync

---

## 🚨 Common Pitfalls & Debugging Guide

- Payment not confirming
- Webhook not firing
- Subscription not updating
- Duplicate events

---

Now generate the full guide step-by-step starting from Basics.
