# 🚀 Java Task Manager API

Professional Backend implementation focusing on **RESTful API standards**, **Clean Architecture**, and **Robust Error Handling**.

### 🛠 Technology Stack
* **Language:** Java 17
* **Framework:** Spring Boot 3.3.0
* **Database:** MySQL
* **ORM:** Spring Data JPA / Hibernate
* **Documentation:** Swagger UI / OpenAPI 3.0
* **Tools:** Maven, Postman, Lombok

### ✨ Key Features
* **Full CRUD Operations:** Seamless management of tasks (Create, Read, Update, Delete).
* **Global Exception Handling:** Centralized logic to handle errors (like 404 Not Found) gracefully, ensuring a professional API response.
* **Data Validation:** Implemented `@Valid` and `@NotBlank` to ensure data integrity at the entry point.
* **Layered Architecture:** Clear separation of concerns using Controller, Service, and Repository layers.
* **API Documentation:** Integrated Swagger UI for real-time API testing and documentation.

### 🛣 API Endpoints
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **POST** | `/api/tasks` | Create a new task |
| **GET** | `/api/tasks` | Retrieve all tasks |
| **GET** | `/api/tasks/{id}` | Get task by specific ID |
| **PUT** | `/api/tasks/{id}` | Update existing task details |
| **DELETE** | `/api/tasks/{id}` | Remove a task from DB |

### 🚦 How to Run
1. Clone the repository.
2. Update `application.properties` with your MySQL credentials.
3. Run `mvn spring-boot:run`.
4. Access Swagger UI at: `http://localhost:8080/swagger-ui/index.html`
