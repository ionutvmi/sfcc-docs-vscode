# SFCC Documentation in VSCode

Browse the SFCC documentation directly from VSCode.

![demo](/screenshots/demo.gif)

## Features

-   Search panel in the activity bar
-   Details penel available as a sideview
-   Search the current selection/word under the cursor
-   Previous/Next page navigation in the documentation details page
-   Panel for browsing the table of contents

## Installation

You can install it from the [marketplace](https://marketplace.visualstudio.com/items?itemName=ionutvmi.sfcc-docs-vscode).  
`ext install sfcc-docs-vscode`

## Keyboard shortcuts

To configure a custom keyboard shortcut for the search current word/selection:

```
    // keybindings.json
    {
        "key": "ctrl+shift+f10",
        "command": "sfcc-docs-vscode.openDocs"
    },
    {
        "key": "ctrl+shift+f11",
        "command": "sfcc-docs-vscode.searchQuery",
        // search a specific keyword
        "args": {
            "query": "ProductMgr"
        }
    }
```

## Release Notes

The release notes are available in the [CHANGELOG.md](./CHANGELOG.md) document.

---

## Author

Mihai Ionut Vilcu

-   [github/ionutvmi](https://github.com/ionutvmi)
-   [twitter/mihai_vlc](http://twitter.com/mihai_vlc)

**Enjoy!**
