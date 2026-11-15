# ASCII Animals — New Tab (Browser Extension)

> ASCII animals as your new tab page — butterflies, koi, jellyfish, dragonflies, frogs, cranes, and crabs, featuring a personalized time-of-day greeting, interactive click ripples, automatic browser shortcuts, and a liquid-glass search bar.>

**Live demo: [ascii-animals-extension.antideploy.app](https://ascii-animals-extension.antideploy.app)

![ASCII Animals New Tab Preview](screenshots/preview.png)

---

## ✨ Features

- **Dynamic Interactive Animals:** 7 beautiful animated ASCII creatures with realistic physics, wing flapping, and behavioral AI (Butterflies, Koi, Jellyfish, Dragonflies, Frogs, Cranes, Crabs).
- **Multiple Creature Modes:** Switch between different animals anytime using the Tweaks panel.
- **Personalized Greeting:** Prompts for your name on first install (`Good morning, [Name]`), saved locally in your browser. Click on your name anytime to edit or change it.
- **Auto Browser Shortcuts:** Automatically fetches and displays your browser's top visited sites (`topSites`). Right-click any shortcut to **Edit** (custom name/URL) or **Remove** it.
- **Multi-Browser Auto-Detect:** Automatically displays the native browser mark for **Brave**, **Google Chrome**, or **Microsoft Edge** with zero external image files; Firefox uses the extension icon.
- **Compact ASCII Clock:** Character-grid clock featuring 12-hour time, AM/PM, and subtle ambient glow.
- **Liquid Glass Search Bar:** Minimalist search pill powered by Google search.
- **Interactive Ripples:** Click anywhere on the canvas to startle the creatures and watch water ripples smoothly dissipate into a clean, dark grid.
- **Tweaks Control Panel:** Click the settings icon at the bottom-right corner to customize animal types, counts, speeds, movement, and visual themes.

---

## 📸 Screenshots & Animal Showcase

### 🐾 Creature Varieties

| 🦋 Butterflies | 🐸 Frogs |
| :---: | :---: |
| ![Butterflies](screenshots/preview.png) | ![Frogs](screenshots/frogs.png) |

| 🦀 Crabs | 🌊 Interactive Click Ripple |
| :---: | :---: |
| ![Crabs](screenshots/crabs.png) | ![Click Ripple](screenshots/click-ripple.png) |

### ⚙️ First-Time Setup
![First-Time Name Setup](screenshots/name-modal.png)

### 🎛️ Tweaks Panel

The **Tweaks** button sits at the bottom-right corner of the page. Click it to reveal the hidden animal panel, where you can switch animals and fine-tune movement and flight settings (density, direction, speed, size, flutter, glide and more).

![Tweaks button](screenshots/tweaks-button.png)

![Tweaks panel](screenshots/tweaks-panel.png)

---

## 🚀 Installation (Firefox / Brave / Chrome / Edge)

1. Clone or download this repository to your computer:
   ```bash
   git clone https://github.com/sushilbyte7/ascii-animals-extension.git
   ```
2. Open your browser's Extensions page:
   - **Firefox:** `about:debugging#/runtime/this-firefox`
   - **Brave:** `brave://extensions`
   - **Chrome:** `chrome://extensions`
   - **Edge:** `edge://extensions`
3. In Firefox, click **Load Temporary Add-on...** and select `manifest.json`. In Chromium browsers, toggle **Developer mode** to **ON**, then click **Load unpacked** and select this `ascii-animals-extension` folder.
4. Open a new tab (`Ctrl + T`) — enter your name and enjoy!

Firefox temporary add-ons are removed when Firefox closes. For a persistent Firefox installation, submit the extension to addons.mozilla.org or install a signed Firefox build.

---

## 🛠️ Tech Stack & Credits

- Built with HTML5 Canvas, modern ES Modules, and vanilla CSS.
- Forked & redesigned from Stephen's [ascii-animals](https://github.com/DesignerStephen1/ascii-animals.git) (MIT License, Copyright (c) 2026 drewdi).
- ASCII clock inspired by pursurer's `AsciiMark` (MIT License, Copyright (c) 2026 pursurer).

---

## ⬇️ Downloads

- **Stable releases:** [GitHub Releases](https://github.com/sushilbyte7/ascii-animals-extension/releases) — download the latest `ascii-animals-extension-vX.Y.zip`, unzip it, and load it unpacked (see Installation above).

---

## 📄 License

This project is licensed under the Apache License 2.0 — see [LICENSE](LICENSE) for details.

Parts of the code come from other MIT-licensed projects and keep their MIT license: Stephen's ascii-animals ([LICENSE-MIT](LICENSE-MIT)) and pursurer's AsciiMark ([LICENSE-pond](LICENSE-pond)).
