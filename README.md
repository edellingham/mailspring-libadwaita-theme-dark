# Mailspring Libadwaita Theme (Dark)

A theme originally by [drakkar1969](https://github.com/drakkar1969/mailspring-libadwaita-theme) for [Mailspring](https://github.com/Foundry376/Mailspring) that matches the new [Libadwaita](https://gitlab.gnome.org/GNOME/libadwaita) theme, modified to have a white background for the email body.

## Screenshots

### Dark variant
<div align="left"><img src="screenshots/main-dark.jpg" alt="main-dark" /></div>

## Installation

Clone the repository into your Mailspring configuration folder:

```bash
git clone https://github.com/edellingham/mailspring-libadwaita-theme-dark ~/.config/Mailspring/packages
```

Restart Mailspsring and select the theme (`Edit -> Change Theme...`).

## Custom colors

Modify the color variables in the `Variant colors` section of `main.less` file for the selected variant:
* ~/.config/Mailspring/packages/Libadwaita-Dark/styles/main.less

## Papirus icons

The theme includes custom icons to match the [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) icon theme. If you want to use Mailspring's own internal icons, delete the `papirus.less` file for the selected variant:
* ~/.config/Mailspring/packages/Libadwaita-Dark/styles/papirus.less
