# 🏓 OFFground Challenge - Arcade Pickleball Game

A mobile-first, browser-based arcade game developed for the **OFFground** brand experience. This project uses HTML5 Canvas and the Web Audio API to deliver a retro gaming experience without external asset dependencies.

## 🎮 Play Now
**[Link to your GitHub Pages URL will go here]**  
*(Scan the QR code generated in the deployment step to play on mobile)*

## ✨ Key Features
*   **Mobile-First Design:** Fully responsive canvas with `touchmove` support and viewport locking to prevent zooming on double-taps.
*   **Procedural Audio:** Features a synthesized, funk-inspired bassline and arcade sound effects generated in real-time using the Web Audio API (no heavy MP3 files).
*   **Brand-Centric Logic:** Custom game loop ensures a "User Always Wins" outcome to drive positive brand association.
*   **Zero Dependencies:** Built entirely in Vanilla JavaScript and CSS—no frameworks or external libraries required.
*   **Arcade Aesthetics:** Retro grid background, pixel-art styling, and dynamic visual feedback.

## 🛠️ Tech Stack
*   **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+)
*   **Rendering:** HTML5 Canvas API
*   **Audio:** Web Audio API (Oscillators, Gain Nodes, Biquad Filters)
*   **Fonts:** Google Fonts (Press Start 2P, Inter/Neue Haas Grotesk)

## 🚀 How to Run Locally
1.  Clone the repository:
    ```
    git clone https://github.com/yourusername/offground-challenge.git
    ```
2.  Open `index.html` in any modern web browser.
3.  *Optional:* For mobile testing on a local network, serve the directory using Python:
    ```
    python3 -m http.server 8000
    ```

## 📱 Deployment
This project is designed to be hosted via **GitHub Pages**:
1.  Go to `Settings` > `Pages`.
2.  Select the `main` branch as the source.
3.  The game will be live at `https://[username].github.io/offground-challenge/`.

## 📄 License
This project is open-source.
