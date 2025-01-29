# My VS Code Configuration

This repository contains my personal VS Code settings and keybindings. I'm sharing these in case they are helpful to others or as a reference for my own setup. Feel free to browse, adapt, or use any parts of this configuration.

## Settings (settings.json)

My `settings.json` file includes customizations for various aspects of VS Code, including:

- **Editor:** Font family (`JetbrainsMono Nerd Font`), font size, line height, ligatures, line numbers (relative), code folding, minimap, word wrap, smooth scrolling, inlay hints, and more. I prioritize a clean and efficient editing experience, often disabling features that add visual clutter.
- **Terminal:** Font size, GPU acceleration.
- **Git/Git Diff:** Smart commit, auto-fetch, blame information, diff editor settings (side-by-side, hiding unchanged regions).
- **Explorer:** Confirmation settings for paste, delete, and drag-and-drop.
- **Extensions:** Ignoring recommendations, affinity settings for specific extensions (VSpaceCode, vscodevim, vscode-neovim).
- **Formatter:** Prettier is used as the default formatter, with settings for single quotes, trailing commas, print width, and ignored files.
- **VSCode-Vim:** Configuration for the VSCode-Vim extension, including cursor styles, clipboard integration, search highlighting, and more. I've replaced EasyMotion with Find-Then-Jump.
- **Files:** Excluded files and folders.
- **Window:** Command center, editor density.
- **Search:** Excluded files and folders.
- **Todo Tree:** Configuration for the Todo Tree extension.
- **Zen Mode:** Settings for Zen Mode.
- **Find It Faster:** Configuration for the Find It Faster extension.
- **WhichKey:** Configuration for the WhichKey extension, providing helpful keybinding hints. This is a core part of my workflow.
- **Tailwind CSS:** Emmet completions.
- **JavaScript/TypeScript:** Preferences for quotes, paths, auto-imports, and inlay hints.
- **Flutter/Dart:** Settings for the Dart extension, including DevTools browser, hot reload, and formatting.
- **Custom CSS:** Imports for custom CSS and JS for animations.
- **Workbench:** Theme (`Tokyo Night Moon`), icon theme (`material-icon-theme`), activity bar location, startup editor, and other UI customizations.
- **Testing:** Automatically open test results setting.
- **Animations:** Settings for animations.
- **Gitlens:** Remotes setting.

A detailed breakdown of each setting can be found within the `settings.json` file itself.

## Keybindings (keybindings.json)

My `keybindings.json` file defines custom keyboard shortcuts to enhance my workflow. Key areas include:

- **Navigation:** Moving between editors, tabs, and explorer navigation.
- **Git:** A comprehensive set of Git commands integrated with WhichKey for easy access.
- **File Management:** Creating, renaming, deleting, and copying file paths.
- **Search:** Searching within files and the project.
- **Code Manipulation:** Code actions, refactoring, and organizing imports.
- **UI:** Toggling various UI elements like the sidebar, minimap, and tabs.
- **Bookmarks:** Managing bookmarks.
- **WhichKey:** A highly customized WhichKey configuration to provide context for my keybindings. Almost all keybindings are routed through WhichKey.
- **Harpoon:** Integration with the Harpoon extension for quick file navigation.

The `keybindings.json` file provides a complete list of my custom keybindings. The WhichKey configuration (`whichkey.bindingOverrides`) is crucial for understanding these keybindings, as it groups them logically.

## Usage

To use these settings and keybindings:

1. Clone this repository.
2. Open VS Code.
3. Go to File > Preferences > Settings (or Code > Preferences > Settings on macOS).
4. In the Settings editor, click the {} icon to open `settings.json`.
5. Replace the contents of your `settings.json` with the contents of the `settings.json` file in this repository.
6. Similarly, open `keybindings.json` (File > Preferences > Keyboard Shortcuts > {} icon) and replace its contents with the `keybindings.json` file from this repository.

**Important:** Some settings, like file paths and extension dependencies, might need adjustments based on your specific environment. Pay close attention to these and modify them as needed. You'll also need to install the extensions mentioned in the `settings.json` file for the full configuration to work correctly.

## Extensions

The following extensions are essential for this configuration:

- **VSCode-Vim:** For Vim keybindings.
- **Prettier - Code formatter:** For code formatting.
- **Dart-Code:** For Dart and Flutter development.
- **Todo Tree:** For managing TODOs.
- **Find it Faster:** For fast file searching.
- **WhichKey:** For keybinding hints.
- **vscode-harpoon:** For quick file navigation.
- **Material Icon Theme:** For file icons.
- **Tokyo Night:** For the color theme.
- **vscode-animations:** For animations (requires custom CSS/JS loader).

You can install these extensions directly from the VS Code Marketplace.

## Custom CSS and JS

I use a custom CSS and JS loader to apply some styling and animations that aren't directly configurable in VS Code. This is referenced in the `vscode_custom_css.imports` setting. You'll need to adapt the file paths to your own system if you want to use this.

## Feedback

I welcome any feedback or suggestions for improvement. Feel free to open an issue or submit a pull request.
