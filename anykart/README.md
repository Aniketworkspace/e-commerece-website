# E-CommerceWebsite

A small, mobile-responsive sample e-commerce site built with HTML, CSS and vanilla JavaScript. Uses a mock API for product data.
## Quick start
- Open [index.html](index.html) in a browser.
- Browse products on the home page and product lists.
- Click a product to view details and add items to the cart.
- Place an order from the cart page.

## Features
- Responsive layout with separate pages for listing, details and cart
- Client-side rendering using API data
- Simple cart persisted via cookies

## Important files
- Pages: [index.html](index.html), [content.html](content.html), [contentDetails.html](contentDetails.html), [cart.html](cart.html), [orderPlaced.html](orderPlaced.html)
- Scripts: [content.js](content.js), [contentDetails.js](contentDetails.js), [cart.js](cart.js), [orderPlaced.js](orderPlaced.js)
- Layout: [header.html](header.html), [footer.html](footer.html)
- Styles: css/ (e.g. [css/content.css](css/content.css), [css/contetDetails.css](css/contetDetails.css), [css/cart.css](css/cart.css))

## Key functions
- [`dynamicClothingSection`](content.js) — renders product cards
- [`dynamicContentDetails`](contentDetails.js) — renders product detail view
- [`dynamicCartSection`](cart.js) — renders items in the cart

## API
- Product data from: https://5d76bf96515d1a0014085cf9.mockapi.io/product


