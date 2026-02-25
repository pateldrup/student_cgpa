# 📘 Backend Assignment 2
E-Commerce Product REST API (In-Memory)<br><br>
📌 Project Overview<br>

This project is a RESTful API built using Express.js that manages product listings for an e-commerce platform using an in-memory JSON database.<br><br>

The API supports GET, POST, and PUT operations and follows REST principles including proper route design and correct HTTP status codes.<br><br>

No external database is used — all data is stored in a local JSON array inside the project.<br><br>

🎯 Objective<br><br>

Build a REST API using Express.js<br>

Implement GET, POST, and PUT routes<br>

Use both static and dynamic routes<br>

Follow REST principles<br>

Return proper HTTP status codes<br>

Store data in an in-memory JSON array<br><br>

🛠 Tech Stack<br><br>

Node.js<br>
Express.js<br>
CORS<br>


JavaScript (ES6)<br><br>
📂 Implemented Routes<br><br>
🔹 GET Routes<br><br>

1️⃣ Get All Products<br>
GET /products<br>
Returns all product records.<br>
Status Code: 200 OK<br><br>

2️⃣ Get Product by ID (Dynamic Route)<br>
GET /products/:id<br>
Returns specific product details.<br>
If product not found → 404 Not Found<br><br>

3️⃣ Get Products by Category (Dynamic Route)<br>
GET /products/category/:categoryName<br>
Returns all products from the specified category (case-insensitive).<br>
Returns empty array if no products match.<br><br>

🔹 POST Route<br><br>

4️⃣ Add New Product<br>
POST /products<br>
Adds a new product to the system.<br>
ID is auto-generated.<br>
Status Code: 201 Created<br><br>

🔹 PUT Routes<br><br>

5️⃣ Replace Full Product<br>
PUT /products/:id<br>
Replaces entire product except ID.<br>
If product not found → 404 Not Found<br><br>

6️⃣ Update Product Stock<br>
PUT /products/stock/:id<br>
Updates only the stock field of a product.<br>
If product not found → 404 Not Found<br><br>

7️⃣ Update Product Price<br>
PUT /products/price/:id<br>
Updates only the price field of a product.<br>
If product not found → 404 Not Found<br><br>



🌍 Sample API URLs (After Deployment)<br><br>
https://your-render-link.onrender.com/products<br>
https://your-render-link.onrender.com/products/1<br>
https://your-render-link.onrender.com/products/category/Electronics<br>
https://your-render-link.onrender.com/products/stock/2<br>
https://your-render-link.onrender.com/products/price/3<br>
<br><br>


## 💻 Steps to Run Locally<br>

1️⃣ Clone the repository<br>
git clone https://github.com/your-username/ecommerce-product-api.git<br><br>

2️⃣ Navigate into the project folder<br>
cd ecommerce-product-api<br><br>

3️⃣ Install dependencies<br>
npm install<br><br>

4️⃣ Start the server<br>
npm start<br><br>

Server will run at:<br>
http://localhost:3000<br><br>


## 🚀 Deployment<br>

This project is deployed on **Render**.<br><br>

🔗 **Deployed Link**<br>
https://your-app-name.onrender.com<br><br>



## 📁 Project Structure<br>

ecommerce-product-api/
│
├── server.js # Main server file
├── package.json # Project configuration
├── package-lock.json
└── README.md # Project documentation



## 📡 HTTP Status Codes Used<br>

| Status Code   | Meaning                       |
| ------------- | ----------------------------- |
| 200 OK        | Request successful            |
| 201 Created   | Resource successfully created |
| 404 Not Found | Resource does not exist       |<br><br>


## 🧠 Key Concepts Implemented<br>

- RESTful API design<br>
- Static and Dynamic routes<br>
- Route parameters (req.params)<br>
- Request body handling (req.body)<br>
- Array methods (find, filter, findIndex)<br>
- Proper HTTP status codes<br>
- Middleware usage (express.json, cors)<br>
- In-memory data management<br><br>