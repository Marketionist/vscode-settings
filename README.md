# vscode-settings

## Where to find config files
Settings for Visual Studio Code can be edited in:
1. Code -> Preferences -> Settings -> Open Settings (JSON) **OR** press
`command+shift+p` (or `control+shift+p` on Windows), type "settings" and
select `Preferences: Open Settings (JSON)` to open User Settings - it's
[settings.json](https://github.com/Marketionist/vscode-settings/blob/master/settings.json) file.
2. Code -> Preferences -> Keyboard Shortcuts -> Open Settings (JSON) **OR** press
`command+shift+p` (or `control+shift+p` on Windows), type "keyboard" and
select `Preferences: Open Keyboard Shortcuts (JSON)` to open Keyboard Shortcuts Settings - it's
[keybindings.json](https://github.com/Marketionist/vscode-settings/blob/master/keybindings.json) file.

## VS Code extensions
1. [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - to apply code
formatting rules from [`.editorconfig` file](https://editorconfig.org/#example-file).
2. [Markdown Notes](https://marketplace.visualstudio.com/items?itemName=kortina.vscode-markdown-notes) - to create
markdown files fast and link them.
3. [Markdown Links](https://marketplace.visualstudio.com/items?itemName=tchayen.markdown-links) - to show a graph with
links between markdown files.
4. [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - to show who was the last to touch a
particular line of code.
5. [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - to check code styling
according to [`.eslintrc.json` rules](https://eslint.org/docs/latest/rules/).

## Keyboard shortcuts
1. `command+shift+p` (or `control+shift+p` on Windows) - open Command Palette.
2. `shift+space` - show quick suggestion.
3. `option+shift+n` (or `alt+shift+n` on Windows) - create a new markdown note.
4. Select some text inside the markdown file -> press `command+shift+p` ->
select `Markdown Notes: New Note From Selection` -> enter file name -> press
`enter` - new markdown file will be created with the selected text and the old
file will have a link to the new file instead of the selected text.

