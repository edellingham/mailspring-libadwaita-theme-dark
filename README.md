# Mailspring Libadwaita Theme (Dark)

A theme originally by [drakkar1969](https://github.com/drakkar1969/mailspring-libadwaita-theme) for [Mailspring](https://github.com/Foundry376/Mailspring) that matches the new [Libadwaita](https://gitlab.gnome.org/GNOME/libadwaita) theme, modified to have a light background for the email body while preserving original email styling.

## Features

- **Dark theme** for the Mailspring interface matching Libadwaita design
- **Light email background** for better readability of email content
- **Preserves original email styling** - marketing emails, newsletters, and styled emails maintain their intended appearance
- **Smart color handling** - only overrides text colors when necessary for readability
- **Custom Papirus icons** to match the Papirus icon theme

## Screenshots

### Dark variant
<div align="left"><img src="screenshots/main-dark.jpg" alt="main-dark" /></div>

## Installation

Clone the repository into your Mailspring configuration folder:

```bash
git clone https://github.com/edellingham/mailspring-libadwaita-theme-dark ~/.config/Mailspring/packages
```

Restart Mailspsring and select the theme (`Edit -> Change Theme...`).

## Email Styling Approach

This theme uses a smart approach to email styling:

1. **Light container background** - Sets a light gray background (`#f8f8f8`) for the email container
2. **Preserves original styling** - Allows emails to use their own backgrounds, colors, and styling
3. **Selective overrides** - Only forces dark text when the original text would be unreadable (e.g., white text on light background)
4. **Fallback styling** - Provides sensible defaults for unstyled elements like blockquotes and code blocks

This ensures that:
- Marketing emails and newsletters look as intended
- Plain text emails are readable with dark text on light background
- Styled emails maintain their original design
- The overall interface remains dark for consistency

## Custom colors

Modify the color variables in the `Variant colors` section of `main.less` file for the selected variant:
* ~/.config/Mailspring/packages/Libadwaita-Dark/styles/main.less

## Papirus icons

The theme includes custom icons to match the [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) icon theme. If you want to use Mailspring's own internal icons, delete the `papirus.less` file for the selected variant:
* ~/.config/Mailspring/packages/Libadwaita-Dark/styles/papirus.less
