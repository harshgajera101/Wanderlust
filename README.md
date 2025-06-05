# 🏠 Wanderlust — Explore Unique Stays Around the World

A full-stack web application inspired by **Airbnb**, where users can **discover, list, and review** accommodations like hotels, villas, apartments, and more from around the globe. Built using the **MERN stack principles** with cloud integrations and responsive design for a seamless user experience.

---

## ✨ Features

### 🔍 Discover & Explore

* Browse curated listings with details like pricing, location, and photos
* View properties on interactive **Mapbox** maps
* Search for listings based on user preferences

### 🏘️ Listing Management

* Authenticated users can **create, edit, and delete** listings
* Upload property images via **Cloudinary**
* Secure ownership-based controls

### ✍️ Review System

* Leave reviews and ratings for properties
* Edit or delete your own reviews
* View aggregated feedback from other travelers

### 🔐 Authentication & Access

* User **registration & login** via Passport.js
* Session management with secure cookies
* Role-based **authorization for protected actions**

<!-- ### 📱 User Experience

* **Mobile-responsive design**
* Flash messages for feedback
* Protected routes and error handling -->

---

## ⚙️ Tech Stack

### 💻 Frontend

* HTML5, CSS3, JavaScript
* **EJS** Templating for dynamic views

### 🌐 Backend

* Node.js + Express.js
* MongoDB (via Mongoose)

### 🔒 Auth & Security

* Passport.js + bcrypt
* Express-session & connect-flash
* Input validation via express-validator

### ☁️ Cloud & APIs

* **MongoDB Atlas** — Cloud database
* **Cloudinary** — Image hosting & optimization
* **Mapbox API** — Maps & geolocation
* **Render** — Deployment platform

---

## 🚀 Live Demo

🔗 [Check Out the Live App](https://wanderlust-4w7p.onrender.com/listings)

---

## 🛠️ Getting Started

### 📋 Prerequisites

Ensure you have the following:


* 🟢 **Node.js** (v14+)
* 📦 **npm**
* 🛢️ **MongoDB** (or 🌩️ **MongoDB Atlas**)
* 🧬 **Git**


### ⚙️ Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/wanderlust.git
   cd Wanderlust
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Configure Environment**
   Create a `.env` file:

   ```env
   MONGODB_URL=your_mongo_url        # Local MongoDB connection string
   ATLASDB_URL=your_atlas_url        # MongoDB Atlas cloud database URL
   
   CLOUD_NAME=your_cloud_name        # Cloudinary - your cloud name
   CLOUD_API_KEY=your_api_key        # Cloudinary - API key
   CLOUD_API_SECRET=your_api_secret  # Cloudinary - API secret
   
   MAP_TOKEN=your_mapbox_token       # Mapbox - access token for interactive maps
   SECRET=your_secret_key            # Express-session - secret key for session management
   ```

4. **Run the App**

   ```bash
   node app.js       # or nodemon app.js (with nodemon)
   ```

Visit: `http://localhost:3000`

---

## 🗂️ Project Structure

```
wanderlust/
├── controllers/
├── init/
├── models/
├── node_modules/
├── routes/
├── views/
├── public/
├── utils/
├── app.js
├── middleware.js
├── cloudConfig.js
├── schema.js
├── package.json
├── .gitignore
├── README.md
└── .env
```

---

<!-- ## 🛡️ Security Highlights

* Encrypted passwords with bcrypt
* Role-based access control
* Input validation
* Session timeout and CSRF protection
* Route protection and error handling

--- -->

## 🔮 Future Enhancements


* 🧲 **Advanced Search Filters** (💰 price, 🛏️ amenities)
* 📅 **Booking System** with Calendar Integration
* 💳 **Payment Gateway** Integration
* 📧 **Email Notifications**
* 🛠️ **Admin Dashboard**
* 📱 **PWA / Mobile App**
* 🌐 **Multi-Language Support**


---

## 🙌 Contribution Guidelines

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit: `git commit -m 'Add AmazingFeature'`
4. Push: `git push origin feature/AmazingFeature`
5. Open a pull request

---

## 🐞 Known Issues


* 🐢 **Image uploads** may be slow on the free **Cloudinary** tier
* 🌐 **Maps** may not load properly on unstable internet connections


---

## 💡 Acknowledgments

* [Express.js](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/)
* [Cloudinary](https://cloudinary.com/)
* [Mapbox](https://mapbox.com/)
* [Bootstrap](https://getbootstrap.com/)


---

## 👨‍💻 Author

**Harsh Gajera**
- GitHub: [@harshgajera101](https://github.com/harshgajera101)
- LinkedIn: [Harsh Gajera](https://linkedin.com/in/gajera-harsh)


---


## 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

