### Title: **Car Rental Management System**

This Java program implements a **Car Rental Management System** that allows users to rent and return cars through a console-based menu interface. The system is designed with three main entities: `Car`, `Customer`, and `Rental`. The `Car` class represents vehicles with attributes like ID, brand, model, price per day, and availability status. The `Customer` class captures customer details such as ID and name. The `Rental` class links a car to a customer along with the number of rental days.

The core functionality is managed by the `CarRentalSystem` class, which maintains lists of cars, customers, and active rentals. Users can rent a car by providing their name, selecting an available car from the list, and specifying the rental duration. The system calculates the total rental cost and confirms the booking after user approval. Cars can be returned by providing the car ID, and the system ensures proper handling of availability status and rental record updates.

The `menu` method provides an interactive interface with options to rent a car, return a car, or exit the system. It uses a `Scanner` for user input and validates actions such as car selection and rental duration. The `main` method initializes the system with predefined cars and starts the menu loop, making this a user-friendly solution for car rental management.
