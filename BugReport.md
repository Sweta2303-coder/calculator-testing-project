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