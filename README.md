# Simple Niri config/ setup (fedora) with noctalia v5

Quick reference and setup guide for my custom Niri Wayland compositor configuration.

## required dependencies 


```bash
sudo dnf install -y \
  noctalia \
  kitty \
  swaylock \
  playerctl \
  brightnessctl \
  wireplumber
```


Keybinding	Action / Command
Mod + Return	Open Terminal (kitty)
Mod + D	Open Launcher (noctalia msg panel-toggle launcher)
Super + Alt + L	Lock Screen (swaylock)
Mod + Q	Close Focused Window
Mod + Shift + E	Quit Niri (Confirmation Dialog)
Mod + Shift + /	Toggle Hotkey Overlay

## Custom Configuration Highlights

- **Touchpad & Input:** Enabled tap-to-click, natural scrolling, and numlock on startup.
- **Layout:** 16px window gaps, 50% default window width, preset column cycles (33%, 50%, 67%).
- **Aesthetics:** Ice blue focus ring (`#7fc8ff`), window borders disabled, subtle drop shadows enabled.
- **Autostart:** `noctalia` desktop shell.
- **Navigation Shortcuts:** `Mod + U` (workspace down) / `Mod + I` (workspace up) bound as workspace navigation alternatives.
