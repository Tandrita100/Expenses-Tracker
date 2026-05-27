# Expense Tracker REST API

A backend RESTful CRUD application developed using Spring Boot, Spring Data JPA, Hibernate, and MySQL for managing expense records.

## Features

- Add new expenses
- Get all expenses
- Get expense by ID
- Update expense amount
- Delete expense
- REST API based backend application
- MySQL database integration using JPA/Hibernate

---

## Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Postman
- Git & GitHub

---

## Project Structure

```expense-tracker
│
├── controller
│ └── ExpenseController
│
├── entity
│ └── Expense
│
├── repository
│ └── ExpenseRepository
│
├── ExpenseTrackerApplication
│
└── application.properties
```

---

## Expense Entity Fields

| Field | Type |
|------|------|
| id | Long |
| item | String |
| amount | Double |
| category | String |
| date | LocalDate |

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /expenses | Add expense |
| GET | /expenses | Get all expenses |
| GET | /expenses/{id} | Get expense by ID |
| PUT | /expenses/{id} | Update expense amount |
| DELETE | /expenses/{id} | Delete expense |

---

## Sample JSON Request

```json
{
  "item": "Pizza",
  "amount": 350,
  "category": "Food",
  "date": "2026-02-12"
}
```

---

## Key Concepts Practiced

- RESTful API development
- CRUD operations
- Spring Boot fundamentals
- Spring Data JPA
- Hibernate ORM
- Entity mapping
- Dependency Injection
- JSON request handling
- MySQL database connectivity

---

## API Testing

All APIs were tested using Postman.

---

## Learning Outcome

This project helped in understanding:
- Difference between JDBC and JPA
- ORM-based database interaction
- Entity and repository layers
- REST controller implementation
- Automatic SQL generation using Hibernate
