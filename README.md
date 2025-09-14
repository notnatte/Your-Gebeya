# Your Gebeya - E-commerce App

Your Gebeya is a modern e-commerce web application built with React, Redux, and Tailwind CSS. It allows users to browse products, manage a shopping cart, checkout, and provides a merchant dashboard for product and order management.

## Features

- Browse products with images, price, and stock info
- Add products to cart and manage cart items
- Checkout with order summary and shipping form
- Merchant dashboard for managing products, orders, and wallet
- Responsive UI with Tailwind CSS
- Routing with React Router

## Project Structure

```
src/
  App.jsx
  main.jsx
  index.css
  app/
    store.js
  component/
    navbar/
      Navbar.jsx
    ui/
      Buttton.jsx
      ProductCard.jsx
  feature/
    cart/
      CartPage.jsx
      cartSlice.js
    merchant/
      MerchantProduct.jsx
      MerchantOrder.jsx
      MerchantDashbord.jsx
      MerchantWallet.jsx
    product/
      ProductPage.jsx
      ProductList.jsx
      productLoader.js
      productListLoader.js
  layouts/
    AppLayout.jsx
    MercantLayout.jsx
  page/
    HomePage.jsx
    CheckoutPage.jsx
    NotFoundPage.jsx
  routes/
    route.jsx
  services/
    Api.js
```

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```

2. **Run the development server:**
   ```sh
   npm run dev
   ```

3. **Build for production:**
   ```sh
   npm run build
   ```

## Tech Stack

- React
- Redux Toolkit
- React Router
- Tailwind CSS
- Vite

## Deployment

This app is ready for deployment on Netlify. See `netlify.toml` for redirect configuration.

## License

MIT

---

Feel free to contribute or suggest new features!
