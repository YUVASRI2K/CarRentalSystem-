##🚗 Car Rental System
A console-based Java application that allows users to rent and return cars efficiently. The system provides an easy-to-use menu interface to view available cars, rent cars for a specified period, and return them. It tracks car availability, rental transactions, and customer details.

🎯 Features
View Available Cars: Displays the list of cars available for rent.
Rent a Car: Rent a car by specifying the number of rental days.
Return a Car: Return a rented car and update its availability.
Customer Management: Manage customer details and rental history.
Pricing Information: Rental prices for each car model displayed.
💰 Pricing
Car Model	Price per Day (₹)
Toyota Camry	₹300
Honda Civic	₹400
Mahindra Thar	₹600
🛠 Technologies Used
Java (Object-Oriented Programming)
🔑 Class Structure
1. Car Class
Manages car details such as:
Car ID
Brand
Model
Price per day
Availability (rented or available)
2. Customer Class
Stores customer details including:
Customer ID
Name
Rental History (list of rented cars)
3. Rental Class
Represents a rental transaction with details:
Car ID
Customer ID
Rental days
4. CarRentalSystem Class
Manages the car inventory, customer details, and rental transactions:
Lists of cars, customers, and rental records
Rental and return car functionality
5. Main Class
Entry point to run the application and interact with the system:
Menu-based console interface for renting and returning cars
Displays available cars and rental pricing
🖥 How to Run
Clone this repository or download the project files.
Open the project in your preferred Java IDE (e.g., IntelliJ, Eclipse).
Run the Main.java class.
Use the console menu to interact with the system.
