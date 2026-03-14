# Personal WebP Viewer 🚀

A personalized, lightweight web tool designed for high-efficiency WebP image browsing. Access local folders securely directly through your browser without server uploads, featuring intelligent directory management and professional lightbox tools.

## ✨ Key Features

### 📁 Intelligent Directory Management
* **Directory Tree Selection**: Preview the complete folder structure upon selection and precisely check the subdirectories you wish to scan.
* **Hierarchical Linking**: Smart checkbox logic; checking a parent folder automatically selects/deselects all its subdirectories.
* **Reselect Scope**: Redefine your scanning range from the current directory without reopening the system file picker.
* **Quick Load**: Utilize IndexedDB to remember permissions and perform a deep recursive scan of your last-used folder with a single click.
* **Smart Filtering**: Automatically excludes macOS system junk files (`._`) and all hidden files (`.`).

### 🛠 Core Controls
* **Aspect Ratio Lock**: Default-enabled ratio locking; height remains synchronized with width adjustments for a tidy layout.
* **Dynamic Thumbnails**: Real-time resizing with a generous default (300px) for high-clarity previews.
* **Professional Sorting**:
    * Supports "Default, Random, Name, Folder, Date, and Size."
    * One-click "↑ / ↓" toggle for ascending/descending order.
    * **Smart Shuffle**: Randomizes image order and locks the "Random" mode to prevent sorting overrides.

### 🖼 Advanced Lightbox
* **Smooth Zoom & Pan**: Support for mouse-wheel zooming and drag-and-drop panning for detail inspection.
* **Automated Slideshow**: Customizable playback speed (0.5s - 15s) with a sleek modern Switch toggle for the play button.
* **Fullscreen Mode**: One-click immersive browsing experience.

---

## ⌨️ Keyboard Shortcuts (Lightbox Active)

| Key | Description |
| :--- | :--- |
| **Space** | **Play / Pause** automated slideshow |
| **Right Arrow (→)** | Navigate to the **Next** image |
| **Left Arrow (←)** | Navigate to the **Previous** image |
| **ESC** | **Close** Lightbox and return to gallery |

---

## 🚀 Quick Start

1. **Download**: Save the `PersonalWebPViewer.html` file to your computer.
2. **Launch**: Open the file in Chrome, Edge, or Brave.
3. **Authorize**: Click **📂 Select Folder** and grant the browser read access.
4. **Scan**: Check the directories you wish to view in the popup window.

---
*Created with ❤️ for efficient image management.*