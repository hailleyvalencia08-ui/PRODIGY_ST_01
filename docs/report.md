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
- Division by zero currently displays "Infinity" instead of an error message.
- Decimal division results are not rounded (e.g., 10 ÷ 3 shows 3.3333333333333335).
- Empty input produces no output instead of an error message.
- Very large numbers are calculated but not flagged as overflow.

## Defects Found
- **TC_CALC_007:** Division by zero → Expected error message, Actual result "Infinity".  
- **TC_CALC_008:** Empty input → Expected error message, Actual result no output.  
- **TC_CALC_013:** Division precision → Expected rounded result, Actual result unrounded float.  
- **TC_CALC_015:** Overflow handling → Expected error message, Actual result large number displayed.

## Conclusion
The calculator performs well for standard operations but fails in critical edge cases such as division by zero, empty input handling, precision control, and overflow detection. These defects should be addressed to improve reliability and user experience.
