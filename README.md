# 🎬 BookMySeat – Movie Ticket Booking App

BookMySeat is a full-stack movie ticket booking platform built with **Django**.
It enables users to explore movies, watch trailers, choose theaters, reserve seats, and complete bookings with online payments.

---

## ✨ Highlights

### 🎥 Movie Discovery

* Browse all available movies
* Filter by genre, language, or search keywords
* Clean and modern UI

### ▶ Trailer Support

* Watch YouTube trailers directly inside the app
* Automatically converts links into embed format

### 💺 Smart Seat Booking

* Real-time seat selection
* Seats are temporarily locked for a short duration
* Prevents double booking

### ⏳ Reservation Logic

* Seats are held for a limited time before payment
* Successful payment → booking confirmed
* Failed/abandoned payment → seats released automatically

### 💳 Payment Integration

* Secure checkout powered by Stripe
* Supports test transactions for development

### 📧 Email Notifications

* Booking confirmation sent instantly
* Includes movie, theater, and seat details

### 📊 Admin Insights

* Revenue tracking
* Most booked movies
* High-traffic theaters
* Visual charts for analytics

---

## 🧰 Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite
* **Payments:** Stripe
* **Email Service:** SendGrid
* **Charts:** Chart.js

---



---

## 🌐 Usage

* App: http://127.0.0.1:8000/
* Admin Panel: http://127.0.0.1:8000/admin/

---

## 🔐 Important Notes

* Users may be granted staff access for dashboard viewing
* Admin panel is used to manage movies, theaters, and bookings

### 💳 Test Payments (Stripe)

Use these test card details:

* ✔ Successful payment

  ```
  4242 4242 4242 4242
  ```

* ❌ Failed payment

  ```
  4000 0000 0000 0002
  ```

---

## 📩 Email Behavior

* Booking confirmation is sent after successful payment
* Check spam folder if not received

---

## ⏱ Seat Handling Logic

* Seats are temporarily reserved during checkout
* Automatically freed if payment is not completed within the time window

---

## 🚧 Limitations

* Some YouTube videos may not allow embedding
* SQLite is not ideal for production-scale apps

---

## 🚀 Future Enhancements

* QR-based digital tickets
* Advanced recommendation system
* Mobile-first UI improvements
* Multi-language support

---

## 👨‍💻 Developer

Priyanka Yadav

---

## 📄 License

This project is intended for learning and demonstration purposes.
