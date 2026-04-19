You are a senior TypeScript engineer and expert in Zod, responsible for creating a **comprehensive, production-ready documentation guide**.

The audience is a developer who knows JavaScript/TypeScript basics and wants to **master validation, type safety, and schema architecture across frontend and backend using Zod (latest version)**.

---

# 🎯 Goal

Help me MASTER Zod with:

- Deep understanding of runtime validation vs TypeScript types
- Strong type inference (VERY IMPORTANT)
- “Parse, don’t validate” mindset
- Full-stack schema usage (React, Next.js, Express)
- Scalable schema architecture for real applications

---

# 📚 Structure (STRICT — follow in order)

---

## 🟢 1. Basics (Foundation of Validation & Types)

---

### 🔹 Core Concepts

- What is Zod?
- Runtime validation vs TypeScript compile-time types (VERY IMPORTANT)
- “Parse, don’t validate” mental model
- Why Zod is better than manual validation

---

### 🔹 Basic Schemas

- Primitive types:
  - string, number, boolean

- Objects
- Arrays
- Enums

---

### 🔹 Parsing & Validation

- `parse` vs `safeParse`
- `parseAsync` (IMPORTANT)
- Handling validation errors

---

### 🔹 Type Inference

- `z.infer`
- Keeping types and validation in sync

---

### ⚠️ Must Include:

- Mental model:
  - single source of truth for types + validation

---

## 🟡 2. Intermediate (Real-World Usage)

---

### 🔹 Schema Composition

- Nested objects
- Reusable schemas
- Extending schemas
- Merging schemas

---

### 🔹 Refinements & Custom Validation

- `.refine()` (sync)
- `.refine()` (async)
- `.superRefine()`
- Custom error messages

---

### 🔹 Transformations

- `.transform()`
- Sanitizing input (trim, normalize, format)

---

### 🔹 Optional, Nullable, Defaults

- `.optional()`
- `.nullable()`
- `.default()`

---

### 🔹 Latest Zod Features (v4+)

- Metadata:
  - `.describe()`
  - `.meta()`

- Improved schema composition
- Better intersection handling

---

### 🔹 Real-World Use Cases

---

#### React (Forms)

- Zod + React Hook Form
- Schema-based validation
- Error display patterns

---

#### Express (Backend APIs)

- Validating:
  - request body
  - params
  - query

- Middleware pattern using Zod

---

#### API Contracts (VERY IMPORTANT)

- Sharing schemas between frontend & backend
- Ensuring type-safe communication
- Validating API responses on frontend

---

## 🔴 3. Advanced (Production-Level Mastery)

---

### 🔹 Advanced Schema Design

- Discriminated unions (`z.discriminatedUnion`) (VERY IMPORTANT)
- Complex nested schemas
- Dynamic schemas

---

### 🔹 Async Validation (CRITICAL)

- `parseAsync`
- Async `.refine()`
- Database/API validation scenarios

---

### 🔹 Error Handling Strategies

- Custom error formatting
- Mapping errors to UI (forms)
- API error responses structure

---

### 🔹 Integration Patterns

---

#### With React Hook Form

- Resolver pattern
- Type-safe forms

---

#### With TanStack Query

- Validating API responses
- Ensuring data integrity

---

#### With Express APIs

- Centralized validation layer
- Reusable middleware

---

### 🔹 Performance & Optimization

- Avoid unnecessary parsing
- Schema reuse strategies

---

### 🔹 Zod in Large Applications

- Folder structure for schemas
- Separation of concerns
- Versioning schemas

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
- Type inference explanation

---

## 3. 💻 Code Example (TypeScript, Production Style)

- Clean, typed code
- Real-world usage

---

## 4. 🌍 Real-World Example

- Example:
  - form validation
  - API request validation
  - response validation
  - data transformation

---

## 5. ⚠️ Common Mistakes

- Misusing optional/nullable
- Not using safeParse
- Ignoring async validation
- Not validating API responses

---

## 6. 🧠 Best Practices

- Schema reuse
- Clean validation architecture
- Error handling patterns

---

## 7. 🧪 Practice Task

- Small hands-on exercise

---

# 🧱 Global Rules

- Use TypeScript everywhere
- Prefer real-world examples over toy examples
- Avoid outdated validation approaches
- Focus on full-stack usage (frontend + backend)
- Emphasize type safety + runtime validation together

---

# 🎁 Final Sections (MANDATORY)

---

## 🔥 Zod API Cheat Sheet

- All major methods with short explanations

---

## 🧠 Mental Models Summary

- “Parse, don’t validate”
- Schema as single source of truth

---

## 🏗 Real Project Example

Build a real feature:

- React form with validation
- Express API validation
- Shared schema
- API response validation
- Error handling

---

## 🚨 Common Pitfalls & Debugging Guide

- Why validation fails unexpectedly
- Handling nested errors
- Async validation issues
- Type mismatch problems

---

Now generate the full documentation step-by-step starting from Basics.
