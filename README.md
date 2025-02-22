# Payment-Api
# Payment Gateway API 🚀

This is a **secure Payment Gateway API** using **Node.js, Express, MongoDB, and Stripe**. It supports user authentication, payment processing, and webhook handling.

## Features 🛠️
- **User Registration & Login** (JWT Authentication)
- **Secure Stripe Payment Processing**
- **Database Storage for Transactions**
- **Webhook Handling for Payment Status Updates**

## Tech Stack 💻
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ORM)
- **Payment Provider:** Stripe API
- **Authentication:** JWT

## Installation 🛠️
1. **Clone the Repository**
   ```sh
   git clone YOUR_REPO_URL
   cd payment-gateway-api
   ```
2. **Install Dependencies**
   ```sh
   npm install
   ```
3. **Set Up Environment Variables**  
   Create a `.env` file and add:
   ```env
   MONGO_URI=your_mongo_db_connection_string
   JWT_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
   ```
4. **Run the Server**
   ```sh
   npm start
   ```

## API Endpoints 📌
| Method | Endpoint        | Description              |
|--------|---------------|--------------------------|
| POST   | /register      | Register a new user     |
| POST   | /login         | User authentication     |
| POST   | /pay           | Create a Stripe Payment |
| POST   | /webhook       | Handle Stripe Webhooks  |

## Deployment 🌍
You can deploy this API on **Render**, **Vercel**, or **Heroku** for live usage.

## Contribution 🤝
Feel free to fork this repository and submit PRs!

## License 📜
This project is licensed under the **MIT License**.

🚀 **Happy Coding!**
