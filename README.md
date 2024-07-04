# rn-assignment6-11074609
This project is a React Native application that demonstrates a simple product listing and cart functionality. Users can view a list of available products, add products to their cart, remove products from their cart, and view the items in their cart. The selected items are stored locally on the device using AsyncStorage.

Features
HomeScreen: Displays a list of available products.
CartScreen: Displays the selected items in the cart.
Add to Cart Button: Allows users to add products to their cart.
Remove from Cart Button: Allows users to remove products from their cart.
Local Storage: Uses AsyncStorage to store selected items locally on the device.
Installation
Clone the repository:


bash
Copy code
npm install
Run the application:

bash
Copy code
npx react-native run-android  # for Android
npx react-native run-ios      # for iOS
Project Structure
App.js: The main entry point of the application. Sets up the navigation between screens.
screens/HomeScreen.js: Displays the list of available products and allows users to add products to their cart.
screens/CartScreen.js: Displays the selected items in the cart and allows users to remove items from the cart.
components/ProductList.js: A reusable component to display a list of products.
components/CartList.js: A reusable component to display a list of items in the cart.
Design Choices
Navigation
React Navigation: Used to handle navigation between the HomeScreen and CartScreen. The @react-navigation/native and @react-navigation/native-stack packages are used to create a stack navigator.
Local Storage
AsyncStorage: Used to store and retrieve the cart items locally on the device. This allows the cart to persist even when the app is closed and reopened.
Component Structure
Reusable Components: The project is structured to use reusable components (ProductList and CartList) for displaying lists of products and cart items, respectively. This helps in maintaining clean and modular code.
Usage
View Products: Open the app and view the list of available products on the HomeScreen.
Add to Cart: Click on the "Add to cart" button to add a product to the cart.
View Cart: Navigate to the CartScreen to view the selected items in the cart.
Remove from Cart: Click on the "Remove from cart" button to remove a product from the cart.
Screenshots
Home Screen
![](./rnAssignment6/homescreen.jpeg)
Cart Screen
![](./rnAssignment6/cartscreen.jpeg)
Contributing
Fork the repository
Create a new branch: git checkout -b my-new-feature
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin my-new-feature
Submit a pull request
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Thanks to the React Native community for their amazing resources and support.