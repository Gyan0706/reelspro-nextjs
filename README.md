# 📹 ImageKit Video Shop

A modern **Next.js** application for managing and selling video content using **ImageKit** integration.
This project provides a full-featured platform with **user authentication, video upload capabilities, and payment processing using Razorpay**.

---

## ✨ Features

* 🔐 **User Authentication** (NextAuth.js)
* 📹 **Video Upload and Management** (ImageKit)
* 🎨 **Modern UI** with Tailwind CSS and DaisyUI
* 📱 **Fully Responsive Design**
* 🔒 **Secure API Routes**
* 🗄️ **MongoDB Database Integration**

---

## 🛠️ Tech Stack

* ⚛️ **Frontend**: Next.js 15, React 19, TypeScript
* 🎨 **Styling**: Tailwind CSS, DaisyUI
* 🔑 **Authentication**: NextAuth.js, JWT
* 🗄️ **Database**: MongoDB with Mongoose
* ☁️ **File Storage**: ImageKit
* 📝 **Form Handling**: React Hook Form

---

## 🎬 Demo Video

Watch the project in action:

https://github.com/user-attachments/assets/0136d3ae-74b3-4c54-9d8c-c5ce5832e037



## ⚡ Prerequisites

* 📦 Node.js (Latest LTS version)
* 🗄️ MongoDB Database
* ☁️ ImageKit Account

---

## 🚀 Getting Started

1️⃣ **Clone the repository:**

```bash
git clone <repository-url>
cd imagekit-video-main
```

2️⃣ **Install dependencies:**

```bash
npm install
```

3️⃣ **Configure environment variables:**

```bash
cp .env.example .env
# Fill in the required variables
```

4️⃣ **Run the development server:**

```bash
npm run dev
```

5️⃣ **Open in browser:**
👉 [http://localhost:3000](http://localhost:3000)

---

## 🔑 Environment Variables

```env
# Database
MONGODB_URI=

# Authentication
NEXTAUTH_SECRET=
NEXTAUTH_URL=

# ImageKit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=
```

⚠️ **Note:** Prefix frontend-exposed variables with `NEXT_PUBLIC_`.

---

## 📜 Available Scripts

* ▶️ `npm run dev` - Start development server
* 🏗️ `npm run build` - Build production application
* 🚀 `npm run start` - Start production server
* ✅ `npm run lint` - Run ESLint
* 🌱 `npm run seed` - Seed the database

---

## 🗂️ Project Structure

```
├── app/                  # Next.js app directory
│   ├── api/              # API routes
│   ├── components/       # Reusable components
│   ├── login/            # Login page
│   ├── register/         # Registration page
│   └── upload/           # Video upload page
├── lib/                  # Utility functions
├── models/               # MongoDB models
├── public/               # Static assets
└── types.d.ts            # TypeScript declarations
```

---
