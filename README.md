# Shopify 2.0 Starter Theme

This project serves as a basic foundation for custom design and build projects on Shopify 2.0. It adheres to the Shopify 2.0 standards and practices and includes essential features required for a Shopify theme.

## Project Structure

The project structure includes the following files and directories:

- `index.json`: JSON template for the homepage.
- `product.json`: JSON template for product details page.
- `collection.json`: JSON template for collections and their filtering options.
- `cart.json`: JSON template for the cart page.
- `account.json`: JSON template for user account-related pages.
- `header-group.json` and `footer-group.json`: JSON templates for the site's header and footer.

All User related inside ``customer`` directory

- `customer/account.json`: JSON template for user account
- `customer/activate_account.json`: JSON template for the customer account activation page
- `customer/addresses.json`: JSON template for the customer addresses page
- `customer/login.json`: JSON template for the customer login page
- `customer/register.json`: JSON template for the customer register page
- `customer/order.json`: JSON template for the customer order page
- `customer/reset_password.json`: JSON template for the password reset page


## Features

1. **Collection Filtering:** Utilizes Shopify's native collection filtering feature for an enhanced user experience.

2. **Search with Suggestions:** Implements Shopify's native search functionality with search suggestions for improved usability.

3. **Dynamic Cart and Mini Cart:** Utilizes the `liquid-ajax-cart.js` library to create a dynamic cart and mini cart with real-time updates of the total.

4. **Vanilla JavaScript File:** Includes a single vanilla JavaScript file for handling all necessary functions.

5. **Vanilla CSS for Filter and Search:** Utilizes vanilla CSS for the filter and search components, maintaining a DRY (Don't Repeat Yourself) code style.

6. **Barebones HTML Structure:** Keeps the HTML structure minimal for improved performance.

7. **Reusable Dynamic Components:** Incorporates reusable dynamic components to ensure the scalability and maintainability of the codebase.

7. **liquid-ajax-cart.js** for ajax cart


## Usage

To use this project as a base for custom design and build projects:

1. Clone the repository.
2. Customize the templates to fit your project's specific requirements.
3. Test the theme thoroughly to ensure its functionality on Shopify 2.0.
4. Deploy the theme to your Shopify store for production use.


## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
