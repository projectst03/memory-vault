# Memory Vault 🎓

This is a responsive, media-rich web application built to archive and stream video playlists. It features a modern, clean interface with a glassmorphism theme and uses a cloud-based setup to stream video files smoothly without overloading local storage.

**Live Project:** [Check it out here](https://projectst03.github.io/memory-vault/)

## 🚀 What It Does

* **Passcode-Protected Entry:** Includes a secure landing overlay. Users need to enter the vault passcode to open the media content, which is handled cleanly via JavaScript `sessionStorage` and DOM events.
* **Dynamic Media Streaming:** Instead of hosting massive video files locally, the app pulls playlists and thumbnails dynamically from Google Drive using a custom Google Apps Script API endpoint.
* **Responsive Glassmorphism UI:** Built with Tailwind CSS to ensure a sleek, frosted-glass design that looks completely consistent and runs smoothly on both mobile screens and laptops.
* **Smooth Animations:** Features custom CSS keyframe animations that provide instant visual feedback (like a shake animation for a wrong passcode and a blink effect for successful access).

## 🛠️ Tech Stack

* **Frontend:** HTML5, JavaScript (ES6+), Tailwind CSS
* **Cloud API:** Google Apps Script, Google Drive API
* **Hosting:** GitHub Pages

## 🔑 Quick Demo Access

When you open the site, you'll be prompted with a secure authorization lock.
* **Passcode for Review:** Enter `UnWrittenChapters` to unlock the vault.
* Once authorized, an asynchronous `fetch()` script runs to sync the media folder and automatically load the video playlist.

## 💻 Running It Locally

If you want to run or test the project locally:

1. Clone the repo:
   ```bash
   git clone [https://github.com/projectst03/memory-vault.git](https://github.com/projectst03/memory-vault.git)
2. Move into the project directory:
     ```bash
    cd memory-vault
3.Open index.html in your browser (using the VS Code Live Server extension works best).

    
    
