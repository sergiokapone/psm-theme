# [PSM Color Scheme for VSCode](https://github.com/sergiokapone/psm-theme)

Enhance your coding experience with the new "**P**rogramming and **S**cripting **M**anagement" color scheme for **VS Code**. This theme is perfect for programmers and script developers looking for a more appealing and professional interface for their work. "Programming and Scripting Management" offers a unique combination of bright colors and subtle lines that make reading code easier and increase productivity.

![Preview](https://raw.githubusercontent.com/sergiokapone/psm-theme/master/images/screenshot1.png)

Also, this theme is an excellent choice for those who work with **Python** and **JavaScript**, particularly in the field of **Data Science**. It combines pleasant tones and improved syntax highlighting, making code easier to read and understand. Moreover, thanks to its greenish hue, the theme is easy on the eyes and code elements are clearly visible. Based on the color scheme of the popular [Spyder IDE](https://www.spyder-ide.org/), which is highly regarded by data scientists.

![Preview](https://raw.githubusercontent.com/sergiokapone/psm-theme/master/images/screenshot2.png)

Furthermore, the theme's improved syntax highlighting allows for better differentiation between different code elements. This means that variables, functions, and keywords can be easily distinguished, reducing the risk of errors and making debugging easier.

Additionally, the improved syntax highlighting for regular expressions in this theme includes the use of different colors to differentiate between matching and non-matching groups, making it easy to see which parts of the expression are performing specific tasks. This feature is particularly useful when working with large or complex regular expressions, where it can be challenging to keep track of all the different parts.

![Preview](https://raw.githubusercontent.com/sergiokapone/psm-theme/master/images/screenshot3.png)

<div align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=Sergiy.psm-theme" align="center">
    <img src="https://img.shields.io/badge/preview%20in-vscode.dev-blue">
  </a>
</div>

## Installation

1. Open Extensions sidebar panel in VS Code. **View → Extensions**
2. Search for **PSM Theme**
3. Click **Install** to install it.
4. Click **Reload** to reload the editor.
5. File > Preferences > Color Theme > **PSM Theme**

## Recommended Settings

I recommend using [JetBrain’s Mono](https://www.jetbrains.com/lp/mono/) mono-spaced font which is useful for both presenting code and working with it in an IDE. It has an increased x-height for a better reading experience, better shapes for seeing columns of letters, and a developer-friendly assortment of ligatures that make all of your multi-character operators actually look like a single, unified operator.

```
{
"editor.fontFamily": "JetBrains Mono, Consolas, monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 12,
  "editor.fontWeight": "normal",
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 1.3,
  "editor.rulers": [79],
  "editor.stickyScroll.enabled": true,
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 79,
  "terminal.integrated.fontSize": 12,
  "terminal.integrated.fontFamily": "Consolas, JetBrains Mono, monospace"

}
```

I recommend to use [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme).

## Contributing

If something don't look correct, please open an issue. I'll try to fix it.
