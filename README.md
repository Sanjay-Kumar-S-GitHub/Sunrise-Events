# 🌅 Sunrise Events

**Sunrise Events** is a specialized event production platform designed to streamline event planning and showcase the creative capabilities of the company. From wedding setups to rental furniture, this full-stack web application empowers users to browse services, explore previous work, and seamlessly book events.

---

## ✨ Project Overview

Sunrise Events provides an elegant and functional digital experience tailored for event production services, including:

* Wedding, Reception, Sangeet, and Haldi Decorations
* Rental Furniture and Sitting Arrangements
* Intuitive Booking System
* Visual Gallery of Past Events

The platform is built with a **React** frontend and a **Node.js/Express** backend, ensuring a responsive, fast, and interactive user experience.

---

## 📁 Project Structure

```
Sunrise-Events/
│
├── frontend/              # Client-side (React + Tailwind CSS)
│   ├── assets/            # Images and static media
│   ├── components/        # Reusable components (Admin & User)
│   │   ├── booking/
│   │   ├── common/
│   │   ├── final/
│   │   ├── footer/
│   │   ├── gallery/
│   │   ├── homepage/
│   │   ├── navbar/
│   │   └── other/
│   ├── mockdata/          # Sample data used for testing
│   ├── pages/             # Page-level components/routes
│   ├── store/             # State management (Redux/Context)
│   └── utils/             # Utility functions and helpers
│
├── backend/               # Server-side (Node.js + Express)
│   ├── config/            # Configuration files (db.js, cloudinary.js)
│   ├── db/                # Database setup and connections
│   ├── mailtrap/          # Email testing integration
│   ├── middleware/        # Middlewares (auth, multer, cloudinary, etc.)
│   ├── models/            # Mongoose models (e.g., booking.model.js)
│   ├── public/            # Static files (CSS, JS)
│   ├── routes/            # Route handlers (admin, auth, utils)
│   └── server.js          # Entry point of the backend
```

---

## 🚀 Key Features

* **Service Listings** – Showcase services with editable price fields (admin access)
* **Gallery Section** – A dynamic, image-rich gallery highlighting past events
* **Contact Section** – Displays phone number, email, Instagram, and physical location
* **Interactive Booking Calendar** – Users can book consultation or reserve event dates
* **CTA Section** – Prominent call-to-action encouraging quick contact
* **Admin Dashboard** – Manage services, bookings, gallery, and content

---

## 🛠️ Tech Stack

### Frontend

* **React.js**
* **Tailwind CSS**

### Backend

* **Node.js**
* **Express.js**
* **MongoDB**
* **Mongoose**
* **Cloudinary** – For image storage
* **Multer** – File upload middleware
* **Mailtrap** – For email testing

---

## 📦 Installation

### Clone the Repository

```bash
git clone https://github.com/<your-username>/sunrise-events.git
cd sunrise-events
```

### Setup Frontend

```bash
cd frontend
npm install
npm start
```

### Setup Backend

```bash
cd backend
npm install
node server.js
```

---

## 👥 Team Members

* Atharv Gupta
* Aditya Gaur
* Sanjay Kumar
* Vedang Dubey

---

## 📌 Future Improvements

* Payment gateway integration
* Admin analytics dashboard
* SMS/email reminders for bookings
* Enhanced SEO for wider reach

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.

---
