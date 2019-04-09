# Devoid VS Code theme

A dark theme for VS Code based on Atom's One Dark with italics support.

[![Version](https://vsmarketplacebadge.apphb.com/version/dev01d.devoid-theme.svg)](https://marketplace.visualstudio.com/items?itemName=dev01d.devoid-theme)

## js/jsx

![Preview jsx](https://raw.githubusercontent.com/dev01d/devoid-theme/master/images/jsx.png)

## html

![Preview html](https://raw.githubusercontent.com/dev01d/devoid-theme/master/images/html.png)

## css

![Preview css](https://raw.githubusercontent.com/dev01d/devoid-theme/master/images/css.png)

## json

![Preview json](https://raw.githubusercontent.com/dev01d/devoid-theme/master/images/json.png)

## Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Devoid`
3. Click **Install** to install it.
4. Click **Reload** to reload the your editor
5. Code > Preferences > Color Theme > **Devoid**

### Recommended settings

```javascript
{
  "editor.wordWrap": "on",
  // Italics support defaults to true for cursive font.
  // Enable a font that supports it like Operator/Fira/Dank mono
  "editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace",
  "files.trimTrailingWhitespace": true
}
```

### A note on italics/cursive

[These](https://gist.github.com/dev01d/2afddac00b14d61b753182f233951c30) are the settings that are used to create the italics support. If you would like to remove italics for a certain scope add it to settings.json.

**Example:**

```javascript
// remove variable italics
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": [
        "storage.type"
      ],
      "settings": {
        "fontStyle": ""
      }
    }
  ]
}
```
