# Tarp Themes

You seem to have found yourself at the unofficial-official theme repository for [Shelter](https://github.com/uwu/shelter).

## Give me the goods!1

Tarp comes with this pack imported and ready to go by default.

If it did not, or if you accidentally deleted it, you can import it by going to the `packs` header in the settings and clicking the import button.

Then, paste the following URL:
`https://grngxd.github.io/tarp-themes/`

## How do I add my own theme?

Create a pull request with your theme in the `themes.json` file. The format is as follows:

```json
{
    "name": string,
    "author": string, // Optional, default is "Anonymous"
    "description": string, // Short description of the theme // Optional, default is "No description"
    "css_link": string, // Link to the CSS file
    "license": string // Optional, default is "None"
    "preview": string // Optional, can be a gif or png
    "tags": [string] // Optional, tags for the theme
    "pack": string // Optional, link to the pack
}
```