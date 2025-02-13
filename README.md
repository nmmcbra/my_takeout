# Course project for Java programming

## 1.Project Introduction
This project is a customized software product designed for catering enterprises (restaurants, eateries), consisting of two parts: System Management Backend and Mini Program Application . The system management backend is primarily used by internal staff of the catering enterprise, allowing them to manage and maintain restaurant categories, dishes, meal sets, orders, employees, and other operational data. It also provides statistical analysis of various restaurant data and includes features like voice notifications for incoming orders. The mini program application is mainly for consumers, enabling them to browse dishes online, add items to their shopping cart, place orders, make payments, and request order reminders.

### 1.1 Management End Functions
Employee login/logout
Employee information management
Category management
Dish management
Meal set management
Dish flavor management
Order management
Data statistics
Incoming order notifications
### 1.2 User End Functions
WeChat login
Recipient address management
User historical order inquiry
Dish specification inquiry
Shopping cart functionality
Placing orders
Payment
Browsing categories and dishes



## 2.Technology Stack

This project is built using a modern and scalable technology stack, organized into four key layers: **User Layer** , **Gateway Layer** , **Application Layer** , and **Data Layer** . 

### 2.1 User Layer

The front-end interface leverages cutting-edge web technologies for both desktop and mobile platforms:

- **Web** : HTML5, Vue.js, ElementUI, and Apache ECharts (for data visualization).
- **Mobile** : WeChat Mini Programs for lightweight, cross-platform mobile applications.

### 2.2 Gateway Layer

- **Nginx** : Serves as an HTTP server for static resource deployment, reverse proxy, and load balancing.
- **Load Balancing** : Nginx seamlessly integrates with Tomcat to distribute traffic efficiently.

### 2.3 Application Layer

The application layer is powered by a combination of Spring-based frameworks and other essential tools:

- **Spring Ecosystem** : Spring Boot (rapid development), Spring MVC (web integration), Spring Task (scheduling), Spring Cache (caching), and Spring Data Redis (Redis operations).
- **Authentication & APIs** : JWT for token-based authentication, Swagger for API documentation and testing.
- **Utilities** : HttpClient for HTTP requests, POI for Excel operations, WebSocket for real-time notifications, and Aliyun OSS for file storage.

### 2.4 Data Layer

- **Database** : MySQL (relational database for core business data), Redis (in-memory caching for high-speed access).
- **Persistence** : MyBatis for ORM, PageHelper for pagination, and Spring Data Redis for streamlined Redis interactions.

### 2.5 Tools

Development and testing are supported by industry-standard tools:

- **Version Control** : Git for collaborative code management.
- **Build & Testing** : Maven for project builds, JUnit for unit testing, and Postman for API testing.
