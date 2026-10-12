# Task 05 — Forms & Input Validation Testing

## Objective

To test form behavior and input validation using the SauceDemo login page.

**Application:** https://www.saucedemo.com/

## Scope of Testing

* Empty fields
* Missing username or password
* Invalid username and password
* Special characters
* Long input values
* Incorrect input formats
* Boundary values
* Successful login with valid credentials

## Test Results

| Test ID | Test Scenario        | Expected Result            | Actual Result        | Status  |
| ------- | -------------------- | -------------------------- | -------------------- | ------- |
| TC-01   | Empty fields         | Validation error displayed | Update after testing | Pending |
| TC-02   | Empty password       | Login rejected             | Update after testing | Pending |
| TC-03   | Empty username       | Login rejected             | Update after testing | Pending |
| TC-04   | Invalid username     | Login rejected             | Update after testing | Pending |
| TC-05   | Incorrect password   | Login rejected             | Update after testing | Pending |
| TC-06   | Valid credentials    | Inventory page opens       | Update after testing | Pending |
| TC-07   | Special characters   | Invalid login rejected     | Update after testing | Pending |
| TC-08   | Long input           | Application remains stable | Update after testing | Pending |
| TC-09   | Email-style username | Login rejected             | Update after testing | Pending |
| TC-10   | Boundary values      | Invalid login rejected     | Update after testing | Pending |

## Evidence

Screenshots of executed test cases will be added to this repository.

## Bug Reporting

Any mismatch between expected and actual behavior will be documented with a test ID, steps to reproduce, expected result, actual result, severity, and screenshot.

## Conclusion

The form validation assessment will be completed after all test cases have been executed and their results recorded.
