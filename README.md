Here’s a **clean, updated README** with your new project name **MedSol** (refined, professional, resume-ready). I’ve also improved structure, clarity, and branding.

---

# 🏥 MedSol – AI-Powered Medical Appointment & Clinic Management Platform

MedSol is a full-stack healthcare platform designed to streamline doctor discovery, appointment booking, clinic management, and AI-driven health insights. It integrates modern web technologies with intelligent report analysis to enhance both patient and provider experience.

---

## 🚀 Live Deployment

| Panel              | URL                                                                            |
| ------------------ | ------------------------------------------------------------------------------ |
| Patient Portal     | [https://meditime-sigma.vercel.app/](https://meditime-sigma.vercel.app/)       |
| Admin/Doctor Panel | [https://meditime-admin-dr.vercel.app/](https://meditime-admin-dr.vercel.app/) |

---

## ✨ Core Features

### 👤 Patient Portal

* Secure authentication using JWT
* Search & filter doctors by specialization
* Book, cancel, and manage appointments
* Razorpay payment integration
* AI-powered health assistant (Dr.AI)
* Upload medical reports → OCR + AI summary
* Responsive UI with real-time interactions

---

### 🩺 Doctor Dashboard

* Manage appointments (view, cancel, complete)
* Track earnings and patient stats
* Update profile and availability
* Real-time dashboard insights

---

### 🛠️ Admin Panel

* Add/manage doctors
* Monitor all appointments
* Platform-wide analytics
* Control doctor availability

---

### 🤖 AI & Report Intelligence

* AI chatbot for medical guidance (Gemini API)
* OCR-based report extraction (Tesseract.js)
* Auto-generated health summaries

---

### 💳 Payment Integration

* Razorpay checkout system
* Secure payment verification
* Seamless booking workflow

---

## 🧰 Tech Stack

| Layer      | Technologies                 |
| ---------- | ---------------------------- |
| Frontend   | React.js, Vite, Tailwind CSS |
| Backend    | Node.js, Express.js          |
| Database   | MongoDB (Mongoose)           |
| Auth       | JWT                          |
| AI         | Google Gemini API            |
| OCR        | Tesseract.js                 |
| Payments   | Razorpay                     |
| Cloud      | Cloudinary                   |
| Deployment | Vercel + Render              |

---

## 📁 Project Structure

```
MEDSOL/
 ├── admin/        # Admin dashboard (React)
 ├── frontend/     # Patient portal (React)
 └── backend/      # REST API (Node.js)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/rajeevcodes1/Medsol.git
cd Medsol
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
cp .env.example .env
npm run server
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

---

### 4️⃣ Admin Panel

```bash
cd admin
npm install
cp .env.example .env
npm run dev
```

---

## 🔑 Environment Variables

### Backend

```env
PORT=5000
MONGODB_URL=your_mongodb_url
JWT_SECRET=your_secret
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret
CLOUDINARY_NAME=your_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_SECRET_KEY=your_secret
GEMINI_API_KEY=your_api_key
```

### Frontend/Admin

```env
VITE_BACKEND_URL=http://localhost:5000
VITE_RAZORPAY_KEY_ID=your_key
```

---

## 📡 API Highlights

* `/api/user/*` → Patient operations
* `/api/doctor/*` → Doctor controls
* `/api/admin/*` → Admin management
* `/api/ai/*` → AI assistant
* `/api/report/*` → Report upload & analysis

---

## 🧠 Key Highlights (Resume Points)

* Built scalable full-stack healthcare system with role-based access
* Integrated AI for medical insights and report analysis
* Implemented secure payment gateway (Razorpay)
* Designed modular REST API with MVC architecture

---

## 🤝 Contributing

1. Fork the repo
2. Create a branch
3. Commit changes
4. Open a PR

---

## 📌 Future Enhancements

* Telemedicine video consultation
* Prescription PDF automation
* Multi-language AI support
* Mobile app version

---

## 📄 License

MIT License


* Add **badges (build, deploy, license)**
* Or tailor it for **GitHub trending-style presentation**
