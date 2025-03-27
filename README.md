# Bike Rental System

## Overview
The **Bike Rental System** is a Python-based project implemented using Object-Oriented Programming (OOP) concepts. This system allows customers to rent bikes on a daily or weekly basis, with a special discount for family rentals.

## Features
- Display available bike inventory.
- Rent bikes on a daily basis (Rs. 100 per day per bike).
- Rent bikes on a weekly basis (Rs. 500 per week per bike).
- Family Rental promotion: A discount of 30% for renting 3 to 5 bikes.
- Return bikes and generate a bill.

## Project Structure
The project consists of two main classes:
1. **BikeRental** (Parent Class)
   - Manages bike inventory.
   - Displays available stock.
2. **Customer** (Child Class)
   - Handles rental requests.
   - Calculates the rental cost.
   - Applies discounts for family rentals.

## How It Works
1. **Creating a Bike Shop**
   ```python
   bike_shop = BikeRental()
   ```
2. **Displaying Available Stock**
   ```python
   bike_shop.displaystock()
   ```
3. **Renting a Bike**
   ```python
   customer = Customer(2, 'daily', 5)  # Renting 2 bikes for 5 days
   customer.rentBike()
   ```
4. **Returning a Bike & Generating Bill**
   ```python
   customer.returnBike()
   ```

## Conclusion
This project demonstrates the use of OOP principles such as inheritance and encapsulation to build a real-world application. It can be further enhanced by adding features like an online booking system, customer registration, and dynamic pricing models.

