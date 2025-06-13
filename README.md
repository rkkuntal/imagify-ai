# Imagify - AI Text-to-Image Generator

Imagify is a full-stack AI-powered SaaS web application that generates images based on user text prompts using the ClipDrop API. It features user authentication, a credit-based image generation system, and online payment integration via Razorpay.

## 🔧 Tech Stack

* **Frontend**: React.js, Tailwind CSS, Framer Motion
* **Backend**: Node.js, Express.js, MongoDB
* **Authentication**: JWT (JSON Web Token)
* **Payments**: Razorpay Integration
* **AI API**: ClipDrop Image Generator API

---

## 🚀 Features

* 🔐 Secure Login/Register using JWT
* 📷 Generate images with text prompts via ClipDrop
* 🪙 Credit system for tracking image generation usage
* 💳 Razorpay integration for buying credits
* 📦 MongoDB-based user and transaction storage
* 🎨 Responsive, modern UI with animation

---

## 📁 Folder Structure

```
Imagify/
├── client/          # React Frontend
├── server/          # Express Backend
├── .gitignore
├── README.md
```

---

## 📦 Installation & Setup

### 1. Clone the Repo

```bash
git clone https://github.com/rkkuntal/imagify-ai.git
cd imagify-ai
```

### 2. Setup Backend

```bash
cd server
npm install
```

Create a `.env` file in `/server` based on `.env.example`:

```env
PORT=4000
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_secret
```

Run backend:

```bash
npm run server
```

### 3. Setup Frontend

```bash
cd ../client
npm install
```

Create `.env` file in `/client`:

```env
VITE_BACKEND_URL=http://localhost:4000
VITE_RAZORPAY_KEY_ID=your_razorpay_key_id
```

Run frontend:

```bash
npm run dev
```

---

## 🌐🌐 Live Demo

🔗 Frontend: https://imagify-ai-pi.vercel.app/

🔗 Backend API: https://imagify-backend-m1sh.onrender.com


---

## 📞 Contact

Built by [Rinku Kuntal](https://github.com/rkkuntal) · [LinkedIn](https://linkedin.com/in/rinkukuntal)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
Add complete README file

