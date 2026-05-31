# Installation

## Requirements

* waybar-cava-git 
* Nerd Font (recommended)
* Cava
* pulseaudio
  

## Install

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/waybar-zoltrak.git
```

Navigate to the project directory:

```bash
cd waybar-zoltrak
```

Copy the configuration files to your Waybar directory:

```bash
mkdir -p ~/.config/waybar
cp -r * ~/.config/waybar/
```

Restart Waybar:

```bash
pkill waybar && waybar &
```

## Customization

You can edit `config` and `style.css` to match your preferences, colors, fonts, and modules.

## Screenshots

![Waybar Preview](preview.png)
