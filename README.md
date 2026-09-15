# Gscrool v1 — Firebase Auth Ready

Gscrool is an original gaming-focused social app starter.

## Firebase connected
- Firebase project: `gscrool-6ff6c`
- Android package: `com.gscrool.app`
- `google-services.json` is included in `app/`
- Firebase Authentication dependency is configured
- Email/password sign-up and sign-in are implemented

## One remaining Firebase step
In Firebase Console, enable **Email/Password** under Authentication → Sign-in method. Firebase's Android docs require the provider to be enabled before email/password accounts can be created.

## Build on a computer
Open the project in Android Studio and choose Build → Generate App Bundles or APKs → Generate APKs.

## Phone-only route
The project can be uploaded to a cloud Android build workflow. The repository should keep `google-services.json` private because it identifies your Firebase project, even though Firebase documents it as containing non-secret project/app identifiers.
