# Python-Week-3-Assignment
# Discount Calculator

## Overview
This Python program calculates the final price of an item after applying a discount. The discount is only applied if it's 20% or higher; otherwise, the original price is returned.

## Features
- Calculates discounted prices based on a percentage threshold
- Only applies discounts of 20% or higher
- Takes user input for both the original price and discount percentage
- Displays formatted output with clear messaging

## How It Works
The program consists of two main components:

1. **`calculate_discount()` Function**
   - Takes two parameters: `price` and `discount_percent`
   - Checks if the discount percentage is at least 20%
   - If yes, calculates and returns the discounted price
   - If no, returns the original price unchanged

2. **User Interaction Section**
   - Prompts the user to enter the original price
   - Prompts the user to enter the discount percentage
   - Calls the `calculate_discount()` function with these inputs
   - Displays the final price with appropriate messaging

## Usage Example
```
Enter the original price of the item: $100
Enter the discount percentage: 25
Discount applied! Final price: $75.00
```

```
Enter the original price of the item: $100
Enter the discount percentage: 15
No discount applied. Original price: $100.00
```

## Implementation Details
- Input values are converted to floating-point numbers for accurate calculations
- The discount amount is calculated as a percentage of the original price
- The final price is formatted to display with 2 decimal places
- Different messages are shown depending on whether a discount was applied

## Requirements
- Python 3.x
