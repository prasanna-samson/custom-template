# Next.js Full-Stack Template with Authentication & Dashboard
This template is a fully functional Next.js starter project that includes user authentication and a customizable dashboard. It's designed to be easy to set up, extend, and customize.

Features
🌐 Next.js 13 – Modern server-side rendering framework.
🔑 Full Authentication Module – User registration, login, logout, password reset.
🏠 Customizable Dashboard – Pre-built layout with user stats, analytics, and UI components.
🔒 Protected Routes – Secure pages with role-based access control (RBAC).
💾 MongoDB Integration – User and session data stored in a MongoDB database.
🎨 Tailwind CSS – Fast styling with a modern utility-first framework.
🚀 API Routes – Built-in API routes for authentication and dashboard data.
📱 Responsive – Mobile-first design.
Quick Start
Follow these steps to set up and run the project locally.

Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v16+)
MongoDB (or a cloud MongoDB Atlas instance)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/nextjs-auth-dashboard.git
cd nextjs-auth-dashboard
Install dependencies:

bash
Copy code
npm install
Set up environment variables:

Create a .env.local file in the root directory and add the following variables:

bash
Copy code
# MongoDB connection string
MONGODB_URI=mongodb://localhost:27017/nextjs-auth-template

# JWT secret for signing tokens
JWT_SECRET=your_jwt_secret

# Optional: Email configuration (for password reset functionality)
EMAIL_SERVER=smtp://smtp.example.com
EMAIL_FROM=noreply@example.com
Replace the values with your own configuration.

Run database migrations (if any):

If you're using MongoDB, ensure the collections and indexes are set up correctly. If there are no migrations, skip this step.

Run the Development Server
To start the development server:

bash
Copy code
npm run dev
Open http://localhost:3000 to view the app in your browser.

Production Build
For a production-ready build:

bash
Copy code
npm run build
npm start
