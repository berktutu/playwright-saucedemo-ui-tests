# Navbar test cases of SauceDemo

**Note:** Additional test cases, such as using navbar from pages with high risk or security could be included. However, because the navbar works globally and the SauceDemo application does not have any security precautions, extensive or selective testing is not needed.

**Note:** Users can logout using the navbar. The logout functionality is already covered by it's own dedicated test cases. To avoid repetitive testing it will not be covered here.

**Note:** Reset App State is not tested because it is not made for users.

### Test Info

| Field            | Description                                                |
| ---------------- | ---------------------------------------------------------- |
| Test Case ID     | TC-NAVBAR-01                                               |
| Title            | Verify user can navigate to Products page using the navbar |
| Module / Feature | Navbar                                                     |
| Type             | Functional                                                 |
| Priority         | P1                                                         |
| Preconditions    | User is logged in and on homepage (Products page)          |
| Test Data        |                                                            |
| Environment      | https://www.saucedemo.com                                  |

---

### Test Steps

| Step No | Action                                   | Expected Result                     |
| ------- | ---------------------------------------- | ----------------------------------- |
| 1       | Click on the first item on products page | The selected item page is displayed |
| 2       | Click on the navbar                      | Navbar menu is displayed            |
| 3       | Click on the text "All Items"            | User is navigated to Products page  |

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
| Test Case ID     | TC-NAVBAR-02                                            |
| Title            | Verify user can navigate to About page using the navbar |
| Module / Feature | Navbar                                                  |
| Type             | Functional                                              |
| Priority         | P1                                                      |
| Preconditions    | User is logged in                                       |
| Test Data        |                                                         |
| Environment      | https://www.saucedemo.com                               |

---

### Test Steps

| Step No | Action                    | Expected Result                                     |
| ------- | ------------------------- | --------------------------------------------------- |
| 1       | Click on the navbar       | Navbar menu is displayed                            |
| 2       | Click on the text "About" | User is navigated to https://saucelabs.com/ website |

---

### Actual Result

()

---

### Status

()

---
