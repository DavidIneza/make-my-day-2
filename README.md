# Meik My Dei PWA for a managed Chromebook

This version is designed for a school Chromebook where Chrome Developer Mode is blocked.

## Install
1. Host this folder on an HTTPS site (GitHub Pages works).
2. Open the HTTPS site in Chrome.
3. Open Settings inside Meik My Dei and choose Enable under notifications.
4. Allow notifications.
5. In Chrome's address bar, use the install icon / menu option to install Meik My Dei as an app when offered.

## Important behavior
- Native Chrome notifications can appear while you are using other websites if the browser/app is allowed to notify.
- The in-app alarm repeats until Turn off alarm is pressed.
- A normal PWA cannot force a custom full-screen webpage overlay over another website; Chrome controls native notification presentation.
- A static PWA cannot guarantee scheduled notifications while the app/browser is completely closed. Guaranteed closed-browser reminders require a Web Push server/backend.


## A/B Week Rotation
The timetable includes A Week and B Week. Automatic mode is anchored to Monday, October 5, 2026 as B Week and alternates every school week. Settings shows the current week and a compact Change control that re-anchors the current week to the opposite week while keeping Automatic mode active.

The app is permanently dark mode. The Full Timetable button opens an aesthetic full-screen timetable view for both A and B weeks. The Calendar shows the selected date, A/B week, timetable, and special Saturday/Monday events.
