# Boxy Theme Kit

A set of color themes based on Sublime's [Boxy Theme](https://github.com/ihodev/sublime-boxy).

All props go to Boxy Theme's author Ihor Oleksandrov. I just republish these theme files to VSCode Marketplace.

My favorite theme in this set is Tomorrow (Night), so I'll keep fixing its syntax color and tweaking the workbench theme to match.

For other themes, please feel free to send PR (please respect the original theme, just fix the coloring issues), I'll publish changes as soon as possible.

[**Preview screenshot below: ⬇**](#boxy-monokai)

## Additional customizations:

Here are my recommendations to set in the user's settings. Since these are personal preferences, I won't set this permanently in theme files.

### Dimmer side bar and status bar

This will make the side bar and status bar text color less bright and distracted.

```json
"workbench.colorCustomizations": {
    "statusBar.foreground": "#888",
    "sideBar.foreground": "#888"
}
```

### Smaller workbench font size

This will make workbench text smaller to make it less distracted, more room to display contents and easier to distinguish between workbench's and editor's texts.

```json
{
	"window.zoomLevel": -0.5,
	"editor.fontSize": 16,
	"terminal.integrated.fontSize": 16,
	"fontshortcuts.defaultFontSize": 16 // if use fontshortcuts extension
}
```

### Override theme's workbench customization

There are workbench customizations mostly based on contributors' preferences. Some may not like it. Luckily, VSCode allows us to override the workbench theme with user's settings. Here's the default workbench theme re-defined as user settings to reset the theme's workbench customization.

```json
{
	"workbench.colorCustomizations": {
		"activityBar.background": "#333333",
		"activityBar.foreground": "#cccccc",
		"activityBarBadge.background": "#007acc",
		"editor.background": "#1E1E1E",
		"editor.foreground": "#D4D4D4",
		"editor.inactiveSelectionBackground": "#3A3D41",
		"editor.selectionHighlightBackground": "#ADD6FF26",
		"editorIndentGuide.background": "#404040",
		"list.dropBackground": "#383B3D",
		"list.hoverBackground": "#2a2d2d",
		"sideBar.background": "#252525",
		"sideBarTitle.foreground": "#BBBBBB",
		"tab.inactiveBackground": "#2d2d2d"
	}
}
```

## Boxy Monokai

![monokai-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/monokai-preview.png)

## Boxy Nova

![nova-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/nova-preview.png)

## Boxy Ocean

- Has custom workbench theming. Thanks [@dganoff](https://github.com/dganoff).

![ocean-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/ocean-preview.png)

## Boxy Ocean (dimmed bg)

- Has custom workbench (based on Boxy Ocean)
- Editor's background is dimmed to make text easier to read, esp. for long period and in dark environment

![ocean-dimmed-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/ocean-dimmed-preview.png)

## Boxy Solarized Dark

- Has custom workbench theming. Thanks [@prog-rajkamal](https://github.com/prog-rajkamal).

![solarized-dark-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/solarized-dark-preview.png)

## Boxy Solarized Light

![solarized-light-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/solarized-light-preview.png)

## Boxy Tomorrow

- This theme is based on the original Tomorrow Night theme with better syntax coloring for HTML, XML, Markdown, JSON, etc.
- The comment doc tags were dimmed to avoid clutter.

![](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/tomorrow-night-preview.png)

## Boxy Yesterday

![yesterday-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/master/images/yesterday-preview.png)

---

MIT License
