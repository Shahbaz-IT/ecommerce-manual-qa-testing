# E-Commerce Website — Test Cases

## Test Case 1 — User Registration with Valid Data

| Field | Details |
|---|---|
| Test Case ID | TC-REG-001 |
| Module | User Registration |
| Priority | High |
| Type | Functional |
| Preconditions | User is on the registration page |

### Test Steps

1. Open the registration page.
2. Enter a valid first name.
3. Enter a valid last name.
4. Enter a valid email address.
5. Enter a valid password.
6. Confirm the password.
7. Click the Register button.

### Expected Result

The account should be created successfully and the user should receive confirmation that registration was successful.

---

## Test Case 2 — Registration with Invalid Email

| Field | Details |
|---|---|
| Test Case ID | TC-REG-002 |
| Module | User Registration |
| Priority | High |
| Type | Negative |
| Preconditions | User is on the registration page |

### Test Steps

1. Open the registration page.
2. Enter valid user information.
3. Enter an invalid email address.
4. Complete the remaining required fields.
5. Click the Register button.

### Expected Result

The system should reject the invalid email address and display an appropriate validation message.

---

## Test Case 3 — Login with Valid Credentials

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-001 |
| Module | Login |
| Priority | Critical |
| Type | Functional |
| Preconditions | A registered user account exists |

### Test Steps

1. Open the login page.
2. Enter a registered email address.
3. Enter the correct password.
4. Click Login.

### Expected Result

The user should be successfully logged in and redirected to the appropriate authenticated area.

---

## Test Case 4 — Login with Incorrect Password

| Field | Details |
|---|---|
| Test Case ID | TC-LOGIN-002 |
| Module | Login |
| Priority | High |
| Type | Negative |
| Preconditions | A registered user account exists |

### Test Steps

1. Open the login page.
2. Enter a registered email address.
3. Enter an incorrect password.
4. Click Login.

### Expected Result

Login should fail and an appropriate error message should be displayed.

---

## Test Case 5 — Search for an Existing Product

| Field | Details |
|---|---|
| Test Case ID | TC-SEARCH-001 |
| Module | Product Search |
| Priority | High |
| Type | Functional |
| Preconditions | User is on the e-commerce website |

### Test Steps

1. Enter a valid product name in the search field.
2. Click Search.

### Expected Result

Relevant products matching the search term should be displayed.

---

## Test Case 6 — Add Product to Cart

| Field | Details |
|---|---|
| Test Case ID | TC-CART-001 |
| Module | Shopping Cart |
| Priority | Critical |
| Type | Functional |
| Preconditions | Product is available |

### Test Steps

1. Open a product details page.
2. Select the required options if applicable.
3. Click Add to Cart.
4. Open the shopping cart.

### Expected Result

The selected product should appear in the shopping cart with the correct product information and price.

---

## Test Case 7 — Remove Product from Cart

| Field | Details |
|---|---|
| Test Case ID | TC-CART-002 |
| Module | Shopping Cart |
| Priority | High |
| Type | Functional |
| Preconditions | Cart contains at least one product |

### Test Steps

1. Open the shopping cart.
2. Select Remove for a product.
3. Review the cart.

### Expected Result

The selected product should be removed and the cart total should be updated correctly.

---

## Test Case 8 — Checkout with Valid Information

| Field | Details |
|---|---|
| Test Case ID | TC-CHECKOUT-001 |
| Module | Checkout |
| Priority | Critical |
| Type | Functional |
| Preconditions | User is logged in and has a product in the cart |

### Test Steps

1. Open the shopping cart.
2. Proceed to checkout.
3. Enter valid shipping information.
4. Select an available payment method.
5. Review the order.
6. Confirm the order.

### Expected Result

The order should be successfully placed and an order confirmation should be displayed.

---

## Test Case 9 — Checkout with Missing Required Information

| Field | Details |
|---|---|
| Test Case ID | TC-CHECKOUT-002 |
| Module | Checkout |
| Priority | High |
| Type | Negative |
| Preconditions | User has reached the checkout page |

### Test Steps

1. Leave one or more required fields empty.
2. Attempt to continue with checkout.

### Expected Result

The system should prevent the user from continuing and display appropriate validation messages.

---

## Test Case 10 — User Logout

| Field | Details |
|---|---|
| Test Case ID | TC-LOGOUT-001 |
| Module | Authentication |
| Priority | Medium |
| Type | Functional |
| Preconditions | User is logged in |

### Test Steps

1. Open the user account menu.
2. Click Logout.

### Expected Result

The user should be logged out successfully and redirected to the appropriate public page.
