# Orebi Shop

Orebi Shop is a modern e-commerce web application built with React, Tailwind CSS, and Redux. It features a clean, responsive UI and provides a seamless shopping experience for users.

## Features

- **Product Catalog**: Browse a variety of products including accessories, clothes, electronics, and home appliances.
- **User Accounts**: Sign up, sign in, manage your profile, view orders, addresses, and payment options.
- **Shopping Cart**: Add, remove, and manage products in your cart.
- **Newsletter Subscription**: Subscribe to receive the latest updates and offers.
- **Social Media Links**: Connect with Orebi Shop on YouTube, Facebook, and LinkedIn.
- **Responsive Design**: Optimized for all devices using Tailwind CSS.
- **Redux State Management**: Efficient state handling for cart and user data.

## Project Structure

```
src/
  components/
    home/
      Footer/
      Banner/
      ...
    designLayouts/
    pageProps/
    SpecialCase/
    constants/
    ...
  pages/
    About/
    Account/
    Cart/
    Contact/
    Home/
    Journal/
    Offer/
    payment/
    ProductDetails/
    Shop/
  redux/
    orebiSlice.js
    store.js
  assets/
    images/
    pdf/
  index.js
  App.js
  index.css
public/
  index.html
  ...
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd orebi
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

### Running the Application

```sh
npm start
# or
yarn start
```

The app will be available at `http://localhost:3000`.

### Building for Production

```sh
npm run build
# or
yarn build
```

## Customization

- **Tailwind CSS**: Modify `tailwind.config.js` and `index.css` for custom styles.
- **Assets**: Add or replace images in `src/assets/images/`.
- **Redux**: Update state logic in `src/redux/`.

## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes.

## License

This project is licensed under the MIT License.

