# Template Engine EJS Web Application

A server-side rendered web application built with **Node.js**, **Express.js**, **EJS (Embedded JavaScript)**, and **MongoDB** using the **MVC** architecture.

## Live Deployment (Render)
* **Live Website:** https://template-engine-ejs-app-l95n.onrender.com/
*(Note: The Render free-tier server may take 30–50 seconds to wake up on the first visit after inactivity.)*

## Tech Stack
* **Backend:** Node.js, Express.js
* **Template Engine:** EJS
* **Database:** MongoDB Atlas & Mongoose
* **Hosting:** Render

## Project Structure
```text
template-engine-ejs-app/
├── config/
├── controllers/
├── models/
├── views/
├── .gitignore
├── package.json
└── server.js
```

## Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd template-engine-ejs-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   Create a `.env` file in the root folder and add:
   ```env
   PORT=3000
   MONGO_URI=your_mongodb_connection_string
   DB_NAME=ejsAppDB
   ```

4. **Start the server:**
   ```bash
   npm start
   ```
   Open `http://localhost:3000` in your browser.
