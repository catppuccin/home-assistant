<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://www.home-assistant.io/">Home Assistant</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/home-assistant/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/home-assistant?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/home-assistant/issues"><img src="https://img.shields.io/github/issues/catppuccin/home-assistant?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/home-assistant/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/home-assistant?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Overview/Overview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/Overview.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/Map.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/Logbook.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/History.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/Code.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/Devtools.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/Settings.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Latte/Profile.webp"/>

</details>
<details>
<summary>🪴 Frappé</summary>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/Overview.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/Map.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/Logbook.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/History.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/Code.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/Devtools.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/Settings.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Frappe/Profile.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/Overview.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/Map.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/Logbook.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/History.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/Code.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/Devtools.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/Settings.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Macchiato/Profile.webp"/>
</details>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/Overview.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/Map.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/Logbook.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/History.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/Code.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/Devtools.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/Settings.webp"/>
<img src="https://raw.githubusercontent.com/catppuccin/home-assistant/main/assets/Mocha/Profile.webp"/>
</details>

## Usage

### With [HACS](https://hacs.xyz/)

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Go to the Community Store.
3. Search for `Catppuccin`.
4. Navigate to `Catppuccin` theme.
5. Press `Install`.
6. Go to Developer Tools, and next Actions. Then select and manually trigger the `frontend.reload_actions` action.
7. Go to the [Profile General tab](https://my.home-assistant.io/redirect/profile) and change Theme under Browser Settings to your desired theme.

### Manual

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Clone the repository

```bash
git clone https://github.com/catppuccin/home-assistant.git
```

3. Copy `themes/catppuccin.yaml` in your existing (or create it) `themes/` folder.

```bash
mv home-assistant/themes/catppuccin.yaml ~/config/themes/.
```

4. Go to the [Profile General tab](https://my.home-assistant.io/redirect/profile) and change Theme under Browser Settings to your desired theme.

## 💝 Thanks to

- [fapfaff](https://github.com/fapfaff)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
