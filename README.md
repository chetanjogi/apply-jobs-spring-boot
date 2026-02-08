# Apply Jobs – Spring Boot Job Portal

Apply Jobs is a simple Job Portal web application built using **Spring Boot**.  
It allows employers to post job openings and users to view and search available jobs.

This project is created for **learning purposes** and demonstrates a basic **MVC architecture** using Spring Boot.

---

## 🚀 Features

- Add new job postings  
- View all available jobs  
- Search and browse job listings  
- Layered architecture (Controller, Service, Repository)  
- In-memory data storage (no database)

---

## 🛠️ Tech Stack

- **Language:** Java  
- **Framework:** Spring Boot  
- **Web:** Spring MVC  
- **View:** JSP  
- **Build Tool:** Maven  

---

## 📂 Project Architecture

The application follows a layered MVC design:

```
Controller  →  Service  →  Repository
```

### Layers Explained

- **Controller:** Handles HTTP requests and responses  
- **Service:** Contains business logic  
- **Repository:** Manages job data (in-memory)  

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/chetanjogi/apply-jobs-spring-boot.git
   ```

2. Navigate to the project directory:
   ```bash
   cd apply-jobs-spring-boot
   ```

3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Open in browser:
   ```
   http://localhost:8080
   ```

---
## 🔗 Sample Endpoints

| Method | Endpoint        | Description                     |
|------|-----------------|---------------------------------|
| GET  | /               | Load home page                  |
| GET  | /home           | Load home page                  |
| GET  | /addjob         | Show add job form               |
| POST | /handleForm     | Submit new job posting          |
| GET  | /viewalljobs    | View all available job listings |

---

## 📌 Limitations

- No database integration (uses in-memory storage)
- No authentication or authorization
- Not production-ready (learning/demo project)

---

## 🔮 Future Enhancements

- Database integration (H2 / PostgreSQL)
- Spring Data JPA
- User authentication (Spring Security)
- Pagination and sorting
- REST API version
- Frontend using React or Angular

---

## 👨‍💻 Author

**Chetan Jogi**  
GitHub: https://github.com/chetanjogi
