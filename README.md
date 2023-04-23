# Instagram Clone - Full Stack
This is a full stack Instagram clone created by Amanat Singh using Flutter as the frontend framework and Firebase as the backend service. It replicates the basic functionalities of Instagram, allowing users to register, login, post images, like and comment on posts, and follow other users.

# Features
User Authentication: Users can register and login with their email and password using Firebase Authentication.
Profile Creation: Users can create and edit their profile with their personal information, including a profile picture.
Image Uploads: Users can upload images to their posts and profile picture using Firebase Storage, a cloud-based storage service.
Social Features: Users can follow other users, like and comment on posts, and view posts from users they follow in their feed.
Post Management: Users can create, view, edit, and delete their own posts.
Search Functionality: Users can search for other users by username.
Responsive Design: The application is responsive and mobile and web friendly, providing a seamless experience on various devices.

# Technologies Used
# Frontend:
Flutter
Dart
Provider (for state management)
http (for API requests)
Firebase SDK (for authentication, storage, and Firestore database)

# Backend:
Firebase (Firebase Authentication, Firebase Storage, Firestore database)

# Installation
To run the Instagram clone on your local machine, follow these steps:

Clone the repository to your local machine using git clone.
Navigate to the instagram-clone-flutter folder in your terminal.
Run flutter pub get to install the dependencies.
Create a Firebase project and configure the necessary Firebase services (Firebase Authentication, Firebase Storage, Firestore database).
Replace the Firebase configuration in the lib/firebase_options.dart file with your own Firebase configuration.
Run the app using flutter run command in the terminal or run it from your preferred IDE.
Open the app on an emulator or physical device to view the Instagram clone.

# Future Enhancements
There are several potential future enhancements that could be implemented to further improve the Instagram clone:

Direct Messaging: Add a direct messaging feature that allows users to send private messages to each other.
Notifications: Implement notifications for new followers, likes, and comments using Firebase Cloud Messaging.
Pagination: Implement pagination for posts to optimize performance when the number of posts grows.
User Settings: Add user settings to allow users to customize their profile and privacy settings.
Social Sharing: Implement social sharing functionality to allow users to share posts on other social media platforms.
Hashtags and Search Filters: Add support for hashtags and search filters to make it easier for users to discover posts.
UI/UX Improvements: Continuously improve the user interface and user experience based on feedback and usability testing.
Contributing
This Instagram clone is a personal project and currently not open for contributions. However, feel free to fork the repository and customize it according to your needs.

# License
This project is licensed under the MIT License.

# Acknowledgements
Special thanks to Rivaan Ranawat for their video on Instagram clone using Flutter and Firebase.
