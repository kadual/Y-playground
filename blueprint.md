# Project Blueprint

## Overview
A modern, responsive Lotto Number Generator web application featuring real-time number generation, theme persistence, and a partnership inquiry system.

## Features & Implementation Detail

### Core Features
*   **Lottery Number Generation:** Generates 6 unique random numbers between 1 and 45. Numbers are automatically sorted in ascending order for better readability.
*   **Theme Management:** Supports Dark Mode and Light Mode with persistence using `localStorage`. The theme state is applied to the `documentElement` via a `data-theme` attribute.
*   **Partnership Inquiry Form:** Integrated with Formspree (`mgoqkbga`) to handle external collaborations. Includes validation and responsive styling.

### Design & Aesthetics
*   **Modern CSS:** Uses CSS variables for consistent theming and smooth transitions between modes.
*   **Responsive Layout:** Flexbox-based design that adapts to mobile and desktop screens.
*   **Visual Feedback:** Interactive buttons with hover and active states, plus shadow effects for depth.

### Current Progress (v2.0)
- [x] Initial Lotto Generation Logic
- [x] Dark/Light Mode Toggle & Persistence
- [x] Partnership Inquiry Form Integration
- [x] GitHub Repository Sync
- [x] Firebase Hosting Configuration (`firebase.json`, `.firebaserc`)

## Deployment Strategy
The application is deployed to **Firebase Hosting** for high performance and global availability.
- **Hosting Target:** `y-playground-12857262-c8683`
- **Root Directory:** `.` (Static deployment)
