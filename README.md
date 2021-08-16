# Boxy Theme Kit for Visual Studio Code
[![VSCode download badge](https://img.shields.io/visual-studio-marketplace/i/trongthanh.theme-boxythemekit?logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=trongthanh.theme-boxythemekit)

A set of color themes based on Sublime's Boxy Theme by Ihor Oleksandrov.

I have ported these theme files to VSCode's theme format and published to VSCode Marketplace. The Boxy Ocean Light was created by me (@trongthanh) by tweaking the colors from Boxy Ocean.

My current themes, Boxy Ocean dimmed (for dark mode) and Boxy Ocean Light (light mode) are getting extra work bench customizations and syntax color tweaks.

For other themes, please feel free to send PR (please respect the original theme, just fix the coloring issues), I'll publish changes as soon as possible.

[**Preview screenshot below: ⬇**](#boxy-monokai)

## Additional customizations:

Here are my recommendations to set in the user's settings. Since these are personal preferences, I won't set this permanently in theme files.

### Smaller workbench font size

This will make workbench text smaller to make it less distracted, more room to display contents and easier to distinguish between workbench's and editor's texts.

```json
{
	"window.zoomLevel": -0.5,
	"editor.fontSize": 16,
	"terminal.integrated.fontSize": 16,
	"workbench.tree.indent": 16,
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

![monokai-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/monokai-preview.png)

## Boxy Nova

![nova-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/nova-preview.png)

## Boxy Ocean

- Has custom workbench theming. Thanks [@dganoff](https://github.com/dganoff).

![ocean-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/ocean-preview.png)

## Boxy Ocean (dimmed bg)

- Has custom workbench
- Editor's background is dimmed to improve contrast and make text easier to read for long period.

![ocean-dimmed-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/ocean-dimmed-preview.png)


## Boxy Ocean Light [NEW]

- Has custom workbench
- This is the light theme created by me by tweaking colors from Boxy Ocean
- Can be used with **Boxy Ocean (dimmed bg)** for day and night shifts.

![ocean-light-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/ocean-light-preview.png)


## Boxy Solarized Dark

- Has custom workbench theming. Thanks [@prog-rajkamal](https://github.com/prog-rajkamal).

![solarized-dark-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/solarized-dark-preview.png)

## Boxy Solarized Light

![solarized-light-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/solarized-light-preview.png)

## Boxy Tomorrow

- This theme is based on the original Tomorrow Night theme with better syntax coloring for HTML, XML, Markdown, JSON, etc.
- The comment doc tags were dimmed to avoid clutter.

![](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/tomorrow-night-preview.png)

## Boxy Yesterday

![yesterday-preview](https://raw.githubusercontent.com/trongthanh/vscode-boxythemekit/main/images/yesterday-preview.png)

---

MIT License
