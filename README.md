This project is a full-stack web application developed using Java 17 and the Spring Boot
framework. The frontend is built using Thymeleaf templates integrated with HTML5, CSS3,
JavaScript, and Bootstrap 5. The backend handles user management, security, and business logic
through a layered architecture involving controllers, services, and repositories.
Key modules of the system include:
• A public-facing homepage with information on courses and contact details.
• User registration and login system with hashed password storage.
• A personalized user dashboard with task-related components.
• An inquiry system for collecting user interest and feedback.
• An admin dashboard with full CRUD capabilities for managing students, centres, courses,
events, and testimonials.
Security mechanisms such as password hashing (using BCrypt), CSRF protection, and CORS
configuration are implemented to ensure secure operation. The system is packaged using Maven
and can be deployed either locally or to a cloud environment.
