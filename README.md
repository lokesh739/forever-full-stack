# 🚀 Forever e-commerce

**Forever** is a full-stack e-commerce platform with role-based dashboards for Admin and Customer. It includes secure authentication, product browsing, cart and wishlist features, payment integration, and real-time order tracking.

## 📸 Project Preview

<p align="center">
  <img src="https://i.ibb.co/jvY7Zd4F/Screenshot-2025-06-25-005845.png" alt="Startup Advisory" width="100%" />
</p>

---

## ✨ Features

### 👤 Authentication & Roles
- Role-based signup via JWT authentication for users and admins.
- Secure access control for different dashboards and features

🛍️ Product Browsing & Discovery

Explore products by category (e.g., Clothing, Electronics, Accessories)

View product details, reviews, and stock availability

⭐ Wishlist System

Customers can add products to a wishlist for later

Easy move-to-cart option

🛒 Smart Cart & Checkout

Add, remove, or update product quantities

Automatic price updates with taxes/discounts

Secure checkout flow

💳 Payment Integration

Supports online payment processing (simulated/test mode)

Order confirmation and receipt generation

🚚 Order Management

Customers can:

Track order status (Placed → Packed → Shipped → Delivered)

Cancel orders before processing

Real-time status updates

👤 Customer Dashboard

View and manage wishlist, cart, and past orders

Update profile information

🛠️ Admin Panel

Add, edit, or delete products

Manage inventory and pricing

View and update order status

Manage users and access logs
---

## 🧑‍💻 Tech Stack

| Category              | Technology                    |
|-----------------------|-------------------------------|
| Frontend              | React, Next.js                |
| UI Library            | ShadCN UI, Tailwind CSS       |
| Authentication        | Clerk                         |
| Database              | Prisma + PostgreSQL           |
| Video Calling         | Vonage (OpenTok)              |
| Styling               | Tailwind CSS                  |
| Deployment            | Vercel (recommended)          |

---

## 📂 Project Structure (High-Level)

```
/app               → App directory (Next.js routing)
/components        → Reusable UI components
/lib               → Utility functions (e.g. checkAuth, db)
 /db               → Prisma client and helpers
/middleware.ts     → Clerk middleware for route protection
/pages/api         → API routes for booking, dashboard, etc.
/styles            → Tailwind base styling
```

---

## 🔧 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/startup-advisory.git
cd startup-advisory
```

### 2. Install dependencies
```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory and add:

```env
DATABASE_URL=postgresql://your-db-url
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-key
CLERK_SECRET_KEY=your-clerk-secret
VONAGE_API_KEY=your-vonage-api-key
VONAGE_API_SECRET=your-vonage-secret
VONAGE_SESSION_ID=session-id
VONAGE_TOKEN=token
```

> Replace the keys with your actual credentials.

---

### 4. Run Prisma Migrations

```bash
npx prisma db push
```

(Optional: Use `npx prisma studio` to explore the DB.)

---

### 5. Start the Development Server

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000)

---

## 🚀 Deployment

This app is ready for deployment on **Vercel**. Just connect your GitHub repository and set the required environment variables in the Vercel dashboard.

---

## 🧠 Future Improvements

- Stripe or Razorpay integration for real payments
- Notification system (email/SMS reminders)
- Advisor ratings and reviews
- Enhanced video features (screen sharing, recording)

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or want to suggest a feature, feel free to open an issue or pull request.

---

## 🧑‍💼 Author

Made with ❤️ by **Lokesh Maheswari**

