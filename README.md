## How to install

make sure you have Node.js installed,
then run:

```
npm install -g @vscode/vsce
```

clone the repository and cd into the extension folder and run the following command to generate a .vsix file

```
vsce package
```

now you can install the extension via the extensions tab in vscode by pressing the "..." at the top, and choosing "Install from VSIX...".
Have fun!

## About

VS Code plugin for the Nova Programming Language by [Pyrotek45](https://github.com/pyrotek45/nova-lang).

### Changes in v0.0.4:

- Added keywords: "extends", "mod" and "in"
- Removed Keywords: "unwrap", "foreach" and "bind"

### Changes in v0.0.3:

- Added comment highlighting

### Changes in v0.0.2:

- Added file icon
- Added extension icon
- New keywords: "unwrap" and "bind"
