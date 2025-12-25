# Functional Requirements of SauceDemo

The requirements are based on exploration and observed application behaviour.

### FR-01: Login

- **FR-01.1** Users can log in using valid credentials.
- **FR-01.2** Login is rejected when invalid credentials are provided.
- **FR-01.3** Login is rejected when required credentials are missing.
- **FR-01.4** An appropriate error message is displayed when login fails.
- **FR-01.5** Written password on login page should be masked.
- **FR-01.6** Users should be able to complete login process while using the keyboard only.

### FR-02: Logout

- **FR-02.1** Users who are logged in can log out of the application.
- **FR-02.2** After the logout user is redirected to the login page.

### FR-03: Navigation Bar

- **FR-03.1** The navigation bar is interactable (it can be opened and closed).
- **FR-03.2** Users can navigate to listed pages using the navigation bar. (About, All Items)
- **FR-03.3** The logout option is available in the navigation bar list.

### FR-04: Products Page

- **FR-04.1** A list of products is displayed.
- **FR-04.2** Product details including name, price, picture and description are displayed.
- **FR-04.3** Products can be added to the shopping cart from the product catalog.
- **FR-04.4** Products can be removed from the shopping cart.

### FR-05: Product Sorting

- **FR-05.1** Product sorting function is visible and accessible.
- **FR-05.2** Products can be sorted alphabetically from A to Z.
- **FR-05.3** Products can be sorted alphabetically from Z to A.
- **FR-05.4** Products can be sorted by price from low to high.
- **FR-05.5** Products can be sorted by price from high to low.
- **FR-05.6** The list of products are updated according to the sorting choice.

### FR-06: Item Page

- **FR-06.1** Users can open the selected item's page from the Products page.
- **FR-06.2** Product details including name, price, picture and description are displayed.
- **FR-06.3** A product can be added to the shopping cart from the item page.
- **FR-06.4** A product can be removed from the shopping cart from the item page.
- **FR-06.5** Users can navigate back to the Products page from the item page.

### FR-07: Shopping Cart

- **FR-07.1** Shopping cart icon is interactable.
- **FR-07.2** The shopping cart icon displays the correct number of items.
- **FR-07.3** Shopping cart icon navigates users to Shopping Cart page.
- **FR-07.4** The shopping cart displays the correct products.
- **FR-07.5** Users can see the contents of the added items in the shopping cart.
- **FR-07.6** Users can continue shopping from the shopping cart page.
- **FR-07.7** Checkout button exists on the Shopping Cart page.

### FR-08: Checkout

- **FR-08.1** The checkout process can be started from the shopping cart while having at least one item in the cart.
- **FR-08.2** User information is required to proceed with checkout.
- **FR-08.3** Checkout progression is blocked when required informations are missing.
- **FR-08.4** An appropriate error message is displayed when required checkout information is missing.
- **FR-08.5** An order overview is displayed before checkout completion.
- **FR-08.6** Users can view their item details in the cart, payment information, shipping information and price information including tax.
- **FR-08.7** The checkout process can be completed successfully.
- **FR-08.8** A confirmation message is displayed after successful checkout.
- **FR-08.9** The user can return to the product page after checkout completion.
