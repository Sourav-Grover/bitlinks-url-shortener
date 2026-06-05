# BitLinks 🔗

![Next.js](https://img.shields.io/badge/Next.js-15-black)
![React](https://img.shields.io/badge/React-19-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-Styling-38BDF8)
![License](https://img.shields.io/badge/License-MIT-yellow)

A full-stack URL shortening platform built with Next.js, MongoDB, and Tailwind CSS that enables users to generate custom short links with fast redirection and persistent storage.

---

## ✨ Features

* Generate custom short URLs
* Instant URL redirection
* MongoDB-backed persistent storage
* Custom alias support
* Responsive and modern UI
* RESTful API integration
* Built with Next.js App Router

---

## 🛠️ Tech Stack

### Frontend

* Next.js 15
* React 19
* Tailwind CSS

### Backend

* Next.js API Routes
* MongoDB

### Development Tools

* Git
* GitHub
* Postman

---

## 🏗️ Architecture

```text
Client (Next.js Frontend)
          │
          ▼
      API Routes
          │
          ▼
   MongoDB Database
          │
          ▼
 URL Storage & Lookup
          │
          ▼
   Fast Redirection
```

---

## 🔌 API Endpoint

### Generate Short URL

```http
POST /api/generate
```

### Request Body

```json
{
  "url": "https://example.com",
  "shorturl": "custom-link"
}
```

### Example Response

```json
{
  "success": true,
  "shorturl": "custom-link"
}
```

---

## 📁 Project Structure

```bash
bitlinks-url-shortener/
│
├── app/
├── public/
│   └── screenshots/
│       ├── home-page.png
│       ├── url-generation.png
│       ├── url-generated-success.png
│       └── database-records.png
│
├── BitLinks.postman_collection.json
├── package.json
├── package-lock.json
├── next.config.mjs
├── tailwind.config.js
├── .gitignore
├── LICENSE
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Sourav-Grover/bitlinks-url-shortener.git
```

### Navigate to Project Directory

```bash
cd bitlinks-url-shortener
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file:

```env
MONGODB_URI=your_mongodb_connection_string
```

### Run Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

## 🎯 Future Improvements

* QR Code Generation
* Click Analytics Dashboard
* User Authentication
* Link Expiration Support

---

## 👨‍💻 Author

### Sourav Grover

B.Tech CSE, KIIT University

* GitHub: https://github.com/Sourav-Grover
* LinkedIn: https://www.linkedin.com/in/souravgroverr
