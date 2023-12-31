<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/alacritty/alacritty">Alacritty</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/alacritty/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/alacritty?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/alacritty/issues"><img src="https://img.shields.io/github/issues/catppuccin/alacritty?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/alacritty/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/alacritty?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
  <img src="assets/screenshot.webp"/>
</p>

## Usage

> [!NOTE]
> Please see this [tag](https://github.com/catppuccin/alacritty/tree/yaml) if you need the config in YAML format.

1. Copy the config files next to your Alacritty config file (usually stored at `~/.config/alacritty/alacritty.toml`), with e.g.

```console
# mocha
curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-mocha.toml
# macchiato
curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-macchiato.toml
# frappe
curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-frappe.toml
# latte
curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-latte.toml
```

2. Import the desired flavour config in your `alacritty.toml`:

```toml
import = [
  # uncomment the flavour you want below:
  "~/.config/alacritty/catppuccin-mocha.toml"
  # "~/.config/alacritty/catppuccin-macchiato.toml"
  # "~/.config/alacritty/catppuccin-frappe.toml"
  # "~/.config/alacritty/catppuccin-latte.toml"
]
```

## 🙋 FAQ

- Q: **_"Help! the colors don't look like in the demo while I'm on Tmux. What do I do?"_**\
  A: The solution is two-fold. First, make sure you have the following set in `alacritty.toml`:

```toml
[env]
TERM = "xterm-256color"
```

Second, make sure you have the following in your `tmux.conf`:

```
set -g default-terminal "xterm-256color"
set-option -ga terminal-overrides ",xterm-256color:Tc"
```

Now you should be all set!

## 💝 Thanks to

- [VictorTennekes](https://github.com/VictorTennekes)
- [Andreas Grafen](https://github.com/andreasgrafen)

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
