# settings.json

Open settings.json with `Cmd + Shift + P`:

![image](https://user-images.githubusercontent.com/261183/63036018-e5626400-be81-11e9-864d-b04de05eb923.png)


## Force VS Code to Open Files in a New Tab (instead of preview mode)

Source: https://www.brcline.com/blog/force-vscode-open-files-new-tab

```json
{
  "workbench.editor.enablePreview": false,
}
```

## Fix Pylint “unresolved import” error

Source: https://stackoverflow.com/a/53940610/234233

```json
{
  "python.pythonPath": "/path/to/your/venv/bin/python",
}
```

## Add Trailing Newline

Source: https://github.com/Microsoft/vscode/issues/1666#issuecomment-300922764

```json
{
  ""files.insertFinalNewline": true,
}
```
