# CoCreate ME10 Language Support for VS Code

This extension provides basic syntax highlighting for the **CoCreate ME10 2008 macro language** inside Visual Studio Code.

## Features
- Syntax highlighting for `.m` files (you can add more extensions in `package.json`)
- Language configuration (comments, brackets, etc.)

## Installation

### From VSIX (local)
1. generate the `.vsix` file with 
   ```bash
   vsce.cmd package

2. Run:
   ```bash
   code --install-extension cocreate-me10-1.0.0.vsix
