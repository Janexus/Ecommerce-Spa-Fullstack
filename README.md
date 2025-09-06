# 🛍️ E-commerce SPA (Fullstack)

A modern single-page **E-commerce Web Application** built with:

- ⚡ **Frontend:** React + Vite + Tailwind CSS  
- 🔐 **Backend:** Node.js + Express + JWT Auth + LowDB (JSON DB)  
- 🛒 **Features:** Authentication, Products CRUD with filters, Persistent Cart  

---

## 🚀 Features

### Frontend
- 🔑 Signup & Login pages with JWT auth  
- 🛍️ Product listing with category & price filters  
- 🛒 Cart page with add/remove items  
- 💾 Cart persists after logout/login  
- 📱 Responsive, mobile-friendly design  

### Backend
- 🔐 Authentication APIs (Signup/Login with JWT)  
- 📦 CRUD APIs for items (with filters)  
- 🛒 Cart APIs (add, remove, list)  

---

## 📂 Project Structure

```
ecommerce-spa-fullstack/
│
├── backend/     # Express.js APIs
│   ├── server.js
│   ├── db.json
│   └── package.json
│
├── frontend/    # React SPA
│   ├── src/
│   ├── vite.config.js
│   └── package.json
│
└── README.md
```

---

## 🛠️ Getting Started

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR-USERNAME/ecommerce-spa-fullstack.git
cd ecommerce-spa-fullstack
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
npm run dev
```
Backend runs on **http://localhost:4000**

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```
Frontend runs on **http://localhost:5173**

---

## ⚙️ Environment Variables

### Backend
Create `backend/.env`:
```
JWT_SECRET=supersecretkey
PORT=4000
```

### Frontend
Create `frontend/.env`:
```
VITE_API_BASE=http://localhost:4000
```

---

## 🚀 Deployment

- **Backend** → [Render](https://render.com), [Railway](https://railway.app)  
- **Frontend** → [Vercel](https://vercel.com), [Netlify](https://www.netlify.com)  

Set environment variables accordingly in hosting platforms.  

---

## 📸 Screenshots

> _(add screenshots of login, products, cart pages here after running locally)_

---

## 🤝 Contributing

1. Fork the repo  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m "feat: add new feature"`)  
4. Push branch (`git push origin feature-name`)  
5. Open a Pull Request  

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify.  
