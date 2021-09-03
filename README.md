# react-vscode-config

This is **Debugging Configuration** to debug React app with VSCode.

## Getting Started

1. Make sure you're running the latest version of VSCode.
2. ~~Also make sure the latest version of the [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) extension is installed in VS Code.~~
    > ~~If you're using **Microsoft Edge browser**, install [Debugger for Microsoft Edge](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-edge) extension.~~
    - Debugger for Chrome extension has been deprecated as Visual Studio Code now has a [bundled JavaScript Debugger](https://github.com/microsoft/vscode-js-debug) that covers the same functionality and supports the [new Microsoft Edge browser](https://www.microsoft.com/edge).
3. Download `.vscode` folder above and put it into your workspace (project root folder). After download, your project should look like this:
    >
    ```
    my-app/
      .vscode/       <-- Must be in Here
      node_modules/
      public/
      src/
      package.json
      README.md
    ```

## Debugging

1. Pick a **'Launch with Chrome'** config from the dropdown on the Debug pane on the side of VSCode.
    > If you're using the **[new Microsoft Edge browser](https://www.microsoft.com/edge)**, select **'Launch with Edge'**.
2. Press the play button or <kbd>F5</kbd> key to start debugging.
3. Set breakpoints in any of the files.
    > You could do this step before first step.

Note: You can learn more about VSCode debugger within the [Debugging in Visual Studio Code](https://code.visualstudio.com/docs/editor/debugging).

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
