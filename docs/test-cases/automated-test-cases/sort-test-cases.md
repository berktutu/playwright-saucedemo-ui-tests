# Sort functionality test cases of SauceDemo

### Test Info

| Field            | Description                                       |
| ---------------- | ------------------------------------------------- |
| Test Case ID     | TC-SORT-01                                        |
| Title            | Verify sort dropdown is visible                   |
| Module / Feature | Sort                                              |
| Type             | Functional                                        |
| Priority         | P2                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |

---

### Test Steps

| Step No | Action                          | Expected Result          |
| ------- | ------------------------------- | ------------------------ |
| 1       | Verify sort dropdown is visible | Sort dropdown is visible |

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
| Test Case ID     | TC-SORT-02                                        |
| Title            | Verify sort dropdown has correct sorting options  |
| Module / Feature | Sort                                              |
| Type             | Functional                                        |
| Priority         | P2                                                |
| Preconditions    | User is logged in and on homepage (Products page) |
| Test Data        |                                                   |
| Environment      | https://www.saucedemo.com                         |
| Depends on       | TC-SORT-01                                        |

---

### Test Steps

| Step No | Action                                   | Expected Result                                                                 |
| ------- | ---------------------------------------- | ------------------------------------------------------------------------------- |
| 1       | Click on the sort dropdown               | Drowpdown list is displayed                                                     |
| 2       | Verify all correct sorting options exist | Options Name A to Z, Name Z to A, Price low to high and Price high to low exist |

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
| Test Case ID     | TC-SORT-03                                             |
| Title            | Verify sorting items A to Z                            |
| Module / Feature | Sort                                                   |
| Type             | Functional                                             |
| Priority         | P2                                                     |
| Preconditions    | User is logged in and on homepage (Products page)      |
| Test Data        |                                                        |
| Environment      | https://www.saucedemo.com                              |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02, TC-SORT-01, TC-SORT-02 |

---

### Test Steps

| Step No | Action                                            | Expected Result                        |
| ------- | ------------------------------------------------- | -------------------------------------- |
| 1       | Click on the sort dropdown                        | Drowpdown list is displayed            |
| 2       | Click on the option with the text "Name (Z to A)" | Items are listed Z to A alphabetically |
| 3       | Click on the sort dropdown                        | Drowpdown list is displayed            |
| 4       | Click on the option with the text "Name (A to Z)" | Items are listed A to Z alphabetically |

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
| Test Case ID     | TC-SORT-04                                             |
| Title            | Verify sorting items Z to A                            |
| Module / Feature | Sort                                                   |
| Type             | Functional                                             |
| Priority         | P2                                                     |
| Preconditions    | User is logged in and on homepage (Products page)      |
| Test Data        |                                                        |
| Environment      | https://www.saucedemo.com                              |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02, TC-SORT-01, TC-SORT-02 |

---

### Test Steps

| Step No | Action                                            | Expected Result                        |
| ------- | ------------------------------------------------- | -------------------------------------- |
| 1       | Click on the sort dropdown                        | Drowpdown list is displayed            |
| 2       | Click on the option with the text "Name (Z to A)" | Items are listed Z to A alphabetically |

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
| Test Case ID     | TC-SORT-05                                             |
| Title            | Verify sorting items low to high price                 |
| Module / Feature | Sort                                                   |
| Type             | Functional                                             |
| Priority         | P2                                                     |
| Preconditions    | User is logged in and on homepage (Products page)      |
| Test Data        |                                                        |
| Environment      | https://www.saucedemo.com                              |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02, TC-SORT-01, TC-SORT-02 |

---

### Test Steps

| Step No | Action                                                  | Expected Result                    |
| ------- | ------------------------------------------------------- | ---------------------------------- |
| 1       | Click on the sort dropdown                              | Drowpdown list is displayed        |
| 2       | Click on the option with the text "Price (low to high)" | Items are listed low to high price |

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
| Test Case ID     | TC-SORT-06                                             |
| Title            | Verify sorting items high to low price                 |
| Module / Feature | Sort                                                   |
| Type             | Functional                                             |
| Priority         | P2                                                     |
| Preconditions    | User is logged in and on homepage (Products page)      |
| Test Data        |                                                        |
| Environment      | https://www.saucedemo.com                              |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02, TC-SORT-01, TC-SORT-02 |

---

### Test Steps

| Step No | Action                                                  | Expected Result                    |
| ------- | ------------------------------------------------------- | ---------------------------------- |
| 1       | Click on the sort dropdown                              | Drowpdown list is displayed        |
| 2       | Click on the option with the text "Price (high to low)" | Items are listed high to low price |

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
| Test Case ID     | TC-SORT-07                                                               |
| Title            | Verify sorting option remains the same after adding and removing an item |
| Module / Feature | Sort                                                                     |
| Type             | Functional                                                               |
| Priority         | P2                                                                       |
| Preconditions    | User is logged in and on homepage (Products page)                        |
| Test Data        |                                                                          |
| Environment      | https://www.saucedemo.com                                                |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02, TC-SORT-01, TC-SORT-02                   |

---

### Test Steps

| Step No | Action                                                  | Expected Result                                     |
| ------- | ------------------------------------------------------- | --------------------------------------------------- |
| 1       | Click on the sort dropdown                              | Drowpdown list is displayed                         |
| 2       | Click on the option with the text "Price (high to low)" | Items are listed high to low price                  |
| 3       | Click Add to cart button for one of the items           | Item is added and sorting option remains the same   |
| 4       | Click Remove button for the added item                  | Item is removed and sorting option remains the same |

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
| Test Case ID     | TC-SORT-08                                                   |
| Title            | Verify sorting option works correctly after multiple changes |
| Module / Feature | Sort                                                         |
| Type             | Functional                                                   |
| Priority         | P2                                                           |
| Preconditions    | User is logged in and on homepage (Products page)            |
| Test Data        |                                                              |
| Environment      | https://www.saucedemo.com                                    |
| Depends on       | TC-PRODUCTS-01, TC-PRODUCTS-02, TC-SORT-01, TC-SORT-02       |

---

### Test Steps

| Step No | Action                                                  | Expected Result                        |
| ------- | ------------------------------------------------------- | -------------------------------------- |
| 1       | Click on the sort dropdown                              | Drowpdown list is displayed            |
| 2       | Click on the option with the text "Name (Z to A)"       | Items are listed Z to A alphabetically |
| 3       | Click on the sort dropdown                              | Drowpdown list is displayed            |
| 4       | Click on the option with the text "Name (A to Z)"       | Items are listed A to Z alphabetically |
| 5       | Click on the sort dropdown                              | Drowpdown list is displayed            |
| 6       | Click on the option with the text "Price (low to high)" | Items are listed low to high price     |
| 7       | Click on the sort dropdown                              | Drowpdown list is displayed            |
| 8       | Click on the option with the text "Price (high to low)" | Items are listed high to low price     |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                                |
| ---------------- | ---------------------------------------------------------- |
| Test Case ID     | TC-SORT-09                                                 |
| Title            | Verify sort dropdown container has dropdown indicator icon |
| Module / Feature | Sort                                                       |
| Type             | Functional                                                 |
| Priority         | P3                                                         |
| Preconditions    | User is logged in and on homepage (Products page)          |
| Test Data        |                                                            |
| Environment      | https://www.saucedemo.com                                  |
| Depends on       | TC-SORT-01                                                 |

---

### Test Steps

| Step No | Action                                                     | Expected Result                         |
| ------- | ---------------------------------------------------------- | --------------------------------------- |
| 1       | Verify sort dropdown container has dropdown indicator icon | Sort dropdown indicator icon is present |

---

### Actual Result

()

---

### Status

()

---
