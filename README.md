# UbuntuMentor - Part 3 Final PoE

## Student Information
*   **Name:** Sakhile Mthembu
*   **Student Number:** ST10455429
*   **Module:** OPSC6312

## Project Overview
UbuntuMentor is an Android application designed to connect South African youth with mentors, career guidance, and verified opportunities. The app features a Node.js REST API backend, SQLite database, JWT authentication, Firebase Cloud Messaging, and RoomDB for offline support.

## Tech Stack
*   **Frontend:** Kotlin, Android Studio, Retrofit, RoomDB
*   **Backend:** Node.js, Express, SQLite
*   **Authentication:** JWT, Firebase Auth (Google SSO)
*   **Notifications:** Firebase Cloud Messaging (FCM)

## Demonstration Video
Watch the full Part 3 demonstration here:
[https://youtu.be/pYPqxZlrM3o](https://youtu.be/pYPqxZlrM3o)

## How to Run the App
1.  Navigate to the backend folder: `cd UbuntuMentorAPI`
2.  Start the server: `node server.js`
3.  Open the Android project in Android Studio.
4.  Ensure the phone and PC are on the same Wi-Fi and update the `BASE_URL` in `ApiClient.kt` if necessary.
5.  Run the app on a physical Android device.

## Release Notes (Version 3.0 - Final PoE)
*   **Added Google SSO Login:** Users can now log in using their Google accounts.
*   **Added Offline Mode (RoomDB):** Users can view saved opportunities without an active internet connection.
*   **Added Real-time Notifications (FCM):** Users receive push notifications for alerts.
*   **Added Multi-language Support:** The app now supports English, isiZulu, and Afrikaans.
*   **Added User Defined Features:** Application Tracking and Saved Opportunities functionality.
