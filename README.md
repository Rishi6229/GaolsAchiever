Goals App
A simple React Native application that helps users set and track their goals. This app allows users to add goals, view them in a list, and remove them when completed.
Features:

Add goals with a text input field

Display goals in a scrollable list

Remove goals by tapping on them

Styled using React Native StyleSheet

Uses useState for state management

Implemented using FlatList for efficient rendering

Technologies Used

React Native

JavaScript (ES6+)

React Hooks (useState)

Flexbox for Layout
Installation

Clone the repository:

git clone https://github.com/your-username/goals-app.git
cd goals-app

Install dependencies:

npm install

Run the app:

npm start

or for Android:

npx react-native run-android

or for iOS:

npx react-native run-ios

Usage

Enter a goal in the input field.

Press the "Add Goal" button to save it.

Tap on a goal to remove it from the list.
Project Structure
/goals-app
│── /Components
│   ├── GoalItem.js  # Displays each goal with delete functionality
│   ├── GoalInput.js # Handles user input for adding goals
│── App.js           # Main entry point managing state and rendering components
│── package.json     # Project dependencies and scripts
│── README.md        # Project documentation

Future Enhancements

Add persistent storage to save goals

Implement animations for goal addition and deletion

Enhance UI with better styling

Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

License

This project is licensed under the MIT License.

Contact

For any questions or suggestions, feel free to connect on LinkedIn or reach out via jharishi220@gmail.com.
