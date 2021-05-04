<p align="center"><img width="800px" src="https://i.ibb.co/3p3t5hr/Code-E2-DQWVz-LUd.png"></p>
<p align="center">

Sublime theme in Visual Studio Code. Only one colored exactly by converting the HSL files from Sublime

## Installing information

Theme install

### Installation

Quick Open:
Windows: Ctrl + P
macOS: ⌘ + P
Linux: Ctrl + P

Paste the following command and press `Enter`:

```shell
ext install sublime-exact-theme
```
...pick the theme

## Theme activation

Quick Open:
Windows: Ctrl + Shift + P
macOS: Shift + P
Linux: Ctrl + Shift + P

Type `theme`, choose `Preferences: Color Theme`, and select Sublime Exact Theme
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
    "editor.links": false,
    "breadcrumbs.enabled": false
}
```
# sublime-exact-theme
