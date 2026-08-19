## BUG-001

**Bug Title:** Calculator accepts consecutive operators (`+ -`)

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Enter `5`
2. Click `+`
3. Click `-`
4. Enter `3`
5. Click `=`

**Expected Result:**

The calculator should not allow consecutive operators. It should display a proper validation/error message.

**Actual Result:**

The calculator accepts `5 + - 3` and displays `2`.

**Status:** Open

## BUG-002

**Bug Title:** Calculator accepts multiple decimal points

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Enter `5`
2. Click `.`
3. Click `.`
4. Enter `5`

**Expected Result:**

The calculator should not allow multiple decimal points within the same number. It should display a proper validation/error message.

**Actual Result:**

The calculator accepts multiple decimal points in the same number.

**Status:** Open

---

## BUG-003

**Bug Title:** Calculator does not properly handle division by zero

**Severity:** High

**Priority:** High

**Steps to Reproduce:**

1. Enter `10`
2. Click `/`
3. Enter `0`
4. Click `=`

**Expected Result:**

The calculator should prevent division by zero and display a proper validation/error message.

**Actual Result:**

The calculator does not properly handle the division-by-zero operation.

**Status:** Open

---

## BUG-004

**Bug Title:** Calculator accepts an operator at the beginning of an expression

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Click `+`
2. Enter `5`
3. Click `=`

**Expected Result:**

The calculator should not allow an operator at the beginning of an expression. It should display a proper validation/error message.

**Actual Result:**

The calculator accepts the operator at the beginning of the expression.

**Status:** Open

---

## BUG-005

**Bug Title:** Calculator accepts an expression ending with an operator

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Enter `5`
2. Click `+`
3. Click `=`

**Expected Result:**

The calculator should not allow an expression to end with an operator. It should display a proper validation/error message.

**Actual Result:**

The calculator accepts the incomplete expression ending with an operator.

**Status:** Open

---

## BUG-006

**Bug Title:** Calculator shows unexpected behavior when the equals button is clicked multiple times

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Enter `5`
2. Click `+`
3. Enter `5`
4. Click `=`
5. Click `=` again

**Expected Result:**

The calculator should handle repeated clicks on the equals button appropriately without performing an unintended additional calculation.

**Actual Result:**

The calculator shows unexpected behavior when the equals button is clicked multiple times.

**Status:** Open

---

## NEGATIVE TESTING 

## BUG-007

**Bug Title:** Calculator displays `Infinity` when dividing by zero

**Severity:** Medium

**Priority:** High

**Steps to Reproduce:**

1. Enter `10`
2. Click `/`
3. Enter `0`
4. Click `=`

**Expected Result:**

The calculator should prevent division by zero and display a proper validation/error message instead of `Infinity`.

**Actual Result:**

The calculator displays `Infinity`.

**Status:** Open

---

## BUG-008

**Bug Title:** Calculator displays `undefined` when equals button is pressed without input

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Open the calculator.
2. Do not enter any number or operator.
3. Click `=`.

**Expected Result:**

The calculator should handle the empty input gracefully and should not display a technical value such as `undefined`.

**Actual Result:**

The calculator displays `undefined`.

**Status:** Open

---

## BUG-009

**Bug Title:** Calculator displays `undefined` in calculation history for a negative number

**Severity:** Medium

**Priority:** Medium

**Steps to Reproduce:**

1. Enter `-2`
2. Click `=`
3. Check the calculation history.

**Expected Result:**

The calculator should display the negative number correctly in the calculation history and should not display `undefined`.

**Actual Result:**

The calculator displays `-2` correctly on the calculator display, but `undefined` is displayed in the calculation history.

**Status:** Open