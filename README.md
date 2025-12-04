# 🌾 AgriShield

**Empowering Farmers with Innovative Technology Solutions for Optimal Farm Operations and Stable Market Access**

---

## 🚀 About AgriShield

AgriShield is an innovative platform designed to revolutionize the agriculture sector by bridging the gap between farmers and buyers. The solution leverages cutting-edge technology to create a transparent, efficient, and farmer-friendly ecosystem.

### Key Features

- **🤖 AI-Driven Price Prediction**: Forecast crop prices up to 12 months in advance, enabling informed decisions about crop selection and planning
- **🔗 Blockchain Technology**: Tamper-proof, transparent digital contracts that secure agreements between farmers and buyers
- **💰 Dynamic Pricing Negotiation**: Flexible pricing with initial and final adjustments to adapt to market changes, plus minimum base price guarantees for stable farmer income
- **🌐 Multi-Language Support**: Voice-command-enabled interface for farmers from diverse regions and literacy levels
- **📱 Real-Time Communication**: WhatsApp, SMS, email, and live chat integration
- **💳 Secure Payments**: Razorpay integration for safe and reliable transactions
- **🛡️ Quality Assurance**: Crop insurance to safeguard against natural calamities

By fostering transparency, market stability, and efficiency, AgriShield empowers farmers, ensures consistent buyer supply, and promotes sustainable agricultural practices.

---

## 🔗 Live Application

**[Visit AgriShield](https://agrishield.vercel.app)**

---

## 🎥 Demo Video

Watch AgriShield in action:

**[AgriShield Demo](https://your-demo-video-link-here)**

---

## 🛠️ Installation Guide

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- Git

### 1. Fork & Clone the Repository

**Fork the Repository:**
- Navigate to the repository URL and click the **Fork** button

**Clone Your Forked Repository:**
```bash
git clone https://github.com/ujjwallsrivastavaa/AgriShield
cd AgriShield
```

---

### 2. Client Setup (Vite)

**Navigate to Client Directory:**
```bash
cd client
```

**Install Dependencies:**
```bash
npm install
```

**Configure Environment Variables:**

Create a `.env` file in the `client` directory:

```env
VITE_GOOGLE_CLIENT_ID=<Your Google Client ID>
VITE_GOOGLE_CLIENT_SECRET=<Your Google Client Secret>
VITE_SERVER_URL=<Your Server URL>
VITE_EMAIL_JS_SERVICE_ID=<Your EmailJS Service ID>
VITE_EMAIL_JS_USER_ID=<Your EmailJS User ID>
VITE_EMAIL_JS_CONTACT_US_TEMPLATE_ID=<Your EmailJS Contact Us Template ID>
VITE_AGRISHIELD_EMAIL=<Your AgriShield Email>
VITE_RAZORPAY_KEY_ID=<Your Razorpay Key ID>
```

**Start the Client:**
```bash
npm run dev
```

The client will be available at `http://localhost:3000`

---

### 3. Server Setup (Express)

**Navigate to Server Directory:**
```bash
cd server
```

**Install Dependencies:**
```bash
npm install
```

**Configure Environment Variables:**

Create a `.env` file in the `server` directory:

```env
PORT=5001
dbURL=<Your MongoDB URL>
SESSION_SECRET=<Your Session Secret Key>
COOKIE_SECRET=<Your Cookie Secret Key>
clientID=<Your Google Client ID>
clientSecret=<Your Google Client Secret>
CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
CLOUDINARY_API_KEY=<Your Cloudinary API Key>
CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
CLOUDINARY_URL=<Your Cloudinary URL>
JWT_SECRET=<Your JWT Secret Key>
VERIFICATION_URL=<Your Verification URL>
AGRISHIELD_EMAIL=<Your Email>
AGRISHIELD_EMAIL_PASSWORD=<Your Password>
OPENCAGE_LOCATION_API_KEY=<Your OpenCage API Key>
AWS_S3_URL=<Your AWS S3 URL>
CLIENT_URL=<Your Client URL>
RAZORPAY_KEY_ID=<Your Razorpay Key ID>
RAZORPAY_KEY_SECRET=<Your Razorpay Key Secret>
```

**Start the Server:**
```bash
npm run dev
```

The server will run on `http://localhost:5001`

---

## 📧 Contact

For queries and support, reach out to us at the AgriShield platform.

**Built with ❤️ for Farmers**
