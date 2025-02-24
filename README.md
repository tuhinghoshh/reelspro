**ImageKit Video Shop
A modern Next.js application for managing and selling video content using ImageKit integration. This project provides a full-featured platform with user authentication, video upload capabilities, and payment processing using Razorpay.

Features
🔐 User Authentication (NextAuth.js)
📹 Video Upload and Management (ImageKit)
💳 Payment Processing (Razorpay)
🎨 Modern UI with Tailwind CSS and DaisyUI
📱 Fully Responsive Design
🔒 Secure API Routes
📧 Email Notifications (Nodemailer)
🗄️ MongoDB Database Integration

*Tech Stack
Frontend: Next.js 15, React 19, TypeScript
Styling: Tailwind CSS, DaisyUI
Authentication: NextAuth.js, JWT
Database: MongoDB with Mongoose
File Storage: ImageKit
Payment: Razorpay
Email: Nodemailer
Form Handling: React Hook Form
Prerequisites
Node.js (Latest LTS version)
ImageKit Account
Razorpay Account
SMTP Server (for email notifications)

**Environment Variables
Create a .env file with the following variables:

# Database
MONGODB_URI=

# Authentication
NEXTAUTH_SECRET=
NEXTAUTH_URL=

# ImageKit
IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
IMAGEKIT_URL_ENDPOINT=

# Razorpay
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=

# Email (SMTP)
SMTP_HOST=
SMTP_PORT=
SMTP_USER=
SMTP_PASS=

**Available Scripts
npm run dev - Start development server
npm run build - Build production application
npm run start - Start production server
npm run lint - Run ESLint
npm run seed - Seed the database
npm run mailtrap - Test email configuration
