# Flutter Widget Snippets

A minimal VS Code extension that provides code snippets for commonly used
Flutter widgets and lifecycle methods.

---

## Installation

`vsce` is the official VS Code extension packaging tool, published by Microsoft under `@vscode/vsce`.

```shell
# On mac: brew install node
node --version # tested with v26.3.0
npm --version # tested with 11.16.0

npm install -g @vscode/vsce
vsce --version # tested with 3.9.2

# Note: from the dir containing `package.json`
vsce package --no-dependencies

code --install-extension flutter-widget-snippets-1.0.0.vsix
code --uninstall-extension flutter-widget-snippets-1.0.0.vsix
```

---


## Snippets included

| Prefix       | Name              | Description                   |
|--------------|-------------------|-------------------------------|
| `slw`        | Stateless Widget  | Creates a Stateless widget    |
| `sfw`        | Stateful Widget   | Creates a Stateful widget     |


