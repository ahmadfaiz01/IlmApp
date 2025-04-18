# IlmApp

# Introduction                      
IlmApp is an Android app with features like notes, lectures, live classes, quizzes, discussions, newsletters, feedback form, personalized profiles and user authentication.

The admin controls are also available in the same app which can be accessed by the specific credentials provided to admin. 
It can be done by setting the isAdmin column in Firebase.

# Motivation

An Android-based mobile application for students to access study material, live classes, notes, quizzes, discussions, and newsletters — all in one place. The app provides a clean and intuitive dashboard, notifications for new content, and essential e-learning features for seamless academic engagement.


## Features

- User Authentication
  - User profile picture and display name.
  - Logout functionality.

- Dashboard
  - Clean and user-friendly UI.
  - Quick-access grid buttons for all major modules.

- Modules
  - Notes: View and download course notes.
  - Lectures: Watch recorded lecture videos.
  - Live Classes: Join live sessions via Zoom integration.
  - Quizzes: Participate in interactive assessments.
  - Discussion: Collaborate with peers through chat/discussion forum.
  - Newsletter: Get the latest updates with a red dot indicator for new newsletters.

- 🔴 Red Dot Notification
  - Shows a red dot above the Newsletter button when there is unread content.



## UI Preview

A minimal and modern dashboard layout using `LinearLayout`, `RelativeLayout`, and `GridLayout`. 

Features:

- Center-aligned profile picture.
- Name display and logout button.
- Grid-style module buttons with icons.
- A red dot overlay on the "Newsletter" button when new updates are available.


## Tech Stack

- Java & XML (Android SDK)
- Firebase / FireStore (for authentication and data)
- Simply use Webview alongwoth Youtube Live set to Private or can use Zoom (for live class support)
- Figma (Custom icons for modules)


## Project Structure


![image](https://github.com/user-attachments/assets/164e803e-f9b3-4b99-8eba-66eb40bacc74)



## How to Run

1. Clone this repo:
   - git clone https://github.com/ahmadfaiz01/IlmApp.git
   - cd IlmApp

2. Open in **Android Studio**.

3. Connect Firebase.

4. Run the project on an emulator or physical device.

## Author

Ahmad Faiz  
- Computer Science @ NUST  
- AI/ML | Android Dev | Python
- LinkedIn: https://www.linkedin.com/in/ahmadfaiz01/
