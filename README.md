# PixelOne

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?logo=kotlin&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![Release](https://img.shields.io/badge/Release-Aug%2010%2C%202026-blue)

PixelOne is a pixel art editor for Android, made for creating sprites, textures and small pixel art projects in a simple way.

> The idea came up when I was trying to make a texture for Minecraft PE and couldn't find an editor that really fit what I needed. Most of the ones I tried felt outdated or too generic, so I ended up building my own.

It's for artists, developers, or really anyone who wants to make pixel art without dealing with unnecessary complexity. You open it, you draw, that's it.

The project is still in development and will keep getting updates and new features over time.

## Features

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

### Sprite Sheet Generator

Select multiple images and PixelOne stitches them into a single `sprite_sheet.png`, along with a JSON file describing the layout, ready to plug into a game engine.

```
Output: /0/Sprite Sheet
```

> ⚠️ Very large projects can slow down on lower-end devices. Optimization is ongoing.

## Development

<details>
<summary><strong>Java → Kotlin migration and why the release got delayed</strong> (click to expand)</summary>

<br>

PixelOne is written in **Kotlin** now, it used to be Java, but the whole codebase got migrated over.

I won't lie, development has had its share of problems, a lot of them actually. Between the Java to Kotlin migration and fixing bugs and performance issues along the way, things took longer than planned to get stable. Because of that, the release date got pushed back.

</details>

**New release date: August 10, 2026**

The release will include the APK, a changelog, and future updates through GitHub.

## Roadmap

- [ ] **Layers** — separate outlines, base colors, shading and details into stacked layers instead of one flat canvas
- [ ] **Move tool** — shift a selection around the canvas
- [ ] **Mirror tool** — flip your art horizontally or vertically, great for symmetrical sprites
- [ ] **Stamp tool** — save a piece of art and drop copies of it wherever you need
- [ ] **Colors panel improvements** — better organization, custom palettes
- [ ] **Performance work** — keep bigger canvases and sprite sheets running smoothly
- [ ] Whatever comes up based on real usage and feedback

## Contributing

Suggestions, bug reports and feedback are welcome, just open a [GitHub Issue](../../issues).

## License

No license added yet. All rights reserved.
