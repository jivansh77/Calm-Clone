# Calm Clone

## Overview

Calm Clone is a web application designed to promote mental health and wellness through meditation, sleep aids, and relaxation techniques. Inspired by the popular Calm app, this project aims to provide users with a comprehensive platform to manage stress, improve sleep quality, and practice mindfulness.

## Features

- **User-Friendly Interface**: A clean and intuitive design that enhances user experience.
- **Carousel**: A dynamic carousel feature that allows users to easily browse through blog posts and user reviews, enhancing engagement and accessibility.
- **Breathing Tool**: A newly added feature that guides users through breathing exercises to reduce stress and anxiety.
- **Dark Mode**: A newly added feature that allows users to switch to a dark theme for a more comfortable viewing experience in low-light environments.
- **Responsive Design**: Optimized for both desktop and mobile devices, ensuring accessibility for all users.
- **FAQ Section**: Answers to common questions about meditation, mindfulness, and the Calm Clone app.
- **Blog Section**: Articles and resources related to mental health, meditation, and wellness.

## Installation

To set up the Calm Clone project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/calm-clone.git
   cd calm-clone
   ```

2. **Open the Project**:
   Open the project in your preferred code editor (e.g., Visual Studio Code).

3. **Open the HTML File**:
   Open `index.html` in your web browser to view the application.

## Usage

1. **Navigating the App**:
   - Use the navigation bar to access different sections of the app, including Sleep, Stress & Anxiety, and Mindfulness.
   - Explore the Benefits section to learn about the features offered by the app.

2. **Using the Breathing Tool**:
   - Click on the Breathing Tool button located at the bottom right of the screen.
   - A modal will appear, allowing you to select the type of breathing exercise and duration.
   - Click "Start Breathing" to begin the guided exercise. Follow the on-screen instructions to inhale and exhale as the circle expands and contracts.
   - The timer will display your progress, and you can stop the exercise at any time.

3. **Exploring the Blog**:
   - Visit the Blog section to read articles on various topics related to mental health and wellness.
   - Use the navigation arrows to browse through blog posts.

4. **FAQ Section**:
   - Access the FAQ section to find answers to common questions about the app and meditation practices.

5. **Dark Mode Feature**:
   - To enable dark mode, click the "Toggle Dark Mode" button located in the navigation bar.
   - The app will switch to a dark theme, providing a more comfortable viewing experience in low-light conditions.
   - Dark mode helps reduce eye strain and can improve battery life on devices with OLED screens.

## Breathing Tool Feature

### Overview

The Breathing Tool is a newly added feature that helps users practice controlled breathing techniques to alleviate stress and anxiety. This tool is designed to guide users through various breathing exercises, promoting relaxation and mindfulness.

### How It Works

- **Breathing Types**: Users can choose from different breathing techniques, including:
  - **Equal Breathing**: Inhale for 4 seconds, exhale for 4 seconds.
  - **4-7-8 Technique**: Inhale for 4 seconds, hold for 7 seconds, exhale for 8 seconds.
  - **Box Breathing**: Inhale for 4 seconds, hold for 4 seconds, exhale for 4 seconds, hold for 4 seconds.

- **Duration Selection**: Users can select the duration of the breathing exercise, ranging from 1 to 5 minutes.

- **Visual Feedback**: The breathing circle visually guides users through the exercise, expanding during inhalation and contracting during exhalation.

- **Timer**: A countdown timer displays the remaining time for the exercise, helping users stay focused.

## Dark Mode Feature

### Overview

The Dark Mode feature allows users to switch the app's theme to a darker color palette, enhancing usability in low-light environments and reducing eye strain.

### How It Works

- **Toggle Button**: Users can enable or disable dark mode by clicking the "Toggle Dark Mode" button in the navigation bar.
- **CSS Variables**: The app uses CSS variables to switch between light and dark themes seamlessly. Background colors, text colors, and other UI elements are adjusted accordingly.
- **User Preference**: The user's theme preference is saved in local storage, ensuring that the selected mode persists across sessions.

### Implementation

The dark mode feature is implemented using CSS and JavaScript:

- **CSS**: Two sets of styles are defined for light and dark modes, utilizing CSS variables for easy switching.
- **JavaScript**: A script listens for the toggle button click event, updates the CSS variables, and saves the user's preference in local storage.

## Acknowledgments

- Inspired by the Calm app and its mission to promote mental health and wellness.

---

Feel free to reach out if you have any questions or need further assistance!
