# Northstar Market

A responsive, Amazon-inspired storefront prototype built with plain HTML, CSS, and JavaScript. The original site in the parent folder is left unchanged.

## Run locally

Open `index.html` in a browser, or serve this folder with VS Code Live Server.

## Demo roles

- **Customer:** Create an account from **Sign in**. Customer accounts, basket contents, saved finds, and demo orders persist in this browser's local storage.
- **Store admin:** Open **Store desk sign in** in the Browse menu or the footer. Use `admin@northstar.market` / `northstar-admin`.

The admin desk includes catalog create/edit/delete, inventory counts, order status updates, customer account listings, and a sales overview. Customer flows include search, department and price filters, sorting, product details, a saved-finds list, basket quantity controls, simulated checkout, and order history.

## Demo limitations

This is a front-end demonstration, not a production commerce service. Authentication and account data are browser-local and are not secure; orders and inventory are not shared between browsers. Checkout does not collect or process a real payment. A production system needs a server API, a real database, secure authentication and authorization, payment-provider integration, server-side inventory and order validation, and operational safeguards. Product photography loads from Unsplash and Google Fonts loads from Google Fonts.
