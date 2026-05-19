# SureBet Nigeria Webhook Service

This repository contains the backend webhook service for handling secure payment notifications and event callbacks for SureBet Nigeria Ltd.

---

## 📌 About The Project

This project is a Node.js webhook server used to receive and process real-time events such as payment confirmations, transaction updates, and callback notifications from payment providers like Paystack.

It ensures that all transactions are verified and securely recorded in the system.

---

## 🚀 Features

- Secure webhook endpoint  
- Handles payment confirmation events  
- Verifies incoming requests for safety  
- Logs transaction data  
- Easy integration with frontend systems  
- Built for scalability  

---

## 🛠️ Built With

- Node.js  
- Express.js  
- JavaScript (ES6+)  
- Paystack Webhooks  

---

## 📁 Project Structure

surebet-webhook/  
├── server.js  
├── package.json  
├── .env  
└── README.md  

---

## ⚙️ Installation

1. Clone the repository:

git clone https://github.com/Surebetnigeria/surebet-webhook.git  

2. Move into the project folder:

cd surebet-webhook  

3. Install dependencies:

npm install  

4. Create a `.env` file:

PORT=3000  
PAYSTACK_SECRET_KEY=your_secret_key  

5. Start the server:

node server.js  

---

## 🔗 Webhook Endpoint

POST /webhook  

This endpoint receives payment events from Paystack or other providers.

---

## 🔐 Security

- Always verify webhook signatures  
- Never expose secret keys on GitHub  
- Use environment variables for sensitive data  

---

## 📞 Contact

Project: SureBet Nigeria Ltd  
Website: www.surebetnigeria.com  
Email: support@surebetnigeria.com  

---

## 📄 License

This project is private and owned by SureBet Nigeria Ltd.
