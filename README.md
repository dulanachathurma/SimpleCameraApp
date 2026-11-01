# Simple Camera App

A simple Android camera app built with **Kotlin** and **Jetpack Compose** for the Mobile Application Development assignment.

**Author:** Dulana Chathurma

## Screenshots

<table>
  <tr>
    <td align="center"><b>1. Home screen</b></td>
    <td align="center"><b>2. Camera opened</b></td>
    <td align="center"><b>3. Photo captured</b></td>
    <td align="center"><b>4. Share sheet</b></td>
    <td align="center"><b>5. Sharing to an app</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/e1735737-a948-417c-a82c-929e5e1e2967" width="200" alt="Share sheet" /></td>
    <td><img src="https://github.com/user-attachments/assets/3dbbc936-3870-41a2-986e-81329f2298cd" width="200" alt="Camera opened" /></td>
    <td><img src="https://github.com/user-attachments/assets/65b61127-9154-4ed4-b770-60aead44661d" width="200" alt="Home screen" /></td>
    <td><img src="https://github.com/user-attachments/assets/8ea17ba8-5c89-4ad7-b383-6ceb0c68c087" width="200" alt="Photo captured" /></td>
      <td><img src="https://github.com/user-attachments/assets/d65891a4-0a38-415f-a848-3dfc1409e321" width="200" alt="Sharing to an app" /></td>
  </tr>
</table>

## Features
- Open the device camera
- Capture a photo
- Display the captured photo in the app
- Share the photo using the Android share sheet

## Concepts used
- Camera permission
- Camera access
- Intents
- FileProvider

## Tech stack
- Kotlin
- Jetpack Compose
- Android Studio

## Tested on
Pixel 6 emulator (API 34)

## How to Run

### Requirements
- Android Studio (latest stable version)
- An Android emulator (API 24 or higher) or a real Android phone
- Internet connection for the first Gradle sync

### Steps
1. Clone the repository:
   git clone :  https://github.com/dulanachathurma/SimpleCameraApp.git

2. Open Android Studio and select **File > Open**, then choose the `SimpleCameraApp` folder.
3. Wait for the Gradle sync to finish.
4. Select a device (emulator or a real phone with USB debugging on) from the device dropdown.
5. Click the **Run** button.
6. Tap **Open Camera** and allow the camera permission.
7. Take a photo. It will appear in the app.
8. Tap **Share** to open the Android share sheet and send the photo through any app.

## Tested on
Pixel 6 emulator (API 34)
