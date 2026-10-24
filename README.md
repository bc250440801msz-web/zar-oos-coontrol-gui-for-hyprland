# zar-oos-coontrol-gui-for-hyprland
cat << 'EOF' > ~/ZarOS-Engine/README.md
# ⚡ ZarOS Studio

> A lightweight, standalone GUI Control Center for Hyprland — built with Python & CustomTkinter.

ZarOS Studio brings a KDE-like visual configuration experience to Hyprland without requiring manual edits to `hyprland.conf`.

---

## ✨ Features

- **Desktop Personality Profiles:** One-click presets (Cyber Neon, Nordic Minimal, Solarized Glass).
- **System Appearance Sync:** Instant toggle between Dark Mode and Light Mode for GTK apps.
- **Live Interactive Sandbox:** Realtime preview of window rounding, outer gaps, and border glow.
- **Wallpaper Palette Sync:** Automatically extracts accent colors from your wallpaper and injects them into Hyprland borders.
- **Hardware & Inputs:** Touchpad natural scrolling, tap-to-click, and display scaling controls.
- **Safety Vault & 10s Rollback:** Test settings with a 10-second fail-safe auto-revert timer to prevent lockouts.

---

## 🚀 Installation

### Universal (Fedora, Arch, Debian)
```bash
git clone [https://github.com/shahzartaqi/zaros-studio.git](https://github.com/shahzartaqi/zaros-studio.git)
cd zaros-studio
sudo ./install.sh
