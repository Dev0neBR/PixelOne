<div align="center">

# 🎨 PixelOne

**A pixel art editor for Android.**

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?logo=kotlin&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![Release](https://img.shields.io/badge/Release-Aug%2010%2C%202026-blue)
![UI Refactor](https://img.shields.io/badge/UI%20Refactor-100%25-brightgreen)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-lightgrey)

</div>

---

PixelOne is a pixel art editor for Android, made for creating sprites, textures and small pixel art projects in a simple way.

> The idea came up when I was trying to make a texture for Minecraft PE and couldn't find an editor that really fit what I needed. Most of the ones I tried felt outdated or too generic, so I ended up building my own.

It's for artists, developers, or really anyone who wants to make pixel art without dealing with unnecessary complexity. You open it, you draw, that's it.

The project is still in development and will keep getting updates and new features over time.

> **Update (August 8, 2026):** the UI refactor is complete — 100%, including an improved window/layout system. Release is confirmed for **August 10, 2026**, no further delays.

---

## 📚 Table of Contents

- [Features](#-features)
- [Sprite Sheet Generator](#-sprite-sheet-generator)
- [Development](#-development)
- [Massive UI Refactor](#-massive-ui-refactor)
- [Community](#-community)
- [Project Status & Risks](#-project-status--risks)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features

| Tool | Description |
|---|---|
| ✏️ Pencil | Basic drawing tool |
| 🧹 Eraser | Clear pixels |
| 🪣 Paint bucket | Fill areas fast |
| 🎯 Color picker | Grab any color from the canvas |
| 🎨 Color palette | Manage your colors |
| 🔍 Zoom | Get in close for detail work |
| 🔳 Grid view | Toggle the pixel grid |
| ↩️ Undo/redo | Full history support |
| 📥 Import | Bring in existing images |
| 📤 Export | Save as PNG or JPG |
| 🖼️ Sprite Sheet Generator | Combine multiple images into one sheet |

Canvas size is fully customizable, up to a max of `4096x4096`.

---

## 🧩 Sprite Sheet Generator

Select multiple images and PixelOne stitches them into a single `sprite_sheet.png`, along with a JSON file describing the layout, ready to plug into a game engine.

```
Output: /0/Sprite Sheet
```

> ⚠️ Very large projects can slow down on lower-end devices. Optimization is ongoing.

---

## 🛠️ Development

<details>
<summary><strong>Java → Kotlin migration and why the release got delayed</strong> (click to expand)</summary>

<br>

PixelOne is written in **Kotlin** now, it used to be Java, but the whole codebase got migrated over.

I won't lie, development has had its share of problems, a lot of them actually. Between the Java to Kotlin migration and fixing bugs and performance issues along the way, things took longer than planned to get stable. Because of that, the release date got pushed back.

</details>

<div align="center">

**🗓️ Release date: August 10, 2026 (confirmed, no more delays)**

</div>

The release will include the APK, a changelog, and future updates through GitHub.

---

## 🎨 Massive UI Refactor

PixelOne just went through its biggest refactor since development started.

The previous interface worked, but over time it accumulated a lot of design problems. Some screens felt inconsistent, certain layouts were difficult to use, and the overall appearance looked outdated, almost like software from the early 2000s. While functional, it didn't match the quality or experience I want PixelOne to deliver.

Instead of applying small visual fixes, a large part of the application was redesigned from the ground up. This refactor focused on creating a cleaner, more modern interface while also improving the internal structure of the UI, making future updates easier to develop and maintain.

### 📈 Current Progress

**Status: 100% complete ✅**

The refactor is done, including a reworked window/layout system, theme polish, and responsiveness edge cases.

This work took longer than expected, but it provides a much stronger foundation for future features and significantly improves the overall user experience.

### 🔄 What's Changed

- Completely redesigned interface
- Modern and minimalistic icon set
- Improved window/layout system
- Cleaner layouts with better spacing and organization
- Better navigation and workflow
- Improved responsiveness across different screen sizes
- More consistent visual language throughout the application
- Better use of screen space, giving more focus to the canvas

### 🧭 New Design Philosophy

The new interface is designed around simplicity.

Instead of filling the screen with unnecessary buttons and clutter, PixelOne aims to keep the workspace clean, allowing the canvas to remain the center of attention.

The redesign follows a modern flat style with improved usability, smoother interactions, and a more polished overall appearance.

### 🌗 Customizable Themes

PixelOne will support multiple appearance themes:

| Theme | Description |
|---|---|
| 🌑 Dark | Default, easy on the eyes |
| 🌌 Midnight Blue | Cool toned |
| ☀️ Light | For daytime and high brightness use |

More themes may be added in future updates based on community feedback.

The goal is to let every user choose the appearance that feels most comfortable, whether working during the day or late at night.

---

## 💬 Community

A Discord server for PixelOne is planned, so users can share art, report bugs, and follow development more closely. It's not up yet, mostly a matter of finding the time/motivation to set it up, but it's on the list.

---

## ⚠️ Project Status & Risks

Development doesn't always move at a constant pace, sometimes there are gaps of several days without commits or updates. That doesn't mean the project is abandoned, PixelOne is still alive and actively worked on.

That said, there are real risks that could affect the project's future:

- **Google's upcoming sideload restrictions**: Google has been rolling out stricter requirements for installing apps outside the Play Store, which could make distributing PixelOne as a standalone APK harder or impossible down the line.
- **No budget for the Play Store**: publishing on the Google Play Store requires a one-time $25 registration fee, which I currently can't afford. Without it, PixelOne can't be officially published there.
- **Hardware limitations**: my current PC can't run Android Studio properly, so development relies on a more limited setup. If the project has to stop, picking it back up in a proper environment could take a long time, realistically, possibly years.

Because of this, there's a real chance development could pause or end at some point without much warning. If that happens, this README and the repo will reflect the project's status honestly.

---

## 🗺️ Roadmap

- [ ] **Layers**: separate outlines, base colors, shading and details into stacked layers instead of one flat canvas
- [ ] **Move tool**: shift a selection around the canvas
- [ ] **Mirror tool**: flip your art horizontally or vertically, great for symmetrical sprites
- [ ] **Stamp tool**: save a piece of art and drop copies of it wherever you need
- [ ] **Colors panel improvements**: better organization, custom palettes
- [ ] **Performance work**: keep bigger canvases and sprite sheets running smoothly
- [ ] **Discord server**: official community space for feedback and updates
- [ ] Whatever comes up based on real usage and feedback

---

## 🤝 Contributing

Suggestions, bug reports and feedback are welcome, just open a [GitHub Issue](../../issues).

## 📄 License

No license added yet. All rights reserved.
