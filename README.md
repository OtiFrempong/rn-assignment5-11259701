Project Setup
Initialize React Native Project:
Created a new React Native project using the react-native init command.
Ensured the development environment was set up according to the official React Native guidelines.
Dependencies
Install Necessary Libraries:
Installed navigation and other necessary libraries using npm:
@react-navigation/native
@react-navigation/bottom-tabs
Other dependencies like react-native-gesture-handler, react-native-reanimated, etc.
Installed @react-native-async-storage/async-storage for persistent storage.
Components
Create Custom Components:

Developed reusable components like Card and Transaction to display the user's card information and transaction history.

Screens
Develop Screens:

Created the HomeScreen to display the welcome message, user's card, and transaction history.
Developed the SettingsScreen to allow users to change application settings, including toggling between light and dark themes.

Navigation
Set Up Navigation:

Configured the bottom tab navigation using @react-navigation/bottom-tabs.
Defined the HomeScreen and SettingsScreen in the navigation container.

Theme Context
Implement Theme Context:

Created a context for theme management to handle light and dark themes.
Stored the theme preference using AsyncStorage for persistence across app restarts.

Testing and Deployment
Test the Application:

Ran the application on both Android and iOS simulators/emulators.
Ensured the theme switching functionality and navigation worked as expected.
Deploy the Application:

Prepared the application for production by optimizing performance and addressing any platform-specific issues.
Followed platform-specific deployment guides for publishing the app to Google Play Store and Apple App Store.
By following these steps, we built a mobile application that closely matches the provided UI mockups, including a feature to switch between light and dark themes. The application is structured to be modular and reusable, ensuring easy maintenance and scalability.


**Screenshots**
![Light Theme HomePage](../assets/LightThemeHomePage.jpg)
![Light Theme HomePage2](../assets/LightThemeHomepage2.jpg)
![Light Theme Settings](../assets/LightThemeSettings.jpg)

![Dark Theme HomePage](../assets/DarkThemeHomepage1.jpg)
![Dark Theme HomePage2](../assets/DarkThemeSettings2.jpg)
![Dark Theme Settings](../assets/DarkThemeSettings.jpg)



