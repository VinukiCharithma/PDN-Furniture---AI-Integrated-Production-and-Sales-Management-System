# ⭐ **PDN Furniture — AI-Integrated Production & Sales Management System**

*A complete MERN-stack platform for furniture e-commerce, production workflow automation, inventory management, employee assignment & delivery tracking.*

---

## 🚀 **Overview**

**PDN Furniture** is a full-stack MERN (MongoDB, Express, React, Node.js) application designed specifically for PDN furniture manufacturing company.
It includes:

✔ A customer-facing **e-commerce site**
✔ An in-depth **admin dashboard**
✔ **AI-based automation** for task scheduling & employee assignment
✔ **Inventory & raw material management**
✔ **Real-time delivery tracking** with Google Maps API
✔ **Reporting & analytics** with exportable reports

This system streamlines the entire workflow — from product listing to delivery.

---

## 🛍️ **Customer-Side Features**

* 🪑 **Product Catalogue** with search, filters & detailed product pages
* 🛒 **Cart & Checkout** flow
* 📦 **Order Placement & History**
* 🚚 **Live Delivery Tracking** (Google Maps)
* 👤 **Profile Management**
* 🔐 Secure login/signup (JWT)

---

## 🛠️ **Admin / Shop Management Features**

### 📦 **Order & Product Catalogue Management**

* Add/update/delete products
* View & manage all customer orders
* Change order statuses (pending → production → delivery)

### 🤖 **AI-Powered Production Task Automation**

* Breaks customer orders into manageable internal tasks
* Auto-assigns employees based on skills & workload
* Task dashboard for tracking progress

### 📉 **Raw Material Inventory Management**

* Real-time inventory dashboard
* Usage tracking for each production task
* Vendor purchase logging
* 🔔 **Automatic Low-Stock Alerts**

### 👷 **Employee & Task Scheduling**

* Workload monitoring
* AI-based assignment
* Manual override with full control
* Daily/weekly calendar view

### 🚚 **Delivery Management**

* Delivery scheduling
* Assign delivery personnel
* **Google Maps API** for live tracking
* Customer-facing tracking page

### 📊 **Reports & Analytics**

* Sales reports
* Inventory usage reports
* Employee productivity
* Delivery performance
* 📥 Export as **PDF/Excel**

---

## 🧱 **Tech Stack**

### 🌐 Frontend

* React.js
* Redux / Context API
* TailwindCSS or Material UI
* Axios

### 🖥️ Backend

* Node.js
* Express.js
* MongoDB + Mongoose
* JWT authentication

### 🔗 Integrations

* Google Maps API
* AI Task Breakdown (OpenAI / custom logic)
* Cloudinary / AWS S3 for images
* Cron Jobs for notifications

---

## 📂 **Project Structure**

```
/
├── frontend/            # React application
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/             # Node/Express application
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── utils/
│   └── server.js
│
├── .env.example
├── package.json
└── README.md
```

---

## 🛠️ **Getting Started**

### 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/VinukiCharithma/PDN-Furniture---AI-Integrated-Production-and-Sales-Management-System.git
cd PDN-Furniture---AI-Integrated-Production-and-Sales-Management-System
```

### 2️⃣ **Install Dependencies**

**Backend**

```bash
cd backend
npm install
```

**Frontend**

```bash
cd ../frontend
npm install
```

### 3️⃣ **Environment Variables**

Create a `.env` file in **backend**:

```
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
GOOGLE_MAPS_API_KEY=your_maps_key
CLOUDINARY_URL=your_cloudinary_url
AI_API_KEY=your_ai_key_if_applicable
```

For **frontend**, create `.env`:

```
REACT_APP_API_BASE_URL=http://localhost:5000/api
REACT_APP_MAPS_KEY=your_maps_key
```

### 4️⃣ **Run the Application**

**Backend**

```bash
npm start
```

**Frontend**

```bash
npm start
```

---

## 📈 **System Workflow**

1. 🛍 Customer browses products and places an order
2. 🤖 AI auto-generates production tasks
3. 👷 Employees are auto-assigned tasks (or assigned manually)
4. 📉 Inventory automatically updates
5. 🔔 Low-stock alerts trigger when needed
6. 🚚 Delivery is scheduled & tracked via Google Maps
7. 📊 Admin reviews analytics and exports reports

---

## 📸 **Screenshots / Demo**

<img width="843" height="478" alt="ITP Home" src="https://github.com/user-attachments/assets/86adbc8f-f61f-48f0-969b-fcfff26f1bcf" />
<img width="844" height="479" alt="ITP Catalog" src="https://github.com/user-attachments/assets/26549b5b-f90b-48c9-8e69-ddfe2a5dff25" />
<img width="836" height="478" alt="ITP Order" src="https://github.com/user-attachments/assets/195d5763-4319-4bd1-86ed-8c6e6c1d0b0e" />
<img width="841" height="470" alt="ITP Products" src="https://github.com/user-attachments/assets/82cb0782-b7ad-4d46-b3b3-0496589c1cb5" />
<img width="839" height="476" alt="ITP Inventory" src="https://github.com/user-attachments/assets/dc505ef5-b400-4a3e-8ea0-80b3278af92d" />
<img width="842" height="474" alt="ITP Tasks" src="https://github.com/user-attachments/assets/f583f9a7-5ed3-4f8c-a2a8-437ded0dbe40" />
<img width="841" height="474" alt="ITP Delivery" src="https://github.com/user-attachments/assets/77753479-1c48-40d7-a285-806e51151c44" />
<img width="840" height="470" alt="ITP Track" src="https://github.com/user-attachments/assets/290c920c-b056-4cf6-86e2-9c794e97b8e9" />

---

## 🤝 **Contributing**

We welcome contributions!

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit changes
4. Push branch
5. Open Pull Request

---

## 📄 **License**

This project is under the **MIT License**.

---

## 💬 **Contact**

For inquiries, contact the me or open an issue on the repository.

---

