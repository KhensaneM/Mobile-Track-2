# Mobile Track 2 - Firebase Authentication

A Flutter application demonstrating user authentication using Firebase Authentication.

## Project Overview

This project was created as part of Mobile Development Track 2.

The application allows users to:

- Create a new account
- Log in using their email and password
- View their logged-in account
- Log out securely

Firebase Authentication is used to manage user accounts and authentication.

## Technologies Used

- Flutter
- Dart
- Firebase
- Firebase Authentication
- Git
- GitHub

## Features

### User Registration

Users can create an account using their email address and password.

The application validates registration details and displays appropriate error messages when registration fails.


### User Login

Existing users can log in using their registered email address and password.

### Logged-in User

After successfully logging in, the user is taken to a logged-in screen where their Firebase account email is displayed.

### Logout

Users can log out of their account. Firebase Authentication signs the user out and returns them to the login screen.

## Firebase Configuration

The application uses Firebase Authentication with the Email/Password sign-in provider.

Firebase is initialized when the application starts using the generated Firebase configuration.

The Firebase configuration is stored in:

```text
lib/firebase_options.dart

## Screenshots

### Login

![Login Screen](screenshots/Screenshot%20from%202026-09-08%2013-36-20.png)

### Registration

![Registration Screen](screenshots/Screenshot%20from%202026-09-08%2013-36-30.png)

### Logged In

![Logged In Screen](screenshots/Screenshot%20from%202026-09-08%2013-36-38.png)

### Logout

![Logout Screen](screenshots/Screenshot%20from%202026-09-08%2013-36-44.png)