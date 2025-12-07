# 🚀 Forever e-commerce

**Forever** is a full-stack e-commerce platform with role-based dashboards for Admin and Customer. It includes secure authentication, product browsing, cart and wishlist features, payment integration, and real-time order tracking.

## 📸 Project Preview

<p align="center">
  <img src="https://i.ibb.co/jvY7Zd4F/Screenshot 2025-12-08 024729.png" alt="Startup Advisory" width="100%" />
</p>

---

## ✨ Features

## ✨ Features

### 👤 Authentication & Roles
- Role-based signup via JWT tokens (Users/Admins)
- Secure access control for different dashboards and features

### 🔍 Product Browsing & Discovery
- Explore products by category (e.g., Clothing, Electronics, Accessories)
- View product details, reviews, and stock availability

### 🛒 Smart Cart & Checkout
- Add, remove, or update product quantities
- Automatic price updates with taxes/discounts
- Secure checkout flow

### 💳 Payment Integration
- Supports online payment processing (simulated/test mode)
- Order confirmation and receipt generation

### 🚚 Order Management
- Customers can:
  - Track order status (Placed → Packed → Shipped → Delivered)
  - Cancel orders before processing 
-Real-time status updates

### 👤 Customer Dashboard
- View and manage wishlist, cart, and past orders
- Update profile information

### 🛠️ Admin Panel
- Add, edit, or delete products and Manage inventory and pricing
- View and update order status and Manage users and access logs

---

## 🧑‍💻 Tech Stack

| Category              | Technology                    |
|-----------------------|-------------------------------|
| Frontend              | React                         |
| UI Library            | Tailwind CSS                  |
| Authentication        | JWT Tokens                    |
| Database              | MongoDB                       |
| Payment Gateway       | Stripe and RazorPay           |
| Styling               | Tailwind CSS                  |
| Deployment            | Vercel (recommended)          |

---

## 🔧 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/forever-full-stack.git
cd forever-full-stack
```

### 2. Install dependencies
```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory and add:

```env
JWT_SECRET = "Your known secret key"
ADMIN_EMAIL = "Your own gmail"
ADMIN_PASSWORD = "Yout own password"
MONGODB_URI = "Your own MONGODB_URL"
CLOUDINARY_API_KEY = "Your Own CLOUDINARY_API_KEY"
CLOUDINARY_SECRET_KEY = "Your Own CLOUDINARY_SECRET_KEY"
CLOUDINARY_NAME = "Your Own CLOUDINARY_NAME""
STRIPE_SECRET_KEY ="Your Own STRIPE_SECRET_KEY"
RAZORPAY_KEY_SECRET = "Your Own RAZORPAY_KEY_SECRET"
RAZORPAY_KEY_ID = "Your Own RAZORPAY_KEY_ID"
```

> Replace the keys with your actual credentials.

---

### 4. Run Database Migrations

```bash
npx run server
```

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

- Seller Dashboard: Enable sellers to register, list products, and manage their own inventory and orders.
- AI Recommendations: Add machine learning–based personalized product suggestions for users.
- Delivery Partner Integration: Connect with logistics APIs for automated shipping, real-time tracking, and delivery updates.
- Dynamic Pricing & Offers: Implement smart discounting, loyalty rewards, and automated promotional campaigns.

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or want to suggest a feature, feel free to open an issue or pull request.

---

## 🧑‍💼 Author

Made with ❤️ by **Lokesh Maheswari**

