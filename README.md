# Car Rental System
<h1>Overview</h1>
The Car Rental System is a Java-based application designed to manage car rentals efficiently. This project implements core functionalities such as adding cars and customers, renting and returning cars, and calculating rental costs. The system provides a simple, interactive console-based user interface for managing the rental process.

<h1>Features</h1>
<h2>Car Management:</h2> Add and manage a fleet of cars with unique IDs, brands, models, and rental prices.
<h2>Customer Management:</h2> Register customers and maintain customer records.
<h2>Rental Management:</h2> Rent out available cars to customers, track rental periods, and calculate total rental costs.
<h2>Return Handling:</h2> Process car returns and update car availability status.
<h2>Interactive Menu:</h2> User-friendly console menu for navigating through rental operations.
<h1>Classes and Their Responsibilities</h1>
<h2>Car:</h2> Represents a car with attributes such as ID, brand, model, rental price, and availability status. Methods to calculate rental price, rent, and return the car.
<h2>Customer:</h2> Represents a customer with attributes like customer ID and name.
<h2>Rental:</h2> Represents a rental transaction, associating a car, a customer, and the rental duration.
<h2>CarRentalSystem:</h2> Manages the overall system, including the list of cars, customers, and rentals. Contains methods to add cars and customers, process rentals and returns, and handle user interactions via the console menu.
<h1>How to Run</h1
<h2>Clone the repositpory:</h2>



git clone https://github.com/yourusername/CarRentalSystem.git
cd CarRentalSystem
<h2>Compile the project:


javac Car_Rental_System.java
<h2>Run the application:</h2>


java Car_Rental_System
<h1>Usage</h1>
<h2>Follow the on-screen instructions to:</h2>

Rent a car by selecting an available car and specifying the rental duration.
Return a car by providing the car ID.
The application will handle availability checks, cost calculations, and record-keeping automatically.

<h1>Future Enhancements</h1>
Implement a graphical user interface (GUI) for better user experience.
Add persistent storage (e.g., database integration) to save and retrieve data across sessions.
Include additional features such as customer authentication, detailed rental history, and more flexible pricing models.
<h1>Contributing</h1>
Contributions are welcome! Please fork the repository and submit pull requests for any improvements or new features.
