# 🧮 Simple Calculator Test Cases

## ✅ Valid Input Test Cases

### Test Case ID: TC_CALC_001
**Description:** Verify addition of two positive integers  
**Preconditions:** Calculator app is open and ready for input  
**Test Steps:**  
1. Enter `5 + 3`  
2. Press `=`  
**Expected Result:** Display shows `8`

### Test Case ID: TC_CALC_002
**Description:** Verify subtraction with negative result  
**Preconditions:** Calculator app is open  
**Test Steps:**  
1. Enter `3 - 7`  
2. Press `=`  
**Expected Result:** Display shows `-4`

### Test Case ID: TC_CALC_003
**Description:** Verify multiplication of decimal numbers  
**Preconditions:** Calculator app is open  
**Test Steps:**  
1. Enter `2.5 × 4`  
2. Press `=`  
**Expected Result:** Display shows `10.0`

### Test Case ID: TC_CALC_004
**Description:** Verify division operation with positive numbers  
**Preconditions:** Calculator app is open  
**Test Steps:**  
1. Enter `20 ÷ 5`  
2. Press `=`  
**Expected Result:** Display shows `4`

### Test Case ID: TC_CALC_005
**Description:** Verify BODMAS rule evaluation  
**Preconditions:** Calculator app supports operator precedence  
**Test Steps:**  
1. Enter `2 + 3 × 4`  
2. Press `=`  
**Expected Result:** Display shows `14`

---

## ⚠️ Invalid Input Test Cases

### Test Case ID: TC_CALC_006
**Description:** Verify handling of non‑numeric characters  
**Preconditions:** Calculator app is open  
**Test Steps:**  
1. Enter `5 + a`  
2. Press `=`  
**Expected Result:** Error message displayed — “Invalid input”

### Test Case ID: TC_CALC_007
**Description:** Verify division by zero  
**Preconditions:** Calculator app is open  
**Test Steps:**  
1. Enter `10 ÷ 0`  
2. Press `=`  
**Expected Result:** Error message displayed — “Cannot divide by zero”

### Test Case ID: TC_CALC_008
**Description:** Verify empty input handling  
**Preconditions:** Calculator app is open  
**Test Steps:**  
1. Press `=` without entering any value  
**Expected Result:** Error message displayed — “No input provided”

### Test Case ID: TC_CALC_009
**Description:** Verify multiple operators entered consecutively  
**Preconditions:** Calculator app is open  
**Test Steps:**  
1. Enter `5 ++ 3`  
2. Press `=`  
**Expected Result:** Error message displayed — “Invalid expression”

---

## 🧩 Boundary Test Cases

### Test Case ID: TC_CALC_010
**Description:** Verify addition with very large numbers  
**Preconditions:** Calculator supports large integer operations  
**Test Steps:**  
1. Enter `999999999 + 1`  
2. Press `=`  
**Expected Result:** Display shows `1000000000`

### Test Case ID: TC_CALC_011
**Description:** Verify subtraction resulting in large negative number  
**Preconditions:** Calculator supports negative integers  
**Test Steps:**  
1. Enter `-999999999 - 1`  
2. Press `=`  
**Expected Result:** Display shows `-1000000000`

### Test Case ID: TC_CALC_012
**Description:** Verify multiplication with large operands  
**Preconditions:** Calculator supports large number multiplication  
**Test Steps:**  
1. Enter `99999 × 99999`  
2. Press `=`  
**Expected Result:** Display shows `9999800001`

### Test Case ID: TC_CALC_013
**Description:** Verify division precision with long decimal result  
**Preconditions:** Calculator supports floating‑point precision up to 10 digits  
**Test Steps:**  
1. Enter `10 ÷ 3`  
2. Press `=`  
**Expected Result:** Display shows `3.3333333333`

### Test Case ID: TC_CALC_014
**Description:** Verify handling of maximum decimal precision  
**Preconditions:** Calculator supports up to 15 decimal digits  
**Test Steps:**  
1. Enter `0.123456789012345 + 0.000000000000001`  
2. Press `=`  
**Expected Result:** Display shows `0.123456789012346`

### Test Case ID: TC_CALC_015
**Description:** Verify overflow handling beyond supported range  
**Preconditions:** Calculator has defined numeric range limit  
**Test Steps:**  
1. Enter `9999999999999999 + 9999999999999999`  
2. Press `=`  
**Expected Result:** Error message displayed — “Number out of range”
