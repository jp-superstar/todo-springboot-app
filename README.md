# 📅 Todo Spring Boot Application

This is a simple **Todo List application** built using **Spring Boot**, **Thymeleaf**, and **Bootstrap**. It allows users to add, mark as complete/incomplete, and delete tasks from a list.

---

## ✨ Features

- Add a new task
- Mark a task as completed or undo it
- Delete a task
- Strike-through styling for completed tasks using Bootstrap

---

## 📊 Tech Stack

- **Java 17**
- **Spring Boot 3.4.4**
- **Spring MVC & Spring Data JPA**
- **Thymeleaf** for server-side templating
- **Bootstrap 5** for styling
- **MySQL** (runtime scope)
- **Lombok** (for boilerplate code elimination)

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/jp-superstar/todo-springboot-app.git
cd todo-springboot-app
```

### 2. Build the project

```bash
./mvnw clean install
```

### 3. Run the application

```bash
./mvnw spring-boot:run
```

> App will run at `http://localhost:8080/tasks`

---

## 🔧 Git Commands Explained

### Initialize the Git repository:

```bash
git init
```

### Add files:

```bash
git add .
```

### Commit changes:

```bash
git commit -m "Initial commit"
```

### Add GitHub remote:

```bash
git remote add origin https://github.com/jp-superstar/todo-springboot-app.git
```

> If using SSH instead:

```bash
git remote set-url origin git@github.com:jp-superstar/todo-springboot-app.git
```

### Rename default branch to main:

```bash
git branch -M main
```

### Push to GitHub:

```bash
git push -u origin main
```

> `-u` sets upstream so next time you can just do `git push`

---

## 📁 Folder Structure

```
src/
 ├── main/
 │   ├── java/com/app/TODOApp/
 │   │   ├── controller/
 │   │   ├── models/
 │   │   ├── repository/
 │   │   └── services/
 │   └── resources/templates/
 └── test/
```

---

## 🚀 Future Enhancements

- Task due dates
- Priority levels
- Persisting user data with login
- REST API integration

---

## 🌟 Screenshot



---

## ✉️ License

MIT

---

> Made with ❤️ by jyotiprakash

