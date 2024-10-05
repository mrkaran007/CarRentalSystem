# Car Rental System in Java

This is a simple console-based **Car Rental System** built using Java, which allows users to rent cars for a specified number of days and return them when done. The system manages available cars, rental information, and customer data efficiently through an interactive menu.

## Features:
- **Car Rental**: 
  - Users can rent a car by selecting from the available cars.
  - The system calculates the total rental cost based on the number of days.
- **Return Car**: 
  - Users can return a rented car by entering the car ID. 
  - The system updates the car's availability and removes it from active rentals.
- **Customer Management**: 
  - Each customer is assigned a unique ID upon renting a car, and their details are stored along with the rental information.
- **Car Management**: 
  - The system manages cars with attributes like car ID, brand, model, and daily rental price.
  - Cars can be marked as rented or available.

## Classes:

- `Car`: Represents a car with properties like car ID, brand, model, and rental status.
- `Customer`: Stores customer details, such as customer ID and name.
- `Rental`: Manages rental data, including the car rented, customer renting, and rental duration.
- `CarRentalSystem`: Provides the main operations for renting and returning cars, as well as interacting with the user through a console-based menu.

## How It Works:

1. **Rent a Car**: 
   - Users input their name, select a car, and specify the number of rental days. 
   - The system displays the total price for confirmation.
2. **Return a Car**: 
   - Users enter the car ID to return a previously rented car.
   - The system checks for active rentals and processes the return accordingly.

## Sample Execution:

```bash
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice: 1

== Rent a Car ==

Enter your name: Karan

Available Cars:
C001 - Toyota Camry
C002 - Honda Accord
C003 - Mahindra Thar

Enter the car ID you want to rent: C001
Enter the number of days for rental: 3

== Rental Information ==
Customer ID: CUS1
Customer Name: Karan
Car: Toyota Camry
Rental Days: 3
Total Price: $180.00

Confirm rental (Y/N): Y

Car rented successfully.

===== Car Rental System =====
```

## Installation and Usage:

1. Clone the repository:
   ```bash
   git clone https: https://github.com/mrkaran007/CarRentalSystem.git
   ```
2. Navigate to the project directory:
   ```bash
   cd car-rental-system-java
   ```
3. Compile the Java code:
   ```bash
   javac Main.java
   ```
4. Run the application:
   ```bash
   java Main
   ```

## Future Enhancements:

- Integrate a database for persistent storage of cars, customers, and rentals.
- Add features like late fee calculations, discounts, and maintenance tracking.


Feel free to customize this further based on your preferences or additional project details!
