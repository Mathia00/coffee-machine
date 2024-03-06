# Python Coffee Machine

This Python project simulates a coffee machine, allowing users to choose from a selection of coffee drinks and manage inventory. It's a simple implementation aimed at demonstrating basic programming concepts.

## Features

- **Drink Selection:** Users can choose from a menu of coffee drinks, including espresso, latte, and cappuccino.
- **Inventory Management:** The coffee machine keeps track of the inventory of ingredients such as coffee, milk, and water. It deducts the required amounts for each drink ordered.
- **Refill Option:** Users can refill the inventory with additional ingredients.
- **Check Resources:** Users can check the current status of ingredients in the coffee machine.
- **Payment:** Although not implemented in this basic version, future iterations could include payment functionality.

## Dependencies

This project requires Python 3.x. There are no additional dependencies beyond the standard library.

## How to Use

1. Clone or download this repository to your local machine.
2. Navigate to the project directory.
3. Run the `coffee_machine.py` script using Python:
    ```
    python coffee_machine.py
    ```
4. Follow the prompts to interact with the coffee machine. You can select drinks, refill ingredients, and check resources as needed.

## File Structure

- `coffee_machine.py`: The main Python script containing the coffee machine functionality.
- `menu.py`: Defines the menu of available drinks and their respective ingredients.
- `inventory.py`: Manages the inventory of ingredients and provides functions for deducting and refilling.
- `README.md`: This README file.

## Example Usage

Welcome to the Python Coffee Machine!

What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
How many quarters?: 2
How many dimes?: 0
How many nickels?: 1
How many pennies?: 0
Here is $0.65 in change.
Here is your latte. Enjoy!

Would you like to order another drink? (yes/no): no
