# My VSCode Setup

## Extensions

- Auto Close Tag
- Auto Rename Tag
- Auto-Open Markdown Preview
- Bracket Pair Colorizer
- Color Picker
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
- Settings Sync
- TODO Highlight
- Turbo Console Log
- vscode-styled-components

## VSCode user config (settings.json)
```
{
  "terminal.external.osxExec": "iTerm.app",
  "terminal.integrated.rendererType": "dom",
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
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "eslint.enable": true,
  "eslint.alwaysShowStatus": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "git.confirmSync": false,
  "git.autofetch": true,
  "workbench.editor.enablePreview": false,
  "terminal.external.windowsExec": "C:\\WINDOWS\\System32\\bash.exe",
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\wsl.exe",
  "extensions.ignoreRecommendations": true,
  "prettier.singleQuote": true,
  "eslint.migration.2_x": "off",
  "sync.gist": "5dd8b9039d23c70475a0c43a135397a0",
  "prettier.useTabs": true
}
```

## Setup SSH for GitHub

https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

```
$ git config --global user.name "John Doe"
$ git config --global user.email "john@doe.org"
```

## Backup and Synchronize VSCode Settings with a GitHub Gist

https://mikefrobbins.com/2019/03/21/backup-and-synchronize-vscode-settings-with-a-github-gist/
