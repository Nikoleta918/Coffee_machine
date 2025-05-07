# Coffee Machine Simulation ☕️

This is a Python-based simulation of a coffee machine. The machine can serve espresso, latte, and cappuccino, and tracks available resources like water, milk, and coffee. It also manages user payments using coin inputs and reports profits.

## Features

- Menu of three coffee options: espresso, latte, cappuccino.
- Tracks and manages machine resources (water, milk, coffee).
- Accepts coin-based payments: quarters, dimes, nickels, pennies.
- Calculates and gives change if overpaid.
- Rejects transactions if there are insufficient ingredients or money.
- Reports current resources and profit.
- Accepts administrative command to turn the machine off (`off`).

## Requirements

- Python 3.x

No external libraries are required.

## How to Run

1. Make sure Python 3 is installed on your system.
2. Save the script in a file, e.g., `coffee_machine.py`.
3. Run the script using:

```bash
python coffee_machine.py
Follow the prompts in the terminal.

Example
bash
Copy
Edit
What would you like? (espresso/latte/cappuccino): latte
Your coffee costs 2.5
Input coins please
How many quarters: 10
How many dimes: 0
How many nickels: 0
How many pennies: 0
Here is $0.00 in change.
Here is your latte. Enjoy!
Notes
Type report to check current machine status.

Type off to shut down the machine.

