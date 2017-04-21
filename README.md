# VS Code Personal Setup
A perosnal list of [Visual Studio Code](https://code.visualstudio.com/) packages and resources to keep track of my personal setup.
For more, checkout [Awesome VS Code](https://github.com/viatsko/awesome-vscode)

# Table of Content
- [setting.json](#setting)
- [Extensions](#extensions)

## setting
```javascript
{
	"terminal.integrated.shell.windows": "C:\\Windows\\sysnative\\cmd.exe",
	// "terminal.integrated.shell.windows": "C:\\Windows\\sysnative\\bash.exe",
	"files.autoSaveDelay": 600,
	"files.autoSave": "afterDelay",
	"editor.minimap.enabled": true,
	"html.format.wrapLineLength": 0,
	"editor.insertSpaces": true,
	"workbench.iconTheme": "vs-seti",
	"git.confirmSync": false,
	"editor.dragAndDrop": true,
	"workbench.colorTheme": "Default Dark+",
	"workbench.experimental.colorCustomizations": {
		"editorLineNumbers": "#ffff00",
		"editorCursor": "#00FFFF",
		"activeTabActiveGroupForeground": "#00FF00",
		"statusBarBackground": "#BB0802"
	},
	"files.autoGuessEncoding": true,
	"editor.quickSuggestions": {
		"comments": false, // <- no 24x7 IntelliSense in comments
		"strings": true, // but in strings and the other parts of source files
		"other": true
	},
	"workbench.editor.closeOnFileDelete": false
}
```

## Extensions



