#  Car Go Rental System

Welcome to "Car Go Rental System"- a simple, console-based car rental management system built using Java. This project showcases the use of Object-Oriented Programming (OOP) principles and demonstrates a functional car rental service where users can rent and return cars with ease.

##  Table of Contents

1) Features
2) How It Works
3) Installation
4) Usage
5) Code Structure
6) Future Enhancements
7) Contributing
  

##  Features

            1) Car Inventory Management: Add and manage car details such as brand, model, and rental price.
             
            2) Customer Management: Automatically generate customer IDs and store customer information.
             
            3) Car Rental Process: Rent cars to customers, calculate rental prices, and mark cars as rented.
             
            4) Car Return Process: Return rented cars, update their availability, and remove rental records.
             
            5) Interactive Menu: Easy-to-navigate console menu for renting and returning cars.

##  How It Works

           1. Add Cars: The system initializes with a predefined set of cars.
   
           2. Rent a Car: Customers can rent available cars by providing their name and selecting the car they wish to rent.
   
           3. Return a Car: Customers can return rented cars by providing the car ID.
   
           4. Rental Calculation: The system calculates the total rental price based on the number of rental days and the car's daily rental rate.

##  Installation

1. Clone the Repository:
           git clone https://github.com/your-username/car-rental-system.git

2. Navigate to the Project Directory:
          cd car-rental-system

3. Compile the Code:
         javac Main.java
    
4. Run the Program:
         java Main

##  Usage

Upon running the program, you'll be greeted with a menu offering options to rent or return a car:

1. Rent a Car: Enter your name, choose from the list of available cars, and specify the number of rental days.
 
2. Return a Car: Provide the car ID to return it and make it available for the next customer.
 
3. Exit: Close the application.

Follow the on-screen prompts to complete your actions.

##  Code Structure

  1)  Main.java: Entry point of the application containing the `main()` method.
   
  2)  CarRentalSystem: Handles the core logic, including managing cars, customers, and rentals.
 
  3)  Car: Represents a car with details like ID, brand, model, and availability.

  4)  Customer: Represents a customer with an ID and name.
 
  5) Rental Represents a rental transaction, linking a car and a customer for a specified duration.

##  Future Enhancements

1) Enhanced User Interface: Improve the console UI or create a graphical interface.

2) Database Integration: Store car and customer data in a database for persistence.
 
3) Reservation System: Allow customers to reserve cars in advance.
 
4) Payment Processing: Integrate payment handling for rental transactions.

