# Changelog

## 2.0.1

- Untracked files in the explorer are lavender (`#b3a6ff`). They were teal, the same colour as built-in types in code.

## 2.0.0

A refresh of the whole theme. The pitch-black background, silver text and neon green accents are unchanged, but many syntax colours are different, so expect your code to look different after updating.

### Works in more editors
- Published to the Open VSX Registry, so the theme can be installed in Cursor, VSCodium, Google Cloud Shell Editor and Cloud Workstations.
- The theme is now listed as **Neon Silver Black**. If you already had it selected, it stays selected.
- Added an extension icon.

### Syntax colours
- Variables and properties are pale cyan (`#c3ebef`) in every language. They were red.
- Parameters are gold italic (`#e5c07b`) in every language. They were bright yellow in Python and red elsewhere.
- Constants are orange and built-in types are teal in every language, matching Python.
- Module and namespace names are silver.
- `this` matches `self` (pale cyan).
- Semantic highlighting is turned on, with colours that match the syntax rules so code does not change colour when a language server starts.

### Languages
- **YAML:** keys are pale cyan; values keep their string, number and boolean colours. Variable references in GitHub Actions expressions are purple.
- **JSON:** follows the same pattern as YAML. Keys are pale cyan, strings pink, numbers and constants orange.
- **Terraform:** block keywords are purple italic, block labels green, attribute names pale cyan and references gold.
- **Java:** plain text is silver instead of red, type names are green, annotations are green, and import paths are silver.
- **C#, PHP and Rust:** parameters in function definitions are gold italic.

### Editor interface
- Colours for newer editor features: bracket pairs, inlay hints, sticky scroll, the command center, git change markers, peek view and the full set of terminal colours.
- Buttons have a green border and text so they are visible on the black background.
- Notifications have a border, and the status bar shows a red line while debugging.
- The find and replace widget has a dark grey border instead of green.
- Warnings are lime yellow (`#d3fc00`) instead of dark green, so they are easier to see and read as warnings.
- Placeholder text, ignored files and dim terminal text are lighter for better contrast.

### Clean-up
- Removed rules that never applied and merged near-identical shades. This does not change how code looks.

## 1.5.1

- README screenshots are stored in the repository instead of on Imgur, so they load everywhere.
- Added a licence, install instructions and packaging for Open VSX.
