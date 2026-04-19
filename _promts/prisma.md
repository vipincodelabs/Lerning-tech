You are a senior backend engineer and expert in Prisma, responsible for creating a **comprehensive, production-ready Prisma learning guide**.

The audience is a developer who knows basic database concepts and wants to **master type-safe database access using Prisma with Node.js, TypeScript, and real-world applications**.

---

# 🎯 Goal

Help me MASTER Prisma with:

- Deep understanding of ORM vs raw SQL
- Type-safe database queries
- Schema design and migrations
- Real-world backend architecture
- Integration with APIs (Express / Next.js)

---

# 📚 Structure (STRICT — follow in order)

---

## 🟢 1. Basics (Foundation of Prisma)

---

### 🔹 Core Concepts

- What is Prisma?
- ORM vs Query Builder vs Raw SQL
- Why Prisma is different (type safety, DX)

---

### 🔹 Setup & Configuration

- Installing Prisma
- Initializing project (`prisma init`)
- Understanding `schema.prisma`

---

### 🔹 Prisma Schema (VERY IMPORTANT)

- Models
- Fields and types
- Relations (1:1, 1:N, N:N)
- Enums

---

### 🔹 Migrations

- Creating migrations
- Applying migrations
- Resetting database

---

### 🔹 Prisma Client

- Generating client
- Basic queries:
  - create
  - findMany
  - findUnique
  - update
  - delete

---

### ⚠️ Must Include:

- Mental model:
  - Prisma schema → database → generated client

---

## 🟡 2. Intermediate (Real-World Usage)

---

### 🔹 Relations & Queries

- Nested queries
- Include vs select
- Filtering and sorting
- Pagination (skip/take, cursor-based)

---

### 🔹 Advanced Querying

- Conditional queries
- Aggregations
- Transactions

---

### 🔹 API Integration

- Using Prisma in Express
- Using Prisma in Next.js App Router
- Service layer pattern

---

### 🔹 Validation Strategy

- Prisma vs Zod
- Where to validate (before DB)

---

### 🔹 Error Handling

- Handling Prisma errors
- Unique constraint errors
- Safe query patterns

---

## 🔴 3. Advanced (Production-Level Mastery)

---

### 🔹 Performance Optimization

- Avoiding N+1 queries
- Efficient relations loading
- Query optimization

---

### 🔹 Transactions & Concurrency

- `$transaction`
- Handling race conditions

---

### 🔹 Raw Queries

- When to use raw SQL
- `prisma.$queryRaw`
- Safety considerations

---

### 🔹 Prisma Middleware

- Logging
- Data transformation
- Auditing

---

### 🔹 Schema Design (Scaling Apps)

- Modular schema structure
- Naming conventions
- Large project organization

---

### 🔹 Prisma with Modern Stack

---

#### With Next.js

- Server actions
- Edge vs Node runtime considerations

---

#### With TanStack Query

- Data fetching patterns

---

#### With Zod

- Type-safe validation pipeline

---

## 🧭 Explanation Rules (STRICT)

For EACH concept, follow this structure:

---

## 1. 🧠 Definition

- Simple explanation
- What problem it solves

---

## 2. ⚙️ How It Works

- Internal behavior
- Prisma architecture

---

## 3. 💻 Code Example (TypeScript, Production Style)

- Clean, real-world code
- API + database interaction

---

## 4. 🌍 Real-World Example

- Example:
  - user system
  - product system
  - relational data handling

---

## 5. ⚠️ Common Mistakes

- Bad schema design
- Over-fetching data
- Ignoring transactions

---

## 6. 🧠 Best Practices

- Query optimization
- Clean architecture
- Type-safe patterns

---

## 7. 🧪 Practice Task

- Small hands-on exercise

---

# 🧱 Global Rules

- Use TypeScript everywhere
- Focus on real backend scenarios
- Avoid theoretical explanations without usage
- Prefer production-ready patterns

---

# 🎁 Final Sections (MANDATORY)

---

## 🔥 Prisma Cheat Sheet

- Most-used queries and commands

---

## 🧠 Mental Models Summary

- How Prisma works internally

---

## 🏗 Real Project Example

Build a real backend feature:

- User + Product system
- Relations
- API endpoints
- Validation + queries

---

## 🚨 Common Pitfalls & Debugging Guide

- Query performance issues
- Migration problems
- Relation bugs
- Transaction errors

---

Now generate the full guide step-by-step starting from Basics.
