The Airline Booking System is designed to facilitate the management of flight reservations, passenger information, and airline operations through a robust and scalable architecture. This system will incorporate key software engineering principles, including object-oriented design, inheritance, interfaces, and polymorphism, ensuring flexibility and maintainability.

Class Structure

The system will be built around several core classes, including:

User: This abstract class will serve as the base for different user types, such as passengers and airline staff. It will include attributes like username, password, and methods for user authentication and management.
Passenger: Inherits from User, representing individuals who book flights. It will contain attributes such as passportNumber, email, and a list of Bookings. Methods will include booking a flight, canceling a reservation, and viewing booking history.
Staff: Also inherits from User, this class represents airline employees responsible for managing bookings and customer service. It will include methods for adding flights, managing reservations, and generating reports.
Flight: Represents a flight and contains attributes like flightNumber, departure, destination, seatsAvailable, and price. Methods will manage seat availability and pricing.
Booking: This class captures the details of a reservation, including the passenger, flight, booking date, and status. It allows the modification and cancellation of bookings.
Airline: This class acts as a central hub for managing flights and bookings. It will utilize Java Collections, such as ArrayList for storing flights and bookings, enabling efficient access and management.
Exceptions: Custom exception classes (e.g., BookingException, UserNotFoundException) will be implemented to handle specific error scenarios, ensuring robust error management throughout the system.
Design Considerations

The system will leverage Java’s Collections API to manage dynamic data structures effectively. For instance, ArrayList will store lists of flights and bookings, while HashMap can be utilized to map user credentials for efficient lookup.

The program will be developed without a graphical user interface for initial testing, focusing instead on a console-based interaction model. This will allow for straightforward verification of class interactions and functionality.

User Interface

Once the core functionalities are validated, a GUI will be implemented to enhance user experience. This interface will allow users to access functionalities such as flight search, booking management, and account settings seamlessly. Users will be able to log in, view available flights, make bookings, and manage their profiles through an intuitive layout.

Data Management

The system will implement file-based data persistence, enabling saving and loading of essential information. Sample files will include:

Log-in Info: Store user credentials securely.
User Info: Keep track of user details and preferences.
Bookings: Maintain a record of all reservations, including flight details and passenger information.
Each team member will contribute to at least one of these files, ensuring collaborative development.

Error Handling

Robust error handling will be a key component of the system, utilizing Java's exception handling mechanisms. User-defined exceptions will provide meaningful feedback to users, such as when a booking is attempted for a non-existent flight or when authentication fails. This ensures a smooth user experience and helps to maintain system integrity.

Overall, the Airline Booking System is designed to be a comprehensive solution for managing flight reservations, incorporating key software development principles and modern programming practices to create a reliable and user-friendly application.
