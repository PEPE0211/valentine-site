# 💖 Be My Valentine?

A playful, interactive "Special Event" website built with HTML, CSS, and JavaScript. This project features a mischievous "No" button that slides away from the cursor, custom floating heart animations, and a festive firework celebration when the "Yes" button is finally clicked.

## ✨ Features

* **Interactive "No" Button**: The "No" button dynamically changes its text and slides to a random position within the viewport on every click, making it impossible to catch.
* **Smooth Animations**: Uses CSS `cubic-bezier` transitions for snappy, playful movement that always stays within the window boundaries.
* **Floating Hearts**: A custom CSS-only background with blurred, floating hearts to set the romantic theme.
* **Firework Celebration**: Integrated with the `canvas-confetti` library for a high-energy 3-second firework show upon acceptance.
* **Polaroid Photo Reveal**: Displays a personalized couple's photo and a heartfelt message after the celebration ends.

## 🚀 Quick Start

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/pepe0211/valentine-site.git](https://github.com/pepe0211/valentine-site.git)
    ```
2.  **Open the project**:
    Simply open `index.html` in any modern web browser.

## 🛠️ Built With

* **HTML5 & CSS3**: For structure, layout, and heart animations.
* **JavaScript (ES6)**: For the movement logic, button randomization, and event handling.
* **[Canvas-Confetti](https://www.npmjs.com/package/canvas-confetti)**: For the firework celebration effects.

## 📸 Customization

To make this site your own:
1.  **The Photo**: Open `index.html` and find the `<img>` tag inside the `#successMessage` div. Replace the `src` URL with a link to your own photo.
2.  **The Messages**: You can add or change the phrases in the `phrases` array within the `<script>` tag to include your own inside jokes or emojis.

