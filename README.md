# REST API for Online Hotel Booking Application - StayWell

## Overview
A Spring Boot REST API web service for an online hotel booking application, developed using Core Java and the Spring Framework. The application utilizes a MySQL database for data storage and CRUD operations. The team consists of five members. This service enables customers to browse and book hotels and provides management functionalities for inventory and customer orders. The API includes endpoints for hotel and reservation management, user authentication, and more. The project is open-source and hosted on GitHub.

---

## Tech Stack and Tools
- Core Java
- Spring Framework
- Spring Boot
- Spring Data JPA
- Spring Validation
- Hibernate
- MySQL
- Lombok
- JUnit
- Swagger-UI
- ER-Diagram

---

## Modules
1. **Login & Logout Module**
2. **Admin Module**
3. **Customer Module**
4. **Hotel Module**
5. **Room Module**
6. **Reservation Module**

---

## Features

### Admin Features
Admin can perform the following operations:
- Add hotel/room
- Delete hotel/room
- View all hotels/rooms

### Customer Features
Customers can perform the following operations:
- Register
- Login
- Delete account
- Search for hotels/rooms
- View hotel/room details
- Make a reservation

### Hotel Features
Hotels can perform the following operations:
- Register
- Login
- Delete account
- Display hotel amenities
- Showcase room types and descriptions
- Provide hotel location information
- Display hotel ratings and reviews
- Showcase hotel photos and virtual tours
- Offer special promotions and discounts

---

## Installation & Run

To run this API server:
1. Update the database configuration inside the `application.properties` file located in the `src/main/resources` folder.
   ```properties
   server.port=8808 
   spring.datasource.url=jdbc:mysql://localhost:3306/StayWell 
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver 
   spring.datasource.username=your_username_here 
   spring.datasource.password=your_password_here
   ```

2. Build and run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

3. Access the API endpoints:
   - Root Endpoint: `https://localhost:8808/`
   - Swagger UI: `https://localhost:8808/swagger-ui/index.html`

---

## created by
@Kishor Darkunde
