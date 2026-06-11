# echocardiogram-vr

[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23689154)

Project for AR/VR class 2026 (Teknologi Kedokteran). This is a browser-based A-Frame VR teaching prototype for echocardiography (USG) views and probe orientation.

## Overview
This scene presents a simplified patient model, a probe indicator, a target zone covering the torso, and a pseudo-heart display that changes by selected view. The goal is to help learners understand where to place the probe and how the ultrasound view relates to the heart anatomy.

## Goals
- Provide a simple VR teaching app for echocardiography view selection.
- Keep the UI accessible and understandable for non-technical users.
- Demonstrate probe orientation and view-dependent anatomy focus.

## Features
- View selection panel (2D overlay) with common echocardiography views.
- Arrow indicator that points toward the patient and moves per selected view.
- Full torso target zone for placement guidance.
- Pseudo-heart display that swaps between different view representations.
- Zoomed focus for left and right ventricle views.
- USG monitor label that updates with the selected view.

## Views Included
- Apical 4-Chamber
- Apical 2-Chamber
- Parasternal Long Axis (PLAX)
- Subcostal
- Left Ventricle Focus
- Right Ventricle Focus

## How to Run
1. Open the folder in a local web server (recommended) or open main.html directly in a browser.
2. Allow the browser to load external scripts.
3. Use the on-screen buttons to switch views.

Tip: For best results, use a local server (for example, VS Code Live Server) to avoid browser restrictions on local files.

## Project Structure
- main.html: The A-Frame scene and UI.
- README.md: Project overview and instructions.

## Tech Stack
- A-Frame (WebVR)
- aframe-extras (utility helpers)

## Notes
- This is a simplified visualization for training and orientation only.
- Geometry is intentionally abstracted to keep the learning focus on view concept and probe position.

## Future Improvements
- Replace pseudo-heart with more accurate USG silhouettes.
- Add in-VR UI panel for full headset usage.
- Include audio guidance for probe positioning.