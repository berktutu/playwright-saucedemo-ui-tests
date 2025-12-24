# Products page test cases of SauceDemo

**Note:** Additional test cases, such as more detailed verification of item information, could be added. But because the SauceDemo is a demo application and the full documentation is not available. Further detailed checks are not possible.

**Note:** Only the presence of item information and product images can be verified, as there is no reference document to prove the correctness of these informations. Accuracy of the data on the page can not be tested.

### Test Info

| Field            | Description                                       |
| ---------------- | ------------------------------------------------- |
| Test Case ID     | TC-PRODUCTS-01                                    |
| Title            | Verify user can view items on Products page       |
| Module / Feature | Products                                          |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |

---

### Test Steps

| Step No | Action                                               | Expected Result                          |
| ------- | ---------------------------------------------------- | ---------------------------------------- |
| 1       | Verify that items are displayed on the Products page | Items are displayed on the Products page |

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
| Test Case ID     | TC-PRODUCTS-02                                    |
| Title            | Verify user can view item informations            |
| Module / Feature | Products                                          |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-PRODUCTS-01                                    |

---

### Test Steps

| Step No | Action                                         | Expected Result          |
| ------- | ---------------------------------------------- | ------------------------ |
| 1       | Verify that displayed items have product names | Items have product names |
| 2       | Verify that displayed items have descriptions  | Items have descriptions  |
| 3       | Verify that displayed items have prices        | Items have prices        |
| 4       | Verify that displayed items have pictures      | Items have pictures      |
| 4       | Verify that displayed items have buttons       | Items have buttons       |

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
| Test Case ID     | TC-PRODUCTS-03                                    |
| Title            | Verify user can add an item on Products page      |
| Module / Feature | Products                                          |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02                    |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                   |
| ------- | -------------------------------------------------------------- | ------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to remove button       |
| 2       | Click the shopping cart icon                                   | Added item is displayed on the shopping cart page |

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
| Test Case ID     | TC-PRODUCTS-04                                                           |
| Title            | Verify Products page state remains the same after going to shopping cart |
| Module / Feature | Products                                                                 |
| Type             | Functional                                                               |
| Priority         | P2                                                                       |
| Preconditions    | User is logged in and on homepage (Products page)                        |
| Test Data        |                                                                          |
| Environment      | https://www.saucedemo.com                                                |
| Depends on       | TC-PRODUCTS-03                                                           |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                     |
| ------- | -------------------------------------------------------------- | --------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to Remove button         |
| 2       | Click the shopping cart icon                                   | Added items are displayed on the shopping cart page |
| 3       | Click on Continue Shopping button                              | User is navigated back to the products page         |
| 4       | Verify if the items are still added                            | Previously added items have Remove button active    |

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
| Test Case ID     | TC-PRODUCTS-05                                    |
| Title            | Verify user can remove an item on Products page   |
| Module / Feature | Products                                          |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-PRODUCTS-03, TC-PRODUCTS-04                    |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                    |
| ------- | -------------------------------------------------------------- | -------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to Remove button        |
| 2       | Click the shopping cart icon                                   | Added item is displayed on the shopping cart page  |
| 3       | Click the Continue Shopping button                             | User is navigated back to Products page            |
| 4       | Click the Remove button for the item that was added            | Remove button changes to Add to cart button        |
| 5       | Click the shopping cart icon                                   | Removed item no longer exists in the shopping cart |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                         |
| ---------------- | --------------------------------------------------- |
| Test Case ID     | TC-PRODUCTS-06                                      |
| Title            | Verify user can add multiple items on Products page |
| Module / Feature | Products                                            |
| Type             | Functional                                          |
| Priority         | P1                                                  |
| Preconditions    | User is logged in and on homepage (Products page)   |
| Test Data        |                                                     |
| Environment      | https://www.saucedemo.com                           |
| Depends on       | TC-PRODUCTS-03                                      |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                     |
| ------- | -------------------------------------------------------------- | --------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to Remove button         |
| 2       | Click the Add to cart button for the last product in the list  | Add to cart button changes to Remove button         |
| 3       | Click the shopping cart icon                                   | Added items are displayed on the shopping cart page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                            |
| ---------------- | ------------------------------------------------------ |
| Test Case ID     | TC-PRODUCTS-07                                         |
| Title            | Verify user can remove multiple items on Products page |
| Module / Feature | Products                                               |
| Type             | Functional                                             |
| Priority         | P1                                                     |
| Preconditions    | User is logged in and on homepage (Products page)      |
| Test Data        |                                                        |
| Environment      | https://www.saucedemo.com                              |
| Depends on       | TC-PRODUCTS-04, TC-PRODUCTS-05                         |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                               |
| ------- | -------------------------------------------------------------- | ------------------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to remove button                   |
| 2       | Click the Add to cart button for the last product in the list  | Add to cart button changes to remove button                   |
| 3       | Click the shopping cart icon                                   | Added items are displayed on the shopping cart page           |
| 4       | Click on Continue Shopping button                              | User is navigated back to the products page                   |
| 5       | Click the Remove button for the both items that were added     | Remove buttons change to Add to cart button                   |
| 6       | Click the shopping cart icon                                   | Added items are no longer displayed on the shopping cart page |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                 |
| ---------------- | ----------------------------------------------------------- |
| Test Case ID     | TC-PRODUCTS-08                                              |
| Title            | Verify the state of Products page after refreshing the page |
| Module / Feature | Products                                                    |
| Type             | Functional                                                  |
| Priority         | P2                                                          |
| Preconditions    | User is logged in and on homepage (Products page)           |
| Test Data        |                                                             |
| Environment      | https://www.saucedemo.com                                   |
| Depends on       | TC-PRODUCTS-03                                              |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                   |
| ------- | -------------------------------------------------------------- | ------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to Remove button       |
| 2       | Refresh the page                                               | The button remains the same as Remove button      |
| 3       | Click the shopping cart icon                                   | Added item is displayed on the shopping cart page |

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
| Test Case ID     | TC-PRODUCTS-09                                                  |
| Title            | Verify the state of Products page after navigating to Item page |
| Module / Feature | Products                                                        |
| Type             | Functional                                                      |
| Priority         | P2                                                              |
| Preconditions    | User is logged in and on homepage (Products page)               |
| Test Data        |                                                                 |
| Environment      | https://www.saucedemo.com                                       |
| Depends on       | TC-PRODUCTS-03, TC-ITEM-01                                      |

---

### Test Steps

| Step No | Action                                                                        | Expected Result                                                                   |
| ------- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| 1       | Click the Add to cart button for the item with the text "Sauce Labs Backpack" | Add to cart button changes to Remove button                                       |
| 2       | Click on the item with the text "Sauce Labs Backpack"                         | User is navigated to the selected item's page                                     |
| 3       | Verify state of the button                                                    | The button remains as Remove                                                      |
| 4       | Click on the Back to Products button                                          | User is navigated back to the Products page                                       |
| 5       | Verify if the Products page state remains the same                            | The product page remains the same. The button for the item is displayed as Remove |
| 6       | Click the shopping cart icon                                                  | Added item is displayed on the shopping cart page                                 |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                         |
| ---------------- | --------------------------------------------------- |
| Test Case ID     | TC-PRODUCTS-10                                      |
| Title            | Verify users can indicate they are on Products page |
| Module / Feature | Products                                            |
| Type             | Functional                                          |
| Priority         | P3                                                  |
| Preconditions    | User is logged in and on homepage (Products page)   |
| Test Data        |                                                     |
| Environment      | https://www.saucedemo.com                           |

---

### Test Steps

| Step No | Action                                                             | Expected Result                                       |
| ------- | ------------------------------------------------------------------ | ----------------------------------------------------- |
| 1       | Verify if there is a visible text indicating that is Products page | There is a text indicating this page is Products page |

---

### Actual Result

()

---

### Status

()

---
