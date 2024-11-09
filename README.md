# Food Ordering Application 🍲

**Platform**: iOS & Android (Cross-platform Mobile Application)  
**Technologies**: Expo, Expo Router, Supabase, Stripe

This food ordering app offers a sleek interface and powerful backend, delivering a smooth and fast user experience. Its flexible deployment allows it to be available on development platforms (Expo Dev) as well as iOS and Android stores.

## Features
- 🛒 Browse menus, add items to the cart, and order easily.
- 🕵️‍♂️ Secure authentication and user management with Supabase.
- 💳 Online payment integration with Stripe for seamless transactions.
- 🎨 Responsive and attractive user interface with Expo.

---

## Screenshots
<<div style="display: flex; flex-wrap: wrap; justify-content: center;">
  <img src="/photos/0.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/1.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/2.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/3.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/4.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/5.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/6.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/7.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/8.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/9.webp" width="200" alt="Payment Screen"/>
  <img src="/photos/10.webp" width="200" alt="Product details Screen"/>
  <img src="/photos/11.webp" width="200" alt="Product details Screen"/>
</div>

---

## Prerequisites

Before you begin, ensure you have the following:
- [Node.js](https://nodejs.org/) version 14.x or above
- [Expo CLI](https://docs.expo.dev/get-started/installation/) installed globally
- A [Supabase](https://supabase.com/) account with API keys
- A [Stripe](https://stripe.com/) account for the payment key

## Environment Variables

In the `.env` file, set up the necessary environment variables:
```env
EXPO_PUBLIC_SUPABASE_URL=YOUR_SUPABASE_URL
EXPO_PUBLIC_SUPABASE_ANON=YOUR_SUPABASE_ANON_KEY
EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=YOUR_STRIPE_PUBLISHABLE_KEY
STRIPE_SECRET_KEY=YOUR_STRIPE_SECRET_KEY
```

## Installation and Execution
```
Clone the project and install dependencies:
git clone git remote add origin https://github.com/TatyOko28/Food-Ordering-Mob.git
cd FoodOrderingApp
npm install
```

Run the app with Expo:
```
expo start
```
Scan the QR code to test the app on your device.

## Deployment
### 1. Backend Deployment (Supabase)
Go to Supabase.com and create a project.
Set up the necessary tables and features for authentication and order management.
Add your API keys (URL and ANON_KEY) to the .env file.

### 2. Deploying to GitHub
Initialize your local repository:
bash
Copier le code
```
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/FoodOrderingApp.git  //modify this link
git push -u origin main
```

### 3. Install the latest EAS CLI
EAS CLI is the command-line app that you will use to interact with EAS services from your terminal. To install it, run the command:
```
npm install -g eas-cli
```

### 4. Log in to your Expo account
If you are already signed in to an Expo account using Expo CLI, you can skip the steps described in this section. If you are not, run the following command to log in:
```
eas login
```

### 5. Run a build
After you have confirmed that you have a Google Play Store or Apple App Store account and decided whether or not EAS CLI should handle app signing credentials, you can proceed with the following set of commands to build for the platform's store:
```
eas build --platform android
```
Alternatively, you can use --platform all option to build for Android and iOS at the same time:
```
eas build --platform all
```

### 6. Deploy the build
If you have made it to this step, congratulations! Depending on which path you chose, you now either have a build that is ready to upload to an app store, or you have a build that you can install directly on an Android device/iOS Simulator.




