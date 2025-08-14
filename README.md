# 🗂️ My Dotfiles

This repository contains my personal configuration files (“dotfiles”) for various tools and development environments.  
Currently included:

- **Neovim** (`nvim/`) — Custom configuration, plugins, and key mappings.
- **tmux** (`tmux/`) — `.tmux.conf` with keybindings.

The goal is to have a single place to manage and version-control my configurations, making it easy to synchronize them across different machines.

---

## 🚀 Quick Installation (coming soon)

I’m working on a small **CLI utility** that will:

- Automatically copy the files from this repository to the correct locations (e.g. `~/.config/nvim`, `~/.tmux.conf`, etc.).
- Install any required **plugins** and **programs**.
- Allow quick updates to already installed dotfiles.

> 💡 For now, you can clone the repository and manually copy the files to the appropriate locations.  
> Example:
> ```bash
> git clone https://github.com/EmanueleValentini/Dots.git ~/dotfiles
> cp -r ~/dotfiles/nvim ~/.config/nvim
> cp ~/dotfiles/tmux/.tmux.conf ~/
> ```

---

## 📂 Repository Structure

```text
dotfiles/
├── nvim/          # Neovim configuration and plugins
│   ├── init.lua
│   └── lua/       # Lua modules for Neovim
├── tmux/
│   └── .tmux.conf # tmux configuration
└── README.md
```
---

## 🔜 Roadmap

- [ ] Add an automatic installation script (`install.sh` or `setup.py`)
- [ ] Add configurations for **zsh**, **fish**, and other tools
- [ ] Continuous updates as I refine my setup

---

## 📜 License

Released under the [MIT License](LICENSE) — feel free to use and adapt.
