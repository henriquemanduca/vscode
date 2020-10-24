# VS Code - Configuration
Visual Studio Code configuration file and others helper files.

### settings.json

Your VS Code settings are conveniently stored in a JSON file called `settings.json`. To edit your settings in `settings.json`, start by opening the Command Palette with `CMD/CTRL + SHIFT + P`.

### prettier.config.js

Prettier is an opinionated code formatter and uses [cosmiconfig](https://github.com/davidtheclark/cosmiconfig) for configuration file support. This means you can configure Prettier via `.prettierrc.js`, `.prettierrc.cjs`, `prettier.config.js`, or `prettier.config.cjs` file that exports an object using `module.exports`.

### .editorconfig

Editorconfig is a plugin [attempts](https://github.com/editorconfig/editorconfig-vscode#known-issues) to override user/workspace settings with settings found in `.editorconfig` files.