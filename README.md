Rainy Days - Interactive Online Store 🌧️
This project is part of my JavaScript 1 - Course Assignment. The task was to build an interactive online store that fetches product data from an API and allows users to browse products, filter them by categories, and add/remove items from their shopping basket. The focus of the assignment is on the dynamic functionality provided by JavaScript and effective use of asynchronous actions (API calls).
🚀 Overview
Rainy Days is a responsive online store built for users to explore a collection of rain gear products. The website dynamically loads products from an external API, providing features such as product filtering, adding products to a cart, and completing the checkout process. The site ensures a smooth and accessible user experience, with error handling and loading indicators for all asynchronous actions.

User Stories
View Products: Users can view a list of all available rain gear on the homepage.
Filter Products: Users can filter products by categories such as gender or type of rain gear.
Product Details: Each product has a dedicated page with detailed information.
Add to Cart: Users can add products to their shopping basket and view a cart summary.
Remove from Cart: Users can remove items from the cart.
Checkout: Users can view a summary of their cart and proceed with checkout.
Order Confirmation: After completing checkout, users are shown an order confirmation page with a thank you message.
🛠️ Features
Dynamic Product Listing: The homepage fetches and displays a list of products from the Rainy Days API, with no hardcoded data.
Product Filtering: Users can filter products by category or type (e.g., raincoats, umbrellas, etc.).
Product Detail Page: A dedicated product page shows detailed information, including product images, descriptions, and pricing.
Cart System: Users can add and remove items from the cart, with the total cost automatically updated.
Checkout Process: Users can review their cart, proceed to checkout, and view a confirmation message once their order is completed.
Error Handling: Errors (e.g., API fetch issues) are handled gracefully, with user-friendly error messages.
Loading Indicators: Loading animations ensure the user knows when the site is fetching data asynchronously.
🖥️ Tech Stack
HTML: Structure of the web pages.
CSS: Styles for a clean, responsive design.
JavaScript: Core logic for fetching API data, handling the cart, and managing the UI dynamically.
API: Uses the Rainy Days API for product data and dynamic content.
📑 Pages Included
Homepage (index.html): Displays a list of products and allows filtering by category.
Product Page (/product/index.html): Shows details about a specific product.
Checkout Page (/checkout/index.html): Displays all items in the user’s basket with total cost.
Order Confirmation Page (/checkout/confirmation/index.html): Displays a thank you message and order confirmation after checkout.
📜 Usage
View Products: Visit the homepage to browse the product collection.
Filter by Category: Use the filter options to narrow down products based on gender or type.
View Product Details: Click on any product to see more information on the product page.
Add to Cart: Add items to your shopping cart from the product page or homepage.
Checkout: Review your cart and complete the checkout process to see the order confirmation.
🗂️ File Structure
assets/: Contains all images and icons used in the project.
css/: Styling for the homepage, product pages, and checkout.
js/: JavaScript files managing the API requests, cart functionality, and dynamic page content.
index.html: The main homepage displaying product listings.
product/: Folder containing the product detail page.
checkout/: Folder containing the cart summary and order confirmation pages.
🤝 Contributions
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

📢 Acknowledgments
Thanks to Noroff for providing the Rainy Days API.
Inspiration from various online JavaScript tutorials and the course material.
Special thanks to teachers and peers for reviewing and helping improve the project.
