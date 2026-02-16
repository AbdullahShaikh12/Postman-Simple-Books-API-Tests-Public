# Postman-Simple-Books-API-Tests-Public


## 📂 Project Overview

This project contains API test scenarios created in Postman for the Simple Books API.  
It covers complete request validation, environment handling, and end-to-end order workflow testing.

---

## 🔎 Test Coverage

The collection includes test cases for:

- Checking API availability
- Registering a new API client
- Fetching books (with filters)
- Retrieving book details by ID
- Creating book orders
- Viewing, updating, and deleting orders

Each request includes proper validations and response checks.

---

## 🧪 Implemented Features

- Postman test scripts written in JavaScript
- Use of environment variables:
  - `baseURL`
  - `accessToken`
  - `bookID`
  - `orderID`
- Assertions for:
  - HTTP status codes
  - Response body validation
  - Data integrity checks

---

## 🛠️ Tools & Technologies

- Postman (API Testing)
- JavaScript (for test validations)
- Environment Variables
- Optional documentation using Excel / Markdown

---

## 🚀 How to Execute

1. Download or clone this repository.
2. Import the `API Course.postman_collection.json` file into Postman.
3. Configure the environment variable:
   ```
   baseURL = https://simple-books-api.glitch.me
   ```
4. Register a new client to generate an `accessToken`.
5. Add the generated `accessToken` to the environment variables.
6. Execute requests individually or run the entire collection.

---

## 📋 Sample Test Scenarios

| No. | API Action | Method | Purpose |
|-----|------------|--------|----------|
| 1 | API Health Check | GET | Verify API availability |
| 2 | Client Registration | POST | Create new API user |
| 3 | Fetch Books | GET | Retrieve books by category |
| 4 | Get Book Details | GET | View specific book info |
| 5 | Create Order | POST | Submit new book order |
| 6 | View Orders | GET | Retrieve all orders |
| 7 | Order Details | GET | Fetch single order |
| 8 | Modify Order | PATCH | Update order information |
| 9 | Remove Order | DELETE | Delete an existing order |

---

## 🎯 Key Learnings

- Understanding REST API workflows
- Writing effective test assertions in Postman
- Managing authentication tokens
- Chaining requests using variables
- Performing positive and negative test scenarios
- Simulating real-world API testing process

