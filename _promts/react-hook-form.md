You are a senior React engineer and expert in React Hook Form, responsible for creating a **comprehensive, production-ready documentation guide**.

The audience is a developer who knows React basics and wants to **master form handling in real-world applications using React Hook Form with TypeScript and Next.js**.

---

# 🎯 Goal

Help me MASTER React Hook Form with:

- Deep understanding of uncontrolled vs controlled components
- Scalable form architecture
- Type-safe forms using TypeScript
- Real-world usage (Next.js App Router, APIs, validation)

---

# 📚 Structure (STRICT — follow in order)

---

## 🟢 1. Basics (Foundation of Forms in RHF)

Focus on understanding how React Hook Form works differently from traditional React forms.

---

### 🔹 Core Concepts

- What is React Hook Form?
- Controlled vs Uncontrolled components (VERY IMPORTANT)
- Why RHF is performant

---

### 🔹 Setup

- Installing and setting up in React / Next.js
- Basic form using `useForm`

---

### 🔹 Core APIs (Must Explain in Detail)

- `useForm`
  - register
  - handleSubmit
  - formState (errors, isSubmitting, etc.)

- Basic validation:
  - required
  - min/max
  - pattern

---

### 🔹 Handling Form Data

- How to GET form values
- How to SET form values:
  - `setValue`
  - `getValues`
  - `watch`

---

### ⚠️ Must Include:

- Mental model:
  - why RHF avoids re-renders
  - how refs are used internally

---

## 🟡 2. Intermediate (Real-World Forms)

Focus on building real applications.

---

### 🔹 Controlled Components

- Using `Controller`
- Integrating with UI libraries (ShadCN, MUI, etc.)

---

### 🔹 Advanced APIs (Explain Each Clearly)

- `Controller`
- `useFormContext`
- `FormProvider`
- `useWatch`

---

### 🔹 Form Architecture

- Splitting forms into reusable components
- Managing large forms cleanly

---

### 🔹 Validation (Production Level)

- Schema validation with Zod
- Error handling patterns
- Custom validation logic

---

### 🔹 Multi-Step Forms (VERY IMPORTANT)

- Building step-by-step forms
- Persisting data between steps
- Navigation between steps
- Validation per step

---

### 🔹 Real-World Use Cases

- Login / Signup forms
- Profile update form
- API integration (POST/PUT)
- Handling async submission

---

## 🔴 3. Advanced (Production-Level Mastery)

---

### 🔹 Performance Optimization

- Avoiding unnecessary re-renders
- Using uncontrolled inputs effectively
- When to use controlled inputs

---

### 🔹 Dynamic Forms

- Adding/removing fields dynamically
- Field arrays (`useFieldArray`)

---

### 🔹 Advanced State Handling

- Resetting forms (`reset`)
- Partial updates
- Default values vs controlled values

---

### 🔹 Integration Patterns

- React Hook Form + TanStack Query
- React Hook Form + API layer (Axios)
- Handling server errors

---

### 🔹 Next.js App Router Integration

- Forms with server actions
- Client vs server components
- Handling form submission in modern Next.js

---

### 🔹 Custom Hooks & Reusability

- Creating reusable form hooks
- Encapsulating validation + logic

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
- Mental model

---

## 3. 💻 Code Example (TypeScript, Production Style)

- Clean, typed code
- Real use case

---

## 4. 🌍 Real-World Example

- Example:
  - auth form
  - multi-step form
  - dashboard form

---

## 5. ⚠️ Common Mistakes

- Misusing Controller
- Over-controlling inputs
- Wrong validation patterns

---

## 6. 🧠 Best Practices

- Performance tips
- Clean architecture

---

## 7. 🧪 Practice Task

- Small hands-on exercise

---

# 🧱 Global Rules

- Use TypeScript everywhere
- Use modern React (React 18+)
- Use functional components only
- Prefer real-world scenarios over toy examples
- Avoid outdated patterns

---

# 🎁 Final Sections (MANDATORY)

---

## 🔥 RHF API Cheat Sheet

- All major APIs with short explanations

---

## 🧠 Mental Models Summary

- How RHF works internally

---

## 🏗 Real Project Example

Build a complete feature:

- Multi-step form
- Validation with Zod
- API submission
- Error handling
- State persistence

---

## 🚨 Common Pitfalls & Debugging Guide

- Why values are not updating
- Controlled vs uncontrolled confusion
- Validation issues
- Performance problems

---

Now generate the full documentation step-by-step starting from Basics.
