<h3 align="center">
  <img src="https://raw.githubusercontent.com/OneiroiTheme/oneiroi-theme/main/assets/oneiroi-logo.png" alt="Oneiroi Theme Logo" width="100" />
  </br>
  Oneiroi theme for <a href="https://code.visualstudio.com/">Visual Studio Code</a>
</h3>

<p align="center">
  <a href="https://github.com/OneiroiTheme/vscode/stargazers"><img src="https://img.shields.io/github/stars/OneiroiTheme/vscode?style=flat-square&labelColor=1c2024&color=ffb0cd" alt='github stars'/></a>
  <a href="https://github.com/OneiroiTheme/vscode/issues"><img src="https://img.shields.io/github/issues/OneiroiTheme/vscode?style=flat-square&labelColor=1c2024&color=ecc06c" alt='github issues'/></a>
  <a href="https://github.com/OneiroiTheme/vscode/contributors"><img src="https://img.shields.io/github/contributors/OneiroiTheme/vscode?style=flat-square&labelColor=1c2024&color=88d6ba" alt='github contributors'/></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/OneiroiTheme/vscode/main/assets/oneiroi-preview.png" alt="preview" width="80%" />
</p>

## Previews

<details>
<summary>💊 malatonin</summary>
<img src="https://raw.githubusercontent.com/OneiroiTheme/vscode/main/assets/oneiroi-melatonin.png" alt="screenshot_melatonin" />
</details>
<details>
<summary>😴 dream</summary>
<img src="https://raw.githubusercontent.com/OneiroiTheme/vscode/main/assets/oneiroi-dream.png" alt="screenshot_dream" />
</details>
<details>
<summary>☕ caffeine</summary>
<img src="https://raw.githubusercontent.com/OneiroiTheme/vscode/main/assets/oneiroi-caffeine.png" alt="screenshot_caffeine" />
</details>

## Installation

### Install via Marketplace (Recommended)

1. Open the **Extensions** sidebar (`Ctrl+Shift+X` / `Cmd+Shift+X`).
2. Search for `Oneiroi Theme`.
3. Click the **Install** button.
4. Open the **Command Palette** with `Ctrl+Shift+P` or `⇧⌘P`.
5. Select **Preferences: Color Theme** and choose a Oneiroi varint.

### Manual Installation (VSIX File)

1. Clone this repository.

    ```bash
    git clone "https://github.com/OneiroiTheme/vscode.git" ./vscode
    cd ./vscode
    ```

2. Install `vsce` if you haven't already.

    ```bash
    npm install -g vsce
    ```

3. Package the extention.

    ```bash
    vsce package
    ```

4. Install the VSIX File.
    1. Open the **Command Palette** with `Ctrl+Shift+P` or `⇧⌘P`.
    2. select **Extensions: Install from VSIX**.
    3. Navigate to the generated .vsix file, and select it.

5. open the **Command Palette** again, select **Preferences: Color Theme**, and choose a Oneiroi variant.

## License

[MIT](https://raw.githubusercontent.com/OneiroiTheme/vscode/main/LICENSE) © [Oneiroi Theme](https://github.com/OneiroiTheme)
