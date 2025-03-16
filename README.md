# Food-Mania

## Overview

Food-Mania is a React Native mobile application designed for food delivery services. It allows users to browse restaurants, add items to their cart, and complete secure checkouts.

## Features

- User authentication (Sign up, Login, Forgot Password)
- Restaurant and menu browsing
- Add/remove items from the cart
- Secure checkout and order tracking
- Firebase Firestore database integration
- Cross-platform compatibility (iOS & Android)
- Responsive and intuitive UI

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Craftzman-Hamza/Food-Mania.git
   cd Food-Mania
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up Firebase:
   - Place `google-services.json` in `android/app/` for Android.
   - Place `GoogleService-Info.plist` in `ios/` for iOS.
   - Create a `.env` file and add Firebase configuration:
     ```env
     REACT_APP_API_KEY=your_api_key
     REACT_APP_AUTH_DOMAIN=your_auth_domain
     REACT_APP_PROJECT_ID=your_project_id
     REACT_APP_STORAGE_BUCKET=your_storage_bucket
     REACT_APP_MESSAGING_SENDER_ID=your_sender_id
     REACT_APP_APP_ID=your_app_id
     ```
4. Run the app:
   ```bash
   npm run android   # For Android
   npm run ios       # For iOS
   ```
