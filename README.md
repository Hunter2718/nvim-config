# 🌀 My Neovim Configuration

This is my fully customized Neovim setup, built for speed, minimalism, and a cyberpunk aesthetic — powered by [LazyVim](https://www.lazyvim.org/). It includes full support for LSP, treesitter, telescope, and more.

Whether you're a power user or just exploring Neovim for the first time, this config is designed to be extensible and easy to understand.

---

## 🚀 Features

* 🧠 Built on [LazyVim](https://www.lazyvim.org/)
* 🌈 Cyberpunk-style colors and visuals
* ⚡ Fast startup and minimal UI clutter
* 🧹 Plugin manager powered by `lazy.nvim`
* 🧠 LSP, Treesitter, Formatter, and Linter integration
* 🔍 Telescope for fuzzy finding files, symbols, and more
* 🗂️ File tree via `nvim-tree` or similar
* 🛠️ Includes helpful mappings and UX improvements

---

## 🛠️ Installation

Clone this repository into your Neovim config directory:

```bash
git clone https://github.com/Hunter2718/nvim-config ~/.config/nvim
```

Make sure you have Neovim 0.9+ installed and launch with:

```bash
nvim
```

The required plugins will install automatically on first launch via LazyVim.

---

## 📦 Requirements

* Neovim ≥ 0.9
* Git
* \[Optional] `ripgrep`, `fd`, or `rg` for Telescope
* \[Optional] `fzf`, `lazygit`, etc.

---

## 🧠 Credits

A massive thank you and shoutout to [@t3kmor3](https://www.youtube.com/@t3kmor3) and their excellent video:

📺 [How I Rice Neovim (Using LazyVim)](https://www.youtube.com/watch?v=46z_h4bNzjk)

This config builds heavily on the workflow and ideas from that video.

---

## 📁 File Structure

```
~/.config/nvim/
├── init.lua          # Entry point
├── lua/
│   ├── config/       # Custom options, keymaps, etc.
│   ├── plugins/      # Plugin specs
│   └── ...           # LazyVim overrides and extensions
└── ...
```

---

## 📸 Screenshots

*Add screenshots here if you want to show off your rice.*

---

## 📜 License

This configuration is open-source under the MIT License. Feel free to fork and adapt it!
