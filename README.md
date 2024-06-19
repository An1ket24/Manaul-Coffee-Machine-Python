# Manaul-Coffee-Machine-Python
This coffee machine program prompts users to select a drink (espresso, latte, cappuccino), checks if resources are sufficient, and processes payments. It prints resource reports and handles transactions, including providing change. The machine can be turned off with "off". It ensures efficient inventory management and user interaction.

Coffee Machine Program Description

This program simulates the operation of a coffee machine, providing a menu of drink options, processing user inputs, handling financial transactions, and maintaining an inventory of resources. Below is an overview of the key features and functions of the program:

User Prompt and Drink Selection:

The program continually prompts the user with "What would you like? (espresso/latte/cappuccino):".
Based on the user input, the program decides whether to dispense a drink, generate a report, or turn off the machine.
Turn Off the Coffee Machine:

Entering "off" at the prompt turns off the machine and ends the program. This feature is intended for maintainers of the machine.
Generate Report:

When the user enters "report", the program prints a report showing the current values of resources (water, milk, coffee, and money).
Check Resource Sufficiency:

Before making a drink, the program checks if there are enough resources available.
If resources are insufficient, it prints an appropriate message (e.g., "Sorry there is not enough water.") and does not proceed with the transaction.
Process Coins:

If resources are sufficient for the selected drink, the program prompts the user to insert coins.
It accepts quarters, dimes, nickels, and pennies, and calculates the total monetary value of the coins inserted.
Check Transaction Success:

The program checks if the inserted money is enough to purchase the selected drink.
If the money is insufficient, it refunds the amount and prints a message.
If the money is sufficient, the program updates the machine's money balance and provides change if necessary.
Make Coffee:

Upon successful transaction and sufficient resources, the program deducts the required ingredients from the inventory.
It then dispenses the drink and prints a message to the user (e.g., "Here is your latte. Enjoy!").
Functions Breakdown
print_report: Prints the current resources of the coffee machine.
check_resources: Verifies if there are enough ingredients to make the selected drink.
process_coins: Prompts the user for coin input and calculates the total value.
check_transaction: Checks if the inserted money is sufficient for the drink cost, updates the money balance, and handles change.
make_coffee: Deducts the ingredients from the inventory and notifies the user that the drink is ready.
coffee_machine: The main function that controls the flow of the program, handles user inputs, and calls other functions as needed.
Program Flow
The program starts by prompting the user for their desired action.
Depending on the input, it either processes a drink order, generates a report, or turns off the machine.
If a drink is selected, it checks resource availability and processes the financial transaction.
If the transaction is successful and resources are sufficient, it makes the drink and updates the resource values.
The loop continues, allowing multiple transactions until "off" is entered.
This program ensures efficient management of a simulated coffee machine, providing an interactive and user-friendly experience.
