# E-Commerce Website — Test Execution Report

## 1. Test Environment

| Item | Details |
|---|---|
| Application | SauceDemo |
| Testing Type | Manual Functional Testing |
| Test Approach | Positive & Negative Testing |
| Browser | Google Chrome |
| Tester | Shahbaz Mumtaz |
| Test Status | Completed |

## 2. Test Execution Summary

| Test Case | Description | Result |
|---|---|---|
| TC-REG-001 | User registration with valid data | Not Executed |
| TC-REG-002 | Registration with invalid email | Not Executed |
| TC-LOGIN-001 | Login with valid credentials | PASS |
| TC-LOGIN-002 | Login with incorrect password | Not Executed |
| TC-SEARCH-001 | Product search | Not Executed |
| TC-CART-001 | Add product to cart | PASS |
| TC-CART-002 | Remove product from cart | PASS |
| TC-CHECKOUT-001 | Checkout with valid information | PASS |
| TC-CHECKOUT-002 | Checkout with missing required information | PASS |
| TC-LOGOUT-001 | User logout | Not Executed |

## 3. Tests Performed

### Login

The standard demo user was able to log in successfully and reach the Products page.

**Result: PASS**

### Product Selection

Products were displayed correctly. Product details could be opened and product images were accessible.

**Result: PASS**

### Shopping Cart

A product was successfully added to the shopping cart.

The product could then be removed from the cart successfully.

**Result: PASS**

### Checkout

The checkout workflow was tested using dummy test information.

The application successfully allowed the checkout process to continue when the required information was provided.

**Result: PASS**

### Required Field Validation

The following validation scenarios were tested:

- First Name left empty
- Last Name left empty
- Postal Code left empty

The application displayed appropriate required-field validation messages.

**Result: PASS**

## 4. Observations

During testing, Google Chrome displayed a password-security warning for the public demo credentials.

This was treated as a browser security warning rather than an application defect.

No reproducible application defect was confirmed during the executed test scenarios.

## 5. Overall Result

The executed test scenarios passed successfully.

No confirmed defects were identified during this test execution.

Further testing would be required to achieve broader coverage of the application.
