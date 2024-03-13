# Day Shift Theme

## Introduction

This theme's main goal is to provide a light, readable & clean experience into your favorite code editor.

In order to stay soft to the eyes, it uses a desaturated color palette and uses only bold characters for function names as they are what describes your code the better.

Visit [Night Shift website](https://www.jeantinland.com/toolbox/day-shift-theme/) for more info.

You can find the dark version of this theme [here](https://marketplace.visualstudio.com/items?itemName=jean.desaturated).

You'll find an iTerm2 port of this theme [here](https://github.com/Jean-Tinland/iTerm2-theme-desaturated).\
A Warp Terminal port is available [here](https://github.com/Jean-Tinland/warp-night-shift-theme).\
A Google Chrome port is available [here](https://github.com/Jean-Tinland/chrome-theme-desaturated).

## Preview

![.tsx preview](./assets/preview.png)

## Colors

| Color                                                                                | Hex Code  | Used for                                                                                                              |
| ------------------------------------------------------------------------------------ | --------- | --------------------------------------------------------------------------------------------------------------------- |
| ![#1e2737](https://placeholder.valraiso.net/15x15?bg=1e2737&text=%20) Deep dark blue | `#1e2737` | Variable names                                                                                                        |
| ![#39465e](https://placeholder.valraiso.net/15x15?bg=39465e&text=%20) Dark blue      | `#39465e` | Comments - Names entities - SCSS include, mixins params & parenthesis - CSS units - Regex - Parameters - Tag brackets |
| ![#74829b](https://placeholder.valraiso.net/15x15?bg=74829b&text=%20) Medium blue    | `#74829b` | Template expressions - Strings - Storage keywords - CSS class selector                                                |
| ![#6db3ce](https://placeholder.valraiso.net/15x15?bg=6db3ce&text=%20) Blue           | `#6db3ce` | Tag brackets - Escape characters - Operators - Special operators                                                      |
| ![#e78482](https://placeholder.valraiso.net/15x15?bg=e78482&text=%20) Red            | `#e78482` | Tag attributes - Units - Pseudo CSS                                                                                   |
| ![#8fc8bb](https://placeholder.valraiso.net/15x15?bg=8fc8bb&text=%20) Green          | `#8fc8bb` | Static types - CSS constant variables                                                                                 |
| ![#e0b972](https://placeholder.valraiso.net/15x15?bg=e0b972&text=%20) Yellow         | `#e0b972` | Function names - JSON property name - CSS transition name, ID selector - Inherited classes - Language variables       |
| ![#ad82cb](https://placeholder.valraiso.net/15x15?bg=ad82cb&text=%20) Magenta        | `#ad82cb` | Constants - Pseudo CSS - Keywords                                                                                     |
| ![#2fc2c3](https://placeholder.valraiso.net/15x15?bg=2fc2c3&text=%20) Cyan           | `#2fc2c3` | Tags selector                                                                                                         |

## Installation

Launch VS Code Quick Open (⌘+P), paste the following command, and press enter.

```
ext install jean.day-shift-theme
```

Or install this theme from the extension panel : search for "_Day Shift Theme_".

You can find this theme in the Visual Studio Code Marketplace.

## Customization

If you want to get rid of all bold or italic text, you can add these lines to your `settings.json` file :

```json
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      // Remove bold
      {
        "name": "Function names",
        "scope": "entity.name.function",
        "settings": {
          "fontStyle": "",
        }
      },
      // Remove italics
      {
        "name": "Comments",
        "scope": "comment",
        "settings": {
          "fontStyle": "",
        }
      }
    ]
  },
```

If you want to override anything else, you can see all the style definitions [here](https://github.com/Jean-Tinland/vscode-theme-day-shift/blob/main/themes/color-theme.json#L101) in the github repo.

## Support

**Javascript**, **Typescript**, **HTML/CSS**, **Python** & **PHP** are for now the only fully tested and supported languages. Other languages may be partially supported too.

Do not hesitate to contact me if you have some suggestions of improvements or language addition requests.
