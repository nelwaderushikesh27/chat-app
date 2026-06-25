# 💬 Chat App

A real-time chat application built with Firebase and Android.

## ✨ Features
- Real-time messaging
- User authentication
- Group chats
- Image sharing
- Online status
- Push notifications
- Typing indicators
- Read receipts

## 🛠️ Tech Stack
| Component | Technology |
|-----------|------------|
| **Language** | Kotlin |
| **UI** | Jetpack Compose |
| **Auth** | Firebase Auth |
| **Database** | Firebase Firestore |
| **Storage** | Firebase Storage |
| **Notifications** | Firebase Cloud Messaging |

## 🏗️ Architecture
```
chat-app/
├── data/
│   ├── auth/
│   ├── chat/
│   └── user/
├── domain/
│   ├── model/
│   └── usecase/
├── ui/
│   ├── auth/
│   ├── chats/
│   ├── profile/
│   └── components/
└── di/
```

## 🚀 Quick Start
```bash
git clone https://github.com/nelwaderushikesh27/chat-app.git
cd chat-app
# Add google-services.json from Firebase Console
./gradlew installDebug
```

---
*Chat in real-time! 💬*
