# My VSCode Setup

## Terminal Setup

1) Git Bash
- https://avladov.com/blog/641/replacing-command-prompt-git-bash (Config)
- http://practicalseries.com/1002-vcs/03-03-install.html (Change default path)

2) Hyper
- https://ksmigiel.com/2019/01/hyper-git/ (Config)
- https://github.com/MozzarellaM/hyper-monokai-pro (Monokai Pro Theme)
- https://github.com/lucleray/hyper-opacity (Hyper Opacity background)

## Setup SSH for GitHub

https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

```
$ git config --global user.name "John Doe"
$ git config --global user.email "john@doe.org"

$ git config user.name
$ git config user.email
```

## Backup and Synchronize VSCode Settings with a GitHub Gist

https://mikefrobbins.com/2019/03/21/backup-and-synchronize-vscode-settings-with-a-github-gist/

## Extensions

- Auto Close Tag
- Auto Rename Tag
- Auto-Open Markdown Preview
- Bracket Pair Colorizer
- Color Picker
- CSS Peek
- ES7 React/Redux/GraphQL/React-Native snippets
- ESLint
- Git History
- GitLens — Git supercharged
- HTML CSS Support
- indent-rainbow
- JavaScript (ES6) code snippets
- Jest Snippets
- Live Server
- Markdown PDF
- Material Icon Theme
- Monokai Pro
- Prettier - Code formatter
- Remote - WSL
- Settings Sync
- TODO Highlight
- Turbo Console Log
- vscode-styled-components

## VSCode user config (settings.json)
```
{
	"terminal.external.osxExec": "iTerm.app",
	"editor.roundedSelection": false,
	"editor.snippetSuggestions": "top",
	"editor.tabSize": 2,
	"editor.minimap.enabled": false,
	"editor.fontSize": 14,
	"editor.fontLigatures": true,
	"editor.suggestSelection": "first",
	"editor.formatOnSave": true,
	"editor.gotoLocation.multipleDefinitions": "goto",
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"explorer.openEditors.visible": 0,
	"explorer.autoReveal": false,
	"explorer.confirmDragAndDrop": false,
	"workbench.iconTheme": "material-icon-theme",
	"workbench.colorTheme": "Monokai Classic",
	"workbench.editor.enablePreviewFromQuickOpen": false,
	"workbench.startupEditor": "newUntitledFile",
	"window.zoomLevel": 1,
	"liveServer.settings.donotShowInfoMsg": true,
	"gitlens.advanced.messages": {
		"suppressCommitHasNoPreviousCommitWarning": false,
		"suppressCommitNotFoundWarning": false,
		"suppressFileNotUnderSourceControlWarning": false,
		"suppressGitVersionWarning": false,
		"suppressLineUncommittedWarning": false,
		"suppressNoRepositoryWarning": false
	},
	"gitlens.keymap": "none",
	"todohighlight.keywords": ["todo", "@todo", "fixme", "@fixme"],
	"todohighlight.isCaseSensitive": false,
	"todohighlight.defaultStyle": {
		"color": "white",
		"backgroundColor": "#ffab00",
		"overviewRulerColor": "#ffab00",
		"fontWeight": "bold"
	},
	"breadcrumbs.enabled": true,
	"javascript.updateImportsOnFileMove.enabled": "never",
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"typescript.updateImportsOnFileMove.enabled": "never",
	"[typescriptreact]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[typescript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[jsonc]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"eslint.alwaysShowStatus": true,
	"eslint.migration.2_x": "off",
	"eslint.validate": [
		"javascript",
		"javascriptreact",
		"typescript",
		"typescriptreact"
	],
	"prettier.singleQuote": true,
	"prettier.useTabs": true,
	"git.confirmSync": false,
	"git.autofetch": true,
	"workbench.editor.enablePreview": false,
	"terminal.external.windowsExec": "C:\\WINDOWS\\System32\\bash.exe",
	"extensions.ignoreRecommendations": true,
	"turboConsoleLog.logMessagePrefix": ""
}
```
