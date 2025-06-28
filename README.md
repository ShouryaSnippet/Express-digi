# 🫖 Express-digi

A simple RESTful API built using **Node.js** and **Express.js** that lets you manage a list of teas. You can create, read, update, and delete tea entries in memory (no database yet). This project is designed to practice core backend skills like routing, middleware, HTTP methods, and CRUD operations.

---

## 🚀 Features

- `POST /teas` – Add a new tea
- `GET /teas` – Get all teas
- `GET /teas/:id` – Get a tea by ID
- `PUT /teas/:id` – Update a tea by ID
- `DELETE /teas/:id` – Delete a tea by ID

---

## 📦 Tech Stack

- Node.js
- Express.js
- Postman (for testing)
- VS Code

---

## 🛠️ How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/ShouryaSnippet/Express-digi.git
   cd Express-digi
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the server
   ```bash
   node index.js
   ```

4. Use Postman or curl to test:
   - URL: `http://localhost:3000/teas`

---

## 🧪 Example POST Request

```http
POST /teas
Content-Type: application/json

{
  "name": "Ginger Tea",
  "price": 100
}
```

---

## 📂 Folder Structure
```
Express-digi/
├── index.js
├── package.json
├── .gitignore
└── README.md
```

---

## 📌 Future Improvements
- Add MongoDB + Mongoose
- Add user authentication with JWT
- Add unit tests using Jest or Supertest
- Deploy to Render or Railway

---

## 🧑‍💻 Author

Made with  by [Shourya](https://github.com/ShouryaSnippet)
