# StayNest (MVP)

StayNest is a web application for listing and reviewing accommodations, inspired by Airbnb.  
This MVP focuses on **user authentication** and **listing creation/viewing**, which represent the core value proposition of the platform.

---

## 🚀 Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (via Mongoose)  
- **Templating Engine:** EJS  
- **Authentication:** Passport.js (passport-local, passport-local-mongoose)  
- **Middleware:** express-session, connect-flash, method-override  
- **Frontend:** HTML, CSS, JavaScript  

---

## 🏗️ Architecture
The app follows an **MVC (Model-View-Controller)** pattern:
- **Models:** Define schema for `User` and `Listing`.
- **Views:** EJS templates for rendering UI.
- **Controllers:** Route files (`listings.js`, `user.js`) manage requests, interact with models, and render views.

---

## ✨ Key Features (MVP)
- ✅ User Authentication (Signup, Login, Logout)  
- ✅ Create Listings (title, description, price, location)  
- ✅ View Listings (all listings + individual detail page)  
- ✅ Session Management with Flash Messages  

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Ananya17032004/StayNest.git
cd StayNest
