# ReactJS-Spring-Boot-CRUD-Full-Stack-App

This is a full-stack CRUD application built with React.js for the frontend and Spring Boot for the backend.

## Getting Started

### Prerequisites

- Node.js (v16 or higher recommended)
- Java Development Kit (JDK 17 or higher)
- MySQL Server

### Installation

#### A. Configuration

```bash
git clone https://github.com/your-username/ReactJS-Spring-Boot-CRUD-Full-Stack-App.git
cd ReactJS-Spring-Boot-CRUD-Full-Stack-App


cd react-frontend
npm install
npm install react-scripts@latest


spring.datasource.url=jdbc:mysql://localhost:3306/employee_management_system?useSSL=false&allowPublicKeyRetrieval=true
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
spring.jpa.hibernate.ddl-auto=update


Running the Application

** Start the Backend**
./mvnw spring-boot:run

**Start the Frontend**
npm start


