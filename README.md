# Primer Dark

**TL;DR:** Primer Dark, Primer with a dark mode.

The [official Primer](https://github.com/pages-themes/primer) is a popular
Jekyll theme for GitHub Pages that renders markdown files in light mode. Primer
Dark adds a dark mode that automatically activates based on the client's browser
settings. This theme reverts to the original Primer when the client's browser
settings is configured to light mode.

You can [preview Primer Dark](https://0xnixxy.github.io/primer-dark/) to see
what it looks like. Check out the [Usage section](#usage) below on how to deploy
Primer Dark for your GitHub Pages site.

## Usage

Include the following `_config.yml` file to your GitHub Pages site. Update the
`title` and `description` fields accordingly.

```yaml
# Front Matter global settings
# ----------------------------

# Default title
title: "The title of your site"

# Default description
description: "A short description of your site's purpose"

# Build settings
# --------------

# Use Primer Dark theme tagged to commit hash
remote_theme: 0xNixxy/primer-dark@fe9ef34

# Plugins required for Primer Dark
plugins:
  - jekyll-remote-theme
```

## Customisation

Primer Dark uses a custom stylesheet at `/assets/css/style.scss` to add the
automatic dark mode for Primer. If you wish to add your own custom styles,
update this custom stylesheet accordingly.

## Technical Notes

1. This Primer Dark commit is built on `pages-themes/primer@be021de` dated
   Oct 2025.

1. In dark mode, code blocks use Base16 Monokai Dark for syntax style.
