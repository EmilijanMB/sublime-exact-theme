<p align="center"><img width="800px" src="https://i.ibb.co/3p3t5hr/Code-E2-DQWVz-LUd.png"></p>
<p align="center">

Sublime theme in Visual Studio Code. Only one colored exactly by converting the HSL files from Sublime

## Installing information

Theme install [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme).

### Installation

Quick Open:
<!-- Windows: Ctrl+P
macOS: ⌘ + P
Linux: Ctrl+P -->

Paste the following command and press `Enter`:

```shell
ext install sublime exact theme
```

...pick the theme

## Theme activation

Quick Open:
<!-- Windows: Ctrl + Shift + PP
macOS: Shift + P
Linux: Ctrl + Shift +  -->

Type `theme`, choose `Preferences: Color Theme`, and select one of the Material Theme variants from the list. After activation, the theme will set the correct icon theme based on your active theme variant.

## Accent color

Quick Open:
<!-- Windows: Ctrl + Shift + P
macOS: Shift + P
Linux: Ctrl + Shift + P -->

Type sublime exact theme and choose Sublime Exact Theme: Set accent color, and pick a color from the list

## Override theme colors
VS Code documentation on overriding colors (https://code.visualstudio.com/docs/getstarted/themes#_customizing-a-color-theme)

### Overriding the colors

**Editor colors**

```js
"editor.tokenColorCustomizations": {
    "[Sublime Exact Theme]": {
        "textMateRules": [
            {
                "scope": "comment",
                "settings": {
                     "foreground": "#74705D",
                }
            },
        ]
    },
},
```

**Theme colors**

"workbench.colorCustomizations": {
	"[Sublime Exact Theme]": {
		"editor.selectionBackground": "#ff0000",
	}
},


## Recommended settings for complete Sublime experience

```js
{
    // Changes to like Sublime even more
    "editor.letterSpacing": 0.55,
    "editor.lineHeight": 18,
    "breadcrumbs.enabled": false
}
```
# Sublime-Exact-Theme