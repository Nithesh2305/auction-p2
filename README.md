# Auction Platform 🏆

![Auction App Demo](demo.gif)

A full-stack auction application with real-time bidding capabilities.

## Features
- ✅ User authentication (JWT)
- 🏷️ Create/list auction items
- 💰 Real-time bidding
- 📱 Responsive design
- 🔒 Secure transactions

## Tech Stack
| Frontend          | Backend           |
|-------------------|-------------------|
| React             | Node.js/Express   |
| Axios             | MongoDB           |
| CSS Modules       | Mongoose          |
| React Router      | JWT               |

## Quick Start

1. Clone the repo:
```bash
git clone https://github.com/yourusername/auction-app.git
cd Auction

Set up backend:
cd backend
npm install
creae .env file
PORT=your port number

# MongoDB
MONGODB_URL=url

# JWT (For Authentication)
JWT_SECRET=your key
npm start

set up frontend
cd ../frontend
npm install
npm start
