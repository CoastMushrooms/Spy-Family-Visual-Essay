# Mission Dossier: Operation Strix
### An Interactive Literary Analysis Website — *Spy x Family*

---

## Project Overview

**Mission Dossier: Operation Strix** is an interactive, single-page web experience designed as a literary analysis of the anime/manga *Spy x Family*. The site explores the thesis that each Forger family member's personal adversity and isolation ultimately became the foundation for their genuine bonds as a family.

The user navigates the site like a spy accessing a classified dossier — unlocking character timelines, reading analytical logs, and assembling a puzzle that reveals the final conclusion.

---

> **Important:** All `.png` and `.mp3` files are referenced by filename directly in `index.html`. Do not rename any files or move them into subfolders, or images and audio will break.

---

## How to Run

This is a static website. No server, framework, or build step is required.

**Option 1 — Open locally:**
1. Clone or download the repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).

**Option 2 — GitHub Pages:**
1. Go to your repository's **Settings > Pages**.
2. Set the source branch to `main` (or whichever branch holds your files) and the folder to `/ (root)`.
3. Save. GitHub will provide a public URL in the format `https://yourusername.github.io/repo-name/`.

> **Audio note:** Most browsers block audio from autoplaying. The background music (`spy_music.mp3`) is triggered when the user clicks the folder on the start screen, which registers as a user gesture and allows playback.

---

## How the Website Works

The site is structured as a multi-stage interactive experience.

**Stage 1 — Start Screen**
An animated spy folder appears on a dark background. Clicking the folder opens it, triggers the intro animation, and starts the background music.

**Stage 2 — Briefing Card**
A card slides in presenting the story context: the user is a new SSS operative reviewing the Forger family dossier. Clicking "Access Dossier" advances to the Thesis page.

**Stage 3 — Thesis Page**
Displays the central literary thesis of the analysis. Clicking "Enter the Archive" brings the user to the main timeline.

**Stage 4 — Main Archive (Timeline Grid)**
Four character rows are displayed: Loid, Yor, Anya, and Bond. Each character has three timeline nodes (analytical checkpoints) that unlock in sequence. Clicking an unlocked node opens a modal with the analysis log for that checkpoint. Closing the modal marks the node as completed and unlocks the next one. Completing all three nodes for a character awards a puzzle piece, which animates to the piece counter in the top-right corner.

**Stage 5 — Operation Strix Node**
Once all four puzzle pieces are collected, the Operation Strix node at the bottom of the page becomes active. Clicking it opens a modal with the overall Operation Strix analysis, including individual tabs for each character's role. Closing this modal unlocks the Puzzle Assembly feature.

**Stage 6 — Puzzle Assembly**
Clicking the piece counter opens a drag-and-drop puzzle interface. The user drags each colored puzzle piece to its matching drop zone. Each drop zone only accepts the correct piece. Once all four pieces are placed, a "Finalize" button appears.

**Stage 7 — Conclusion**
Finalizing the puzzle reveals the conclusion screen with the closing analysis text.

---

## Design Notes

- **Fonts:** Special Elite (dossier/typewriter feel) and Poppins (body text), loaded via Google Fonts. An internet connection is required for fonts to display correctly.
- **Color palette:** Spy Red `#d93f3f`, Spy Teal `#4b7c7c`, Accent Gold `#d4af37`, Paper `#fffef2`.
- **Dependencies:** No external JavaScript libraries are used. All interactivity is written in vanilla JS within `index.html`.

---

## Browser Compatibility

| Browser           | Supported |
|-------------------|-----------|
| Chrome 90+        | Yes       |
| Firefox 88+       | Yes       |
| Edge 90+          | Yes       |
| Safari 14+        | Yes       |
| Internet Explorer | No        |

---

*All character names, images, and story elements are the property of Tatsuya Endo / Shueisha / VIZ Media.*

## Live Site
---
> https://spy-family-visual-essay.onrender.com/
---
