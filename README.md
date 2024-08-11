# 🚗 Car Go Rental System

Welcome to "Car Go Rental System"- a simple, console-based car rental management system built using Java. This project showcases the use of Object-Oriented Programming (OOP) principles and demonstrates a functional car rental service where users can rent and return cars with ease.

## 📋 Table of Contents

- [Features](#features)
- [How It Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## 🌟 Features

- [Car Inventory Management]: Add and manage car details such as brand, model, and rental price.
- [Customer Management]: Automatically generate customer IDs and store customer information.
- [Car Rental Process]: Rent cars to customers, calculate rental prices, and mark cars as rented.
- [Car Return Process]: Return rented cars, update their availability, and remove rental records.
- [Interactive Menu]: Easy-to-navigate console menu for renting and returning cars.

## 💻 How It Works

1. [Add Cars]: The system initializes with a predefined set of cars.
2. [Rent a Car]: Customers can rent available cars by providing their name and selecting the car they wish to rent.
3. [Return a Car]: Customers can return rented cars by providing the car ID.
4. [Rental Calculation]: The system calculates the total rental price based on the number of rental days and the car's daily rental rate.

## 🛠️ Installation

1. [Clone the Repository]:
    ```bash
    git clone https://github.com/your-username/car-rental-system.git
    ```

2. [Navigate to the Project Directory]:
    ```bash
    cd car-rental-system
    ```

3. [Compile the Code]:
    ```bash
    javac Main.java
    ```

4. [Run the Program]:
    ```bash
    java Main
    ```

## 🚀 Usage

Upon running the program, you'll be greeted with a menu offering options to rent or return a car:

1. [Rent a Car]: Enter your name, choose from the list of available cars, and specify the number of rental days.
2. [Return a Car]: Provide the car ID to return it and make it available for the next customer.
3. [Exit]: Close the application.

Follow the on-screen prompts to complete your actions.

## 🗂️ Code Structure

- [Main.java]: Entry point of the application containing the `main()` method.
- [CarRentalSystem]: Handles the core logic, including managing cars, customers, and rentals.
- [Car]: Represents a car with details like ID, brand, model, and availability.
- [Customer]: Represents a customer with an ID and name.
- [Rental]: Represents a rental transaction, linking a car and a customer for a specified duration.

## 🔮 Future Enhancements

- [Enhanced User Interface]: Improve the console UI or create a graphical interface.
- [Database Integration]: Store car and customer data in a database for persistence.
- [Reservation System]: Allow customers to reserve cars in advance.
- [Payment Processing]: Integrate payment handling for rental transactions.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request with your improvements.



Thank you for checking out the Car Go Rental System! 🚗💨
