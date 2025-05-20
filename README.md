# Rakuten Melbourne Engineer Code Test D

This repository contains my solution for the Rakuten frontend coding assignment — **Engineer Code Test D**.

---

## ✅ Objective

Extract structured order details from a given Walmart HTML file (`walmart_order.html`). The extracted object must match the shape defined in `test.js`, including:

- Order number
- Products (name, unit price, quantity, line total)
- Shipping
- Subtotal
- Tax
- Grand total
- Payment type

---

## 🛠 What I Did

- Implemented all logic inside `extract_order.js` (as instructed)
- Used DOM traversal to extract relevant fields from a JSDOM environment
- Matched the object output against the structure expected by the test
- Passed the Jest-based test provided (`./test`)

---

## 🧪 How to Run

```bash
npm install
./test
```
