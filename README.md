# Midnight Slate Theme

Midnight Slate is a VS Code color theme tuned for long sessions in Java-heavy projects. It keeps the Monokai-style syntax balance, but reworks the workbench chrome toward a darker JetBrains-like layout with a clearer status bar, deeper panels, and calmer sidebars.

## What this theme changes

- Deep dark workbench surfaces inspired by modern JetBrains UI spacing and contrast
- Monokai-style syntax palette as the base layer
- Blue status bar close to VS Code's default dark accent
- Non-italic parameters for better readability in Java methods
- Stronger field declaration color so property names do not wash out

## Included theme

- `Midnight Slate`
- `Midnight Slate JetBrains Base`

## Theme variants

`Midnight Slate` keeps the stronger Midnight Slate shell and custom workbench accents.

`Midnight Slate JetBrains Base` uses a JetBrains New UI Dark workbench base and only overrides the editor area with the Midnight Slate / Monokai-style code palette. This variant is intended for cleaner Quick Open, symbol search, and picker visuals while preserving the Java editor readability tweaks.

## Local development

1. Install dependencies:

```bash
npm install
```

2. Build a VSIX:

```bash
npm run package
```

3. In VS Code, run `Extensions: Install from VSIX...` and pick the generated file.

## Marketplace publishing

This repository is prepared for Marketplace publishing, but the actual release still requires:

- a VS Code Marketplace publisher named `springandme` or an updated `publisher` field in `package.json`
- a Marketplace Personal Access Token
- `vsce publish` run locally or in CI

The workflow template under [`.github/workflows/publish.yml`](/root/code/vscode-midnight-slate-theme/.github/workflows/publish.yml) expects a repository secret named `VSCE_PAT`.

## Inspiration and licensing

This theme is an original packaged theme assembled from personal editor customization work. It is inspired by Monokai-style syntax contrast and JetBrains-style dark workbench layering, but it is not affiliated with third-party themes or publishers.

## Repository

- Source: `https://github.com/springandme/vscode-midnight-slate-theme`
- Issues: `https://github.com/springandme/vscode-midnight-slate-theme/issues`
