## KeyBindings

```
[
  {
      "key": "ctrl+t",
      "command": "-workbench.action.showAllSymbols"
  },
  {
      "key": "ctrl+t",
      "command": "workbench.action.terminal.toggleTerminal",
      "when": "terminal.active"
  },
  {
      "key": "ctrl+j",
      "command": "-workbench.action.togglePanel"
  },
  {
      "key": "ctrl+j",
      "command": "editor.action.joinLines"
  },
  {
      "key": "ctrl+d",
      "command": "-editor.action.addSelectionToNextFindMatch",
      "when": "editorFocus"
  },
  {
      "key": "ctrl+d",
      "command": "editor.action.addSelectionToNextFindMatch",
      "when": "editorFocus"
  },
  {
      "key": "ctrl+shift+d",
      "command": "-workbench.view.debug",
      "when": "viewContainer.workbench.view.debug.enabled"
  },
  {
      "key": "ctrl+shift+d",
      "command": "editor.action.copyLinesDownAction",
      "when": "editorTextFocus && !editorReadonly"
  },
  {
      "key": "ctrl+shift+alt+down",
      "command": "-editor.action.copyLinesDownAction",
      "when": "editorTextFocus && !editorReadonly"
  }
]
```

[Back to readme](README.md)
