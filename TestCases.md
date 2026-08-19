## TC-001

**Test Case ID:** TC-001

**Test Description:** Verify addition of two positive numbers.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `10`
2. Click `+`
3. Enter `5`
4. Click `=`

**Expected Result:** The calculator should display `15`.

---

## TC-002

**Test Case ID:** TC-002

**Test Description:** Verify subtraction of two positive numbers.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `10`
2. Click `-`
3. Enter `5`
4. Click `=`

**Expected Result:** The calculator should display `5`.

---

## TC-003

**Test Case ID:** TC-003

**Test Description:** Verify multiplication of two positive numbers.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `6`
2. Click `*`
3. Enter `5`
4. Click `=`

**Expected Result:** The calculator should display `30`.

---

## TC-004

**Test Case ID:** TC-004

**Test Description:** Verify division of two positive numbers.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `20`
2. Click `/`
3. Enter `4`
4. Click `=`

**Expected Result:** The calculator should display `5`.

---

## TC-005

**Test Case ID:** TC-005

**Test Description:** Verify the Clear (`C`) button.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `25`
2. Click `+`
3. Enter `10`
4. Click `C`

**Expected Result:** The calculator display should be cleared.

---

## TC-006

**Test Case ID:** TC-006

**Test Description:** Verify addition using decimal numbers.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `5.5`
2. Click `+`
3. Enter `2.5`
4. Click `=`

**Expected Result:** The calculator should display `8`.

---

## TC-007

**Test Case ID:** TC-007

**Test Description:** Verify subtraction resulting in a negative number.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `5`
2. Click `-`
3. Enter `10`
4. Click `=`

**Expected Result:** The calculator should display `-5`.

---

## TC-008

**Test Case ID:** TC-008

**Test Description:** Verify division resulting in a decimal value.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `10`
2. Click `/`
3. Enter `4`
4. Click `=`

**Expected Result:** The calculator should display `2.5`.

---

## TC-009

**Test Case ID:** TC-009

**Test Description:** Verify calculation history after performing a calculation.

**Preconditions:**

* Calculator application is open.
* Calculation history is visible.

**Test Steps:**

1. Enter `5`
2. Click `+`
3. Enter `5`
4. Click `=`

**Expected Result:** The calculation `5+5 = 10` should be displayed in the Recent Calculations section.

---

## TC-010

**Test Case ID:** TC-010

**Test Description:** Verify that multiple calculations are added to the calculation history.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Perform `5 + 5 =`
2. Perform `10 - 3 =`
3. Perform `4 * 2 =`

**Expected Result:** All completed calculations should be displayed in the Recent Calculations section.

---

## TC-011

**Test Case ID:** TC-011

**Test Description:** Verify that the latest calculation appears first in the calculation history.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Perform `5 + 5 =`
2. Perform `10 - 2 =`
3. Perform `8 * 2 =`

**Expected Result:** The latest calculation `8 * 2 = 16` should appear at the top of the calculation history.

---

## TC-012

**Test Case ID:** TC-012

**Test Description:** Verify calculator behavior when dividing a number by zero.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `10`
2. Click `/`
3. Enter `0`
4. Click `=`

**Expected Result:** The calculator should handle division by zero appropriately and display a proper error or validation message.

---

## TC-013

**Test Case ID:** TC-013

**Test Description:** Verify that multiple consecutive addition operators are not accepted.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `5`
2. Click `+`
3. Click `+`
4. Click `+`
5. Enter `3`
6. Click `=`

**Expected Result:** The calculator should not allow multiple consecutive addition operators and should display a proper validation message.

---

## TC-014

**Test Case ID:** TC-014

**Test Description:** Verify calculator behavior when multiple decimal points are entered.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Enter `2`
2. Click `.`
3. Click `.`
4. Enter `5`
5. Click `=`

**Expected Result:** The calculator should not allow multiple decimal points in the same number and should handle the invalid input appropriately.

---

## TC-015

**Test Case ID:** TC-015

**Test Description:** Verify calculator behavior when the equals (`=`) button is clicked without entering a calculation.

**Preconditions:**

* Calculator application is open.

**Test Steps:**

1. Open the Calculator application.
2. Do not enter any number or operator.
3. Click `=`.

**Expected Result:** The calculator should handle the action gracefully without crashing or displaying an unexpected result.
