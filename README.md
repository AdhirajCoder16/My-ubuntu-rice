# 🌟 My Ubuntu i3wm Dotfiles

Welcome to my personal Linux rice! This repository contains my highly customized configuration files for a clean, minimalist, and productive workflow on Ubuntu using the **i3 Window Manager** and the **Catppuccin Mocha** color palette.

---

## 🎨 Preview & Aesthetics

* **Color Scheme:** Catppuccin Mocha ☕
* **Window Manager:** i3wm
* **Bar:** Polybar (Status bar showing system stats)
* **Launcher:** Rofi (Minimalist application menu)
* **Terminal:** Alacritty
* **Compositor:** Picom (For smooth animations and transparency)

---

## 📂 Repository Structure

| Directory / File | Description |
| :--- | :--- |
| `alacritty/` | Terminal configurations, padding, and Catppuccin color profile |
| `btop/` | Modern system monitor styling |
| `cava/` | Audio visualizer configuration bars and frequencies |
| `dunst/` | Minimalist notification positioning, fonts, and alert levels |
| `i3/` | Keybindings, workspace rules, autostart configurations, and layout |
| `picom/` | Compositor settings for shadows, fading, and background opacity |
| `polybar/` | Status bar setup including layout modules and the `launch.sh` script |
| `rofi/` | Application menu theme and launcher layout |
| `background` | Current desktop wallpaper image |

---

## ⚙️ How to Replicate This Setup

> [!WARNING]  
> Please back up your existing local configuration files before copying these files onto your machine!

### 1. Install Dependencies
Make sure you have all the required core software utilities installed on Ubuntu:

bash
sudo apt update
sudo apt install i3 polybar rofi alacritty picom dunst btop cava

3. Handle the Wallpaper
The configuration points natively to the background file included in this repository. Ensure your favorite wallpaper utility (such as feh or nitrogen) targets this specific file trajectory within your active initialization script.

🛠️ Key Features
Streamlined Polybar: Clean, lightweight modules tracking active workspaces, time metrics, CPU capacity, Memory footprints, and system battery percentages.

Cohesive Environment: Strict hex-code matching across all individual program stylesheets via Catppuccin Mocha colors.

Modern Rendering: Subtle background transparencies and smooth window transitions handled via Picom rules.

