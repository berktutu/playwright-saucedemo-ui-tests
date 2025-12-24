# Shopping cart test cases of SauceDemo

**Note:** Additional test cases, such as adding a large number of items or adding the same item multiple times could be added. However, since SauceDemo is a demo application and does not provide enough items or functionality to add the same item multiple times, further detailed tests are not possible.

### Test Info

| Field            | Description                                                       |
| ---------------- | ----------------------------------------------------------------- |
| Test Case ID     | TC-SCART-01                                                       |
| Title            | Verify shopping cart icon is visible and present on Products page |
| Module / Feature | Shopping Cart                                                     |
| Type             | Functional                                                        |
| Priority         | P1                                                                |
| Preconditions    | User is logged in and on homepage (Products page)                 |
| Test Data        |                                                                   |
| Environment      | https://www.saucedemo.com                                         |

---

### Test Steps

| Step No | Action                                                                        | Expected Result                                                |
| ------- | ----------------------------------------------------------------------------- | -------------------------------------------------------------- |
| 1       | Verify the visibility and presence of the shopping cart icon on Products page | Shopping cart icon is visible and present on the Products page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                      |
| ---------------- | ---------------------------------------------------------------- |
| Test Case ID     | TC-SCART-02                                                      |
| Title            | Verify shopping cart icon is visible and present on an Item page |
| Module / Feature | Shopping Cart                                                    |
| Type             | Functional                                                       |
| Priority         | P1                                                               |
| Preconditions    | User is logged in and on homepage (Products page)                |
| Test Data        |                                                                  |
| Environment      | https://www.saucedemo.com                                        |

---

### Test Steps

| Step No | Action                                                                                   | Expected Result                                                       |
| ------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| 1       | Click on the name of the first item in the list                                          | User is navigated to the selected item's page                         |
| 2       | Verify the visibility and presence of the shopping cart icon on the selected item's page | Shopping cart icon is visible and present on the selected item's page |

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
| Test Case ID     | TC-SCART-03                                                                      |
| Title            | Verify shopping cart icon navigates to Shopping Cart page from the Products Page |
| Module / Feature | Shopping Cart                                                                    |
| Type             | Functional                                                                       |
| Priority         | P1                                                                               |
| Preconditions    | User is logged in and on homepage (Products page)                                |
| Test Data        |                                                                                  |
| Environment      | https://www.saucedemo.com                                                        |
| Depends on       | TC-SCART-01                                                                      |

---

### Test Steps

| Step No | Action                       | Expected Result                         |
| ------- | ---------------------------- | --------------------------------------- |
| 1       | Click the shopping cart icon | User is navigated to Shopping Cart page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                 |
| ---------------- | --------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-04                                                                 |
| Title            | Verify shopping cart icon navigates to Shopping Cart page from an Item Page |
| Module / Feature | Shopping Cart                                                               |
| Type             | Functional                                                                  |
| Priority         | P1                                                                          |
| Preconditions    | User is logged in and on homepage (Products page)                           |
| Test Data        |                                                                             |
| Environment      | https://www.saucedemo.com                                                   |
| Depends on       | TC-SCART-02                                                                 |

---

### Test Steps

| Step No | Action                                       | Expected Result                               |
| ------- | -------------------------------------------- | --------------------------------------------- |
| 1       | Click the name of the first item in the list | User is navigated to the selected item's page |
| 2       | Click the shopping cart icon                 | User is navigated to Shopping Cart page       |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                            |
| ---------------- | -------------------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-05                                                                            |
| Title            | Verify shopping cart icon gets updated correctly after adding an item on Products page |
| Module / Feature | Shopping Cart                                                                          |
| Type             | Functional                                                                             |
| Priority         | P2                                                                                     |
| Preconditions    | User is logged in and on homepage (Products page)                                      |
| Test Data        |                                                                                        |
| Environment      | https://www.saucedemo.com                                                              |
| Depends on       | TC-SCART-01                                                                            |

---

### Test Steps

| Step No | Action                                     | Expected Result                                                    |
| ------- | ------------------------------------------ | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 1 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                                   |
| ---------------- | --------------------------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-06                                                                                   |
| Title            | Verify shopping cart icon gets updated correctly after adding multiple items on Products page |
| Module / Feature | Shopping Cart                                                                                 |
| Type             | Functional                                                                                    |
| Priority         | P2                                                                                            |
| Preconditions    | User is logged in and on homepage (Products page)                                             |
| Test Data        |                                                                                               |
| Environment      | https://www.saucedemo.com                                                                     |
| Depends on       | TC-SCART-01                                                                                   |

---

### Test Steps

| Step No | Action                                      | Expected Result                                                    |
| ------- | ------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart  | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Add the second item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 2 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                              |
| ---------------- | ---------------------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-07                                                                              |
| Title            | Verify shopping cart icon gets updated correctly after removing an item on Products page |
| Module / Feature | Shopping Cart                                                                            |
| Type             | Functional                                                                               |
| Priority         | P2                                                                                       |
| Preconditions    | User is logged in and on homepage (Products page)                                        |
| Test Data        |                                                                                          |
| Environment      | https://www.saucedemo.com                                                                |
| Depends on       | TC-SCART-01                                                                              |

---

### Test Steps

| Step No | Action                                                           | Expected Result                                                    |
| ------- | ---------------------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart                       | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Remove the previously added first item in the list from the cart | Shopping cart icon gets updated correctly with the icon count of 0 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                        |
| ---------------- | ---------------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-08                                                                        |
| Title            | Verify shopping cart icon gets updated correctly when items get removed one by one |
| Module / Feature | Shopping Cart                                                                      |
| Type             | Functional                                                                         |
| Priority         | P2                                                                                 |
| Preconditions    | User is logged in and on homepage (Products page)                                  |
| Test Data        |                                                                                    |
| Environment      | https://www.saucedemo.com                                                          |
| Depends on       | TC-SCART-01                                                                        |

---

### Test Steps

| Step No | Action                                                            | Expected Result                                                    |
| ------- | ----------------------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart                        | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Add the second item in the list to the cart                       | Shopping cart icon gets updated correctly with the icon count of 2 |
| 3       | Remove the previously added first item in the list from the cart  | Shopping cart icon gets updated correctly with the icon count of 1 |
| 4       | Remove the previously added second item in the list from the cart | Shopping cart icon gets updated correctly with the icon count of 0 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                           |
| ---------------- | ------------------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-09                                                                           |
| Title            | Verify shopping cart icon gets updated correctly after adding an item on an item page |
| Module / Feature | Shopping Cart                                                                         |
| Type             | Functional                                                                            |
| Priority         | P2                                                                                    |
| Preconditions    | User is logged in and on homepage (Products page)                                     |
| Test Data        |                                                                                       |
| Environment      | https://www.saucedemo.com                                                             |
| Depends on       | TC-SCART-02                                                                           |

---

### Test Steps

| Step No | Action                                       | Expected Result                                                    |
| ------- | -------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Click the name of the first item in the list | User is navigated to the selected item's page                      |
| 2       | Add the item to the cart                     | Shopping cart icon gets updated correctly with the icon count of 1 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                             |
| ---------------- | --------------------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-10                                                                             |
| Title            | Verify shopping cart icon gets updated correctly after removing an item on an item page |
| Module / Feature | Shopping Cart                                                                           |
| Type             | Functional                                                                              |
| Priority         | P2                                                                                      |
| Preconditions    | User is logged in and on homepage (Products page)                                       |
| Test Data        |                                                                                         |
| Environment      | https://www.saucedemo.com                                                               |
| Depends on       | TC-SCART-02                                                                             |

---

### Test Steps

| Step No | Action                                       | Expected Result                                                    |
| ------- | -------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Click the name of the first item in the list | User is navigated to the selected item's page                      |
| 2       | Add the item to the cart                     | Shopping cart icon gets updated correctly with the icon count of 1 |
| 3       | Remove the item from the cart                | Shopping cart icon gets updated correctly with the icon count of 0 |

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
| Test Case ID     | TC-SCART-11                                                         |
| Title            | Verify the presence of an item that is added from the Products page |
| Module / Feature | Shopping Cart                                                       |
| Type             | Functional                                                          |
| Priority         | P1                                                                  |
| Preconditions    | User is logged in and on homepage (Products page)                   |
| Test Data        |                                                                     |
| Environment      | https://www.saucedemo.com                                           |
| Depends on       | TC-SCART-01                                                         |

---

### Test Steps

| Step No | Action                                                | Expected Result                                                    |
| ------- | ----------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart            | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Click on the shopping cart icon                       | User is navigated to the Shopping Cart page                        |
| 3       | Verify the added item is present in the shopping cart | Added item is present in the shopping cart                         |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                |
| ---------------- | -------------------------------------------------------------------------- |
| Test Case ID     | TC-SCART-12                                                                |
| Title            | Verify the presence of multiple items that is added from the Products page |
| Module / Feature | Shopping Cart                                                              |
| Type             | Functional                                                                 |
| Priority         | P1                                                                         |
| Preconditions    | User is logged in and on homepage (Products page)                          |
| Test Data        |                                                                            |
| Environment      | https://www.saucedemo.com                                                  |
| Depends on       | TC-SCART-01                                                                |

---

### Test Steps

| Step No | Action                                                          | Expected Result                                                    |
| ------- | --------------------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart                      | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Add the second item in the list to the cart                     | Shopping cart icon gets updated correctly with the icon count of 2 |
| 3       | Click on the shopping cart icon                                 | User is navigated to the Shopping Cart page                        |
| 4       | Verify both of the added items are present in the shopping cart | Added items are present in the shopping cart                       |

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
| Test Case ID     | TC-SCART-13                                                     |
| Title            | Verify the presence of an item that is added from the Item page |
| Module / Feature | Shopping Cart                                                   |
| Type             | Functional                                                      |
| Priority         | P1                                                              |
| Preconditions    | User is logged in and on homepage (Products page)               |
| Test Data        |                                                                 |
| Environment      | https://www.saucedemo.com                                       |
| Depends on       | TC-SCART-02                                                     |

---

### Test Steps

| Step No | Action                                                | Expected Result                                                    |
| ------- | ----------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Click the name of the first item in the list          | User is navigated to the selected item's page                      |
| 2       | Add the selected item into the cart                   | Shopping cart icon gets updated correctly with the icon count of 1 |
| 3       | Click on the shopping cart icon                       | User is navigated to the Shopping Cart page                        |
| 4       | Verify the added item is present in the shopping cart | Added item is present in the shopping cart                         |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                    |
| ---------------- | -------------------------------------------------------------- |
| Test Case ID     | TC-SCART-14                                                    |
| Title            | Verify the presence of contents of an added item into the cart |
| Module / Feature | Shopping Cart                                                  |
| Type             | Functional                                                     |
| Priority         | P1                                                             |
| Preconditions    | User is logged in and on homepage (Products page)              |
| Test Data        |                                                                |
| Environment      | https://www.saucedemo.com                                      |
| Depends on       | TC-SCART-11                                                    |

---

### Test Steps

| Step No | Action                                                                                 | Expected Result                                                                     |
| ------- | -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| 1       | Add the first item in the list to the cart                                             | Shopping cart icon gets updated correctly with the icon count of 1                  |
| 2       | Click on the shopping cart icon                                                        | User is navigated to the Shopping Cart page                                         |
| 3       | Verify the presence of name, description, price and a remove button for the added item | Added item has name, description, price and remove button on the Shopping Cart page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                           |
| ---------------- | ----------------------------------------------------- |
| Test Case ID     | TC-SCART-15                                           |
| Title            | Verify added item contents match in the shopping cart |
| Module / Feature | Shopping Cart                                         |
| Type             | Functional                                            |
| Priority         | P1                                                    |
| Preconditions    | User is logged in and on homepage (Products page)     |
| Test Data        |                                                       |
| Environment      | https://www.saucedemo.com                             |
| Depends on       | TC-SCART-11                                           |

---

### Test Steps

| Step No | Action                                                                    | Expected Result                                                    |
| ------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Get the product name, description and price of first item in the list     |                                                                    |
| 2       | Add the first item in the list to the cart                                | Shopping cart icon gets updated correctly with the icon count of 1 |
| 3       | Click on the shopping cart icon                                           | User is navigated to the Shopping Cart page                        |
| 4       | Verify if the content of the added item is same on the Shopping Cart page | Added item has same name, description and price                    |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                        |
| ---------------- | ------------------------------------------------------------------ |
| Test Case ID     | TC-SCART-16                                                        |
| Title            | Verify multiple items are displayed correctly in the shopping cart |
| Module / Feature | Shopping Cart                                                      |
| Type             | Functional                                                         |
| Priority         | P1                                                                 |
| Preconditions    | User is logged in and on homepage (Products page)                  |
| Test Data        |                                                                    |
| Environment      | https://www.saucedemo.com                                          |
| Depends on       | TC-SCART-12                                                        |

---

### Test Steps

| Step No | Action                                                                     | Expected Result                                                    |
| ------- | -------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Get the product name, description and price of first item in the list      |                                                                    |
| 2       | Add the first item in the list to the cart                                 | Shopping cart icon gets updated correctly with the icon count of 1 |
| 3       | Get the product name, description and price of the second item in the list |                                                                    |
| 4       | Add the second item in the list to the cart                                | Shopping cart icon gets updated correctly with the icon count of 2 |
| 5       | Click on the shopping cart icon                                            | User is navigated to the Shopping Cart page                        |
| 6       | Verify both items have their unique matching name, description and price   | Added item has same name, description and price                    |

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
| Test Case ID     | TC-SCART-17                                                            |
| Title            | Verify shopping cart icon is visible and present on Shopping Cart page |
| Module / Feature | Shopping Cart                                                          |
| Type             | Functional                                                             |
| Priority         | P2                                                                     |
| Preconditions    | User is logged in and on homepage (Products page)                      |
| Test Data        |                                                                        |
| Environment      | https://www.saucedemo.com                                              |
| Depends on       | TC-SCART-03                                                            |

---

### Test Steps

| Step No | Action                                                                             | Expected Result                                                     |
| ------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| 1       | Click the shopping cart icon                                                       | User is navigated to Shopping Cart page                             |
| 2       | Verify the visibility and presence of the shopping cart icon on Shopping Cart page | Shopping cart icon is visible and present on the Shopping Cart page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                                          |
| ---------------- | ------------------------------------------------------------------------------------ |
| Test Case ID     | TC-SCART-18                                                                          |
| Title            | Verify the visibility and presence of Continue Shopping button on Shopping Cart page |
| Module / Feature | Shopping Cart                                                                        |
| Type             | Functional                                                                           |
| Priority         | P1                                                                                   |
| Preconditions    | User is logged in and on homepage (Products page)                                    |
| Test Data        |                                                                                      |
| Environment      | https://www.saucedemo.com                                                            |
| Depends on       | TC-SCART-03                                                                          |

---

### Test Steps

| Step No | Action                                                                                   | Expected Result                                                           |
| ------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 1       | Click the shopping cart icon                                                             | User is navigated to Shopping Cart page                                   |
| 2       | Verify the visibility and presence of the Continue Shopping button on Shopping Cart page | Continue Shopping button is visible and present on the Shopping Cart page |

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
| Test Case ID     | TC-SCART-19                                       |
| Title            | Verify removing an item on the Shopping Cart page |
| Module / Feature | Shopping Cart                                     |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-SCART-11                                       |

---

### Test Steps

| Step No | Action                                     | Expected Result                                                    |
| ------- | ------------------------------------------ | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Click the shopping cart icon               | User is navigated to Shopping Cart page                            |
| 3       | Click the Remove button for the added item | Item is removed from the Shopping Cart                             |

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
| Test Case ID     | TC-SCART-20                                              |
| Title            | Verify removing multiple items on the Shopping Cart page |
| Module / Feature | Shopping Cart                                            |
| Type             | Functional                                               |
| Priority         | P1                                                       |
| Preconditions    | User is logged in and on homepage (Products page)        |
| Test Data        |                                                          |
| Environment      | https://www.saucedemo.com                                |
| Depends on       | TC-SCART-11                                              |

---

### Test Steps

| Step No | Action                                                        | Expected Result                                                    |
| ------- | ------------------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart                    | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Add the second item in the list to the cart                   | Shopping cart icon gets updated correctly with the icon count of 2 |
| 3       | Click the shopping cart icon                                  | User is navigated to Shopping Cart page                            |
| 4       | Click the Remove button for the first item in the list        | The correct item is removed from the Shopping Cart                 |
| 5       | Click the Remove button for the item that is left in the list | The remaining item is removed from the Shopping Cart               |

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
| Test Case ID     | TC-SCART-21                                                         |
| Title            | Verify Checkout button is visible and present on Shopping Cart page |
| Module / Feature | Shopping Cart                                                       |
| Type             | Functional                                                          |
| Priority         | P1                                                                  |
| Preconditions    | User is logged in and on homepage (Products page)                   |
| Test Data        |                                                                     |
| Environment      | https://www.saucedemo.com                                           |
| Depends on       | TC-SCART-03                                                         |

---

### Test Steps

| Step No | Action                                                | Expected Result                                    |
| ------- | ----------------------------------------------------- | -------------------------------------------------- |
| 1       | Click the shopping cart icon                          | User is navigated to Shopping Cart page            |
| 2       | Verify the visibility and presence of Checkout button | Checkout button is visible and present on the page |

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
| Test Case ID     | TC-SCART-22                                                                                    |
| Title            | Verify Checkout and Continue Shopping buttons remain visible when cart contains multiple items |
| Module / Feature | Shopping Cart                                                                                  |
| Type             | Functional                                                                                     |
| Priority         | P1                                                                                             |
| Preconditions    | User is logged in and on homepage (Products page)                                              |
| Test Data        |                                                                                                |
| Environment      | https://www.saucedemo.com                                                                      |
| Depends on       | TC-SCART-03                                                                                    |

---

### Test Steps

| Step No | Action                                                | Expected Result                                                      |
| ------- | ----------------------------------------------------- | -------------------------------------------------------------------- |
| 1       | Add all the items on the Products page (6)            | Shopping cart icon gets updated correctly with the icon count of 6   |
| 2       | Verify the visibility and presence of Checkout button | Checkout button is visible and present on the page without a problem |

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
| Test Case ID     | TC-SCART-23                                                           |
| Title            | Verify shopping cart state remains the same after refreshing the page |
| Module / Feature | Shopping Cart                                                         |
| Type             | Functional                                                            |
| Priority         | P1                                                                    |
| Preconditions    | User is logged in and on homepage (Products page)                     |
| Test Data        |                                                                       |
| Environment      | https://www.saucedemo.com                                             |
| Depends on       | TC-SCART-03                                                           |

---

### Test Steps

| Step No | Action                                                    | Expected Result                                                    |
| ------- | --------------------------------------------------------- | ------------------------------------------------------------------ |
| 1       | Add the first item in the list to the cart                | Shopping cart icon gets updated correctly with the icon count of 1 |
| 2       | Click the shopping cart icon                              | User is navigated to Shopping Cart page                            |
| 3       | Verify the shopping cart has the item that has been added | Shopping cart has the item displayed                               |
| 4       | Refresh the page                                          | Shopping cart state remains the same                               |

### Test Info

| Field            | Description                                              |
| ---------------- | -------------------------------------------------------- |
| Test Case ID     | TC-SCART-24                                              |
| Title            | Verify users can indicate they are on Shopping Cart page |
| Module / Feature | Shopping Cart                                            |
| Type             | Functional                                               |
| Priority         | P3                                                       |
| Preconditions    | User is logged in and on homepage (Products page)        |
| Test Data        |                                                          |
| Environment      | https://www.saucedemo.com                                |

---

### Test Steps

| Step No | Action                                                                     | Expected Result                                            |
| ------- | -------------------------------------------------------------------------- | ---------------------------------------------------------- |
| 1       | Click the shopping cart icon                                               | User is navigated to Shopping Cart page                    |
| 2       | Verify if there is a visible text indicating you are on Shopping Cart page | There is a text indicating this page is Shopping Cart page |

---

### Actual Result

()

---

### Status

()

---
