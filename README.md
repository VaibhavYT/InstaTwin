# Instagram Clone

This is a Flutter project for building an Instagram clone, created by [Vaibhav Jaiswal](https://github.com/VaibhavYT).

## Overview

The Instagram clone is a mobile application built using Flutter, which allows users to sign up, create posts, follow other users, and interact with their posts by liking and commenting on them. It utilizes Firebase Authentication, Cloud Firestore, and Cloud Storage for Firebase for backend functionality.

## Features

- User authentication (sign up, sign in, sign out)
- Create, edit, and delete posts
- Like and comment on posts
- Follow and unfollow other users
- View posts from followed users on the home page
- Search for users by username
- View user profiles, including their posts and followers

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone this repository:

git clone https://github.com/VaibhavYT/instagram_clone.git



2. Navigate to the project directory:

cd instagram_clone


3. Install the dependencies:

flutter pub get



4. Create a new Firebase project and configure it for Android and iOS platforms.
5. Download the `google-services.json` file for Android and the `GoogleService-Info.plist` file for iOS, and place them in the `android/app` and `ios/Runner` directories, respectively.
6. Enable authentication, Cloud Firestore, and Cloud Storage for Firebase in your Firebase project.
7. Run the app:

flutter run



## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find a bug or have a suggestion.

## License

This project is licensed under the [MIT License](LICENSE).
