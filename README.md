**Huge WIP (work in progress), most of these features arent added yet!**



# 🎮 Jacob’s Controller Modding Storefront

A modern, full-stack eCommerce platform built for **custom PS5 controllers** and future gaming tech services.
Developed with **React**, **Node.js**, **MongoDB**, and **Stripe** for a smooth, secure buying experience.

---

## 🚀 Features

✅ **Custom Controller Builder** — visitors can select controller models and choose their preferred mod options (hall effect sticks, hair triggers, tactile buttons).
✅ **Secure Checkout** — payments handled via **Stripe Checkout**.
✅ **Order Notifications** — both customer and admin receive confirmation emails.
✅ **Admin Dashboard** — sales analytics, order tracking, and stock management for Jacob only.
✅ **Scalable Backend** — structured for additional future services (console mods, accessories, etc.).
✅ **Responsive Design** — optimized for mobile and desktop.

---

## 🛠️ Tech Stack

**Frontend:** React (Vite or CRA), React Router, TailwindCSS
**Backend:** Node.js, Express, MongoDB (Mongoose)
**Payments:** Stripe API
**Email Service:** Nodemailer / SendGrid
**Hosting:** Vercel (frontend) + Render / DigitalOcean (backend)

---

## ⚙️ Setup Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/jacobs-storefront.git
cd jacobs-storefront
```

### 2️⃣ Install Dependencies

Frontend:

```bash
cd frontend
npm install
```

Backend:

```bash
cd ../backend
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file inside `/backend`:

```
MONGO_URI=your_mongo_connection_string
STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:3000
```

### 4️⃣ Run the App

Start backend:

```bash
npm run dev
```

Start frontend (in a second terminal):

```bash
npm start
```

Frontend runs on `http://localhost:3000`
Backend runs on `http://localhost:5000`

---

## 📊 Admin Dashboard

* Displays daily/weekly/monthly sales charts.
* Shows live order data fetched from the database.
* Allows editing stock and viewing customer orders.

---

## 💳 Payments

Integrated with **Stripe Checkout** for secure, PCI-compliant transactions.
Supports all major credit/debit cards, Apple Pay, and Google Pay.

---

## 🧱 Future Plans

* Add Xbox controller modding options
* Integrate PayPal as secondary payment method
* Expand dashboard with product management
* Implement user accounts and order history

---

## 👨‍💻 Developer

**Developed by:** Rez @ [Nullbyte Labs](https://github.com/YOUR_USERNAME)
**Commissioned by:** Jacob — Founder of Jacob’s Mods

---

## 🧾 License

This project is licensed under the **MIT License**.
Feel free to use and modify with attribution.

---

> 💡 *“Custom controllers built for performance. Mods that elevate your gameplay.”*
> — Jacob’s Mods
