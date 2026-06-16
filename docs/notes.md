# Notes for Calculator Test Cases

## Thought Process

### Why I Chose Certain Boundary Values
- Very large numbers (e.g., 999999999 + 1) were selected to test how the calculator handles integer overflow.
- Decimal precision values (e.g., 0.123456789012345 + 0.000000000000001) were chosen to verify rounding and floating‑point accuracy.
- Division with repeating decimals (e.g., 10 ÷ 3) was included to check precision limits.

### How Invalid Inputs Were Identified
- Non‑numeric characters (e.g., `5 + a`) to test input validation.
- Division by zero (`10 ÷ 0`) to ensure proper error handling.
- Empty input (pressing `=` without values) to check default error messages.
- Multiple consecutive operators (`5 ++ 3`) to confirm expression validation.

### Assumptions Made
- Calculator supports basic arithmetic operations (add, subtract, multiply, divide).
- Calculator follows BODMAS/PEMDAS rules for operator precedence.
- Calculator has a defined numeric range and precision limit.
- Error messages are displayed clearly when invalid inputs occur.
