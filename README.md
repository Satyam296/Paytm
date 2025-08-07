# Paytm Wallet Clone

> A secure, scalable digital wallet inspired by **Paytm**.  
> Users can register, add money, transfer funds via phone or QR code, and view transaction history in real time.

---

## Features

- 🔐 **User Registration & Login** with JWT authentication  
- 💰 **Add Money** to wallet securely  
- 📲 **Transfer Money** via phone number or QR code scanning  
- 📜 **View Transaction History** with timestamps  
- 🖼️ **Dynamic QR Code Generation** for payments  
- ✅ **Input Validation** and security best practices  
- ⚙️ *(Optional)* Admin dashboard to monitor users & transactions  

---

## Tech Stack

| Frontend             | Backend                | Other Tools                   |
|----------------------|------------------------|------------------------------|
| React.js / Next.js   | Node.js + Express.js   | MongoDB + Mongoose           |
| TypeScript           | JWT Authentication     | QR Code Generation (`qrcode`)|
| Tailwind CSS         | REST APIs              | Docker (optional)            |
| Axios                |                        | Tesseract.js (OCR, optional) |

---

## Getting Started

### Prerequisites

- Node.js v16+  
- MongoDB (local or cloud)  
- npm or yarn  

### Installation

```bash
# Clone the repo
git clone https://github.com/Satyam296/paytm-wallet-clone.git
cd paytm-wallet-clone

# Backend setup
cd backend
npm install
npm run dev

# Frontend setup (in a new terminal)
cd ../frontend
npm install
npm run dev
```


## Roadmap / Future Improvements

- UPI integration (mock API)  
- Wallet to bank withdrawals  
- Real-time payment notifications  
- Dark mode & PWA support  
- Multi-language interface  

---

## Author

**Satyam Chhetri**  
[LinkedIn](https://www.linkedin.com/in/satyam-chhetri-010447318) | [GitHub](https://github.com/Satyam296) | [Email](mailto:satyamchhetri629@gmail.com)

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
