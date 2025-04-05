# eCommerce Platform Project - MERN Stack

Welcome to the **eCommerce Platform Project** built using the **MERN (MongoDB, Express.js, React, Node.js)** stack. This project offers a comprehensive, full-featured online shopping experience with powerful functionalities tailored to both users and administrators.

🔗 **Live App Demo**: [https://mern-shop-abxs.onrender.com/](https://mern-shop-abxs.onrender.com/)
> Note: Render's free tier will shut down after 15 minutes of inactivity. The first request after reactivation may be delayed.

## Features

- **Shopping Cart**: Add, remove, and manage products easily.
- **Product Reviews & Ratings**: Share user experiences through reviews and ratings.
- **Top Products Carousel**: Highlight top-rated or featured items.
- **Pagination**: Navigate through products page-by-page.
- **Search**: Find products using keywords.
- **User Profile & Orders**: Track orders via user dashboard.
- **Admin Dashboard**: Manage products, users, orders, and admins.
- **Admin Functionalities**:
  - Admin account management
  - Product CRUD operations
  - User management
  - Order details and delivery status
- **Checkout Flow**: Seamless experience with shipping and payment options.
- **Razorpay Integration**: Secure payment gateway.
- **Database Seeder**: Populate with sample data for testing/demo.

## Getting Started

### Prerequisites

1. Fork and clone the repository:
   ```bash
   git clone https://github.com/your-username/MERN-eCommerce.git
   cd MERN-eCommerce
   ```
2. Set up your MongoDB database via [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
3. Get Razorpay credentials from [Razorpay](https://razorpay.com/).
4. Sign up on [Brevo](https://www.brevo.com/) and get your SMTP key.

### Environment Variables

1. Rename `.env.example` to `.env`.
2. Fill in the following:

```env
NODE_ENV=development
PORT=5000
JWT_SECRET=your_jwt_secret
MONGO_URI=your_mongo_uri
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
PAGINATION_MAX_LIMIT=12
EMAIL_HOST=smtp-relay.brevo.com
EMAIL_PORT=587
EMAIL_USER=your_brevo_login
EMAIL_PASS=your_brevo_password
EMAIL_FROM=your_brevo_login
```

## Install Dependencies

```bash
# Install backend dependencies
npm install

# Navigate to frontend and install dependencies
cd frontend
npm install
```

## Run Application

To run backend and frontend concurrently:
```bash
npm run dev
```

To run backend only:
```bash
npm run server
```

## Build & Deploy

To build the frontend for production:
```bash
cd frontend
npm run build
```

## Seed Database

```bash
# Import sample data
npm run data:import

# Delete all data
npm run data:destroy
```

## Sample User Logins

### Admin:
  - [Admin Login](https://mern-shop-abxs.onrender.com/admin/login)
  - **Email**: admin@admin.com
  - **Password**: admin123

### Customers:
  - [Customer Login](https://mern-shop-abxs.onrender.com/login)
  - **John Doe**
    - Email: john@email.com
    - Password: john123
  - **Alice Smith**
    - Email: alice@email.com
    - Password: alice123

## Contributing

We welcome contributions from developers, designers, and testers. Here's how to contribute:

### Step-by-Step:

1. Fork the repository
2. Clone it:
   ```bash
   git clone https://github.com/your-username/MERN-eCommerce.git
   cd MERN-eCommerce
   ```
3. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   # or for issues:
   git checkout -b issues/your-issue-name
   ```

### Make Your Changes:
- Follow coding conventions
- Test thoroughly
- Update documentation if needed

### Commit & Push:
```bash
git add .
git commit -m "Describe your changes"
git push origin your-branch-name
```

### Submit Pull Request:
1. Open a PR from your fork
2. Provide a clear title and description
3. Wait for review and feedback

## Thank You!

Thanks for contributing to the project! For questions or help, use the issue tracker or discussion tab. Happy coding! 

