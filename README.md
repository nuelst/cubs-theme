<div align="center">

<img src="assets/icon.png" width="140" />

# Cubs Theme

A minimal VS Code theme with three variants — Dawn, Dusk and Midnight.

[![Preview in vscode.dev](https://img.shields.io/badge/preview%20in-vscode.dev-blue)](https://vscode.dev/theme/nuelst.cubs-theme)

</div>

## Variants

- **Dawn** — Clean light gray base (`#f3f4f5`) with teal accents, optimized for bright environments

![preview-dawn](assets/cubs-dawn.png)

- **Dusk** — Neutral dark gray base (`#1f1f1f`) with subtle gray tones, for minimal distraction. Based on [Min Dark](https://github.com/misolori/min-theme) by Miguel Solorio (MIT)

![preview-dusk](assets/cubs-dusk.png)

- **Midnight** — Deep dark blue base (`#111422`) with soft blue accents

![preview-midnight](assets/cubs-midnight.png)

## Installation

1. Install from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=nuelst.cubs-theme)
2. Open the Color Theme picker:
   - **Windows / Linux:** `Ctrl+K` then `Ctrl+T`
   - **macOS:** `Cmd+K` then `Cmd+T`
3. Choose **Cubs Dawn**, **Cubs Dusk** or **Cubs Midnight**

Or via CLI:

```bash
code --install-extension nuelst.cubs-theme
cursor --install-extension nuelst.cubs-theme
```

## Development

```bash
git clone https://github.com/nuelst/cubs-theme
cd cubs-theme
pnpm install
```

Press `F5` in VS Code to launch the Extension Development Host.

## Local Build & Install

```bash
pnpm run package
code --install-extension cubs-theme-1.0.1.vsix
cursor --install-extension cubs-theme-1.0.1.vsix
```

## License

[MIT](LICENSE)