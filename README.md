# gopls-debug
A VS Code extension for Go that uses only gopls, the Go language server

The code for this extension comes from
a combination of 
https://github.com/Microsoft/vscode-extension-samples/blob/master/lsp-sample
and https://github.com/Microsoft/vscode-go. 

## Installation

To package the extension, run `vsce package` from this directory. To install
the extension, navigate to the "Extensions" panel in VSCode, and select
"Install from VSIX..." from the menu in the top right corner. Choose the 
`gopls-1.0.0.vsix file` and reload VSCode.
