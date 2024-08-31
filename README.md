# Coffee Machine Project

Welcome to the Coffee Machine project! This project is a simple Python-based coffee machine simulation that allows users to select drinks, check resources, and make payments.

## Project Overview

This project simulates a coffee machine that can serve three types of coffee: espresso, latte, and cappuccino. Users can select a drink, check the available resources, and make payments. The coffee machine will then prepare the selected drink if there are enough resources and if the payment is successful.

## Features

- **Menu**: Provides options for three types of coffee drinks.
- **Resource Management**: Tracks the available resources (water, milk, coffee) and updates them based on the drinks prepared.
- **Payment Processing**: Handles user payments and updates the profit.
- **Reporting**: Allows users to check the current status of resources and the total profit.

## Object-Oriented Programming

In this project, we utilized Object-Oriented Programming (OOP) to structure the code. The use of OOP principles allows us to:

- **Encapsulate** related data and functions into classes (`CoffeeMaker`, `Menu`, `MenuItem`, `MoneyMachine`).
- **Organize** the code into manageable and reusable components.
- **Improve** code readability and maintainability by following OOP design principles.


## Usage

1. **Start the Program**:
   Run the program by executing `python main.py`.

2. **Choose a Drink**:
   - Type the name of the drink you want (espresso, latte, cappuccino).
   - The program will check if there are enough resources and if your payment is sufficient.

3. **Check Resources and Profit**:
   - Type `report` to see the current status of resources and profit.

4. **Turn Off the Machine**:
   - Type `off` to turn off the coffee machine.

## Code Structure

- **`main.py`**: The main file that runs the coffee machine simulation.
- **`coffee_maker.py`**: Contains the `CoffeeMaker` class that manages resources and prepares drinks.
- **`menu.py`**: Contains the `Menu` and `MenuItem` classes that define the available drinks and their ingredients.
- **`money_machine.py`**: Handles payment processing.

