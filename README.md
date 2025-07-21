# 🎮 cachyos-xfce-i3-gaming

A lightweight Arch-based hybrid gaming setup using **XFCE + i3**, themed with **TokyoNight**, optimized for performance and style. Includes preconfigured game launchers, rofi integration, Whisker Menu support, and a one-liner installer.

![preview](preview/preview.gif)

---

### ✅ Features

- 🧠 Hybrid XFCE + i3 session (with LightDM selector)
- 🎮 Game `.desktop` launchers (Steam + native)
- 💠 rofi games menu (`$mod+g`)
- 🌌 TokyoNight GTK + i3 theming
- ⚡ Gamemode + performance tweaks
- 🧭 Whisker menu support
- 🖼 Beautiful wallpapers
- 🧩 Plug-and-play dotfiles

---

### 🖥️ Target Hardware

- CPU: Intel i5-4430  
- GPU: AMD RX 580  
- RAM: 16GB  
- SSD: 500GB  
- OS: [CachyOS](https://cachyos.org) (Arch-based)

---

### 📦 Included Game Launchers

- The Division 2  
- The First Descendant  
- Fallout 4  
- Far Cry 5 & 6  
- Warframe  
- Cyberpunk 2077  
- Horizon Zero Dawn  
- Shadow of the Tomb Raider  

---

### 🧪 Installation

#### One-liner:
```bash
bash <(curl -s https://raw.githubusercontent.com/CrowdRocker/cachyos-xfce-i3-gaming/main/install.sh)

Or manually:
git clone https://github.com/CrowdRocker/cachyos-xfce-i3-gaming.git
cd cachyos-xfce-i3-gaming
chmod +x install.sh
./install.sh

🔁 Switch to XFCE+i3 Session
After reboot, choose XFCE+i3 from the LightDM login session selector.

🕹️ Launch Games
You can:
Use Whisker Menu or rofi to launch installed games


Hit $mod+g to bring up the rofi Games Menu


Steam launch options use gamemoderun by default



💠 Theme Preview
📁 Folder Structure

├── install.sh
├── README.md
├── dotfiles/
│   ├── i3/
│   ├── xfce/
│   ├── rofi/
│   ├── desktop/
│   └── lightdm/
├── wallpapers/
└── preview/

🛠️ Customize
Edit the i3 config:
~/.config/i3/config

Edit rofi script:
~/.config/rofi/rofi-games.sh

Add more launchers to:
~/.local/share/applications/

📸 Credits
Theme: TokyoNight


Games: Launchers made for personal use


Base Distro: CachyOS



✨ Maintainer
CrowdRocker
🕹️ Twitch-ready, keyboard-focused gaming setups
🎯 Built for performance, beauty, and control

