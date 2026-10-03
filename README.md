# Discount Calculator

A Python project completed through the freeCodeCamp discount calculator workshop to practice object-oriented programming and abstraction.

## Features

- Calculates percentage discounts.
- Calculates fixed dollar discounts.
- Applies a 20% discount for premium users.
- Compares eligible discounts and returns the lowest price.
- Displays prices with two decimal places.

Discounts are compared separately, not stacked. If no discounts apply, the original price is returned.

## Requirements

- Python 3.9 or newer
- No external packages required

## How to Run

Open a terminal in the project folder and run:

```bash
python discount_calculator.py
```

## Example Output

```text
Best price for Wireless Mouse for Premium user: $40.00
```

For a $50.00 product, the calculator compares:

| Discount                | Final Price |
| ----------------------- | ----------- |
| 10% off                 | $45.00      |
| $5 off                  | $45.00      |
| Premium discount of 20% | $40.00      |

## What I Learned

- Classes and objects
- Inheritance
- Abstract base classes with `ABC` and `@abstractmethod`
- Polymorphism through different discount strategies
- Parameter and return type hints
- Boolean comparisons
- Calling object methods
- Lists, loops, and `.append()`
- Finding the lowest value with `min()`
- Formatting prices using f-strings
- Using `if __name__ == '__main__':`

## Project Structure

```text
discount_calculator/
    discount_calculator.py
    README.md
```

## Project Status

The workshop is complete, and the calculator runs locally with a predefined example. User input and additional input validation are possible future improvements.
