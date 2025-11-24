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
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte/dashboard.webp"/>
<img src="assets/latte/editor-jinja2.webp"/>
<img src="assets/latte/editor-yaml.webp"/>
<img src="assets/latte/devtools.webp"/>
<img src="assets/latte/settings.webp"/>
<img src="assets/latte/profile.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe/dashboard.webp"/>
<img src="assets/frappe/editor-jinja2.webp"/>
<img src="assets/frappe/editor-yaml.webp"/>
<img src="assets/frappe/devtools.webp"/>
<img src="assets/frappe/settings.webp"/>
<img src="assets/frappe/profile.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato/dashboard.webp"/>
<img src="assets/macchiato/editor-jinja2.webp"/>
<img src="assets/macchiato/editor-yaml.webp"/>
<img src="assets/macchiato/devtools.webp"/>
<img src="assets/macchiato/settings.webp"/>
<img src="assets/macchiato/profile.webp"/>
</details>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha/dashboard.webp"/>
<img src="assets/mocha/editor-jinja2.webp"/>
<img src="assets/mocha/editor-yaml.webp"/>
<img src="assets/mocha/devtools.webp"/>
<img src="assets/mocha/settings.webp"/>
<img src="assets/mocha/profile.webp"/>
</details>

## Usage

### With [HACS](https://hacs.xyz/)

> [!NOTE]
> This will install the default mauve theme shown in the example screenshots. If you wish to have a different highlight color you will need to follow the [manual installation steps](#manual) below.

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

2. Go to the [latest GitHub release](https://github.com/catppuccin/home-assistant/releases/latest)
   - If you want to install the default (mauve) theme, download the `catppuccin.yaml` file
   - If you want a different highlight color, download and extract the `catppuccin-accents.zip` file and select the accent(s) you want available
3. Move the selected file(s) to the `themes` folder in your [HA configuration directory](https://www.home-assistant.io/docs/configuration/#to-find-the-configuration-directory). (E.g. `~/config/themes`)
4. Run the `frontend.reload_themes` action or restart Home Assistant.
5. Go to the [Profile General tab](https://my.home-assistant.io/redirect/profile) and change Theme under Browser Settings to your desired theme.

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
