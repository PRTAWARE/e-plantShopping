# Paradise Nursery Shopping Application

Paradise Nursery is an intuitive, responsive e-commerce web application for plant enthusiasts to explore, select, and purchase a variety of houseplants. Built with React and Redux Toolkit, this application provides an interactive online shopping experience featuring dynamic cart quantity updates, real-time total price calculations, and seamless navigation.

## Features

- **Landing Page**: An inviting landing page with a serene greenhouse background, company branding, mission statement ("Where Green Meets Serenity"), and a "Get Started" call-to-action button.
- **About Us Section**: Detailed company background highlighting Paradise Nursery's passion for quality plants and customer care.
- **Product Listing**: 
  - Over 30 unique houseplants categorized across multiple categories (Air Purifying Plants, Aromatic Fragrant Plants, Insect Repellent Plants, Medicinal Plants, Low Maintenance Plants).
  - Each plant displays a high-quality thumbnail, name, description, and price.
  - Interactive "Add to Cart" button that adds the selected plant to the shopping cart, changes status to "Added to Cart", disables further clicks, and increments the navbar cart counter.
- **Global Navigation Bar**:
  - Available across both product listing and cart views.
  - Quick links to Home, Plants, and the Shopping Cart.
  - Dynamic cart badge displaying total item count in real-time.
- **Interactive Shopping Cart**:
  - Displays all chosen plants with thumbnail, title, and unit price.
  - Real-time subtotal calculation per plant based on selected quantity.
  - Increment (+) and Decrement (-) quantity controls with automatic zero-quantity removal.
  - Delete button to instantly remove specific plants from the cart.
  - Overall total cart cost calculation.
  - "Continue Shopping" button to return to the plant gallery.
  - "Checkout" button with a "Coming Soon" notification.

## Tech Stack

- **React 18**: Component-based user interface.
- **Redux Toolkit & React-Redux**: Centralized state management for the shopping cart slice.
- **Vite**: Ultra-fast front-end build tool and development server.
- **CSS3**: Custom styling and responsive design.

## Author

- **Prathamesh Taware** ([PRTAWARE](https://github.com/PRTAWARE))