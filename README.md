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
  <img src="assets/preview.webp"/>
</p>

## Previews

<details>
  <summary>🌻 Latte</summary>
  <img src="assets/latte.webp"/>
</details>
<details>
  <summary>🪴 Frappé</summary>
  <img src="assets/frappe.webp"/>
</details>
<details>
  <summary>🌺 Macchiato</summary>
  <img src="assets/macchiato.webp"/>
</details>
<details>
  <summary>🌿 Mocha</summary>
  <img src="assets/mocha.webp"/>
</details>

## Usage

> [!NOTE]  
> Please see the [`yaml`](https://github.com/catppuccin/alacritty/tree/yaml) tag if you need the config in YAML format.

1. Copy the theme files next to your `alacritty.toml` configuration file.
   See [Alacritty's README](https://github.com/alacritty/alacritty#configuration) to see where your config file can be
   stored, it is usually stored at `~/.config/alacritty/alacritty.toml`

    - Latte
      ```shell
      curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-latte.toml
      ```

    - Frappé
      ```shell
      curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-frappe.toml
      ```

    - Macchiato
      ```shell
      curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-macchiato.toml
      ```

    - Mocha
      ```shell
      curl -LO --output-dir ~/.config/alacritty https://github.com/catppuccin/alacritty/raw/main/catppuccin-mocha.toml
      ```

2. Import the desired flavour config in your `alacritty.toml`:

    ```toml
    general.import = [
      # uncomment the flavour you want below:
      "~/.config/alacritty/catppuccin-latte.toml"
      # "~/.config/alacritty/catppuccin-frappe.toml"
      # "~/.config/alacritty/catppuccin-macchiato.toml"
      # "~/.config/alacritty/catppuccin-mocha.toml"
    ]
    ```

## 🙋 FAQ

- Q: **_"My colours don't look the same as the previews. What do I do?"_**\
  A: Make sure you have the following set in `alacritty.toml`:

  ```toml
  [env]
  TERM = "xterm-256color"
  ```

- Q: **_"What font have you used in the screenshots above?"_**\
  A: [Iosevka Term](https://typeof.net/Iosevka/)

## 💝 Thanks to

- [VictorTennekes](https://github.com/VictorTennekes)
- [Andreas Grafen](https://github.com/andreasgrafen)

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
