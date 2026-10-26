# Friends Chat — Android starter source

This is the first runnable UI milestone for **Friends Chat**, a green WhatsApp-style Android app built with Kotlin and Jetpack Compose.

## What works in this starter
- Chat list, Status, Calls, and Groups tabs
- Open a sample conversation and send local demo messages
- Green material-style interface
- Sample call and group screens

## What is not connected yet
This starter is a UI prototype. Messages stay in local app memory. There is no real login, multi-device messaging, push notifications, cloud storage, voice/video transport, or end-to-end encryption yet. Do not use it for sensitive conversations.

## Open it
1. Install Android Studio: https://developer.android.com/studio
2. Choose **Open** and select this `FriendsChat` folder.
3. Let Gradle sync.
4. Run on an Android emulator or USB-connected Android phone.

The package name is `com.example.friendschat`. You can change it later.

## Next implementation milestones
1. Connect Firebase Authentication.
2. Add Cloud Firestore conversations/messages with strict security rules.
3. Add Firebase Cloud Messaging for notifications.
4. Add image upload and expiring status documents.
5. Add WebRTC calling with signaling and a TURN server.
6. Add a vetted end-to-end encryption protocol/library before claiming chats are end-to-end encrypted.

Firebase setup: https://firebase.google.com/docs/android/setup
Compose setup: https://developer.android.com/develop/ui/compose/setup
WebRTC peer connections/signaling: https://webrtc.org/getting-started/peer-connections

Security note: never put Firebase Admin credentials, service-account keys, or other server secrets in the Android app. Cloud database rules must be restrictive before testing with real users.
