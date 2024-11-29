# Flight App Project

The **Flight App** is a prototype airline management system developed as part of a database application and transaction management project. It features a command-line interface (CLI) connected to a live SQL Server database on Azure, enabling users to create accounts, log in, search for flights, book itineraries, and manage payments.

---

## Key Features

- **User Account Management**  
  - Secure account creation with salted password hashing.  
  - Unique usernames and login functionality using `PasswordUtils` for authentication.

- **Flight Search and Itinerary Management**  
  - Search functionality supporting both direct and indirect flights.  
  - Real-time flight availability and sorting by travel time.

- **Reservation and Payment System**  
  - Booking and payment processing for flight reservations.  
  - Comprehensive transaction management to ensure data consistency, especially under concurrent user access.

- **Transaction Handling**  
  - SQL transactions integrated to maintain ACID properties.  
  - Safeguards data integrity during operations like booking and payment by handling race conditions and preventing conflicts.

- **Database Schema Design**  
  - Created and maintained a relational database schema, including tables for users, flights, itineraries, and reservations.  
  - Utilized SQL and JDBC for database interaction.

- **Testing and Debugging**  
  - Developed extensive test cases to validate application functionality across multiple scenarios, including edge cases and concurrent user operations.

---

## Technologies Used

- **Programming Languages:** Java, SQL  
- **Database and SQL:** SQL Server, JDBC  
- **Cloud Platform:** Microsoft Azure  
- **Development Tools:** Visual Studio Code, Maven
