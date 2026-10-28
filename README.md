# Common Screens App (Android Assignment 2)

Android application (Java + XML) implementing common authentication and navigation screens.
Authentication and password recovery are simulated locally (hardcoded default account + SharedPreferences). No backend is used.

**Student:** Urooj Fatima | **Registration ID:** 24108238 | **Email:** 24108238@szabist-isb.pk

## Implemented Features
- **Splash** screen showing logo and app name, then navigates to Login
- **Login** with email/username + password, validation, show-password checkbox
- **Register** with name, email, password, confirm password validation
- **Forgot Password** accepts email and simulates recovery
- **Reset Password** with new/confirm password validation
- **Landing** screen with a grid of cards (icon + text) for main modules
- **Profile** screen showing user information with **Logout**

## Technical Requirements Covered
- Default and alternative resources: `strings.xml`, `colors.xml`, `dimens.xml`, night-mode colors (`values-night`), landscape dimensions (`values-land`), Urdu strings (`values-ur`)
- Layouts: LinearLayout, GridLayout, ConstraintLayout (also ScrollView)
- Input controls: text, email and password EditText, CheckBox, Button
- Button click events and input validation
- Explicit Intents for all Activity navigation

## Navigation Flow
Splash -> Login -> Landing -> Profile -> Logout (Login)

Login -> Register -> Login

Login -> Forgot Password -> Reset Password -> Login

## Demo Login
Use the registered email `24108238@szabist-isb.pk` (or the registration ID `24108238`) with the demo password defined in `UserStore.java`.

## How to Run
1. Open the folder in Android Studio and wait for Gradle sync
2. Run on an emulator or a physical device
