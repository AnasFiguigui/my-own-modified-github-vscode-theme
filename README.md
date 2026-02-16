# Dark Reign Theme for VS Code

A modern, high-contrast dark theme inspired by GitHub Dark, with personal customizations for a sleek coding experience.

![Screenshot](https://raw.githubusercontent.com/AnasFiguigui/dark-reign-theme/main/images/screenshots.gif)

## Features
- True dark mode for comfortable coding
- Enhanced syntax highlighting for readability
- Minimal, distraction-free UI
- Based on GitHub Dark, with unique tweaks
- **Now includes four new themes: Void, Inferno, Emerald, and Ocean**

### Git Staged Color (Required) ⚠️⚠️

By default, both your `git status` staged files and your terminal user/hostname will appear the same color, since both use `terminal.ansiGreen`.

If you want your staged files to use the original green (and not match the user/hostname color), you can override the color for staged files with this git command:

```sh
git config --global color.status.added "green bold"
```
This will make staged files use the default green.

## Installation

### From Marketplace
1. Search for "Dark Reign Theme" in the Extensions view.
2. Click Install.
3. Open the Command Palette (`Ctrl+Shift+P`), search for `Color Theme`, and select your preferred Dark Reign theme (**Dark Reign**, **Void**, or **Inferno**).

### Manual (.vsix)
1. Download the latest `.vsix` from the [build/](build/) directory or generate your own.
2. In VS Code, open the Command Palette (`Ctrl+Shift+P`), type `Extensions: Install from VSIX...`, and select your `.vsix` file.
3. Set the theme as above.

## Customization
- Edit the JSON files in the `themes/` directory for advanced tweaks.
- Only dark themes included; light variants removed for focus.

## Contributing
Contributions, feedback, and suggestions are welcome! Fork the repo, make your changes, and submit a pull request. enjoy (*￣▽￣*)ブ !!

## License
MIT
