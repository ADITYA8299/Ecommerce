# MERN Stack eCommerce Platform

A fully functional eCommerce website built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This platform includes features such as user authentication, product browsing, cart management, checkout with Stripe integration, and an admin dashboard for managing products and orders.

---

## 🔧 Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (using MongoDB Atlas)
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Integration**: Stripe (or PayPal)
- **Deployment**: Vercel (Frontend), MongoDB Atlas (Database), Render/Heroku (Backend)

---

## ✨ Features

### User
- Register & Login (JWT Auth)
- Browse products
- Add to cart
- Checkout with payment
- View order history

### Admin
- Role-based access
- Add/edit/delete products
- Manage user accounts
- View/manage all orders

---

## 🗂️ Folder Structure

```bash
root/
├── client/                 # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.jsx
├── server/                 # Express Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
