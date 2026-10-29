# Contacts Content Provider Demo

This is an Android application that demonstrates how to implement data sharing by reading device contacts using the **Contacts Content Provider**. 

## Features

* **Runtime Permissions**: Uses the modern `ActivityResultContracts.RequestPermission` API to request the `READ_CONTACTS` permission from the user at runtime.
* **Content Provider**: Queries the `ContactsContract.CommonDataKinds.Phone.CONTENT_URI` to fetch contact names and phone numbers.
* **UI Display**: Displays the retrieved contact information in a simple `ListView` using an `ArrayAdapter`.

## How to Run

1. Open the project in Android Studio.
2. Build and run the app on an Android device or emulator.
3. Click the **"Load Contacts"** button on the main screen.
4. Grant the required Contacts permission when prompted.
5. The app will fetch and display a list of all your contacts in a `Name: Phone Number` format.

## Technologies Used

* Kotlin
* Android SDK (compileSdk 37)
* Content Providers (`ContactsContract`)
* AndroidX Core / AppCompat
