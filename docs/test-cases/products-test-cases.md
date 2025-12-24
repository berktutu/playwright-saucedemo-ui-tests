# Products page test cases of SauceDemo

**Note:** Additional test cases, such as more detailed verification of item information, could be added. But because the SauceDemo is a demo application and the full documentation is not available. Further detailed checks are not possible.

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

---

### Test Steps

| Step No | Action                                                | Expected Result                 |
| ------- | ----------------------------------------------------- | ------------------------------- |
| 1       | Verify that displayed items have correct product name | Items have correct product name |
| 2       | Verify that displayed items have correct description  | Items have correct description  |
| 3       | Verify that displayed items have correct price        | Items have correct price        |
| 4       | Verify that displayed items have correct picture      | Items have correct picture      |

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
| Depends on       | TC-PRODUCTS-01                                    |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                                                           |
| ------- | -------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to remove button and shopping cart icon gets updated correctly |
| 2       | Click the shopping cart icon                                   | Added item is displayed on the shopping cart page                                         |

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
| Test Case ID     | TC-PRODUCTS-04                                    |
| Title            | Verify user can remove an item on Products page   |
| Module / Feature | Products                                          |
| Type             | Functional                                        |
| Priority         | P1                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-03                    |

---

### Test Steps

| Step No | Action                                                         | Expected Result                                                                           |
| ------- | -------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| 1       | Click the Add to cart button for the first product in the list | Add to cart button changes to remove button and shopping cart icon gets updated correctly |
| 2       | Click the shopping cart icon                                   | Added item is displayed on the shopping cart page                                         |
| 3       | Click the Continue Shopping button                             | User is navigated back to Products page                                                   |
| 4       | Click the Remove button for the item that was added            | Remove button changes to Add to cart button and shopping cart gets updated correctly      |
| 5       | Click the shopping cart icon                                   | Removed item no longer exists in the shopping cart                                        |

---

### Actual Result

()

---

### Status

()

---
