<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for Alacritty
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/dev/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/alacritty/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/alacritty?colorA=1e1e28&colorB=c9cbff&style=for-the-badge&logo=starship style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/alacritty/issues"><img src="https://img.shields.io/github/issues/catppuccin/alacritty?colorA=1e1e28&colorB=f7be95&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/alacritty/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/alacritty?colorA=1e1e28&colorB=b1e1a6&style=for-the-badge"></a>

<p align="center">
  <img src="assets/ss.png"/>
</p>


## Usage

1. Copy the contents of `catppuccin.yml` into your Alacritty config file (usually stored at `~/.config/alacritty/alacritty.yml`)

## 🙋 FAQ

- Q: **_"Help! the colors don't look like in the demo while I'm on Tmux. What do I do?"_**
  A: The solution is two-fold. First, make sure you have the following set in `alacritty.yml`:

```yml
env:
  TERM: xterm-256color
```

Second, make sure you have the following in your `tmux.conf`:

```
set -g default-terminal "xterm-256color"
set-option -ga terminal-overrides ",xterm-256color:Tc"
```

Now you should be all set!

## 💝 Thanks to

- [Pocco81](https://github.com/Pocco81)
- [VictorTennekes](https://github.com/VictorTennekes)