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
    git clone "https://github.com/{{repository.publisher}}/{{repository.repo}}.git" ./vscode
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
