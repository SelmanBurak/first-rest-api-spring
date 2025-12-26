# Product Management REST API - Task 2 (CRUD)

This README covers **Task 2 (and final implementation)** of the project. It builds upon Task 1 by implementing a full Product Management System with CRUD operations (Create, Read, Update, Delete), Exception Handling, and an In-Memory Repository pattern.

## 🚀 Features

* **Create Product:** Add new products to the in-memory database.
* **Read Product:** Fetch product details using their ID.
* **Update Product:** Modify the name of an existing product.
* **Delete Product:** Remove a product from the system.
* **Exception Handling:** Returns proper **404 Not Found** errors if a product ID does not exist.
* **Storage:** Uses a `HashMap` implementation (In-Memory) inside the Repository class as per assignment requirements.
* **API Documentation:** Integrated with Swagger UI.

## 🛠 Technologies Used

* Java 17
* Spring Boot 3.2.5
* Spring Web (REST API)
* SpringDoc OpenAPI (Swagger UI)
* Maven

## ⚙️ How to Run

1.  Open the project in **IntelliJ IDEA**.
2.  Run the `FirstRestApiSpringApplication` class.
3.  The application will start on port `8080`.

## 📖 Swagger Documentation

You can test all endpoints (Task 2 operations) using the interactive Swagger UI:

👉 **[http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)**

## 🔌 API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/` | Task 1: Hello World check |
| **POST** | `/api/v1/products` | Create a new product |
| **GET** | `/api/v1/products/{id}` | Get a product by ID |
| **PUT** | `/api/v1/products/{id}` | Update a product by ID |
| **DELETE** | `/api/v1/products/{id}` | Delete a product by ID |

## 👨‍💻 Author

* **Student:** [Selman Burak Uygurturk]
* **Task:** #2 - Product CRUD Operations
