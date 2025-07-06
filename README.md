# 🌐 Internet Speed Testing App (MERN)

## 🌟 Overview

A full-stack **MERN (MongoDB, Express.js, React.js, Node.js)** application that enables users to:

- Test their **internet speed** (download & upload)
- View their **public IP address**
- Detect their **current geographic location**

This app leverages **browser APIs**, **network tools**, and an optional **MongoDB** backend for result logging and analytics.

---

## 🚀 Features

- ⚡ **Real-time Internet Speed Testing** (Download & Upload)
- 🌍 **Display Public IP Address**
- 📍 **Detect User’s Current Location** using browser geolocation
- 📊 **Responsive & Intuitive UI** built with React
- 🌐 **Backend API** for fetching and optionally logging network data
- 🧾 **Optional Logging** of speed test results into MongoDB

---

## 🛠️ Tech Stack

- **Frontend:** React.js, JavaScript, Axios, HTML/CSS  
- **Backend:** Node.js, Express.js  
- **Database (Optional):** MongoDB (for storing test results)

### 📎 Additional Tools & APIs

- `ipify` or `ipapi` – Retrieve public IP address  
- `HTML5 navigator.geolocation` – Detect user location  
- `speedtest-net` or custom logic using `fetch`/sockets – Measure internet speed

---

## 🎯 How It Works

The **frontend React application** performs the following:

1. **Fetches the user’s public IP address** using an external API.
2. **Detects the location** via the HTML5 Geolocation API.
3. **Measures download and upload speed** by sending/receiving data packets.
4. **Sends results to the backend**, which can optionally store them in **MongoDB** for analytics.

---

## 📦 Installation & Usage

```bash
# 1. Clone the repository
git clone https://github.com/noormalik33/Internet-Speed-Testing-App-MERN.git
cd Internet-Speed-Testing-App-MERN

# 2. Setup backend
cd backend
npm install
npm start

# 3. Setup frontend
cd ../frontend
npm install
npm start

👨‍💻 Team Members
Name	Location	Contact
Noor Malik	Islamabad, Pakistan	📧 noormalik56500@gmail.com
🔗 LinkedIn
Ghulam Qadir	Rawalpindi, Pakistan	🔗 LinkedIn

# 📜 License
This project is open-source and available for educational and non-commercial use under the MIT License.

**Ghulam Qadir**  
- Email: [gqitspecialist@gmail.com](mailto:gqitspecialist@gmail.com)  
- LinkedIn: [Ghulam Qadir](https://www.linkedin.com/in/ghulam-qadir-07a982365)

**Noor Malik**		📧 noormalik56500@gmail.com
          🔗 LinkedIn
