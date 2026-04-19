You are a senior React engineer and expert in TanStack Query (React Query), responsible for creating a **comprehensive, production-ready learning guide**.

The audience is a developer who knows React basics and API calls but wants to **master server-state management using TanStack Query**.

---

# 🎯 Goal

Help me MASTER TanStack Query from beginner to advanced level with:

- Deep understanding of server-state vs client-state
- Real-world API integration patterns
- Performance optimization strategies
- Scalable architecture for production apps

---

# 📚 Structure (STRICT — follow in order)

---

## 🟢 1. Basics (Foundation of Server State)

Focus on understanding what makes TanStack Query different.

### Topics to cover:

- What is TanStack Query?
- Server state vs client state (VERY IMPORTANT)
- Why not just use useEffect + fetch?

---

### Core Concepts:

- Query Client & Provider setup
- `useQuery` (basic usage)
- Query keys (how and why they matter)
- Loading, error, and success states

---

### Data Fetching Basics:

- Fetching data from API
- Handling loading UI
- Error handling patterns

---

### ⚠️ Must Include:

- Mental model:
  - caching
  - background refetching
  - stale vs fresh data

---

## 🟡 2. Intermediate (Real-World Usage)

Focus on how TanStack Query is used in actual applications.

---

### 🔹 Mutations (VERY IMPORTANT)

- `useMutation`
- Creating, updating, deleting data
- Handling success & error states

---

### 🔹 Cache Management

- Invalidating queries
- Refetching strategies
- Manual cache updates

---

### 🔹 Query Behavior

- Stale time vs cache time
- Refetch on window focus
- Refetch intervals

---

### 🔹 Pagination & Infinite Queries

- Paginated API calls
- Infinite scrolling (`useInfiniteQuery`)

---

### 🔹 Dependent Queries

- Fetching data based on other queries

---

### 🔹 Real-World Patterns

- Forms + API (react-hook-form style)
- Authenticated requests (tokens, headers)
- Dashboard data fetching

---

## 🔴 3. Advanced (Production-Level Mastery)

---

### 🔹 Performance Optimization

- `useQuery` vs `useInfiniteQuery`
- Avoiding unnecessary re-renders
- Memoization strategies

---

### 🔹 Advanced Caching Strategies

- Optimistic updates (VERY IMPORTANT)
- Updating cache without refetch
- Normalization patterns

---

### 🔹 SSR & Next.js Integration

- Using TanStack Query with Next.js App Router
- Prefetching data
- Hydration & dehydration

---

### 🔹 Custom Hooks Architecture

- Creating reusable query hooks
- Structuring API layers
- Separation of concerns

---

### 🔹 Error Handling Strategies

- Global error handling
- Retry logic
- Handling API failures gracefully

---

### 🔹 DevTools & Debugging

- Using TanStack Query DevTools
- Debugging cache issues

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
- Mental model (important)

---

## 3. 💻 Code Example (Production Style)

- Clean, scalable code
- Real API examples

---

## 4. 🌍 Real-World Use Case

- Example:
  - dashboard
  - form submission
  - CRUD app
  - authentication

---

## 5. ⚠️ Common Mistakes

- Wrong query keys
- Over-fetching
- Misusing mutations

---

## 6. 🧠 Best Practices

- Caching strategies
- Naming conventions
- Performance tips

---

## 7. 🧪 Practice Task

- Small hands-on exercise

---

# 🧱 Global Rules

- Use modern React (React 18+)
- Prefer functional components
- Avoid outdated patterns
- Focus on real-world usage over theory
- Teach like a senior developer

---

# 🎁 Final Sections (MANDATORY)

---

## 🔥 Query Key Strategy Guide

- How to structure query keys properly

---

## 🧠 Mental Models Summary

- How TanStack Query works internally

---

## 🏗 Real Project Example

Build a real feature combining:

- data fetching
- mutations
- caching
- error handling

Example: dashboard or CRUD system

---

## 🚨 Common Pitfalls & Debugging Guide

- Why data is not updating
- Cache issues
- Infinite refetch problems

---

Now generate the full guide step-by-step starting from Basics.
