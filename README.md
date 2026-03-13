# Express Instagram Profile Viewer 📸

A simple backend project built using **Node.js**, **Express.js**, and **EJS** that dynamically renders Instagram-like profile pages using data stored in a JSON file.

This project demonstrates basic backend concepts such as routing, dynamic parameters, template rendering, and serving static files.

---

## 🚀 Features

- Dynamic routing using `/ig/:username`
- Profile data loaded from a JSON file
- Instagram-style profile page rendering
- Multiple posts displayed dynamically
- Error page for invalid usernames
- Reusable EJS partials (header & footer)
- Static CSS styling using Express

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- EJS (Embedded JavaScript Templates)
- HTML
- CSS

---

## 📂 Project Structure

```
express-instagram-profile-viewer
│
├── public
│   └── style.css
│
├── views
│   ├── includes
│   │   ├── head.ejs
│   │   └── footer.ejs
│   │
│   ├── home.ejs
│   ├── instagram.ejs
│   ├── error.ejs
│   └── rolldice.ejs
│
├── data.json
├── index.js
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

1. Clone the repository

```
git clone https://github.com/Siddhartha03112004/express-instagram-profile-viewer.git
```

2. Move into the project folder

```
cd express-instagram-profile-viewer
```

3. Install dependencies

```
npm install
```

4. Start the server

```
node index.js
```

---

## 🌐 Usage

Open your browser and visit:

```
http://localhost:8080
```

To view a profile page:

```
http://localhost:8080/ig/username
```

Example:

```
http://localhost:8080/ig/siddhartha
```

If the username does not exist in the JSON file, the application will render an error page.

---

## 🎯 Learning Purpose

This project was built to practice:

- Express server setup
- Dynamic routing
- EJS template rendering
- JSON data handling
- Static file serving

---

## 👨‍💻 Author

**Siddhartha Singh**
B.Tech ECE – USICT, GGSIPU
