# Objective

In this challenge, you will work with arithmetic operators. Check out the Tutorial tab for learning materials and an instructional video.

# Task

Given the meal price (base cost of a meal), tip percent (the percentage of the meal price being added as tip), and tax percent (the percentage of the meal price being added as tax) for a meal, find and print the meal's total cost. Round the result to the nearest integer.

## Example

- `meal_cost = 12.00`
- `tip_percent = 15`
- `tax_percent = 8`

A tip of 15% \* 100 = 15, and the taxes are 8% \* 100 = 8. Print the value and return from the function.

## Function Description

Complete the solve function in the editor below.

`solve` has the following parameters:

- `int meal_cost`: the cost of food before tip and tax
- `int tip_percent`: the tip percentage
- `int tax_percent`: the tax percentage

### Returns

The function returns nothing. Print the calculated value, rounded to the nearest integer.

**Note:** Be sure to use precise values for your calculations, or you may end up with an incorrectly rounded result.

## Input Format

There are 3 lines of numeric input:

1. The first line has a double, `meal_cost` (the cost of the meal before tax and tip).
2. The second line has an integer, `tip_percent` (the percentage of `meal_cost` being added as tip).
3. The third line has an integer, `tax_percent` (the percentage of `meal_cost` being added as tax).

## Sample Input

```bash
12.00
20
8
```

## Sample Output

```bash
15
```

## Explanation

Given:

- `meal_cost = 12.00`
- `tip_percent = 20`
- `tax_percent = 8`

Calculations:

- Tip: `12.00 * 20 / 100 = 2.40`
- Tax: `12.00 * 8 / 100 = 0.96`
- Total cost: `12.00 + 2.40 + 0.96 = 15.36`

We round `total_cost` to the nearest integer and print the result, `15`.
