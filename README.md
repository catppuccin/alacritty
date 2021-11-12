<p align="center">
  <h2 align="center">😸 Catppuccin for Alacritty</h2>
</p>

<p align="center">Warm mid-tone dark theme to show off your vibrant self!</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/catppuccin/alacritty/main/assets/ss.png"/>
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

- @Pocco81
