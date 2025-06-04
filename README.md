# 📌 Pinterest Clone

[![Deploy on Render](https://img.shields.io/badge/Deployed%20on-Render-green.svg?style=flat&logo=render)](https://pinterest-cs3q.onrender.com/)
[![GitHub repo size](https://img.shields.io/github/repo-size/manishN1999/Pintrest?color=blue&style=flat-square)](https://github.com/manishN1999/Pintrest)
[![License](https://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat-square)](LICENSE)

A full-stack Pinterest-inspired web application that allows users to upload, view, and save image-based content. Designed with a mobile-first approach and powered by modern web technologies, this project demonstrates scalable architecture, clean UI/UX design, and essential social media functionalities.

---

## 🚀 Live Demo

▶️ **Try it now:** [Pinterest Clone Live](https://pinterest-cs3q.onrender.com/)

---

## 📸 Preview

| Home Feed | Pin Detail | Upload Pin | User Profile |
|-----------|-------------|------------|---------------|
| _Add screenshots here if available_ |

---

## 🧱 Tech Stack

### 💻 Frontend
- HTML5, CSS3, JavaScript (Vanilla or React if used)
- Responsive Design with Flexbox/Grid
- Client-side form validation

### 🖥 Backend
- **Node.js** with **Express.js**
- RESTful API design
- Authentication using JWT

### 🗃 Database
- **MongoDB** with **Mongoose**

### ⚙️ Dev Tools & Deployment
- **Render** – Cloud deployment
- **Git & GitHub** – Version control
- **Postman** – API testing

---

## ✨ Key Features

- 🔐 **User Authentication:** Secure login and registration using JWT
- 🖼️ **Upload Pins:** Users can upload images with title, description, and tags
- 📌 **Pin Boards:** Save and organize favorite pins
- 🧑‍💼 **User Profiles:** Personalized dashboards to view uploaded and saved pins
- 🔍 **Search:** Discover pins using keyword-based search
- 💡 **Responsive UI:** Seamless experience across desktop and mobile

---

## 📂 Project Structure

Pintrest/
├── client/ # Frontend (if separated)
├── models/ # Mongoose schemas (User, Pin)
├── routes/ # Express routes (Auth, Pin, User)
├── controllers/ # Business logic
├── middleware/ # JWT Auth and error handling
├── public/ # Static files & uploads
├── .env # Environment configuration
├── server.js # Entry point
└── README.md

yaml
Copy
Edit

---

## 🧪 Getting Started Locally

### Prerequisites
- Node.js & npm
- MongoDB instance (local or cloud)

### Installation

```bash
# Clone the repository
git clone https://github.com/manishN1999/Pintrest.git
cd Pintrest

# Install dependencies
npm install

# Create and configure .env file
touch .env
.env example:

ini
Copy
Edit
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
bash
Copy
Edit
# Run the server
npm start
Navigate to http://localhost:5000 in your browser.

🛠️ Future Enhancements
🗨️ Comments on pins

🧭 Explore page with recommendations

🌙 Dark mode toggle

🔔 Notification system

📈 Analytics for pin popularity

👤 Author
Manish Nair
📎 GitHub Profile
🌐 Live App
📧 [Portfolio: https://manish-portfolio-ten.vercel.app/]

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Inspired by Pinterest UI/UX

MongoDB, Express, Node.js community documentation

Render for free deployment service

⭐ Support the Project
If you found this project helpful or interesting, consider giving it a ⭐ on GitHub. Your support is appreciated!

yaml
Copy
Edit
