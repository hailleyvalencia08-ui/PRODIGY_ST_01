# Report for Task-01: Calculator Test Cases

## Task Objective
To design and document comprehensive test cases for a simple calculator application as part of the Software Testing internship at Prodigy InfoTech.

## Scope of Testing
- Basic arithmetic operations (addition, subtraction, multiplication, division).
- Operator precedence (BODMAS).
- Handling of invalid inputs (non-numeric, division by zero, empty input).
- Boundary conditions (large numbers, precision limits).

## Key Findings
- Calculator correctly handles valid inputs and produces expected results.
- Division by zero is flagged with an appropriate error message.
- Non-numeric inputs are rejected with error handling.
- Large numbers and decimal precision are tested to ensure robustness.
  
## Defects Found
- Division by zero displays "Infinity" instead of an error message.
- Decimal division results are not rounded (e.g., 10 ÷ 3 shows 3.3333333333333335).
- Large number operations may not be formatted in scientific notation.
