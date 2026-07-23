# Employee Bonuses — FirstChoice Bank, South Street Branch

**GEN BUS 885: Python Fundamentals — Module 7**

## About this notebook

This notebook calculates annual bonuses for five bank tellers based on their
average customer rating for the year. It's the example notebook used
throughout Module 7 to illustrate the "notebook to module" workflow and
version control with Git.

## The business logic

Tellers are paid a bonus as a percentage of salary, based on their average
customer rating:

| Average rating   | Bonus          |
|-------------------|----------------|
| 4.5 to 5           | 17% of salary |
| 4 up to 4.5         | 10% of salary |
| 3 up to 4           | 5% of salary  |
| 1.5 up to 3         | 2% of salary  |
| below 1.5           | 0%            |

## What's in the notebook

- **`employees`** — a list of dictionaries holding each teller's name,
  average rating, and salary.
- **`bonus_calculator(emp_list)`** — loops through a list of employee
  dictionaries, applies the bonus structure above, and prints each teller's
  bonus.

## How to use it

Run the cells top to bottom. The final cell calls
`bonus_calculator(employees)` and prints a bonus line for each of the five
tellers.

Later versions of this logic that you build during the module's activities
should live in their own files/branches rather than overwriting this
original notebook, so you can always compare "before" and "after."
