# Task-01: Test Cases for Simple Calculator Applications

## Addition – Test Cases

### Test Case Id:

**TC_001**

**Test Description:**
Verify addition of two positive numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 18
2. Click `+`
3. Enter 27
4. Click `=`

**Expected Result:**
Result should be **45**

---

### Test Case Id:

**TC_002**

**Test Description:**
Verify addition of two negative numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter -12
2. Click `+`
3. Enter -18
4. Click `=`

**Expected Result:**
Result should be **-30**

---

### Test Case Id:

**TC_003**

**Test Description:**
Verify addition of decimal numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 6.5
2. Click `+`
3. Enter 3.5
4. Click `=`

**Expected Result:**
Result should be **10.0**

---

## Subtraction – Test Cases

### Test Case Id:

**TC_004**

**Test Description:**
Verify subtraction of two positive numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 30
2. Click `-`
3. Enter 12
4. Click `=`

**Expected Result:**
Result should be **18**

---

### Test Case Id:

**TC_005**

**Test Description:**
Verify subtraction resulting in negative value

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 8
2. Click `-`
3. Enter 19
4. Click `=`

**Expected Result:**
Result should be **-11**

---

## Multiplication – Test Cases

### Test Case Id:

**TC_006**

**Test Description:**
Verify multiplication of two numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 7
2. Click `*`
3. Enter 8
4. Click `=`

**Expected Result:**
Result should be **56**

---

### Test Case Id:

**TC_007**

**Test Description:**
Verify multiplication with zero

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 21
2. Click `*`
3. Enter 0
4. Click `=`

**Expected Result:**
Result should be **0**

---

### Test Case Id:

**TC_008**

**Test Description:**
Verify multiplication of decimal numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 2.5
2. Click `*`
3. Enter 4
4. Click `=`

**Expected Result:**
Result should be **10.0**

---

## Division – Test Cases

### Test Case Id:

**TC_009**

**Test Description:**
Verify division of two positive numbers

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 48
2. Click `/`
3. Enter 8
4. Click `=`

**Expected Result:**
Result should be **6**

---

### Test Case Id:

**TC_010**

**Test Description:**
Verify division resulting in decimal value

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 7
2. Click `/`
3. Enter 4
4. Click `=`

**Expected Result:**
Result should be **1.75**

---

### Test Case Id:

**TC_011**

**Test Description:**
Verify division by zero

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter 15
2. Click `/`
3. Enter 0
4. Click `=`

**Expected Result:**
Error message should be displayed (e.g., *“Cannot divide by zero”*)

---

## BODMAS – Test Case

### Test Case Id:

**TC_012**

**Test Description:**
Verify calculator follows BODMAS rule

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter `12 + 4 * 3`
2. Click `=`

**Expected Result:**
Result should be **24**

---

## Invalid Input – Test Cases

### Test Case Id:

**TC_013**

**Test Description:**
Verify behavior for non-numeric input

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter `y`
2. Click `+`
3. Enter 6
4. Click `=`

**Expected Result:**
Error message should be displayed

---

### Test Case Id:

**TC_014**

**Test Description:**
Verify behavior for special characters

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Enter `@`
2. Click `+`
3. Enter `&`
4. Click `=`

**Expected Result:**
Error message should be displayed

---

### Test Case Id:

**TC_015**

**Test Description:**
Verify behavior when no input is provided

**Precondition:**
Calculator application is opened

**Test Steps:**

1. Click `=` without entering any value

**Expected Result:**
No result or validation message should be shown
