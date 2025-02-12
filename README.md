# Final project for Java programming

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
Regarding the technology stack of this project, we will introduce the technologies and frameworks used in the User Layer , Gateway Layer , Application Layer , and Data Layer . This section primarily showcases the technical frameworks and middleware employed in the project.

### 2.1 User Layer
In building the front-end pages for the system management backend, we will utilize technologies such as HTML5 (H5) , Vue.js , ElementUI , and Apache ECharts (for displaying charts). For the mobile application, we will use WeChat Mini Programs .

### 2.2 Gateway Layer
Nginx is a server that primarily serves as an HTTP server, used to deploy static resources with high performance. Nginx also plays two crucial roles: reverse proxy and load balancing . During project deployment, if we need to achieve load balancing for Tomcat, it can be easily implemented through Nginx.

### 2.3 Application Layer
Spring Boot : A framework for quickly building Spring projects, adopting the "convention over configuration" philosophy to simplify the configuration and development of Spring projects.
Spring MVC : A module of the Spring framework, Spring MVC seamlessly integrates with Spring without requiring intermediate integration layers.
Spring Task : A scheduling framework provided by Spring for handling scheduled tasks.
HttpClient : Primarily used for sending HTTP requests.
Spring Cache : A data caching framework provided by Spring.
JWT (JSON Web Token) : A token-based authentication mechanism used to authenticate users on the application.
Aliyun OSS (Object Storage Service) : Used for storing files such as images in the project.
Swagger : Automatically generates API documentation for developers and allows for API testing.
POI : A library that encapsulates common operations for Excel spreadsheets.
WebSocket : A communication protocol that simplifies data exchange between clients and servers, used in this project for order notifications and order reminders.

### 2.4 Data Layer
MySQL : A relational database, which will be used to store the core business data of this project.
Redis : An in-memory database that stores data in key-value format, known for its fast access speed and commonly used for caching.
MyBatis : The persistence layer of this project will be developed using MyBatis.
PageHelper : A pagination plugin.
Spring Data Redis : Simplifies Java code operations for Redis by providing convenient APIs.

### 2.5 Tools
Git : A version control tool used to manage project code in team collaboration.
Maven : A project build tool.
JUnit : A unit testing tool. After developers complete feature implementation, they use JUnit to perform unit tests on the functionality.
Postman : An API testing tool that simulates various HTTP requests initiated by users and retrieves corresponding response results.
