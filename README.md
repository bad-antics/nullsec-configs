<div align="center">

# ⚙️ NullSec Configs

### Hacker Dotfiles & System Configurations

**by bad-antics development**

[![License: NPL](https://img.shields.io/badge/License-NullSec%20Public-red.svg)](LICENSE)
[![Shell](https://img.shields.io/badge/Shell-Bash%20%26%20Zsh-green.svg)]()
[![GitHub](https://img.shields.io/badge/GitHub-bad--antics-black?logo=github)](https://github.com/bad-antics)

```
     ██████╗ ██████╗ ███╗   ██╗███████╗██╗ ██████╗ ███████╗
    ██╔════╝██╔═══██╗████╗  ██║██╔════╝██║██╔════╝ ██╔════╝
    ██║     ██║   ██║██╔██╗ ██║█████╗  ██║██║  ███╗███████╗
    ██║     ██║   ██║██║╚██╗██║██╔══╝  ██║██║   ██║╚════██║
    ╚██████╗╚██████╔╝██║ ╚████║██║     ██║╚██████╔╝███████║
     ╚═════╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝     ╚═╝ ╚═════╝ ╚══════╝

            [ bad-antics development | Dotfiles ]
```

</div>

---

## 📦 What's Included

### Shell Configuration

| File | Description |
|------|-------------|
| `.bashrc` | Bash configuration with aliases |
| `.zshrc` | Zsh configuration with plugins |
| `.profile` | Environment variables |
| `.aliases` | Security-focused aliases |

### Terminal

| Config | Application |
|--------|-------------|
| `alacritty.yml` | Alacritty terminal |
| `kitty.conf` | Kitty terminal |
| `tmux.conf` | Tmux multiplexer |

### Editor

| Config | Application |
|--------|-------------|
| `init.vim` | Neovim configuration |
| `vscode/settings.json` | VS Code settings |
| `.nanorc` | Nano configuration |

### Desktop

| Config | Application |
|--------|-------------|
| `i3/config` | i3 window manager |
| `sway/config` | Sway (Wayland) |
| `polybar/` | Status bar |
| `rofi/` | Application launcher |
| `dunst/` | Notifications |

### Security Tools

| Config | Application |
|--------|-------------|
| `proxychains.conf` | Proxy configuration |
| `nmap/scripts/` | Custom NSE scripts |
| `metasploit/` | MSF resource files |

---

## 🚀 Quick Install

```bash
git clone https://github.com/bad-antics/nullsec-configs.git
cd nullsec-configs
./install.sh
```

### Selective Install

```bash
# Shell only
./install.sh --shell

# Terminal only
./install.sh --terminal

# Full desktop
./install.sh --full
```

---

## 🎨 Features

### Custom Prompt

```
┌──[bad-antics]─[user@host]─[~/path]
└──╼ $
```

### Useful Aliases

```bash
# Security aliases
alias scan='nullsec-scan'
alias crack='nullsec-crack'
alias tunnel='nullsec-tunnel'

# Navigation
alias ..='cd ..'
alias ...='cd ../..'

# Safety
alias rm='rm -i'
alias cp='cp -i'
alias mv='mv -i'
```

### Tmux Layout

Pre-configured layouts for:
- Penetration testing
- Monitoring
- Development

---

## 📁 Structure

```
nullsec-configs/
├── shell/
│   ├── bashrc
│   ├── zshrc
│   ├── aliases
│   └── profile
├── terminal/
│   ├── alacritty.yml
│   ├── kitty.conf
│   └── tmux.conf
├── editor/
│   ├── nvim/
│   └── vscode/
├── desktop/
│   ├── i3/
│   ├── sway/
│   ├── polybar/
│   └── rofi/
├── security/
│   ├── proxychains.conf
│   └── nmap/
└── install.sh
```

---

## 🔗 Related

- [nullsec-linux](https://github.com/bad-antics/nullsec-linux)
- [nullsec-tools](https://github.com/bad-antics/nullsec-tools)
- [nullsec-themes](https://github.com/bad-antics/nullsec-themes)

---

## 🏷️ Keywords

`dotfiles` `linux configuration` `bash config` `zsh config` `tmux config`
`i3 config` `sway config` `alacritty config` `neovim config` `hacker setup`
`terminal customization` `r/unixporn` `rice` `bad-antics` `nullsec`
`security dotfiles` `pentesting setup` `developer config`

---

<div align="center">

**Developed with ⚙️ by [bad-antics](https://github.com/bad-antics)**

*NullSec Project © 2025*

</div>

[![GitHub](https://img.shields.io/badge/GitHub-bad--antics-181717?style=flat&logo=github&logoColor=white)](https://github.com/bad-antics)
[![Discord](https://img.shields.io/badge/Discord-killers-5865F2?style=flat&logo=discord&logoColor=white)](https://discord.gg/killers)
