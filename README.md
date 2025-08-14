# AuctionVerse (BIDFAIR) 🎯

Quirkle is a powerful, real-time auction platform engineered using the MERN stack and Socket.io, delivering seamless live bidding, strong security, advanced search, user management, and analytics for administrators—all wrapped in a responsive design for every device._

***

## 🚀 Live Demo

Experience AuctionVerse in action:  
🔗 [View Live Project](https://quirkle-bid-3.onrender.com/)

***

## 🎨 Project Preview
✨ Key Features

#### For Users
- **Real-Time Auctions:** Place live bids and see instant updates across all users via Socket.io
- **JWT Authentication:** Secure sign-up/login with token-based sessions, password hashing via bcrypt
- **Advanced Search:** Quickly discover auctions with dynamic filters (by item name, category, etc.)
- **User Profile Management:** Track your bids, purchases, and update account settings
- **Responsive UI:** Optimized for mobile, tablet, and desktop

#### For Admins
- **Admin Dashboard:** Monitor auctions, users, system metrics and activity in real time
- **Auction Management:** Create, edit, and remove auction items; control auction timings
- **User Management:** Ban/activate users, view user stats, manage permissions
- **Analytics:** Live charts for active users, ongoing bids, and site statistics

***

## 🛠️ Detailed Tech Stack

| Layer      | Tools/Libraries                                       | Purpose                                 |
|------------|-------------------------------------------------------|-----------------------------------------|
| **Frontend**  | React.js, Axios, Tailwind CSS/Material UI           | SPA, UI components, API communication   |
| **Backend**   | Node.js, Express.js, Socket.io                      | REST & WebSocket server, API endpoints  |
| **Database**  | MongoDB, Mongoose                                   | Storing user, auction, and bid data     |
| **Authentication** | JWT, bcrypt.js                               | Secure sessions, password hashing       |
| **Real-Time** | Socket.io                                           | Live bid updates, user presence         |
| **DevOps/Hosting** | Render.com                                    | Free/paid cloud hosting                 |

***

## 📂 Folder Structure

```
AuctionVerse/
├── client/              # React front-end
│   ├── src/
│   └── public/
├── server/              # Node/Express back-end
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── sockets/
│   └── config/
├── .env.example
├── README.md
└── package.json
```

***

## ⚡ Getting Started

**To run locally:**

1. **Clone the repository**  
   ```
   git clone https://github.com/yourusername/auctionverse.git
   cd auctionverse
   ```

2. **Install dependencies**
   ```
   cd server && npm install
   cd ../client && npm install
   ```

3. **Configure environment variables**  
   - Copy `server/.env.example` to `server/.env`
   - Add your MongoDB connection string, JWT secret, and any other keys:
     ```
     PORT=5000
     MONGO_URI=
     JWT_SECRET=
     ```

4. **Run the backend server**
   ```
   cd server
   npm run dev
   ```

5. **Run the React frontend**
   ```
   cd ../client
   npm start
   ```


***


***

## 🤝 Contributing

Want to contribute? Found a bug or have a feature request?  
Check out [issues](https://github.com/rohitpatil33/quirkle/issues) and submit a pull request.

***


## 👤 Author

**Your Name**  
📧 Email: rohitpatil8226@gmail.com


***

### If you want your readers to see your live AuctionVerse project:
**Just click here — [View Live Project](https://quirkle-bid-3.onrender.com/)**

***

