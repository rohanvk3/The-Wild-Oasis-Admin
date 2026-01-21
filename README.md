🏨 The Wild Oasis — Admin Dashboard
The Wild Oasis is an internal hotel management system designed for administrators and hotel staff. It allows employees to manage cabins, bookings, guests, and view real-time business insights through an intuitive dashboard.

Note: This application is not customer-facing and is intended strictly for internal operations.

🚀 Live Demo
🔗 Deployed on Vercel: [Add your live URL here]

✨ Key Features
🔐 Authentication & Access Control
Secure Authentication: Powered by Supabase Auth.

Role-Based Access: Strictly for authorized hotel staff.

Protected Routes: Prevents unauthorized access to sensitive data.

👤 Employee Profile Management
Update personal details and password securely.

Upload and manage avatar images.

📊 Admin Dashboard
Real-time Overview: Instant view of recent bookings and check-ins.

Financial Insights: Track revenue and sales statistics.

Occupancy Data: Visual metrics for quick decision-making.

🏡 Cabin Management
CRUD Operations: Create, update, and delete cabin records.

Inventory Control: Manage capacity, pricing, and discounts.

Visuals: Upload and host cabin images via Supabase Storage.

📅 Booking Management
Centralized View: See all bookings in a unified table.

Check-in/Check-out: Streamlined guest processing.

Status Updates: Modify booking and payment statuses instantly.

⚡ Real-Time & Analytics
Live Updates: Immediate synchronization for cabins and bookings using Supabase Realtime.

Data Visualization: Interactive charts powered by Recharts for sales trends and occupancy rates.

🌙 Dark Mode
System-wide theme switching for better accessibility and user comfort.

🛠 Tech Stack
Frontend
Core: React, React Router

State Management: React Query (TanStack Query)

Forms: React Hook Form

Styling: Styled Components

Visualization: Recharts

Backend & Services (Supabase)
Database: PostgreSQL

Auth: Secure user authentication

Storage: Image hosting for avatars and cabins

Real-time: Live data subscriptions

Tooling
Build Tool: Vite

Deployment: Vercel

⚙️ Setup & Installation
Follow these steps to set up the project locally.

1️⃣ Clone the Repository
Bash
git clone https://github.com/rohanvk3/The-Wild-Oasis-Admin.git
cd The-Wild-Oasis-Admin
2️⃣ Install Dependencies
Bash
npm install
3️⃣ Environment Variables
Create a .env file in the root directory and add your Supabase credentials:

Code snippet
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
4️⃣ Run the App Locally
Start the development server:

Bash
npm run dev
Open http://localhost:5173 in your browser to view the app.
