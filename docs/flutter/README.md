# Flutter Development

## VS Code

We use `Visual Studio Code` for `Flutter` development. Also take a look into [VS code documentation](../vscode.md).

## User setttings

There are the required VS Code settings for `Flutter` development. Set globally in user settings (recommended), or per project.

```json
{
    "dart.hotReloadOnSave": "never",
    "dart.flutterHotReloadOnSave": "never",
    "dart.runPubGetOnPubspecChanges": "never",
    "dart.showTodos": false,
    "dart.lineLength": 120,
    "[dart]": {
        "editor.formatOnSave": true,
        "editor.codeActionsOnSave": {
            "source.fixAll": "never",
            "source.organizeImports": "always",
        }
    },
}
```
