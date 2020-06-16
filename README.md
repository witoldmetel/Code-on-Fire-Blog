# My VSCode Setup

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
	"terminal.integrated.rendererType": "dom",
	"css.remoteStyleSheets": [
    		"https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
  	],
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
		"suppressNoRepositoryWarning": false,
		"suppressResultsExplorerNotice": false,
		"suppressShowKeyBindingsNotice": true,
		"suppressUpdateNotice": true,
		"suppressWelcomeNotice": true
	},
	"gitlens.views.fileHistory.enabled": true,
	"gitlens.views.lineHistory.enabled": true,
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
		"editor.defaultFormatter": "esbenp.prettier-vscode",
	},
	"[typescript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode",
	},
	"[jsonc]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"eslint.enable": true,
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
	"extensions.ignoreRecommendations": true
}
```

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

## Terminal Setup

- Git Bash
https://avladov.com/blog/641/replacing-command-prompt-git-bash

## Terminal (preview) settings
```profiles.json
{
	"closeOnExit": "never",
	"colorScheme": "UbuntuLegit",
	"commandline": "wsl.exe -d Ubuntu-18.04",
	"cursorColor": "#FFFFFF",
	"cursorShape": "bar",
	"fontFace": "Fira Code",
	"fontSize": 12,
	"guid": "{c6eaf9f4-32a7-5fdc-b5cf-066e8a4b1e40}",
	"historySize": 9001,
	"icon": "ms-appdata:///roaming/ubuntu.png",
	"name": "Ubuntu",
	"padding": "0, 0, 0, 0",
	"snapOnInput": true,
	"tabTitle": "Ubuntu",
	"useAcrylic": true
}

"schemes": [
	{
	"name": "UbuntuLegit",
	"foreground": "#EEEEEE",
	"background": "#2C001E",
	"black": "#4E9A06",
	"red": "#CC0000",
	"green": "#300A24",
	"yellow": "#C4A000",
	"blue": "#3465A4",
	"purple": "#75507B",
	"cyan": "#06989A",
	"white": "#D3D7CF",
	"brightBlack": "#555753",
	"brightRed": "#EF2929",
	"brightGreen": "#8AE234",
	"brightYellow": "#FCE94F",
	"brightBlue": "#729FCF",
	"brightPurple": "#AD7FA8",
	"brightCyan": "#34E2E2",
	"brightWhite": "#EEEEEE"
	}
],
```
			
