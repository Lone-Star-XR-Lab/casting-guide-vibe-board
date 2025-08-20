# Meta Quest to Vibe Board Casting Guide

This repo contains a printable step-by-step guide for casting the view from a **Meta Quest 2, Quest Pro, or Quest 3** headset to a **Vibe Smart Whiteboard**.

It's designed for students, instructors, and XR lab staff at **Lone Star College**, but can be adapted for use in any VR-enabled learning environment.

---

## 📄 What's Included

* **HTML guide** (`quest-casting-guide.html`)
  A clean, print-optimized walkthrough using Tailwind CSS and live screenshots.

* **Images folder** (`/images`)
  All the screenshots and icons used in the guide:

  * Quest menu flow (Camera, Cast, Web)
  * Vibe board casting page
  * Full screen button
  * Meta button icon

---

## 🖨️ Printing the Guide

Open `quest-casting-guide.html` in any modern browser and hit **Ctrl+P** or use the **Print This Guide** button at the bottom.

* Formats cleanly across 1–2 pages
* Includes embedded screenshots and icons
* Hides UI elements during print

---

## 🪰 Technologies

* [Tailwind CSS](https://tailwindcss.com/) via CDN (requires internet connection)

> ⚠️ **Offline note:** This guide depends on Tailwind via CDN.
> To use the guide fully offline (e.g., air-gapped labs), you’ll need to generate a local CSS file using Tailwind CLI and update the link in the HTML.
>
> See: [Tailwind CLI Production Build](https://tailwindcss.com/docs/installation)

---

## 🌐 Use Case

Designed for use in:

* Classroom VR sessions
* XR lab check-ins and tutorials
* Onboarding materials for students and faculty

---

## 📂 Folder Structure

```
├── quest-casting-guide.html       # Main printable guide
├── images/
│   ├── quest-camera.jpg
│   ├── quest-cast.jpg
│   ├── quest-web.jpg
│   ├── meta-button-icon.png
│   ├── vibe-casting-page.png
│   └── vibe-fullscreen-paint.png
└── README.md                      # This file
```

---

