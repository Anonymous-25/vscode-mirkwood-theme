### [Visual Studio Code](https://code.visualstudio.com/)

#### Install from VSIX

1. Download the latest `Mirkwood` `.vsix` file from the project's releases.
2. Open Visual Studio Code.
3. Press `Ctrl+Shift+P` to open the Command Palette.
4. Search for **Extensions: Install from VSIX...**
5. Select the downloaded `.vsix` file.
6. After installation, open the Command Palette again.
7. Search for **Preferences: Color Theme**.
8. Select **Mirkwood** from the available themes.

#### Install using Command Line

If you already have the `.vsix` package, install it directly from the terminal:

```bash
code --install-extension mirkwood-theme-1.0.0.vsix
```

Replace the filename with the version of the `.vsix` package you downloaded.

#### Install from Source

If you want to install the development version directly from the source repository:

```bash
git clone https://github.com/Anonymous-25/vscode-mirkwood-theme.git ~/.vscode/extensions/mirkwood-theme

cd ~/.vscode/extensions/mirkwood-theme

npm install

npm run build
```

Then reload Visual Studio Code.

#### Activating the Theme

Open Visual Studio Code and press:

```text
Ctrl+Shift+P
```

Search for:

```text
Preferences: Color Theme
```

Then select:

```text
Mirkwood
```

If your package contains multiple variants, you can select the corresponding **Mirkwood Dark** or **Mirkwood Light** theme.

#### Updating

When a new `.vsix` release is available, install the newer package using:

```bash
code --install-extension mirkwood-theme-NEW_VERSION.vsix
```

Visual Studio Code will replace the previous version with the newer one.
