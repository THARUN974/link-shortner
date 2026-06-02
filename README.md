🔗 Link Shortener

📌 Overview

Link Shortener is a web application that converts long URLs into short, shareable links. Users can generate shortened URLs, access the original website through redirection, and view basic analytics such as click counts.

This project is built using Node.js, Express.js, MongoDB, and JavaScript.

---

✨ Features

- Create short URLs from long links
- Automatic redirection to original URLs
- Unique short code generation
- Click tracking and analytics
- MongoDB database integration
- RESTful API architecture
- Responsive and user-friendly interface

---

🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JavaScript
- HTML
- CSS

---

📂 Project Structure

link-shortener/

├── config/

│   └── db.js

├── controllers/

│   └── urlController.js

├── models/

│   └── Url.js

├── routes/

│   └── urlRoutes.js

├── public/

│   ├── index.html

│   ├── style.css

│   └── script.js

├── .env

├── package.json

├── server.js

└── README.md

---

🚀 Installation

1. Clone Repository

git clone https://github.com/yourusername/link-shortener.git
cd link-shortener

2. Install Dependencies

npm install

3. Configure Environment Variables

Create a ".env" file and add:

MONGO_URI=your_mongodb_connection_string
PORT=5000

4. Start Application

npm run dev

or

npm start

---

📊 API Endpoints

Create Short URL

POST /shorten

Redirect to Original URL

GET /:shortCode

View Analytics

GET /analytics/:shortCode

---

🎯 Future Enhancements

- User Authentication
- Custom Short URLs
- QR Code Generation
- Expiration Dates for Links
- Dashboard Analytics
- URL Management Panel

---

👨‍💻 Author

Tharun Raju

---

📄 License

This project is developed for educational and internship submission purposes.
