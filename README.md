# BitLinks 🔗

![Next.js](https://img.shields.io/badge/Next.js-15-black)
![React](https://img.shields.io/badge/React-19-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-Styling-38BDF8)
![License](https://img.shields.io/badge/License-MIT-yellow)

A full-stack URL shortening platform built with Next.js, MongoDB, and Tailwind CSS that enables users to generate custom short links with fast redirection and persistent storage.

## Live Demo

🚀 https://your-vercel-link.vercel.app

---

## Features

* Generate custom short URLs
* Instant URL redirection
* MongoDB-backed persistent storage
* Responsive and user-friendly interface
* RESTful API support
* Custom alias creation
* Built using Next.js App Router

---

## Screenshots

### Home Page

<img src="./public/screenshots/home-page.png" width="900"/>

### URL Generation Interface

<img src="./public/screenshots/url-generation.png" width="700"/>

### Successful URL Creation

<img src="./public/screenshots/url-generated-success.png" width="700"/>

### MongoDB Database Records

<img src="./public/screenshots/database-records.png" width="900"/>

---

## Tech Stack

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
* Postman API Testing

---

## Architecture

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
URL Storage & Retrieval
          │
          ▼
   Fast Redirection
```

---

## API Endpoint

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

## Project Structure

```bash
bitlinks-url-shortener/
│
├── app/
├── components/
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

## Installation

### Clone Repository

```bash
git clone https://github.com/Sourav-Grover/bitlinks-url-shortener.git
```

### Navigate to Project

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

### Start Development Server

```bash
npm run dev
```

The application will run on:

```text
http://localhost:3000
```

---

## Future Enhancements

* QR Code Generation
* Click Analytics Dashboard
* User Authentication
* Link Expiration Support

---


## Author

### Sourav Grover

B.Tech CSE, KIIT University

* GitHub: https://github.com/Sourav-Grover
* LinkedIn: https://www.linkedin.com/in/souravgroverr
