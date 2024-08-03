# VS Code Settings

## Font

main:

- [Hack Nerd Font Mono](https://www.nerdfonts.com/font-downloads)

alternative:

- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)


## Extensions

For easy install paste the below content in a txt file (ex. extensions.txt) and run the below command in terminal:

```
cat extensions.txt | xargs -L1 code --install-extension
```

this command will pipe every line as argument to vscode cli command, code, with install-extension flag.

```
apollographql.vscode-apollo
dbaeumer.vscode-eslint
dotjoshjohnson.xml
dsznajder.es7-react-js-snippets
eamodio.gitlens
esbenp.prettier-vscode
kumar-harsh.graphql-for-vscode
ms-azuretools.vscode-docker
ms-dotnettools.csdevkit
ms-dotnettools.csharp
ms-dotnettools.vscode-dotnet-runtime
ms-dotnettools.vscodeintellicode-csharp
ms-mssql.data-workspace-vscode
ms-mssql.mssql
ms-mssql.sql-database-projects-vscode
ms-vscode.powershell
ms-vscode.vscode-typescript-next
msjsdiag.vscode-react-native
pkief.material-icon-theme
rangav.vscode-thunder-client
ritwickdey.liveserver
simonsiefke.svg-preview
vincesalvino.dark-plus-black
yoavbls.pretty-ts-errors
```


## Settings

Depending on your platform, the global user settings file is located here:

- macOS `$HOME/Library/Application\ Support/Code/User/settings.json`
- Windows `%APPDATA%\Code\User\settings.json`
- Linux `$HOME/.config/Code/User/settings.json`

copy json below inside the settings.json file and save.

```
{
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.detectIndentation": true,
  "editor.fontFamily": "Hack Nerd Font Mono",
  "editor.fontLigatures": true,
  "editor.fontSize": 13,
  "editor.guides.bracketPairs": true,
  "editor.inlineSuggest.enabled": true,
  "editor.lineHeight": 0,
  "editor.linkedEditing": true,
  "editor.minimap.enabled": false,
  "editor.snippetSuggestions": "top",
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "editor.unicodeHighlight.invisibleCharacters": false,
  "editor.stickyScroll.enabled": false,
  "eslint.enable": true,
  "eslint.validate": ["react", "typescript", "html", "javascript"],
  "explorer.openEditors.visible": 1,
  "explorer.confirmDelete": false,
  "extensions.ignoreRecommendations": true,
  "files.autoSave": "onWindowChange",
  "files.associations": {
    "*.tsx": "typescriptreact"
  },
  "git.autofetch": true,
  "git.openRepositoryInParentFolders": "never",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "security.workspace.trust.untrustedFiles": "open",
  "search.exclude": {
    "**/*.code-search": true,
    "**/bower_components": true,
    "**/node_modules": true
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  "window.zoomLevel": 1,
  "workbench.colorTheme": "Dark+ Black",
  "workbench.editor.labelFormat": "medium",
  "workbench.editor.showTabs": "none",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.sideBar.location": "right",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[handlebars]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```