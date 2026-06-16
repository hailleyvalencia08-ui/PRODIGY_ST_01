# 🧮 Simple Calculator Test Cases (with Actual Results)

## ✅ Valid Input Test Cases

### Test Case ID: TC_CALC_001
**Description:** Verify addition of two positive integers  
**Steps:** Enter `5 + 3` → Press `=`  
**Expected Result:** `8`  
**Actual Result:** `8`  
**Status:** Pass

### Test Case ID: TC_CALC_002
**Description:** Verify subtraction with negative result  
**Steps:** Enter `3 - 7` → Press `=`  
**Expected Result:** `-4`  
**Actual Result:** `-4`  
**Status:** Pass

### Test Case ID: TC_CALC_003
**Description:** Verify multiplication of decimal numbers  
**Steps:** Enter `2.5 × 4` → Press `=`  
**Expected Result:** `10.0`  
**Actual Result:** `10`  
**Status:** Pass (rounded but correct)

### Test Case ID: TC_CALC_004
**Description:** Verify division operation with positive numbers  
**Steps:** Enter `20 ÷ 5` → Press `=`  
**Expected Result:** `4`  
**Actual Result:** `4`  
**Status:** Pass

### Test Case ID: TC_CALC_005
**Description:** Verify BODMAS rule evaluation  
**Steps:** Enter `2 + 3 × 4` → Press `=`  
**Expected Result:** `14`  
**Actual Result:** `14`  
**Status:** Pass

---

## ⚠️ Invalid Input Test Cases

### Test Case ID: TC_CALC_006
**Description:** Verify handling of non‑numeric characters  
**Steps:** Enter `5 + a` → Press `=`  
**Expected Result:** Error message “Invalid input”  
**Actual Result:** Input not accepted (no calculation performed)  
**Status:** Pass (handled by ignoring invalid input)

### Test Case ID: TC_CALC_007
**Description:** Verify division by zero  
**Steps:** Enter `10 ÷ 0` → Press `=`  
**Expected Result:** Error message “Cannot divide by zero”  
**Actual Result:** `Infinity`  
**Status:** Fail

### Test Case ID: TC_CALC_008
**Description:** Verify empty input handling  
**Steps:** Press `=` without entering any value  
**Expected Result:** Error message “No input provided”  
**Actual Result:** Nothing happens (no output)  
**Status:** Fail

### Test Case ID: TC_CALC_009
**Description:** Verify multiple operators entered consecutively  
**Steps:** Enter `5 ++ 3` → Press `=`  
**Expected Result:** Error message “Invalid expression”  
**Actual Result:** Input not accepted (calculator ignores invalid sequence)  
**Status:** Pass (expression prevented)

---

## 🧩 Boundary Test Cases

### Test Case ID: TC_CALC_010
**Description:** Verify addition with very large numbers  
**Steps:** Enter `999999999 + 1` → Press `=`  
**Expected Result:** `1000000000`  
**Actual Result:** `1000000000`  
**Status:** Pass

### Test Case ID: TC_CALC_011
**Description:** Verify subtraction resulting in large negative number  
**Steps:** Enter `-999999999 - 1` → Press `=`  
**Expected Result:** `-1000000000`  
**Actual Result:** `-1000000000`  
**Status:** Pass

### Test Case ID: TC_CALC_012
**Description:** Verify multiplication with large operands  
**Steps:** Enter `99999 × 99999` → Press `=`  
**Expected Result:** `9999800001`  
**Actual Result:** `9999800001`  
**Status:** Pass

### Test Case ID: TC_CALC_013
**Description:** Verify division precision with long decimal result  
**Steps:** Enter `10 ÷ 3` → Press `=`  
**Expected Result:** `3.3333333333` (rounded to 10 digits)  
**Actual Result:** `3.3333333333333335` (unrounded float)  
**Status:** Fail

### Test Case ID
