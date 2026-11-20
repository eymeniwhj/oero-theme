# Œro (`oero-theme`)

**Œro** (pronounced *Oero*, typed `oero` on standard keyboards) is a Windows 11 theme that fuses **2009 Frutiger Aero** glossy glass with **modern dark mode**.

The name uses the **Œ** ligature because it merges two letters into one single glyph—just like this theme merges two eras of Windows UI design into one desktop.

---

## What's in v0.1 (`oero-desktop`)
* **3 Custom 5K Wallpapers (`assets/wallpapers/`):**
  * `oero_horizon.png` — Diagonal blend of classic Windows 7 grass-and-sky Aero with dark Windows 11 mountains and glowing glass squares.
  * `oero_emblem.png` — The signature fused **Œ** logo (bubbly cyan/emerald Aero **O** + neon-edged dark **E**).
  * `oero_bloom.png` — Smooth diagonal fusion of glossy water droplets and the dark Windows 11 Bloom flower.
* **Custom "Œ" Start Button Orb (`assets/icons/oero_start_orb.png`)**
* **Windhawk Configs (`configs/`):**
  * Full-length frosted dark-glass taskbar with a glowing cyan-to-emerald Aero top highlight (`taskbar.json`)
  * Custom taskbar height & icon scaling (`taskbar-size.json`)
  * LiquidGlass refraction Start menu with diagonal Aero border glow (`start-menu.json`)
  * Start button orb replacer config (`start-orb.json`)

---

## How to Install (Windows 11)

1. **Create a System Restore Point** first just to be safe.
2. Download and install **[Windhawk](https://windhawk.net)**.
3. Install these four Windhawk mods from the **Explore** tab:
   * `Windows 11 Taskbar Styler`
   * `Windows 11 Start Menu Styler`
   * `Start Button Replacer`
   * `Taskbar height and icon size`
4. Open each mod's **Advanced** tab, paste the matching `.json` text from the `configs/` folder in this repo, and click **Save settings**.
   * *(In **Start Button Replacer**, update the image path to wherever you saved `oero_start_orb.png` on your PC.)*
5. Right-click your favorite wallpaper from `assets/wallpapers/` and select **Set as desktop background**.

---

## Roadmap
* **v0.1 — Desktop Edition** *(Current)*: Wallpapers, custom Start orb, glass taskbar, and Start menu.
* **v0.2 — Apps Edition** *(Next)*: Bringing the **Œro** glass + dark fusion into File Explorer, Discord, and browsers.

---

## Note on Assets & Contributing
I'm a 13-year-old solo creator building **Œro** from scratch with zero budget, so the wallpapers and **Œ** Start orb were generated with AI to bring the visual idea to life. If you're a designer, coder, or theme maker who wants to contribute hand-crafted icons, cursors, or app CSS themes, pull requests and issues are always welcome!
