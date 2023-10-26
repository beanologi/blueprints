# Ansible Conditionals
RHCE v9 Learning

## Objectives
  - Core: Conditionals

## Notes

- **Basic Operators in Ansible Conditionals**
  - Equalities and Inequalities
  - Logical Operators (`and`, `or`)
  - Using `is defined` and `is not defined`
  - Checking a variable's truth value directly
  - Using `not` before a variable to check its falsity
  - Using `in` keyword to check presence in a list

- **Multiple Conditions**
  - Basics of `or` and `and` 
  - Demonstrating the use of braces for complex conditionals
    - *Example:* `when: (condition1 or condition2) and condition3`
  - List form for combining multiple `and` conditions
    - *Example:* `when: [condition1, condition2, condition3]`

- **Special Directives: `failed_when` and `changed_when`**
  - Explanation of how they are used 
  - Common use cases

- **Integrating Loops with Conditionals**
  - *Example:* Looping through a list and applying conditions to each item
  - *Example:* Conditionally creating resources based on loop iterations