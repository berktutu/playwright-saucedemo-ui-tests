# Item page test cases of SauceDemo

**Note:** Only the presence of item information and product images can be verified, as there is no reference document to prove the correctness of these informations. Accuracy of the data on the page can not be tested.

### Test Info

| Field            | Description                                            |
| ---------------- | ------------------------------------------------------ |
| Test Case ID     | TC-ITEM-01                                             |
| Title            | Verify item page has all contents of the selected item |
| Module / Feature | Items                                                  |
| Type             | Functional                                             |
| Priority         | P1                                                     |
| Preconditions    | User is logged in and on homepage (Products page)      |
| Test Data        |                                                        |
| Environment      | https://www.saucedemo.com                              |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02                         |

---

### Test Steps

| Step No | Action                                               | Expected Result                               |
| ------- | ---------------------------------------------------- | --------------------------------------------- |
| 1       | Click the name of the first product in the list      | User is navigated to the selected item's page |
| 2       | Verify that displayed item has product name          | Item has product name                         |
| 3       | Verify that displayed item has description           | Item has description                          |
| 4       | Verify that displayed item has price                 | Item has price                                |
| 5       | Verify that displayed item has picture               | Item has picture                              |
| 6       | Verify that displayed item has button to add to cart | Item has add to cart button                   |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                               |
| ---------------- | ------------------------------------------------------------------------- |
| Test Case ID     | TC-ITEM-02                                                                |
| Title            | Verify selected product details match between Products page and Item page |
| Module / Feature | Items                                                                     |
| Type             | Functional                                                                |
| Priority         | P1                                                                        |
| Preconditions    | User is logged in and on homepage (Products page)                         |
| Test Data        |                                                                           |
| Environment      | https://www.saucedemo.com                                                 |
| Depends on       | TC-ITEM-01                                                                |

---

### Test Steps

| Step No | Action                                                                                       | Expected Result                               |
| ------- | -------------------------------------------------------------------------------------------- | --------------------------------------------- |
| 1       | Get the product name, description, price and picture of first item in the list               |                                               |
| 2       | Click the name of the first product in the list                                              | User is navigated to the selected item's page |
| 3       | Verify product name, description, price, and image match between Products page and Item page | Item informations are matching                |

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
| Test Case ID     | TC-ITEM-03                                        |
| Title            | Add item into the cart on Item page               |
| Module / Feature | Items                                             |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-ITEM-01                                        |

---

### Test Steps

| Step No | Action                                          | Expected Result                                   |
| ------- | ----------------------------------------------- | ------------------------------------------------- |
| 1       | Click the name of the first product in the list | User is navigated to the selected item's page     |
| 2       | Click on the Add to cart button                 | Add to cart button changes to Remove button       |
| 3       | Click the shopping cart icon                    | Added item is displayed on the shopping cart page |

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
| Test Case ID     | TC-ITEM-04                                        |
| Title            | Remove item from the cart on Item page            |
| Module / Feature | Items                                             |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-ITEM-01                                        |

---

### Test Steps

| Step No | Action                                          | Expected Result                                                   |
| ------- | ----------------------------------------------- | ----------------------------------------------------------------- |
| 1       | Click the name of the first product in the list | User is navigated to the selected item's page                     |
| 2       | Click on the Add to cart button                 | Add to cart button changes to Remove button                       |
| 3       | Click the shopping cart icon                    | Added item is displayed on the shopping cart page                 |
| 4       | Click on Continue Shopping button               | User is navigated back to the products page                       |
| 5       | Click the name of the first product in the list | User is navigated to the selected item's page                     |
| 6       | Click on the Remove button                      | Remove button changes to Add to cart button                       |
| 7       | Click the shopping cart icon                    | The removed item is no longer displayed on the shopping cart page |

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
| Test Case ID     | TC-ITEM-05                                        |
| Title            | Verify Back to products button is visible         |
| Module / Feature | Items                                             |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |

---

### Test Steps

| Step No | Action                                                        | Expected Result                                                 |
| ------- | ------------------------------------------------------------- | --------------------------------------------------------------- |
| 1       | Click the name of the first product in the list               | User is navigated to the selected item's page                   |
| 2       | Verify the presence and visibility of Back to products button | Back to products button is visible and present on the item page |

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
| Test Case ID     | TC-ITEM-06                                                    |
| Title            | Verify user can navigate back to Products page from Item page |
| Module / Feature | Items                                                         |
| Type             | Functional                                                    |
| Priority         | P1                                                            |
| Preconditions    | User is logged in and on homepage (Products page)             |
| Test Data        |                                                               |
| Environment      | https://www.saucedemo.com                                     |
| Depends on       | TC-ITEM-05                                                    |

---

### Test Steps

| Step No | Action                                          | Expected Result                               |
| ------- | ----------------------------------------------- | --------------------------------------------- |
| 1       | Click the name of the first product in the list | User is navigated to the selected item's page |
| 2       | Click on the Back to products button            | User is navigated back to the Products page   |

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
| Test Case ID     | TC-ITEM-07                                              |
| Title            | Verify the state of item page after refreshing the page |
| Module / Feature | Items                                                   |
| Type             | Functional                                              |
| Priority         | P2                                                      |
| Preconditions    | User is logged in and on homepage (Products page)       |
| Test Data        |                                                         |
| Environment      | https://www.saucedemo.com                               |
| Depends on       | TC-ITEM-03                                              |

---

### Test Steps

| Step No | Action                                          | Expected Result                                   |
| ------- | ----------------------------------------------- | ------------------------------------------------- |
| 1       | Click the name of the first product in the list | User is navigated to the selected item's page     |
| 2       | Click on the Add to cart button                 | Add to cart button changes to remove button       |
| 3       | Refresh the page                                | The button and the cart icon remains the same     |
| 4       | Click the shopping cart icon                    | Added item is displayed on the shopping cart page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                          |
| ---------------- | -------------------------------------------------------------------- |
| Test Case ID     | TC-ITEM-08                                                           |
| Title            | Verify the item remains added after navigating back to Products page |
| Module / Feature | Items                                                                |
| Type             | Functional                                                           |
| Priority         | P2                                                                   |
| Preconditions    | User is logged in and on homepage (Products page)                    |
| Test Data        |                                                                      |
| Environment      | https://www.saucedemo.com                                            |
| Depends on       | TC-ITEM-03                                                           |

---

### Test Steps

| Step No | Action                                          | Expected Result                                                      |
| ------- | ----------------------------------------------- | -------------------------------------------------------------------- |
| 1       | Click the name of the first product in the list | User is navigated to the selected item's page                        |
| 2       | Click on the Add to cart button                 | Add to cart button changes to remove button                          |
| 3       | Click on the Back to Products button            | User is navigated back to the Products page                          |
| 4       | Verify the item's state on the Products page    | Previously added item has Remove button on the Products page as well |
| 5       | Click the shopping cart icon                    | Added item is displayed on the shopping cart page                    |

---

### Actual Result

()

---

### Status

()

---
