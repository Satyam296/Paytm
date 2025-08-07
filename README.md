Paytm Wallet Clone – Full Stack Project
A secure, scalable digital wallet web app inspired by Paytm, allowing users to register, add money, transfer funds via phone number or QR code, and view transaction history in real time.

Features
User Registration & Login with JWT authentication

Add money to wallet securely

Transfer money to other users using phone numbers or scanning QR codes

View detailed transaction history with timestamps

Dynamic QR code generation for payments

Input validation and security best practices

(Optional) Admin dashboard to monitor users and transactions

Tech Stack
Frontend:

React.js / Next.js (TypeScript)

Tailwind CSS for responsive UI

Axios for API communication

Backend:

Node.js + Express.js

MongoDB with Mongoose ORM

JWT-based authentication

QR code generation (qrcode npm package)

Optional / Additional:

Docker for containerization

Cloudinary for QR code image hosting

Tesseract.js for OCR (if integrated)

Getting Started
Prerequisites
Node.js (v16 or higher recommended)

MongoDB (local or Atlas cluster)

npm or yarn

Installation
Clone the repo

bash
Copy
Edit
git clone https://github.com/Satyam296/paytm-wallet-clone.git
cd paytm-wallet-clone
Setup Backend

bash
Copy
Edit
cd backend
npm install
npm run dev
Setup Frontend

bash
Copy
Edit
cd frontend
npm install
npm run dev
Open your browser at http://localhost:3000 (or the port your frontend runs on)

Screenshots
Add screenshots here showing:

User registration/login

Wallet dashboard

QR code payment screen

Transaction history

Admin dashboard (if applicable)

Future Improvements
UPI integration with mock APIs

Wallet to bank withdrawals

Real-time notifications for transactions

Dark mode & PWA support

Multi-language support

Author
Satyam Chhetri

LinkedIn: linkedin.com/in/satyam-chhetri-010447318

GitHub: github.com/Satyam296

Email: satyamchhetri629@gmail.com

License
This project is licensed under the MIT License — see the LICENSE file for details.
