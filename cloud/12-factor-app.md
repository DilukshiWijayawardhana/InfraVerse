# 12-Factor App - Key Concepts

Before learning the 12-Factor App principles, it is important to understand some key concepts used in modern applications.

---

## 01. Scalability

### 📌 Definition

Scalability means a system can **handle more users or traffic as demand increases**.

---

### 💡 Example

- 100 users → system works ✅
- 10,000 users → system still works ✅

👉 Because of scalability, the system grows without crashing.

---

### 🔄 Types of Scaling

There are two main types:

---

## 1. Vertical Scaling (Scale Up)

### 📌 Definition

Vertical scaling means **increasing the power of a single server**.

---

### 💡 Example

Upgrade the same machine by adding:

- More CPU
- More RAM
- More Storage

---

### ✅ Advantages

- Simple to implement
- No need to change application architecture

---

### ❌ Disadvantages

- Has a limit (cannot upgrade forever)
- If the server fails, everything goes down
- Can be expensive

---

## 2. Horizontal Scaling (Scale Out)

### 📌 Definition

Horizontal scaling means **adding more servers instead of upgrading one**.

---

### 💡 Example

Instead of using one server:

- Use 3 servers
- Use multiple servers

👉 Traffic is distributed using a load balancer.

---

### ✅ Advantages

- Highly scalable (can keep adding servers)
- Better fault tolerance (if one fails, others still work)
- Used in modern systems like microservices

---

### ❌ Disadvantages

- More complex setup
- Requires load balancing
- Application must support distributed systems

---

## 🧠 Summary

- **Scalability** → system can grow with demand
- **Vertical Scaling** → bigger server
- **Horizontal Scaling** → more servers

---
