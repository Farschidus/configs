# VS Code Settings

## Font

main:

- [Hack Nerd Font Mono](https://www.nerdfonts.com/font-downloads)

alternative:

- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

## Settings

Depending on your platform, the global user settings file is located here:

- macOS `$HOME/Library/Application\ Support/Code/User/settings.json`
- Windows `%APPDATA%\Code\User\settings.json`
- Linux `$HOME/.config/Code/User/settings.json`

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
