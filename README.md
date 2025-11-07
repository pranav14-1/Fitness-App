🏋️‍♂️ Fitness-App

A smart fitness tracking Android app that helps users manage workouts, monitor diet, track steps, heart points, and body metrics — built using Kotlin, Jetpack Compose, and Firebase.

📱 Overview

Fitness-App is a comprehensive health and wellness application designed to help users stay on top of their fitness goals.
It allows users to:

Log meals and track calories/macronutrients

Record workouts, repetitions, and calories burned

Track daily step count using built-in motion sensors

View all stats in an interactive, real-time dashboard

Built with a clean, modern UI powered by Jetpack Compose and a secure cloud backend using Firebase.

⚙️ Tech Stack
Layer	Technologies
Language	Kotlin
UI	Jetpack Compose
Architecture	MVVM (Model-View-ViewModel)
Backend	Firebase Firestore, Firebase Authentication
Local Storage	Jetpack DataStore
Build System	Gradle
IDE	Android Studio / IntelliJ IDEA
✨ Key Features
🏃 Step Tracking

Real-time pedometer powered by Android motion sensors

Requires ACTIVITY_RECOGNITION permission

Displays live step count on home dashboard

🍱 Meal Logging

Add meals and drinks manually

Automatically calculates calories, carbs, protein, and fat

Stores meal logs securely in Firebase Firestore

💪 Workout Tracker

Choose from predefined exercises or add your own

Track sets, reps, and calories burned

Plan weekly or custom workout routines

Includes visual guides for common exercises

📊 Home Dashboard

Real-time overview of daily progress

Animated progress bars for calorie and macro breakdown

Displays total calories consumed vs. burned

🔐 Authentication

Secure Google Sign-In using Firebase Authentication

Persistent session management

☁️ Cloud + Local Storage

Firebase Firestore: Cloud-based user data sync

DataStore: Local caching and state management with ViewModel + ViewModelFactory

🧭 Navigation

Built using Jetpack Compose Navigation

Context-aware routing (auth-based navigation flows)

🛠️ Getting Started
1️⃣ Clone the Repository
git clone https://github.com/pranav14-1/Fitness-App.git

2️⃣ Open in Android Studio

Open the project in Android Studio (latest version recommended)

Let Gradle sync automatically

3️⃣ Configure Firebase

Replace the existing google-services.json with your own Firebase config file

Add your Web Client ID in Constants.kt

4️⃣ Enable Firebase Services

In the Firebase Console
:

Authentication → Sign-in method → Enable Google

Firestore Database → Create database

5️⃣ Run the App

Use a physical device or emulator with motion sensor support

Grant required permissions (e.g. Activity Recognition)

Build and run from Android Studio

📸 UI Preview
Dashboard	Meal Log	Workout Tracker

	
	

(Replace placeholders with real screenshots)

👨‍💻 About the Developer

Hi! I’m Pranav Kumar Thakur 
 — an Android developer passionate about crafting scalable, user-centric apps using Kotlin, Jetpack Compose, and modern Android architecture.

🔍 Key Learnings

Integrated Firebase Authentication and Firestore seamlessly

Built reactive UIs with Jetpack Compose and StateFlow

Applied MVVM architecture and modular code design principles

Improved performance through smart caching with DataStore