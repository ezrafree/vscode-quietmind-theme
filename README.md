# Quiet Mind Dark

A near-black VS Code theme with a calm blue accent (`#569CD6`). Built for long sessions. Dark enough to mean it, minimal enough to stay out of the way.

## Colors

- **Background**: `#080808`
- **Accent**: `#569CD6`
- **Syntax base**: One Dark Pro-inspired palette

## Install locally

```bash
# From the extension directory
npm install -g @vscode/vsce
vsce package
code --install-extension vscode-quietmind-theme-1.0.0.vsix
```

Or copy the folder to `~/.vscode/extensions/vscode-quietmind-theme` and restart VS Code.

## Recommended settings

```json
{
  "editor.fontFamily": "'Fira Code', monospace",
  "editor.fontLigatures": true,
  "editor.minimap.enabled": false
}
```
