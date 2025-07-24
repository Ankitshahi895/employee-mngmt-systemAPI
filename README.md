# 🧑‍💼 Employee Management System (EMS)

A simple **CRUD-based REST API** built with **Spring Boot** and **MySQL** to manage employee records.

---

## 📌 Features

- Add new employees
- Get list of all employees
- Update employee details
- Delete employee record
- Connected to MySQL database
- Tested with Postman

---

## ⚙️ Technologies Used

- Java 17+
- Spring Boot 3.5.4
- Spring Data JPA
- MySQL
- Maven
- Postman (for testing)

---

## 🚀 API Endpoints

| Method | Endpoint        | Description             |
|--------|------------------|-------------------------|
| GET    | `/employees`     | Get all employees       |
| POST   | `/employees`     | Add a new employee      |
| PUT    | `/employees/{id}`| Update an employee      |
| DELETE | `/employees/{id}`| Delete an employee      |

### ✅ Sample JSON for POST/PUT:

```json
{
  "name": "Ankit",
  "role": "Developer",
  "department": "IT"
}
