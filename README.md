<div align="center">

# 🎨 PixelOne

**A pixel art editor for Android.**

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?logo=kotlin&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![Release](https://img.shields.io/badge/Release-Aug%2010%2C%202026-blue)
![UI Refactor](https://img.shields.io/badge/UI%20Refactor-90%25-orange)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-lightgrey)
![Made with](https://img.shields.io/badge/Made%20with-Termux%20%26%20Stubbornness-critical)

</div>

---

PixelOne is a pixel art editor for Android, made for creating sprites, textures and small pixel art projects in a simple way.

> The idea came up when I was trying to make a texture for Minecraft PE and couldn't find an editor that really fit what I needed. Most of the ones I tried felt outdated or too generic, so I ended up building my own.

It's for artists, developers, or really anyone who wants to make pixel art without dealing with unnecessary complexity. You open it, you draw, that's it.

The project is still in development and will keep getting updates and new features over time.

<div align="center">

### 📊 Refactor Progress

![Progress](https://progress-bar.dev/90/?title=UI%20Refactor&width=400&color=babaca)

</div>

> 🐌 **Real talk:** the refactor was supposed to land on July 20. It's July 21 and it's sitting at 90%, not 100%. Yeah, I'm late — turns out "just polishing" always takes longer than expected. No excuses, just a dev who underestimated his own to-do list. It's close though, promise.

---

## 📚 Table of Contents

- [Features](#-features)
- [Sprite Sheet Generator](#-sprite-sheet-generator)
- [Development](#-development)
- [Massive UI Refactor](#-massive-ui-refactor)
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

**🗓️ New release date: August 10, 2026**

</div>

The release will include the APK, a changelog, and future updates through GitHub.

---

## 🎨 Massive UI Refactor

PixelOne is currently going through its biggest refactor since development started.

The previous interface worked, but over time it accumulated a lot of design problems. Some screens felt inconsistent, certain layouts were difficult to use, and the overall appearance looked outdated — almost like software from the early 2000s. While functional, it didn't match the quality or experience I want PixelOne to deliver.

Instead of applying small visual fixes, a large part of the application is being redesigned from the ground up. This refactor focuses on creating a cleaner, more modern interface while also improving the internal structure of the UI, making future updates easier to develop and maintain.

### 📈 Current Progress

```
[██████████████████░░] 90%
```

The refactor was originally targeted for **July 20, 2026**. It's now past that date and still at 90% — the last stretch (theme polish + responsiveness edge cases) is what's holding it up. Closing this out is the top priority right now.

Although this work increases development time, it provides a much stronger foundation for future features and significantly improves the overall user experience.

### 🔄 What's Changing?

- Completely redesigned interface
- Modern and minimalistic icon set
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

| Theme | Vibe |
|---|---|
| 🌑 Dark | Default, easy on the eyes |
| 🌌 Midnight Blue | Cool-toned, moody |
| ☀️ Light | Daytime / high-brightness use |

More themes may be added in future updates based on community feedback.

The goal is to let every user choose the appearance that feels most comfortable, whether working during the day or late at night.

> ⚠️ This refactor affects a large portion of the application's interface. While it delays development slightly, it creates a much stronger foundation for upcoming features such as Layers, the Move Tool, Animation improvements, and many other future updates.

---

## 🗺️ Roadmap

- [ ] **Layers** — separate outlines, base colors, shading and details into stacked layers instead of one flat canvas
- [ ] **Move tool** — shift a selection around the canvas
- [ ] **Mirror tool** — flip your art horizontally or vertically, great for symmetrical sprites
- [ ] **Stamp tool** — save a piece of art and drop copies of it wherever you need
- [ ] **Colors panel improvements** — better organization, custom palettes
- [ ] **Performance work** — keep bigger canvases and sprite sheets running smoothly
- [ ] Whatever comes up based on real usage and feedback

---

## 🤝 Contributing

Suggestions, bug reports and feedback are welcome, just open a [GitHub Issue](../../issues).

## 📄 License

No license added yet. All rights reserved.

<div align="center">
</div>
