# aglio-theme-otto
a collapsible, slightly more compact aglio theme

Daniel Taylor's [aglio](https://github.com/danielgtaylor/aglio) tool is a nice
renderer for API Blueprints. Aglio comes with a handsomely-styled theme called
[olio](https://github.com/danielgtaylor/aglio/tree/olio-theme#readme). This
repo contains a modified version of olio. Changes:

- this theme is slightly more compact in its layout (a wee smaller typeface,
  tighter margins)
- this theme is more collapsible which is nice for big, complicated
  APIs (see screenshot below)

## Preview

[Collapsed view](screenshot.png)

## Quick start

Install aglio: `npm install -g aglio`.

Install this theme (maybe eventually via npm, but let's not get ahead of
ourselved).

Run: `aglio -t otto -i docs.apib -o docs.html`

