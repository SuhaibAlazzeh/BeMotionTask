# BeMotionTask - iOS SwiftUI App

Features
- User authentication via Firebase (sign in & sign up).
- Basic email/password validation.
- add Google map view.
- get current location on google map view.
- tracking a user location.
- "Log Out" functionality to clear user credentials.
- SwiftUI-based UI.

#Architecture Overview 
- SwiftUI views are used to build the user interface, including login and map screen navigation.
- Views are reactive, with state-driven UI updates using @State and @Binding properties.

#Dependencies 
This project uses the following dependencies:

- Firebase
Firebase is used to handle user authentication.

Firebase Authentication: Manages user login, registration, and sign-out functionality.
Used to check the user's login status (Auth.auth().currentUser).
Used for logging users in with email and password (Auth.auth().signIn(withEmail:password:)).
Used for registering users if they don’t exist (Auth.auth().createUser(withEmail:password:)).

- SwiftUI
The app is built entirely with SwiftUI, Apple's modern framework for building user interfaces.

SwiftUI: Framework used for building the app's UI declaratively.
NavigationView and NavigationLink are used for handling navigation.
Views like TextField, SecureField, and Button are used for input fields and actions.

- Google Map
