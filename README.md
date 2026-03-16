<div align="center">

# 🌟 NexStock Dev Suite

**The Ultimate 2-in-1 Stock Media & AI Utility Engine**

[![Made with JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Powered by Pexels](https://img.shields.io/badge/Pexels_API-05A081?style=for-the-badge&logo=pexels&logoColor=white)](#)
[![Powered by Pixabay](https://img.shields.io/badge/Pixabay_API-27AE60?style=for-the-badge&logo=pixabay&logoColor=white)](#)
[![AI Integration](https://img.shields.io/badge/AI_Generative-6C5CE7?style=for-the-badge&logo=openai&logoColor=white)](#)

</div>

<br>

> **Note from the Developer:** I built NexStock because I was tired of opening five different tabs just to find a decent stock video, then opening another tool to remove the background, and *another* one to extract the color palette. This project pulls the best global media APIs into a single, high-speed dashboard and sprinkles in some AI magic. No tab switching required.

## 🚀 Why This Project Exists

Finding the perfect asset shouldn't break your flow state. NexStock takes the massive libraries of **Pixabay** and **Pexels**, merges them into a single search bar, and handles both high-res photos and 4K footage. 

But it doesn't stop at search. I baked a full developer toolkit right into the sidebar so you can manipulate those assets on the fly. 
## Project Screen Shot

## ✨ The Core Features

* 📸 **Two Giants, One Search:** Hits the Pexels and Pixabay APIs simultaneously, shuffles the results, and displays them in a seamless, zero-lag Masonry grid.
* 🎬 **No-Friction Media Switching:** Toggle between static photos and motion footage instantly. Hover over video cards for live, muted previews.
* 🤖 **AI Generation Built-In:** Stock sites failing you? Pop open the Dev Sidebar and generate custom imagery on the fly using Latent Diffusion models.
* 🪄 **Instant Background Removal:** Click a button to strip the background from any photo using integrated Computer Vision (Remove.bg API). It renders on a clean checkerboard canvas.
* 🎨 **Color Extraction & QR:** Auto-extracts HEX color palettes from the images you click on, and generates instant QR codes so you can scan and preview assets on your phone.
* 🛡️ **Zero Broken Images:** Custom error-handling scripts immediately hide broken links so the UI stays pristine.

## 🛠️ Under the Hood

This project is built to be lightweight, fast, and entirely client-side.

* **Frontend:** HTML5, CSS3, ES6+ JavaScript
* **Layout:** Custom CSS Masonry Grid (No bulky libraries)
* **Design System:** Glassmorphism UI, Bootstrap 5 Offcanvas & Modals, FontAwesome Icons
* **Integrations:**
  * `Pixabay REST API`
  * `Pexels API`
  * `Pollinations.ai` (Stable Diffusion Text-to-Image)
  * `Remove.bg API` (Foreground Segmentation)
  * `QRious` (Client-side QR generation)
  * `HTML5 Canvas API` (Pixel data reading for HEX extraction)

## 🚦 Getting Started

Want to run this locally? It's literally just one file, but you'll need to plug in your own API keys.

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/yourusername/nexstock-dev-suite.git](https://github.com/yourusername/nexstock-dev-suite.git)
Open the file: Open index.html in your favorite code editor.

Add your API Keys: Find the KEYS object at the top of the <script> tag and paste in your developer keys for Pexels, Pixabay, and Remove.bg.

JavaScript
const KEYS = {
    pixabay: "YOUR_PIXABAY_KEY", 
    pexels: "YOUR_PEXELS_KEY",
    removeBg: "YOUR_REMOVE_BG_KEY"
};
Launch: Open index.html in your browser (or use Live Server). You're good to go!

<div align="center">

💻 Crafted for the Developer Portfolio
This project is a piece of my ongoing journey in building robust, API-driven web applications and IT infrastructure solutio
