# 🏨 The Wild Oasis — Admin Dashboard

The Wild Oasis is an internal hotel management system designed for administrators and hotel staff. It allows employees to manage cabins, bookings, guests, and view real-time business insights through an intuitive dashboard.

## 🚀 Live Demo

🔗 **Deployed on Vercel:** [https://the-wild-oasis-rohan.vercel.app/]

---

## ✨ Key Features

### 🔐 Authentication & Access Control
- **Secure Authentication:** Powered by Supabase.
- **Role-Based Access:** Only authorized hotel staff can access the application.
- **Protected Routes:** Prevents unauthorized access to sensitive pages.

### 👤 Employee Profile Management
- Update personal profile details.
- Upload and update avatar images.
- Change passwords securely.

### 📊 Admin Dashboard
- **Overview:** View recent bookings and check-ins.
- **Stats:** Revenue and sales statistics.
- **Insights:** Occupancy data for quick decision-making.

### 🏡 Cabin Management
- Create, update, and delete cabin records.
- Manage capacity, pricing, and discounts.
- Upload and manage cabin images.

### 📅 Booking Management
- View all bookings in one place.
- Check guests in and out.
- Update booking and payment statuses.

### ⚡ Real-Time Updates
- Live updates for cabins and bookings.
- Powered by Supabase real-time subscriptions.

### 📈 Analytics & Data Visualization
- **Interactive charts:**
  - Sales trends
  - Booking activity
  - Occupancy rates

### 🌙 Dark Mode
- Fully functional dark mode.
- System-wide theme switching for better accessibility.

---

## 🛠 Tech Stack

### Frontend
- **React**
- **React Router**
- **React Query (TanStack Query)**
- **React Hook Form**
- **Styled Components**
- **Recharts**

### Backend & Services
- **Supabase**
- **Authentication**
- **PostgreSQL Database**
- **Real-time subscriptions**
- **File storage (avatars & cabin images)**

### Tooling & Deployment
- **Vite**
- **Vercel**

---

## ⚙️ Setup & Installation

Follow these steps to run the project locally.

### 1️⃣ Clone the Repository
```bash
git clone [https://github.com/rohanvk3/The-Wild-Oasis-Admin.git](https://github.com/rohanvk3/The-Wild-Oasis-Admin.git)
cd The-Wild-Oasis-Admin

npm install

Create a .env file in the root directory and add the following:

VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

npm run dev

Open http://localhost:5173 in your browser.
