
# Random Number Generator

This Python script generates random financial values and prints them in a structured format. The script creates 10 sets of random values, including an actual charge, two adjustment values (P and R), a subtotal, and a total.

## Description

The script consists of two main functions:
1. `generate_numbers()`: This function generates random financial values.
2. `print_set(number_set)`: This function prints a set of generated numbers in a readable format.

### Function: `generate_numbers()`

This function generates the following random values:
- `actual_charge`: A random float between 614 and 630, rounded to two decimal places.
- `p`: A random float between -40 and 40, rounded to two decimal places.
- `r`: A random float between -0.28 and 0.76, rounded to two decimal places.
- `subtotal`: This is the same as `actual_charge`.
- `total`: Calculated as `actual_charge - p - r`, rounded to two decimal places.

The function returns a tuple containing these five values.

### Function: `print_set(number_set)`

This function takes a tuple of five values (generated by `generate_numbers()`) and prints each value with a label:
- Actual Charge
- P
- R
- Subtotal
- Total

### Main Script

The main script generates 10 sets of numbers using the `generate_numbers()` function and prints each set using the `print_set()` function.

## Usage

To run the script, simply execute it in a Python environment:


## License

This project is licensed under the MIT License - see the LICENSE file for details.
