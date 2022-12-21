# SCSS Syntax

Visual Studio Code plugin that fixes incorrect syntax highlighting for SCSS property names overlapping with tag names (content, cursor, filter, font and mask).

## Installation

Install the extension manager.

```sh
npm install -g @vscode/vsce
```

Clone this repository and package the extension.

```sh
git clone https://github.com/lrdn/vscode-scss-syntax.git
cd vscode-scss-syntax
vsce package
```

Install the generated extension package.

```sh
code --install-extension vscode-scss-syntax-1.0.0.vsix
```
