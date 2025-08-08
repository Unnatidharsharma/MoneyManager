# Money Manager

A full-stack Money Manager application built with Spring Boot (Java) for the backend and React (Vite) for the frontend.

---

## Features

- User registration with email activation
- JWT-based authentication
- Add, view, and manage transactions
- Responsive frontend with React
- MySQL database integration

---

## Prerequisites

- Java 17+ (JDK)
- Node.js (v16+ recommended)
- MySQL Server
- Maven

---

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/Unnatidharsharma/MoneyManager.git
cd "MoneyManager/money manager youtube"
```

---

### 2. Backend Setup

#### Configure Database

- Create a MySQL database named `moneymanager`.
- Update `src/main/resources/application.properties` with your MySQL username and password.

#### Start Backend

```sh
cd moneymanager
./mvnw spring-boot:run
```
or on Windows:
```sh
mvnw.cmd spring-boot:run
```

---

### 3. Frontend Setup

```sh
cd moneymanagerwebapp
npm install
npm run dev
```

The frontend will run at [http://localhost:5173](http://localhost:5173).

---

### 4. Usage

- Register a new account.
- Check your email for an activation link and activate your account.
- Log in and start managing your finances!

---

## Configuration

- **Backend:**  
  `money manager youtube/moneymanager/src/main/resources/application.properties`
- **Frontend:**  
  API endpoints are configured to use `http://localhost:8080/api/v1.0`

---

## License

This project is for educational purposes.
