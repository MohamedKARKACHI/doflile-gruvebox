<p align="center">
  <img src="./i3/walls/wall2.jpg" alt="Gruvbox Theme Preview" width="100%"/>
</p>

<h1 align="center">🎨 Dotfiles Gruvbox Theme</h1>

<p align="center">
  <strong>A beautiful, carefully crafted Linux desktop environment with the warm Gruvbox color palette</strong>
</p>

<p align="center">
  <a href="#-features"><img src="https://img.shields.io/badge/Features-✨-orange?style=for-the-badge" alt="Features"/></a>
  <a href="#-installation"><img src="https://img.shields.io/badge/Install-🚀-green?style=for-the-badge" alt="Install"/></a>
  <a href="#-configurations"><img src="https://img.shields.io/badge/Configs-📦-blue?style=for-the-badge" alt="Configs"/></a>
  <a href="https://github.com/MohamedKARKACHI/doflile-gruvebox/stargazers"><img src="https://img.shields.io/github/stars/MohamedKARKACHI/doflile-gruvebox?style=for-the-badge&color=yellow" alt="Stars"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white" alt="Neovim"/>
  <img src="https://img.shields.io/badge/i3wm-2E7D32?style=flat-square&logo=i3&logoColor=white" alt="i3"/>
  <img src="https://img.shields.io/badge/Kitty-000000?style=flat-square&logo=gnome-terminal&logoColor=white" alt="Kitty"/>
</p>

---

## ✨ Features

- 🎨 **Gruvbox Color Scheme** - Warm, retro-inspired colors that are easy on the eyes
- 🪟 **i3 Window Manager** - Efficient tiling with custom keybindings and workspace setup
- ⚡ **GPU-Accelerated Terminal** - Kitty terminal with Gruvbox styling
- 📝 **Neovim IDE** - Full-featured code editor with LSP, autocomplete, and plugins
- 🔍 **Rofi Launcher** - Beautiful application launcher with Gruvbox theme
- 🖼️ **Picom Compositor** - Smooth animations and transparency effects
- 📁 **Yazi File Manager** - Lightning-fast terminal file manager

---

## 📦 Configurations

| Tool | Description | Status |
|:----:|:------------|:------:|
| <img src="https://img.shields.io/badge/i3-2E7D32?style=flat-square&logo=i3&logoColor=white" width="60"/> | Tiling window manager with workspaces, keybinds, and autostart | ✅ |
| <img src="https://img.shields.io/badge/Kitty-000000?style=flat-square" width="60"/> | GPU-accelerated terminal emulator | ✅ |
| <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white" width="60"/> | Modern Vim with LSP, Treesitter, and NvChad base | ✅ |
| <img src="https://img.shields.io/badge/Picom-333333?style=flat-square" width="60"/> | X11 compositor for shadows and transparency | ✅ |
| <img src="https://img.shields.io/badge/Rofi-1793D1?style=flat-square" width="60"/> | Application launcher and dmenu replacement | ✅ |
| <img src="https://img.shields.io/badge/Yazi-FF6B6B?style=flat-square" width="60"/> | Blazing fast terminal file manager | ✅ |

---

## 🚀 Installation

### Quick Install

```bash
# Clone the repository
git clone https://github.com/MohamedKARKACHI/doflile-gruvebox.git
cd doflile-gruvebox

# Backup your existing configs (recommended)
mkdir -p ~/.config-backup
cp -r ~/.config/i3 ~/.config/kitty ~/.config/nvim ~/.config/picom ~/.config/rofi ~/.config/yazi ~/.config-backup/ 2>/dev/null

# Install configurations
cp -r i3 kitty nvim picom rofi yazi ~/.config/
```

### Manual Installation

1. **Clone** this repository
2. **Copy** individual folders to `~/.config/`
3. **Reload** your window manager

---

## 🎹 Keybindings

| Key | Action |
|-----|--------|
| `Super + Enter` | Open terminal |
| `Super + D` | Open Rofi launcher |
| `Super + Q` | Close window |
| `Super + 1-9` | Switch workspace |
| `Super + Shift + 1-9` | Move window to workspace |
| `Super + H/J/K/L` | Navigate windows |

---

## 🖼️ Wallpapers

Beautiful wallpapers are included in `i3/walls/`:

<p align="center">
  <img src="./i3/walls/wall.jpg" alt="Wallpaper 1" width="45%"/>
  <img src="./i3/walls/wall2.jpg" alt="Wallpaper 2" width="45%"/>
</p>

---

## 📋 Dependencies

```bash
# Arch Linux / Manjaro
sudo pacman -S i3-wm kitty neovim picom rofi yazi

# Ubuntu / Debian
sudo apt install i3 kitty neovim picom rofi
# Note: Install yazi separately from GitHub releases
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. ⭐ **Star** this repository
2. � **Fork** and submit pull requests
3. 🐛 **Report** issues or bugs
4. 💡 **Suggest** new features

---

## 👤 Author

<p align="center">
  <img src="https://github.com/MohamedKARKACHI.png" width="100" style="border-radius: 50%"/>
  <br/>
  <strong>Mohamed KARKACHI</strong>
  <br/>
  <a href="https://github.com/MohamedKARKACHI">@MohamedKARKACHI</a>
</p>

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  <strong>If you like this project, please consider giving it a ⭐!</strong>
  <br/><br/>
  <a href="https://github.com/MohamedKARKACHI/doflile-gruvebox/stargazers">
    <img src="https://img.shields.io/github/stars/MohamedKARKACHI/doflile-gruvebox?style=social" alt="GitHub Stars"/>
  </a>
</p>
