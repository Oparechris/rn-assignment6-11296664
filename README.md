# rn-assignment6-11296664
# ShoppingApp

This is a simple shopping application built with React Native. It allows users to view a list of available products, add products to their cart, and remove products from their cart. The selected items are stored locally on the device using `AsyncStorage`.

## Components

### HomeScreen

- Displays a list of available products.
- Each product has an "Add to Cart" button.
- A "Go to Cart" button navigates to the CartScreen.

### CartScreen

- Displays selected items.
- Each item has a "Remove from Cart" button.

## Local Storage

- `AsyncStorage` is used to store selected items locally on the device.

## Functionality

- Users can view a list of available products.
- Users can add products to their cart.
- Users can remove products from their cart.
- Users can view the items in their cart.

## Running the Application

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies:

    ```bash
    npm install
    ```

4. Run the application:

    ```bash
    npx react-native run-android  # For Android
    npx react-native run-ios      # For iOS
    ```

## Design Choices

- Used React Native's `FlatList` component for efficient rendering of the product list and cart items.
- Utilized `TouchableOpacity` for button components to provide better styling flexibility.
- Chose `AsyncStorage` for local storage due to its simplicity and ease of use.

## Future Improvements

- Add more product details and images.
- Implement better state management with Redux or Context API.
- Improve UI/UX with additional styling and animations.

![photo_2024-07-03_18-59-13](https://github.com/Oparechris/rn-assignment6-11296664/assets/152171543/039b39bd-9800-4f5d-95a9-90ca34ff1ac1)
![photo_2024-07-03_18-59-08](https://github.com/Oparechris/rn-assignment6-11296664/assets/152171543/208c4d74-c5f9-4b4f-921b-391e207ace44)

