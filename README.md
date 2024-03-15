# Fast React Pizza

Fast React Pizza is a web application built with React.js, styled using Tailwind CSS, and utilizes React Router for routing and Redux Toolkit for state management. It serves as a dummy pizza shop web app, allowing users to order pizzas online with ease.

## Live Site

Check out the live site [here](https://aaliyanasif.github.io/fast-react-pizza/) to order your favorite pizzas hassle-free!

## Features

- **User Authentication:**

  - Users are prompted to enter their name to access the menu.

- **Dynamic Menu:**

  - Displays a list of pizzas fetched from the restaurant's API.
  - Each pizza is showcased with a picture, name, ingredients, and price.
  - Sold-out pizzas are visually marked and grayed out.

- **Cart Management:**

  - Users can add pizzas to the cart.
  - Ability to adjust the quantity of pizzas or remove them from the cart.
  - Provides a cart overview at the bottom of the screen, displaying the total number of pizzas and the total price.

- **Order Placement:**

  - Users can proceed to the cart to review their selections.
  - Option to clear the cart or continue adding pizzas before ordering.
  - Upon checkout, users are directed to the order screen to provide their contact and address details.
  - Option to prioritize the order for an additional fee.

- **Order Tracking:**

  - After placing the order, users are shown order details, including order number, status, time left for delivery, items ordered, total price, and additional priority price (if applicable).
  - Users can choose to make their order a priority even after placing it.

- **Order Lookup:**
  - Users can enter their order number in the navbar to retrieve their order details at any time.

## Technologies Used

- React.js: Building the dynamic user interface.
- Tailwind CSS: Styling components for a modern and responsive design.
- React Router: Managing navigation within the application.
- Redux Toolkit: Managing application state, especially for cart and order management.

## Getting Started

1. Clone the repository: `git clone [repository URL]`
2. Navigate to the project directory: `cd fast-react-pizza`
3. Install dependencies: `npm install`
4. Start the development server: `npm run dev`

Now, you can experience the Fast React Pizza web app and order your favorite pizzas hassle-free!
