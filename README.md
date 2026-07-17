# AV Checklist

## Overview
This project is a single-page web application that serves as an AV (Audio/Visual) Projection checklist for Sunday service setup, streaming, and teardown. It is built using HTML, CSS (with custom design tokens for light and dark modes), and JavaScript to manage checklist state and progress.

## Features
- **Modern UI**: A sleek, responsive user interface with an animated mesh background and glassmorphism elements.
- **Dark Mode**: Built-in light and dark modes, toggleable via the UI.
- **Checklist Sections**:
  - **8:30 AM and Onward**: Setup for the projector, camera, OBS, music, and livestream pages.
  - **After the Meeting on Stage with the Team**: Starting the livestream, recording, and AI tools.
  - **After the Service**: Teardown instructions including stopping the stream, recording, and turning off equipment.
- **Progress Tracking**: Overall and per-section progress bars that update dynamically as tasks are checked off.
- **Local Storage**: Saves the checklist progress in the browser so it persists across reloads.
- **Confetti Animation**: A celebratory confetti animation triggers when all tasks are completed.

## Technologies Used
- HTML5
- CSS3 (Vanilla, no external frameworks besides Google Fonts)
- JavaScript (Vanilla)

## Deployment
This is a static website. You can run it by simply opening `index.html` in any modern web browser. It is configured with a `CNAME` file, implying it might be deployed using GitHub Pages or a similar static hosting service.
