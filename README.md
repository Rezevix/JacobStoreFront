**Huge WIP (work in progress), most of these features arent added yet!**


# 🎮 Jacob’s Controller Modding Storefront

A sleek, modern storefront for **custom PS5 controllers** and future gaming services.
Built with **Java (Spring Boot)** and **React**, featuring secure payments, live order tracking, and an admin dashboard.

---

## 🚀 Features

✅ **Custom Controller Builder** — customers choose a base controller and apply mod options (hall effect sticks, hair triggers, tactile buttons).

✅ **Stripe Payments Integration** — safe, fast, and supports all major cards.

✅ **Email Notifications** — customers receive confirmation and receipts; admin receives order alerts.

✅ **Admin Dashboard** — password-protected dashboard for Jacob to view sales, manage stock, and analyze performance.

✅ **Scalable Architecture** — structured to handle future expansions like console mods or accessory sales.

✅ **Delivery Calculator** — automatic UK delivery cost calculation at checkout.

---

## 🛠️ Tech Stack

**Frontend:** React, TailwindCSS, React Router
**Backend:** Java 17+, Spring Boot, Spring Data JPA, Spring Security
**Database:** MySQL / PostgreSQL
**Payments:** Stripe Java SDK
**Email Service:** JavaMailSender (Spring Boot Starter Mail)
**Hosting:** Vercel (frontend) + Render / Railway / VPS (backend)

---

## ⚙️ Setup Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/jacobs-storefront.git
cd jacobs-storefront
```

### 2️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

### 3️⃣ Backend Setup

```bash
cd ../backend
./mvnw spring-boot:run
```

---

## 🔑 Environment Variables

In the backend, create a `.env` or configure in `application.properties`:

```
spring.datasource.url=jdbc:mysql://localhost:3306/jacobsmods
spring.datasource.username=your_username
spring.datasource.password=your_password

stripe.api.key=your_stripe_secret_key
mail.username=your_email_address
mail.password=your_email_password
frontend.url=http://localhost:3000
```

---

## 📊 Admin Dashboard

* Accessible only to Jacob via login
* Displays order data and analytics
* Allows toggling product availability and prices
* Uses REST API endpoints for data visualization

---

## 💳 Payments

Powered by **Stripe’s Java SDK** — fully PCI-compliant and secure.
Supports:

* Credit/Debit Cards
* Apple Pay
* Google Pay

---

## 🧱 Future Plans

* Add Xbox and custom PC modding
* Expand dashboard to include product CRUD management
* Integrate PayPal SDK (secondary payment option)
* Build Android companion app (Spring API integration)

---

## 👨‍💻 Developers

**Developed by:** Rez @ [Nullbyte Labs](https://github.com/rezevix)

**Developed by:** Holly @ [Nullbyte Labs](https://github.com/HoGoodDev)

---

## 🧾 License

Licensed under the **MIT License**.
Free for educational and commercial use with attribution.

---

> 💡 *“Precision-built mods for precision players.”*
> — Jacob’s Mods
