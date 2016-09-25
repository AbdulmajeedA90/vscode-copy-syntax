# copy-syntax

[![Marketplace Version](http://vsmarketplacebadge.apphb.com/version/atian25.copy-syntax.svg)](https://marketplace.visualstudio.com/items?itemName=atian25.copy-syntax)
[![Installs](http://vsmarketplacebadge.apphb.com/installs/atian25.copy-syntax.svg)](https://marketplace.visualstudio.com/items?itemName=atian25.copy-syntax) 
[![Rating](http://vsmarketplacebadge.apphb.com/rating/atian25.copy-syntax.svg)](https://marketplace.visualstudio.com/items?itemName=atian25.copy-syntax)
[![Build Status](https://travis-ci.org/atian25/copy-syntax.svg?branch=master)](https://travis-ci.org/atian25/vscode-copy-syntax)

copy your code with syntax highlight, so you can show code at keynote.

## Features

  - Copy code as RTF
  - Auto detect language: `markdown syntax` -> `vscode languageId` -> `file extension`
  - Support language to highlight
  - Use `pygmentize`

## Usages

![Usage](https://github.com/atian25/vscode-copy-syntax/raw/master/usage.gif)

  - Open code file or select code snippet in Text Editor, then press `F1` and then select/type `Copy Syntax`, or right click the Text Editor and then click `Copy Syntax` in context menu, the code with syntax highlight will copy to clipboard.
  - To select language to run, use press `F1` and then select/type `Copy Syntax as ...`, then type the language: e.g `php, js, bash...`

## Installation

Press `F1` in VSCode, type `ext install` and then look for `copy-syntax`.

## Requirements

  - python is required by `pygmentize`

## Configuration

  - `copy-syntax.defaults.lang`: the default language is `js`
  - `copy-syntax.defaults.format`: currently is only support `rtf`, feel free to PR.
  - `copy-syntax.showMessage`: set to `false` to skip boring success message
  - `copy-syntax.formatters.rtf`: RtfFormatter options

```json
{
    "copy-syntax.defaults.lang": "js",
    "copy-syntax.formatters.rtf": {
        "style": "default",
        "fontsize": 50,
        "fontface": "Monaco"
    }
}
```

## Issues
Submit the [issues](https://github.com/atian25/vscode-copy-syntax/issues) if you find any bug or have any suggestion.

## Contribution
Fork the [repo](https://github.com/atian25/vscode-copy-syntax) and submit pull requests.

## Release Notes
see [CHANGELOG](https://github.com/atian25/vscode-copy-syntax/raw/master/CHANGELOG.md)