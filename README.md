# VSCODE config files

## Formatter - JS
* whitespace after trailing coma in array


## TSLint
* Insert space start/end parentesis JSX expression

## Instructions:

1. Run the ```set_settings.sh``` script. This will copy keybindings, settings, tslint and typescriptreact to ~/.config/Code/User (Linux only)

2. Run the following comand to extract the list of extensions with executable command to install them on the old machine:
```
code --list-extensions | xargs -L 1 echo code --install-extension
```
The output run on the new machine.  
Sample output:  
```
code --install-extension Angular.ng-template
code --install-extension DSKWRK.vscode-generate-getter-setter
code --install-extension EditorConfig.EditorConfig
code --install-extension HookyQR.beautify
```
 [SOF link](https://stackoverflow.com/questions/35773299/how-can-you-export-vs-code-extension-list)