# 🌐 Express.js Basics

Express is a **popular web application framework** for Node.js.  
It simplifies the process of building web applications by providing a robust set of features for web and mobile apps.

---

## 🧵 Thread

- Can do one thing at a time (single-threaded).

---

## 🌍 HTTP

- **HTTP** stands for *HyperText Transfer Protocol*.

---

## 🖥️ HTTP Server

- A place where your logic is exposed and requests are handled.

---

## ⚙️ Express (Framework)

- Express helps **create an HTTP server**.
- It is a **framework**, not just a Node.js library.

---

## 🔌 Port

- A machine can run **multiple HTTP servers** using **unique ports**.
- Example: `localhost:3000`

---

## 🔁 Request & Response Cycle

- You → **request** → server (single-threaded, one task at a time)  
- Server → **response** → you (same threading model)

---

## 📡 Sending Requests

- URL format: `localhost:3000/?key=value`
- **Query parameters** come after the `?`.
- Note: Always send **values as strings**, not numbers (to avoid status code conflicts).

---

## 📥 Installing Express

```bash
npm install express
````

---

## 🧱 Boilerplate Code

```js
const express = require("express");
const app = express();

app.get("/", function (req, res) {
  // your logic here
  res.send("Hello World!");
});

app.listen(3000);
```

---

## ❗ Error: "Cannot GET /"

* The route is not defined or the server is not ready.
* This means Express doesn't know how to handle the requested route.

---

## 📍 Routes

* `/` is a **route**.
* It listens for requests and responds accordingly.

---

## 🧾 Two Ways of Input

1. **Query Parameters**

   * Sent in URL after `?`
   * Example: `/search?term=book`
   * Key-value pairs.

2. **Request Body**

   * Sent in the **body** of the request.
   * Common in `POST` or `PUT` requests.
   * Supports JSON, form data, etc.

---

## 📬 HTTP Request Methods

* **GET** – Read / Fetch data
* **POST** – Insert new data
* **PUT** – Replace/update data
* **DELETE** – Remove data

---

## 🧾 Common HTTP Status Codes

| Code | Meaning                    |
| ---- | -------------------------- |
| 200  | OK / Successful            |
| 404  | Not Found                  |
| 505  | Server Error               |
| 414  | URI Too Long / Input Error |
| 403  | Forbidden / Not Allowed    |

---

## 🧪 Postman

* Postman is a tool to **test HTTP APIs**.
* You can test GET, POST, PUT, DELETE requests.
* Allows debugging by inspecting request and response.

---

## 🧾 res.json({})

* Use `res.json({})` to send a JSON response.
* Prevents the program from **hanging** or failing silently.

---



