---
title: "Todo Tree 扩展设置"
tags:
- VSCode
---

## 自定义图标

> icon - used to set a different icon in the tree view. Must be a valid octicon (see <https://octicons.github.com>) or codicon (see <https://microsoft.github.io/vscode-codicons/dist/codicon.html>). If using codicons, specify them in the format "$(icon)".The icon defaults to a tick if it's not valid. You can also use "todo-tree", or "todo-tree-filled" if you want to use the icon from the activity view.

## 自定义高亮

```json
"todo-tree.highlights.defaultHighlight": {
    "icon": "alert",
    "type": "text",
    "foreground": "red",
    "background": "white",
    "opacity": 50,
    "iconColour": "blue"
},
"todo-tree.highlights.customHighlight": {
    "TODO": {
        "icon": "check",
        "type": "line"
    },
    "FIXME": {
        "foreground": "black",
        "iconColour": "yellow",
        "gutterIcon": true
    },
    "TIPS": {
        "icon": "zap",
        "iconColour": "#00ffaa",
        "gutterIcon": true,
        "foreground": "#33ff00",
        "background": "#ffffff",
        "type": "text"
    },
}
```
