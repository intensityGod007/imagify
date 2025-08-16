# 🖼️ Text-to-Image Generator SaaS

An AI-powered **Text-to-Image Generator SaaS** built with **React, TailwindCSS, Node.js, express.js, and MongoDB**, featuring **user authentication** and **Razorpay integration** for subscriptions and credits.

## 🚀 Features

* **User Authentication** JWT
* **Razorpay Payment Gateway** (subscriptions & one-time credits)
* **AI Image Generation** from text prompts
* **Usage Tracking** (credit-based system)
* **Responsive & modern UI** (React + TailwindCSS)
* **Deployed** on Vercel & Render

## 🛠️ Tech Stack

* **Frontend:** React, TailwindCSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Payments:** Razorpay API
* **Authentication:** JWT
* **Deployment:** Vercel (frontend), Render (backend)

## 📦 Installation

### 1️⃣ Clone the repo

```bash
git clone https://github.com/intensityGod007/imagify.git
cd imagify
```

### 2️⃣ Backend Setup

```bash
cd server
npm install
```

Create a `.env` file in `/server` with:

```env
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLIPDROP_API=your_clipdrop_api
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
CURRENCY="INR"
```

Run backend:

```bash
npm run server
```

### 3️⃣ Frontend Setup

```bash
cd client
npm install
```

Create a `.env` file in `/client` with:

```env
VITE_APP_API_URL=http://localhost:5000
VITE_RAZORPAY_KEY_ID=your_key_id
```

Run frontend:

```bash
npm run dev
```

Now visit 👉 [http://localhost:3000](http://localhost:3000)

## 📸 Screenshots

![Home Page](/client//src/assets/home_page.png)
![Generate Page](/client//src/assets/generate_page.png)
![Pricing Page](/client//src/assets/pricing_page.png)
![Login](/client//src/assets/login.png)