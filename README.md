# Spring Boot Machine Test – CRUD Application

This is a Java Spring Boot application for managing Categories and Products, developed as part of a machine test for the Java Developer position at Nimap Infotech.

## 🔗 Live Repo

[GitHub Repository](https://github.com/jishanmansuri/SPRING-BOOT-MACHINE-TEST)

---

## 🚀 Tech Stack

- Java 17
- Spring Boot
- Spring Data JPA
- H2 In-Memory Database
- Maven
- RESTful APIs
- Postman (for testing)

---

## ⚙️ How to Run

### Prerequisites

- Java 17+
- Maven
- IDE like IntelliJ IDEA or Eclipse

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/jishanmansuri/SPRING-BOOT-MACHINE-TEST.git
   cd SPRING-BOOT-MACHINE-TEST
Run the application:

bash
Copy
Edit
./mvnw spring-boot:run
or open the project in an IDE and run CrudAppApplication.java.

Access H2 Database Console:

URL: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb

User: sa | Password: (leave blank)

🧪 How I Tested
APIs tested via Postman

Verified:

Create, Read, Update, Delete operations for Category and Product

Pagination using query params (?page=0&size=5)

Relationships between Category and Product

🗃️ Database Design (H2)
Entities
Category
Field	Type	Constraints
id	Long	Primary Key
name	String	Unique, Not Null

Product
Field	Type	Constraints
id	Long	Primary Key
name	String	Not Null
price	Double	Not Null
category_id	Foreign Key	References Category

Relationship: One-to-Many (One Category has many Products)

📫 Contact
Jeeshan Mansuri
📞 7581910915
📧 jeeshanorme@gmail.com
