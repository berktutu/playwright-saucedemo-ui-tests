# Login Functionality test cases of SauceDemo

### Test Info

| Field            | Description                  |
| ---------------- | ---------------------------- |
| Test Case ID     | TC-LOGIN-01                  |
| Title            | Login with valid credentials |
| Module / Feature | Login                        |
| Type             | Functional                   |
| Priority         | P1                           |
| Preconditions    | User is on login page        |
| Test Data        | standard_user / secret_sauce |
| Environment      | https://www.saucedemo.com    |

---

### Test Steps

| Step No | Action                                                     | Expected Result                                                           |
| ------- | ---------------------------------------------------------- | ------------------------------------------------------------------------- |
| 1       | Navigate to https://www.saucedemo.com                      | Login page is displayed                                                   |
| 2       | Enter valid credentials in the username and password field | Input fields allow user input and password field masks the entered value. |
| 3       | Click the Login button                                     | User is logged in and navigated to the Products page                      |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                 |
| ---------------- | --------------------------- |
| Test Case ID     | TC-LOGIN-02                 |
| Title            | Login with invalid password |
| Module / Feature | Login                       |
| Type             | Functional                  |
| Priority         | P1                          |
| Preconditions    | User is on login page       |
| Test Data        | standard_user / invalidpw   |
| Environment      | https://www.saucedemo.com   |

---

### Test Steps

| Step No | Action                                                                                     | Expected Result                                                          |
| ------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| 1       | Navigate to https://www.saucedemo.com                                                      | Login page is displayed                                                  |
| 2       | Enter a valid username in the username field and an invalid password in the password field | Input fields allow user input and password field masks the entered value |
| 3       | Click the Login button                                                                     | User remains on the login page and receives an appropriate error message |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                   |
| ---------------- | ----------------------------- |
| Test Case ID     | TC-LOGIN-03                   |
| Title            | Login with invalid username   |
| Module / Feature | Login                         |
| Type             | Functional                    |
| Priority         | P1                            |
| Preconditions    | User is on login page         |
| Test Data        | standard_user1 / secret_sauce |
| Environment      | https://www.saucedemo.com     |

---

### Test Steps

| Step No | Action                                                                                     | Expected Result                                                              |
| ------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| 1       | Navigate to https://www.saucedemo.com                                                      | Login page is displayed                                                      |
| 2       | Enter an invalid username in the username field and a valid password in the password field | Input fields allow user input and the password field masks the entered value |
| 3       | Click the Login button                                                                     | User remains on the login page and receives an appropriate error message     |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                    |
| ---------------- | ------------------------------ |
| Test Case ID     | TC-LOGIN-04                    |
| Title            | Login with invalid credentials |
| Module / Feature | Login                          |
| Type             | Functional                     |
| Priority         | P1                             |
| Preconditions    | User is on login page          |
| Test Data        | standard_user1 / invalidpw     |
| Environment      | https://www.saucedemo.com      |

---

### Test Steps

| Step No | Action                                                        | Expected Result                                                          |
| ------- | ------------------------------------------------------------- | ------------------------------------------------------------------------ |
| 1       | Navigate to https://www.saucedemo.com                         | Login page is displayed                                                  |
| 2       | Enter invalid credentials in the username and password fields | Input fields allow user input and password field masks the entered value |
| 3       | Click the Login button                                        | User remains on the login page and receives an appropriate error message |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                  |
| ---------------- | -------------------------------------------- |
| Test Case ID     | TC-LOGIN-05                                  |
| Title            | Login with empty username and valid password |
| Module / Feature | Login                                        |
| Type             | Functional                                   |
| Priority         | P1                                           |
| Preconditions    | User is on login page                        |
| Test Data        | secret_sauce                                 |
| Environment      | https://www.saucedemo.com                    |

---

### Test Steps

| Step No | Action                                                                        | Expected Result                                                             |
| ------- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 1       | Navigate to https://www.saucedemo.com                                         | Login page is displayed                                                     |
| 2       | Leave the username field empty and enter valid password in the password field | Password field allows user input and password field masks the entered value |
| 3       | Click the Login button                                                        | User remains on the login page and receives an appropriate error message    |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                  |
| ---------------- | -------------------------------------------- |
| Test Case ID     | TC-LOGIN-06                                  |
| Title            | Login with valid username and empty password |
| Module / Feature | Login                                        |
| Type             | Functional                                   |
| Priority         | P1                                           |
| Preconditions    | User is on login page                        |
| Test Data        | standard_user                                |
| Environment      | https://www.saucedemo.com                    |

---

### Test Steps

| Step No | Action                                                                        | Expected Result                                                          |
| ------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| 1       | Navigate to https://www.saucedemo.com                                         | Login page is displayed                                                  |
| 2       | Enter valid username in the username field and leave the password field empty | Username field allows user input                                         |
| 3       | Click the Login button                                                        | User remains on the login page and receives an appropriate error message |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                  |
| ---------------- | -------------------------------------------- |
| Test Case ID     | TC-LOGIN-07                                  |
| Title            | Login with empty username and empty password |
| Module / Feature | Login                                        |
| Type             | Functional                                   |
| Priority         | P1                                           |
| Preconditions    | User is on login page                        |
| Test Data        | N/A                                          |
| Environment      | https://www.saucedemo.com                    |

---

### Test Steps

| Step No | Action                                                | Expected Result                                                          |
| ------- | ----------------------------------------------------- | ------------------------------------------------------------------------ |
| 1       | Navigate to https://www.saucedemo.com                 | Login page is displayed                                                  |
| 2       | Leave the username field and the password field empty |                                                                          |
| 3       | Click the Login button                                | User remains on the login page and receives an appropriate error message |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                  |
| ---------------- | -------------------------------------------- |
| Test Case ID     | TC-LOGIN-08                                  |
| Title            | Verify password field masks input characters |
| Module / Feature | Login                                        |
| Type             | Functional                                   |
| Priority         | P1                                           |
| Preconditions    | User is on login page                        |
| Test Data        | secret_sauce                                 |
| Environment      | https://www.saucedemo.com                    |

---

### Test Steps

| Step No | Action                                     | Expected Result         |
| ------- | ------------------------------------------ | ----------------------- |
| 1       | Navigate to https://www.saucedemo.com      | Login page is displayed |
| 2       | Enter the password into the password field | Password is masked      |

---

### Actual Result

()

---

### Status

()

---

### Test Info

| Field            | Description                                      |
| ---------------- | ------------------------------------------------ |
| Test Case ID     | TC-LOGIN-09                                      |
| Title            | Login with valid credentials using only keyboard |
| Module / Feature | Login                                            |
| Type             | Functional                                       |
| Priority         | P3                                               |
| Preconditions    | User is on login page                            |
| Test Data        | standard_user / secret_sauce                     |
| Environment      | https://www.saucedemo.com                        |

---

### Test Steps

| Step No | Action                                                                              | Expected Result                                                                                   |
| ------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| 1       | Navigate to https://www.saucedemo.com                                               | Login page is displayed                                                                           |
| 2       | Enter valid credentials in the username and password fields using only the keyboard | Tab order is correct and input fields allow user input and password field masks the entered value |
| 3       | Press enter for login                                                               | User is logged in and navigated to Products page                                                  |

---

### Actual Result

()

---

### Status

()

---

**Note:** Additional test cases, such as entering special characters, performing multiple invalid login attempts, and verifying session timeout, could be included. However, since the SauceDemo application does not support these functionalities, these cases cannot be executed.
