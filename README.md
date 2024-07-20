# Pantry App Tracker

Pantry App Tracker is an application designed to help you keep track of the food items in your home pantry. Whether you want to prevent food wastage, plan meals more efficiently, or simply know what's available, Pantry App Tracker has you covered.

## Features

- **Inventory Management**: Add, update, and remove items from your pantry inventory. Categorize items for better organization (e.g., grains, spices, canned goods).
- **Expiry Notifications**: Receive alerts when items are approaching their expiration date. Reduce food waste by using items before they expire.
- **Shopping List**: Automatically generate a shopping list based on the items you need to restock. Customize your shopping list and mark items as purchased.
- **Usage History**: Track usage history to understand consumption patterns and make informed shopping and meal planning decisions.
- **User-Friendly Interface**: Intuitive design for easy navigation and quick data entry. Support for both web and mobile platforms for convenience.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/pantry_app_tracker.git
    cd pantry_app_tracker
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Set up Firebase**:

    - Go to the Firebase Console.
    - Create a new project.
    - Set up Firestore Database.
    - Get your Firebase configuration and replace the config in `src/firebase.js`.

4. **Start the development server**:

    ```bash
    npm start
    ```

    The application will start on `http://localhost:3000`.

## Usage

1. **Sign In**: Create an account or sign in if you already have one.
2. **Add Items**: Navigate to the `Add Item` page to add new items to your pantry.
3. **Edit Items**: Click on an item to edit its details.
4. **Delete Items**: Click on the delete icon to remove an item from your pantry.
5. **Shopping List**: View and manage your shopping list.

## Technologies Used

- **Frontend**: React, Material-UI
- **Backend**: Firebase (Firestore, Authentication)
- **State Management**: React Hooks
- **Routing**: React Router

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

---

