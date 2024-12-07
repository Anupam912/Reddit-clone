# Reddit Clone: A Cross-Platform, Responsive Full-Stack Application

Welcome to the **Reddit Clone** project! This responsive, feature-rich application brings the essence of Reddit to Android, iOS, and Web platforms. Built with cutting-edge technology, the app ensures a seamless user experience across devices.

---

## 🚀 Features

### 🌐 **User Authentication**
- **Google Sign-In**: Authenticate using Google for a personalized experience.
- **Guest Mode**: Explore without the need to sign in.

### 🏠 **Community Management**
- Create and join communities effortlessly.
- Fully customizable **Community Profile** with:
  - Avatar
  - Banner
  - Member list
  - Editable description and avatar

### ✍️ **Posting and Interaction**
- Post content in multiple formats:
  - Links
  - Photos
  - Text-only posts
- View posts from communities the user is a part of.
- Engage with content through:
  - **Upvotes/Downvotes**
  - **Comments**
  - **Awards**

### 🔧 **Moderation Tools**
- Add moderators to your community.
- Remove inappropriate posts as a moderator.
- Delete your posts as needed.

### 🌟 **User Profiles**
- Personalize your profile with:
  - Avatar
  - Banner

### 🎭 **Karma System**
- Earn and update your Karma score for your activities.

### 🌈 **Theming**
- Switch between **light** and **dark** themes for an optimized viewing experience.

### 📰 **Latest Posts**
- Guest users can view the latest posts instead of a personalized home feed.

---

## 🛠️ Installation

After cloning this repository, navigate to the `flutter-reddit-clone` folder and follow these steps:

1. **Set up Firebase:**
   - Create a Firebase project.
   - Enable Authentication (Google Sign-In and Guest Sign-In).
   - Configure Firestore Rules.
   - Set up Android, iOS, and Web apps.
   - Use the FlutterFire CLI to integrate Firebase with this app.

2. **Run the application:**
   ```bash
   flutter pub get
   open -a simulator # Launch iOS Simulator
   flutter run
   flutter run -d chrome --web-renderer html # For the best web output
    ```
## 💻 Tech Stack

### **Server-Side**
- **Firebase Auth**: User authentication.
- **Firebase Storage**: Storing media files.
- **Firebase Firestore**: Realtime database for posts and community data.

### **Client-Side**
- **Flutter**: Frontend framework.
- **Riverpod 2.0**: State management.
- **Routemaster**: Navigation.

---

## 🙌 Contributing
We welcome contributions to enhance this project! Feel free to submit issues and pull requests.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).
