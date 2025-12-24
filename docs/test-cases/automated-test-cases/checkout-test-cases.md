# Checkout functionality test cases of SauceDemo

**Note:** The First Name, Last Name, and Postal Code fields accept numbers, special characters, and unlimited-length input. Because the application does not enforce input restrictions, no negative or boundary tests for these inputs are required.

**Note:** The tax calculation with multiple items could be tested. But, the tax policy is unknown. Therefore, it can not be tested.

### Test Info

| Field            | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| Test Case ID     | TC-CHECKOUT-01                                               |
| Title            | Verify user can proceed to checkout with an item in the cart |
| Module / Feature | Checkout                                                     |
| Type             | Functional                                                   |
| Priority         | P1                                                           |
| Preconditions    | User is logged in and on homepage (Products page)            |
| Test Data        |                                                              |
| Environment      | https://www.saucedemo.com                                    |
| Depends on       | TC-SCART-03, TC-SCART-21                                     |

---

### Test Steps

| Step No | Action                                     | Expected Result                                                               |
| ------- | ------------------------------------------ | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon               | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                   | User is navigated to first step of checkout (Checkout: Your Information) page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                         |
| ---------------- | ------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-02                                                      |
| Title            | Verify user can proceed to checkout with multiple items in the cart |
| Module / Feature | Checkout                                                            |
| Type             | Functional                                                          |
| Priority         | P1                                                                  |
| Preconditions    | User is logged in and on homepage (Products page)                   |
| Test Data        |                                                                     |
| Environment      | https://www.saucedemo.com                                           |
| Depends on       | TC-SCART-03, TC-SCART-21                                            |

---

### Test Steps

| Step No | Action                                      | Expected Result                                                               |
| ------- | ------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart  | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Add the second item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 2            |
| 3       | Click the shopping cart icon                | User is navigated to Shopping Cart page                                       |
| 4       | Click on checkout button                    | User is navigated to first step of checkout (Checkout: Your Information) page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                       |
| ---------------- | ----------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-03                                                    |
| Title            | Verify user can't proceed to checkout without an item in the cart |
| Module / Feature | Checkout                                                          |
| Type             | Functional                                                        |
| Priority         | P1                                                                |
| Preconditions    | User is logged in and on homepage (Products page)                 |
| Test Data        |                                                                   |
| Environment      | https://www.saucedemo.com                                         |
| Depends on       | TC-SCART-03, TC-SCART-21                                          |

---

### Test Steps

| Step No | Action                       | Expected Result                                                                               |
| ------- | ---------------------------- | --------------------------------------------------------------------------------------------- |
| 1       | Click the shopping cart icon | User is navigated to Shopping Cart page                                                       |
| 2       | Click on checkout button     | User receives appropriate notification that the cart is empty and stays on Shopping Cart page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                          |
| ---------------- | ---------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-04                                       |
| Title            | Verify checkout information page has required fields |
| Module / Feature | Checkout                                             |
| Type             | Functional                                           |
| Priority         | P1                                                   |
| Preconditions    | User is logged in and on homepage (Products page)    |
| Test Data        |                                                      |
| Environment      | https://www.saucedemo.com                            |
| Depends on       | TC-CHECKOUT-01                                       |

---

### Test Steps

| Step No | Action                                                                                  | Expected Result                                                               |
| ------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                              | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                                            | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                                                | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Verify if first name, last name, postal code fields are visible and present on the page | All 3 fields are visible and present on the page                              |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                           |
| ---------------- | --------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-05                                                        |
| Title            | Verify Checkout: Your Information page has cancel and continue button |
| Module / Feature | Checkout                                                              |
| Type             | Functional                                                            |
| Priority         | P1                                                                    |
| Preconditions    | User is logged in and on homepage (Products page)                     |
| Test Data        |                                                                       |
| Environment      | https://www.saucedemo.com                                             |
| Depends on       | TC-CHECKOUT-01                                                        |

---

### Test Steps

| Step No | Action                                                                         | Expected Result                                                               |
| ------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                     | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                                   | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                                       | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Verify if both cancel and continue buttons are visible and present on the page | Both of the buttons are visible and present on the page                       |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                              |
| ---------------- | -------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-06                                           |
| Title            | Verify cancel process on Checkout: Your Information page |
| Module / Feature | Checkout                                                 |
| Type             | Functional                                               |
| Priority         | P1                                                       |
| Preconditions    | User is logged in and on homepage (Products page)        |
| Test Data        |                                                          |
| Environment      | https://www.saucedemo.com                                |
| Depends on       | TC-CHECKOUT-01                                           |

---

### Test Steps

| Step No | Action                                     | Expected Result                                                               |
| ------- | ------------------------------------------ | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon               | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                   | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Click on Cancel button                     | The user is navigated back to the Shopping Cart page                          |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                               |
| ---------------- | --------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-07                                            |
| Title            | Verify proceeding to Overview page with valid information |
| Module / Feature | Checkout                                                  |
| Type             | Functional                                                |
| Priority         | P1                                                        |
| Preconditions    | User is logged in and on homepage (Products page)         |
| Test Data        | John / Smith / 60311                                      |
| Environment      | https://www.saucedemo.com                                 |
| Depends on       | TC-CHECKOUT-01                                            |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Verify added item is added to the cart              | Added item is displayed in the cart                                           |
| 4       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 5       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 6       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 7       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 8       | Click on Continue button                            | User is navigated to the Overview page                                        |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                          |
| ---------------- | ---------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-08                                       |
| Title            | Verify proceeding to Overview page with empty fields |
| Module / Feature | Checkout                                             |
| Type             | Functional                                           |
| Priority         | P1                                                   |
| Preconditions    | User is logged in and on homepage (Products page)    |
| Test Data        | John / Smith / 60311                                 |
| Environment      | https://www.saucedemo.com                            |
| Depends on       | TC-CHECKOUT-01                                       |

---

### Test Steps

| Step No | Action                                     | Expected Result                                                               |
| ------- | ------------------------------------------ | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon               | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                   | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Leave all 3 fields empty                   |                                                                               |
| 5       | Click on Continue button                   | User stays on the page and gets an appropriate error message                  |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                              |
| ---------------- | -------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-09                                           |
| Title            | Verify proceeding to Overview page with empty first name |
| Module / Feature | Checkout                                                 |
| Type             | Functional                                               |
| Priority         | P1                                                       |
| Preconditions    | User is logged in and on homepage (Products page)        |
| Test Data        | Smith / 60311                                            |
| Environment      | https://www.saucedemo.com                                |
| Depends on       | TC-CHECKOUT-01                                           |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Leave the First Name field empty                    |                                                                               |
| 5       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                            | User stays on the page and gets an appropriate error message                  |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                             |
| ---------------- | ------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-10                                          |
| Title            | Verify proceeding to Overview page with empty last name |
| Module / Feature | Checkout                                                |
| Type             | Functional                                              |
| Priority         | P1                                                      |
| Preconditions    | User is logged in and on homepage (Products page)       |
| Test Data        | John / 60311                                            |
| Environment      | https://www.saucedemo.com                               |
| Depends on       | TC-CHECKOUT-01                                          |

---

### Test Steps

| Step No | Action                                                  | Expected Result                                                               |
| ------- | ------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart              | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                            | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid first name empty | First Name field accepts user input                                           |
| 5       | Leave the Last Name field empty                         |                                                                               |
| 6       | Fill the Postal Code field with a valid postal code     | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                | User stays on the page and gets an appropriate error message                  |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                               |
| ---------------- | --------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-11                                            |
| Title            | Verify proceeding to Overview page with empty postal code |
| Module / Feature | Checkout                                                  |
| Type             | Functional                                                |
| Priority         | P1                                                        |
| Preconditions    | User is logged in and on homepage (Products page)         |
| Test Data        | John / Smith                                              |
| Environment      | https://www.saucedemo.com                                 |
| Depends on       | TC-CHECKOUT-01                                            |

---

### Test Steps

| Step No | Action                                                  | Expected Result                                                               |
| ------- | ------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart              | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                            | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid first name empty | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name         | Last Name field accepts user input                                            |
| 6       | Leave the Postal Code field empty                       |                                                                               |
| 7       | Click on Continue button                                | User stays on the page and gets an appropriate error message                  |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                     |
| ---------------- | --------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-12                                                  |
| Title            | Verify Checkout: Overview page has the item details in the cart |
| Module / Feature | Checkout                                                        |
| Type             | Functional                                                      |
| Priority         | P1                                                              |
| Preconditions    | User is logged in and on homepage (Products page)               |
| Test Data        |                                                                 |
| Environment      | https://www.saucedemo.com                                       |
| Depends on       | TC-CHECKOUT-07                                                  |

---

### Test Steps

| Step No | Action                                                  | Expected Result                                                               |
| ------- | ------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart              | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                            | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username         | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name         | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code     | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                | User is navigated to the Overview page                                        |
| 8       | Verify item details of the item on the page are visible | Item details are visible                                                      |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                   |
| ---------------- | ----------------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-13                                                                |
| Title            | Verify Checkout: Overview page has item details of multiple items in the cart |
| Module / Feature | Checkout                                                                      |
| Type             | Functional                                                                    |
| Priority         | P1                                                                            |
| Preconditions    | User is logged in and on homepage (Products page)                             |
| Test Data        |                                                                               |
| Environment      | https://www.saucedemo.com                                                     |
| Depends on       | TC-CHECKOUT-07                                                                |

---

### Test Steps

| Step No | Action                                               | Expected Result                                                               |
| ------- | ---------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart           | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Add the second item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 2            |
| 3       | Click the shopping cart icon                         | User is navigated to Shopping Cart page                                       |
| 4       | Verify both items are in the cart                    | Both items are in the cart                                                    |
| 5       | Click on checkout button                             | User is navigated to first step of checkout (Checkout: Your Information) page |
| 6       | Fill the First Name field with a valid username      | First Name field accepts user input                                           |
| 7       | Fill the Last Name field with a valid last name      | Last Name field accepts user input                                            |
| 8       | Fill the Postal Code field with a valid postal code  | Postal Code field accepts user input                                          |
| 9       | Click on Continue button                             | User is navigated to the Overview page                                        |
| 10      | Verify item details of items on the page are visible | Item details are visible                                                      |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                            |
| ---------------- | ---------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-14                                                         |
| Title            | Verify Checkout: Overview page has the details of the checkout process |
| Module / Feature | Checkout                                                               |
| Type             | Functional                                                             |
| Priority         | P1                                                                     |
| Preconditions    | User is logged in and on homepage (Products page)                      |
| Test Data        |                                                                        |
| Environment      | https://www.saucedemo.com                                              |
| Depends on       | TC-CHECKOUT-07                                                         |

---

### Test Steps

| Step No | Action                                                                    | Expected Result                                                               |
| ------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                              | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                                  | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username                           | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name                           | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code                       | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                                  | User is navigated to the Overview page                                        |
| 8       | Verify Payment Information is visible and present on the page             | Payment Information is visible and present on the page                        |
| 9       | Verify Shipping Information is visible and present on the page            | Shipping Information is visible and present on the page                       |
| 10      | Verify Price information including tax is visible and present on the page | Price information including tax is visible and present on the page            |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                      |
| ---------------- | -------------------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-15                                                                   |
| Title            | Verify Checkout: Overview page has matching item total price with the item value |
| Module / Feature | Checkout                                                                         |
| Type             | Functional                                                                       |
| Priority         | P1                                                                               |
| Preconditions    | User is logged in and on homepage (Products page)                                |
| Test Data        |                                                                                  |
| Environment      | https://www.saucedemo.com                                                        |
| Depends on       | TC-CHECKOUT-07                                                                   |

---

### Test Steps

| Step No | Action                                                              | Expected Result                                                               |
| ------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username                     | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name                     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code                 | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                            | User is navigated to the Overview page                                        |
| 8       | Verify Item total price is matching with the item price in the cart | Prices are matching                                                           |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                              |
| ---------------- | ------------------------------------------------------------------------ |
| Test Case ID     | TC-CHECKOUT-16                                                           |
| Title            | Verify Checkout: Overview page has tax calculated and added up correctly |
| Module / Feature | Checkout                                                                 |
| Type             | Functional                                                               |
| Priority         | P1                                                                       |
| Preconditions    | User is logged in and on homepage (Products page)                        |
| Test Data        |                                                                          |
| Environment      | https://www.saucedemo.com                                                |
| Depends on       | TC-CHECKOUT-07                                                           |

---

### Test Steps

| Step No | Action                                                                                         | Expected Result                                                               |
| ------- | ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                                     | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                                                   | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                                                       | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username                                                | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name                                                | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code                                            | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                                                       | User is navigated to the Overview page                                        |
| 8       | Verify when adding up Item total and Tax price together it gives correct amount of Total price | Item total and Tax price adds up correctly                                    |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                  |
| ---------------- | ------------------------------------------------------------ |
| Test Case ID     | TC-CHECKOUT-17                                               |
| Title            | Verify Checkout: Overview page has Cancel and Finish buttons |
| Module / Feature | Checkout                                                     |
| Type             | Functional                                                   |
| Priority         | P1                                                           |
| Preconditions    | User is logged in and on homepage (Products page)            |
| Test Data        |                                                              |
| Environment      | https://www.saucedemo.com                                    |
| Depends on       | TC-CHECKOUT-07                                               |

---

### Test Steps

| Step No | Action                                                               | Expected Result                                                               |
| ------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                           | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                         | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                             | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username                      | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name                      | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code                  | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                             | User is navigated to the Overview page                                        |
| 8       | Verify Cancel and Finish buttons are visible and present on the page | Cancel and Finish buttons are visible and present on the page                 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                       |
| ---------------- | ------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-18                                    |
| Title            | Verify cancel process on Checkout: Overview page  |
| Module / Feature | Checkout                                          |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-CHECKOUT-07                                    |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                            | User is navigated to the Overview page                                        |
| 8       | Click on Cancel button                              | Checkout process is canceled and user is navigated back to Products page      |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                                    |
| ---------------- | ---------------------------------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-19                                                                                 |
| Title            | Verify Cancel and Finish buttons remain visible with multiple items on Checkout: Overview page |
| Module / Feature | Checkout                                                                                       |
| Type             | Functional                                                                                     |
| Priority         | P1                                                                                             |
| Preconditions    | User is logged in and on homepage (Products page)                                              |
| Test Data        |                                                                                                |
| Environment      | https://www.saucedemo.com                                                                      |
| Depends on       | TC-CHECKOUT-07                                                                                 |

---

### Test Steps

| Step No | Action                                                               | Expected Result                                                               |
| ------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add all the items on the Products page (6)                           | Shopping cart icon gets updated correctly with the icon count of 6            |
| 2       | Click the shopping cart icon                                         | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                             | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username                      | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name                      | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code                  | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                             | User is navigated to the Overview page                                        |
| 8       | Verify Cancel and Finish buttons are visible and present on the page | Cancel and Finish buttons are visible and present on the page                 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                     |
| ---------------- | --------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-20                                                  |
| Title            | Verify finishing the checkout process successfully with an item |
| Module / Feature | Checkout                                                        |
| Type             | Functional                                                      |
| Priority         | P1                                                              |
| Preconditions    | User is logged in and on homepage (Products page)               |
| Test Data        |                                                                 |
| Environment      | https://www.saucedemo.com                                       |
| Depends on       | TC-CHECKOUT-07                                                  |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                            | User is navigated to the Overview page                                        |
| 8       | Click on Finish button                              | User gets notification that the checkout process is successful                |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                            |
| ---------------- | ---------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-21                                                         |
| Title            | Verify finishing the checkout process successfully with multiple items |
| Module / Feature | Checkout                                                               |
| Type             | Functional                                                             |
| Priority         | P1                                                                     |
| Preconditions    | User is logged in and on homepage (Products page)                      |
| Test Data        |                                                                        |
| Environment      | https://www.saucedemo.com                                              |
| Depends on       | TC-CHECKOUT-07                                                         |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Add the second item in the list to the cart         | Shopping cart icon gets updated correctly with the icon count of 2            |
| 3       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 4       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 5       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 6       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 7       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 8       | Click on Continue button                            | User is navigated to the Overview page                                        |
| 9       | Click on Finish button                              | User gets notification that the checkout process is successful                |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                  |
| ---------------- | ---------------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-22                                                               |
| Title            | Verify Back Home button is visible and functional on Checkout: Complete page |
| Module / Feature | Checkout                                                                     |
| Type             | Functional                                                                   |
| Priority         | P1                                                                           |
| Preconditions    | User is logged in and on homepage (Products page)                            |
| Test Data        |                                                                              |
| Environment      | https://www.saucedemo.com                                                    |
| Depends on       | TC-CHECKOUT-07                                                               |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                            | User is navigated to the Overview page                                        |
| 8       | Click on Finish button                              | User gets notification that the checkout process is successful                |
| 9       | Verify Back Home button is visible                  | Back Home button is visible                                                   |
| 10      | Click on Back Home button                           | Back Home button navigates the user to the Products page                      |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                       |
| ---------------- | ------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-23                                    |
| Title            | Verify the cart state after completing checkout   |
| Module / Feature | Checkout                                          |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-CHECKOUT-07                                    |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                            | User is navigated to the Overview page                                        |
| 8       | Click on Finish button                              | User gets notification that the checkout process is successful                |
| 9       | Verify Back Home button is visible                  | Back Home button is visible                                                   |
| 10      | Click on Back Home button                           | Back Home button navigates the user to the Products page                      |
| 11      | Verify if shopping cart is reseted                  | Shopping cart is reseted and does not have any value indicator on it          |
| 12      | Click on shopping cart icon                         | User is navigated to the Shopping Cart page                                   |
| 13      | Verify the state of the shopping cart               | Shopping cart is empty                                                        |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                                 |
| ---------------- | ------------------------------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-24                                                                              |
| Title            | Verify refresh on the Checkout: Your Information page does not get the user out of the page |
| Module / Feature | Checkout                                                                                    |
| Type             | Functional                                                                                  |
| Priority         | P1                                                                                          |
| Preconditions    | User is logged in and on homepage (Products page)                                           |
| Test Data        |                                                                                             |
| Environment      | https://www.saucedemo.com                                                                   |
| Depends on       | TC-SCART-01                                                                                 |

---

### Test Steps

| Step No | Action                                     | Expected Result                                                               |
| ------- | ------------------------------------------ | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon               | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                   | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Refresh the page                           | User remains on the Checkout: Your Information page                           |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                         |
| ---------------- | ----------------------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-25                                                                      |
| Title            | Verify refresh on the Checkout: Overview page does not get the user out of the page |
| Module / Feature | Checkout                                                                            |
| Type             | Functional                                                                          |
| Priority         | P1                                                                                  |
| Preconditions    | User is logged in and on homepage (Products page)                                   |
| Test Data        |                                                                                     |
| Environment      | https://www.saucedemo.com                                                           |
| Depends on       | TC-SCART-01                                                                         |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                            | User is navigated to the Overview page                                        |
| 8       | Refresh the page                                    | User remains on the Checkout: Overview page                                   |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                         |
| ---------------- | ----------------------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-26                                                                      |
| Title            | Verify refresh on the Checkout: Complete page does not get the user out of the page |
| Module / Feature | Checkout                                                                            |
| Type             | Functional                                                                          |
| Priority         | P1                                                                                  |
| Preconditions    | User is logged in and on homepage (Products page)                                   |
| Test Data        |                                                                                     |
| Environment      | https://www.saucedemo.com                                                           |
| Depends on       | TC-SCART-01                                                                         |

---

### Test Steps

| Step No | Action                                              | Expected Result                                                               |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart          | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                        | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                            | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username     | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name     | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                            | User is navigated to the Overview page                                        |
| 8       | Click on Finish button                              | User gets notification that the checkout process is successful                |
| 9       | Refresh the page                                    | User remains on the Checkout: Complete page                                   |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                           |
| ---------------- | --------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-27                                                        |
| Title            | Verify users can indicate they are on Checkout: Your Information page |
| Module / Feature | Checkout                                                              |
| Type             | Functional                                                            |
| Priority         | P3                                                                    |
| Preconditions    | User is logged in and on homepage (Products page)                     |
| Test Data        |                                                                       |
| Environment      | https://www.saucedemo.com                                             |
| Depends on       | TC-CHECKOUT-07                                                        |

---

### Test Steps

| Step No | Action                                                                               | Expected Result                                                               |
| ------- | ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                           | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                                         | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                                             | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Verify if there is a visible text indicating that is Checkout: Your Information page | There is a text indicating this page is Checkout: Your Information page       |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                           |
| ---------------- | --------------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-28                                                        |
| Title            | Verify users can indicate they are on Checkout: Your Information page |
| Module / Feature | Checkout                                                              |
| Type             | Functional                                                            |
| Priority         | P3                                                                    |
| Preconditions    | User is logged in and on homepage (Products page)                     |
| Test Data        |                                                                       |
| Environment      | https://www.saucedemo.com                                             |
| Depends on       | TC-CHECKOUT-07                                                        |

---

### Test Steps

| Step No | Action                                                                       | Expected Result                                                               |
| ------- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                   | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                                 | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                                     | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username                              | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name                              | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code                          | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                                     | User is navigated to the Overview page                                        |
| 8       | Verify if there is a visible text indicating that is Checkout: Overview page | There is a text indicating this page is Checkout: Overview page               |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                   |
| ---------------- | ------------------------------------------------------------- |
| Test Case ID     | TC-CHECKOUT-29                                                |
| Title            | Verify users can indicate they are on Checkout: Complete page |
| Module / Feature | Checkout                                                      |
| Type             | Functional                                                    |
| Priority         | P3                                                            |
| Preconditions    | User is logged in and on homepage (Products page)             |
| Test Data        |                                                               |
| Environment      | https://www.saucedemo.com                                     |
| Depends on       | TC-CHECKOUT-07                                                |

---

### Test Steps

| Step No | Action                                                                       | Expected Result                                                               |
| ------- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                   | Shopping cart icon gets updated correctly with the icon count of 1            |
| 2       | Click the shopping cart icon                                                 | User is navigated to Shopping Cart page                                       |
| 3       | Click on checkout button                                                     | User is navigated to first step of checkout (Checkout: Your Information) page |
| 4       | Fill the First Name field with a valid username                              | First Name field accepts user input                                           |
| 5       | Fill the Last Name field with a valid last name                              | Last Name field accepts user input                                            |
| 6       | Fill the Postal Code field with a valid postal code                          | Postal Code field accepts user input                                          |
| 7       | Click on Continue button                                                     | User is navigated to the Overview page                                        |
| 8       | Click on Finish button                                                       | User gets notification that the checkout process is successful                |
| 9       | Verify if there is a visible text indicating that is Checkout: Complete page | There is a text indicating this page is Checkout: Complete page               |

---

### Actual Result

()

---

### Status

()

---
