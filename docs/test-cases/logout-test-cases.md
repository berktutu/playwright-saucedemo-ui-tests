# Logout Functionality test cases of SauceDemo

**Note:** Additional test cases, such as logging out from pages with high risk or security could be included. However, because the logout functionality is global and the SauceDemo application does not have any security precautions, extensive or selective testing is not needed.

### Test Info

| Field            | Description               |
| ---------------- | ------------------------- |
| Test Case ID     | TC-LOGOUT-01              |
| Title            | Verify user is logged out |
| Module / Feature | Logout                    |
| Type             | Functional                |
| Priority         | P1                        |
| Preconditions    | User is logged in         |
| Test Data        |                           |
| Environment      | https://www.saucedemo.com |

---

### Test Steps

| Step No | Action              | Expected Result                                                    |
| ------- | ------------------- | ------------------------------------------------------------------ |
| 1       | Click on the navbar | Navbar menu is displayed                                           |
| 2       | Click on Logout     | User is logged out from the account and is navigated to login page |

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
| Test Case ID     | TC-LOGOUT-02                                                                             |
| Title            | Verify user can not access the application using back button on the browser after logout |
| Module / Feature | Logout                                                                                   |
| Type             | Functional                                                                               |
| Priority         | P1                                                                                       |
| Preconditions    | User is logged in                                                                        |
| Test Data        |                                                                                          |
| Environment      | https://www.saucedemo.com                                                                |

---

### Test Steps

| Step No | Action                        | Expected Result                                                               |
| ------- | ----------------------------- | ----------------------------------------------------------------------------- |
| 1       | Click on the navbar           | Navbar menu is displayed                                                      |
| 2       | Click on Logout               | User is logged out from the account and is navigated to login page            |
| 3       | Click the browser back button | User is not navigated back into the application and recieves an error message |

---

### Actual Result

()

---

### Status

()

---
