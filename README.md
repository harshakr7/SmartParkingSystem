# SmartParkingSystem
# 🚗 Smart Parking Slot Reservation System

A full-stack web application that allows users to **book parking slots**, **verify using OTP**, **view booking history**, and **cancel active bookings**.  
Built using **Node.js, Express, MongoDB**, and **HTML/CSS/JS** frontend.

---

## 📌 Features

### ✅ User Features
- User Registration & Login  
- Parking Slot Selection  
- OTP Verification via Email  
- QR Code Generation for Booked Slot  
- Booking Expiry Time with Auto-Unblock  
- Booking History Page  
- Cancel Active Bookings Anytime  

### 🛠 Backend Features
- Node.js + Express Server  
- MongoDB for Storing Users & Bookings  
- Nodemailer for Email OTP  
- JWT Authentication  
- REST API Endpoints  
- Auto-clear expired bookings  

---

## 📂 Project Structure

```
SmartParking/
│
├── server.js
├── package.json
├── package-lock.json
├── .gitignore
├── README.md
├── .env.example
│
├── public/
│   ├── slot.html
│   ├── otp.html
│   ├── confirm.html
│   ├── history.html
│   ├── login.html
│   ├── register.html
│   └── styles.css
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```
git clone https://github.com/YOUR_USERNAME/SmartParking.git
cd SmartParking
```

### 2️⃣ Install dependencies
```
npm install
```
if you want your only email receives otp do this or else directly you can enter your email.
### 3️⃣ Create `.env` file
Copy `.env.example` → `.env`  
Add your email & app password:

```
EMAIL_USER=yourgmail@gmail.com
EMAIL_PASS=yourapppassword
```

### 4️⃣ Start the server
```
node server.js
```

---

## 🚀 How It Works

1. User selects a slot → selects duration  
2. OTP is sent to email  
3. After verification, slot gets booked  
4. Slot is blocked until expiry time  
5. User can view all past bookings  
6. User can cancel active bookings  
7. Slot auto-unlocks after expiry or cancellation  

---

## 🤝 Contributing
Pull requests are welcome!  
Feel free to open issues and suggest new features.

---

## 📄 License
This project is open-source and free to use.

---

