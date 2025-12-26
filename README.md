# For Her ❤️ - A Digital Lantern Festival Proposal

A personalized, immersive web experience designed to simulate a lantern festival under a starry night sky. This project was built as a romantic birthday surprise and proposal, featuring floating memories, interactive elements, and a cinematic "Yes" moment.

**Live Demo:** [https://birthday-snowy-mu.vercel.app/]

## ✨ Features

* **Immersive Atmosphere:** A CSS-animated background with hundreds of glowing lanterns rising endlessly.
* **River of Memories:** 14 "Polaroid-style" photos float in the background with zero-displacement hover effects, creating a permanent gallery of memories.
* **Interactive Story:**
    * **Phase 1:** A birthday wish that waits for interaction (to enable audio).
    * **Phase 2:** A dramatic "Will You..." proposal with a typewriter text effect.
    * **Phase 3:** A celebration screen with a live "Falling in Love" timer.
* **Audio Sync:** Background music plays automatically upon the first user interaction.
* **Responsive Design:** Optimized for both mobile (touch-friendly, no address bar issues) and desktop.
* **Heart Particles:** Clicking or tapping anywhere on the screen creates a burst of hearts.
* **Peaceful Mode:** The final message card can be minimized to enjoy the background visuals.

## 📂 File Structure (Critical)

For the site to work correctly (especially on Linux/Vercel servers), the file names **must** match exactly (case-sensitive).

```text
/ (Root Directory)
├── index.html          # The main application code
├── README.md           # This file
├── proposal.jpg        # The main background/proposal image
├── song.mp3            # Background music file
├── image1.jpg          # Floating memory photo 1
├── image2.jpg          # Floating memory photo 2
...
└── image14.jpg         # Floating memory photo 14
```
## 🚀 How to Deploy
**Option 1: Vercel (Recommended)**
- Push this code to a GitHub repository.

- Go to Vercel and "Add New Project".

- Import your repository.

- Hit Deploy. (No build command needed, it's static HTML).

**Option 2: GitHub Pages**
- Go to your repository Settings -> Pages.

- Select the main branch as the source.

- Save. Your site will be live at yourusername.github.io/repo-name.

## 🛠️ Customization
**To make this your own, edit the index.html file:**

- The Date: Search for const START_DATE in the <script> tag to change the "Falling in Love" timer start date.
- The Images: Ensure you have exactly 14 images named image1.jpg through image14.jpg in the root folder. If you want more or fewer, update the PHOTO_LIST array in the JavaScript section.
- The Music: Replace song.mp3 with any audio file you prefer.

## 💻 Tech Stack
- HTML5
- CSS3 (Animations, Glassmorphism)
- Tailwind CSS (via CDN for layout utility)
- Vanilla JavaScript (DOM manipulation, logic)

***Built with ❤️ and code.***
