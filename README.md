# VS Code Personal Setup
A perosnal list of [Visual Studio Code](https://code.visualstudio.com/) packages and resources to keep track of my personal setup.
For more, checkout [Awesome VS Code](https://github.com/viatsko/awesome-vscode)

# Table of Content
- [Settings](Settings)

# Settings
```javascript
{
    "terminal.integrated.shell.windows": "C:\\Windows\\sysnative\\cmd.exe",
    // "terminal.integrated.shell.windows": "C:\\Windows\\sysnative\\bash.exe",
    "files.autoSave": "onFocusChange",
    "editor.minimap.enabled": true,
    "html.format.wrapLineLength": 0,
    "editor.insertSpaces": true,
    "editor.tabSize": 4,
    "editor.fontSize": 16,
    "terminal.integrated.fontSize": 16,
    "editor.detectIndentation": false,
    "workbench.iconTheme": "vs-seti",
    "git.confirmSync": false,
    "editor.dragAndDrop": true,
    "workbench.colorTheme": "Default Dark+",
    "workbench.colorCustomizations": {
        "editorLineNumber.foreground": "#FFFF00",
        "editorCursor.foreground": "#00FFFF",
        "statusBar.background": "#BB0802",
        "tab.activeForeground": "#00FF00",
        "tab.inactiveForeground": "#969696"
    },
    "files.autoGuessEncoding": true,
    "editor.quickSuggestions": {
        "comments": false, // <- no 24x7 IntelliSense in comments
        "strings": true, // but in strings and the other parts of source files
        "other": true
    },
    "workbench.editor.closeOnFileDelete": false,
    "window.zoomLevel": 0,
    "git.enableSmartCommit": true,
    "editor.fontFamily": "Consolas, 'Ubuntu Mono', Mocano, 'Courier New', monospace",
    "window.menuBarVisibility": "toggle",
    "python.linting.enabled": false,
    "python.workspaceSymbols.tagFilePath": "",
    "python.venvPath": "~/.pyenv",
    "latex-workshop.latex.clean.enabled": true,
    "latex-workshop.latex.clean.fileTypes": [
        "*.aux",
        "*.bbl",
        "*.blg",
        "*.idx",
        "*.ind",
        "*.lof",
        "*.lot",
        "*.out",
        "*.toc",
        "*.acn",
        "*.acr",
        "*.alg",
        "*.glg",
        "*.glo",
        "*.gls",
        "*.ist",
        "*.fls",
        "*.log",
        "*.fdb_latexmk",
        "*.synctex",
        "*.synctex.gz"
    ],
    "latex-workshop.latex.toolchain": [
        {
            "command": "latexmk",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-output-directory=build",
                "-file-line-error",
                "-pdf",
                "%DOC%"
            ]
        }
    ],
    "latex-workshop.latex.outputDir": "./build"
}
```
