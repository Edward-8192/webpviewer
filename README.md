# WebP Viewer - Powered by Google Gemini

A lightweight, fluid, and powerful web-based WebP image viewer. Access local folders directly without uploading, featuring professional-grade previewing and slideshow capabilities.

## ✨ Key Features

### 🛠 Core Controls
* **Local Folder Access**: Leverage modern Browser APIs to read all WebP files directly from your local directories.
* **Quick Load (IndexedDB)**: Automatically remembers the last opened folder path, allowing one-click restoration upon return.
* **Default Aspect Ratio Lock**: Pre-configured to lock image proportions; height adjusts automatically when width is modified.
* **Flexible Thumbnail Sizing**: Real-time thumbnail resizing, now with a generous default size (300px) for high-clarity previews.

### 📊 Sorting & Search
* **Multiple Sorting Modes**: Support for "Default, Name, Folder Path, Date, and File Size."
* **Smart Shuffle**: One-click to randomize the image order; automatically switches to "Random Mode" to prevent sorting overrides.
* **Intuitive Toggle**: Replaces clunky menus with a sleek "↑ / ↓" button to switch between Ascending and Descending orders.
* **Instant Search**: Filter specific images by filename in real-time.

### 🖼 Advanced Lightbox
* **Smooth Zoom & Pan**: Support for mouse-wheel zooming and drag-and-drop panning for precise detail inspection.
* **Automated Slideshow**: Customizable transition speed (0.5s - 15s) with a quick play/pause toggle.
* **Modern UI Switch**: Features a sleek toggle switch to show or hide the play control bar in the lightbox (hidden by default).
* **Fullscreen Mode**: One-click immersive browsing experience.

---

## ⌨️ Keyboard Shortcuts

Enhance your efficiency with these shortcuts while the **Lightbox is open**:

| Key | Description |
| :--- | :--- |
| **Space** | **Play / Pause** automated slideshow |
| **Right Arrow (→)** | Navigate to the **Next** image (Stops slideshow) |
| **Left Arrow (←)** | Navigate to the **Previous** image (Stops slideshow) |
| **ESC** | **Close** Lightbox and return to gallery |

---

## 🚀 Quick Start

1.  **Download**: Save `webp_viewer2.html` to your local machine.
2.  **Open**: Launch the file using Chrome, Edge, or Brave.
3.  **Select Folder**: Click **📂 Select** at the top-left and grant permissions to access your image directory.

## ⚠️ Browser Support

This project utilizes the **File System Access API**. For the best experience, please use:
* **Google Chrome** (Recommended)
* **Microsoft Edge**
* **Brave** (If issues occur, disable Shields or enable relevant flags in `brave://flags`)

## 🛠 Technical Stack

* **HTML5 / CSS3**: Responsive Grid layout with modern UI Switch components.
* **Vanilla JavaScript**: Zero dependencies, ensuring lightweight and high-speed performance.
* **IndexedDB**: Used for persistent storage of Folder Handles.

---
*Created with ❤️ for efficient WebP management.*