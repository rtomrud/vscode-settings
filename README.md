# vscode-settings

My [Visual Studio Code](https://code.visualstudio.com/) settings

## Installing

On Linux:

```bash
# Install the settings
cd ~/.config/Code/User
git init
git remote add origin https://github.com/rtomrud/vscode-settings.git
git fetch
git checkout -ft origin/master

# Install the GitHub Theme extension
code --install-extension github.github-vscode-theme

# Install the Source Code Variable fonts
curl -Lo ~/.fonts/SourceCodeVariable-Italic.ttf https://github.com/adobe-fonts/source-code-pro/releases/download/variable-fonts/SourceCodeVariable-Italic.ttf
curl -Lo ~/.fonts/SourceCodeVariable-Roman.ttf https://github.com/adobe-fonts/source-code-pro/releases/download/variable-fonts/SourceCodeVariable-Roman.ttf
```

_Note that the settings use the [GitHub Theme extension](https://github.com/primer/github-vscode-theme) and the [Source Code Variable fonts](https://github.com/adobe-fonts/source-code-pro/releases/tag/variable-fonts). Make sure those are installed or update the `"workbench.colorTheme"` and the `"editor.fontFamily"` properties in the [settings.json](./settings.json) file accordingly._
