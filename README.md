# Awesome Go Development Extension Pack

This is an extension pack for Visual Studio Code that is specifically designed to help Go developers be productive and efficient in their development work. The extension pack includes a carefully curated set of extensions that are designed to work together seamlessly to provide a comprehensive set of tools and features for working with Go code.

## How to Install

To install the Awesome Go Development Extension Pack, follow these simple steps:

1. Open Visual Studio Code and click on the "Extensions" icon in the sidebar.
2. In the search bar, type "Awesome Go Development" and press enter.
3. Click on the "Install" button next to the extension pack.
4. Wait for the installation to complete.
5. Append or replace your settings.json file with the settings provided

## List of extentions

- awehook.vscode-blink-mind: Provides a mind mapping tool to help you organize your thoughts and ideas.
- bierner.markdown-mermaid: Create diagrams and flowcharts in Markdown files using the Mermaid syntax.
- eamodio.gitlens: Provides advanced Git functionality, including blame annotations, code lens, and repository history.
- EliverLara.andromeda: A vibrant and dark color theme for VS Code.
- euskadi31.json-pretty-printer: Helps you format and prettify JSON files for better readability.
- fehey.brackets-light-pro: A simple and elegant light color theme for VS Code.
- formulahendry.code-runner: Run code snippets directly within VS Code.
- golang.go: An official extension from the Go team at Google, providing syntax highlighting, code completion, debugging, testing, formatting, and more.
- johnpapa.vscode-peacock: Customize the color of your VS Code workspace.
- josephcz.vscode-markdown-mindmap-preview: Provides a preview of Markdown files as a mind map.
- k--kato.intellij-idea-keybindings: Provides the IntelliJ IDEA keybindings for VS Code.
- maracko.json-to-go: Convert JSON to Go struct.
- mhutchie.git-graph: Provides an interactive Git history graph.    
- ms-vscode-remote.remote-containers: Develop inside a container running your application's environment.
- ms-vscode-remote.remote-ssh: Use SSH to connect to and work on remote machines.
- ms-vscode-remote.remote-ssh-edit: Open any file on a remote machine using SSH.
- ms-vscode.remote-explorer: Browse and interact with files on remote machines.
- ms-vsliveshare.vsliveshare: Bollaborate on code in real-time with other developers.
- premparihar.gotestexplorer: Provides an interface for running and managing Go tests.
- redhat.vscode-yaml:  Provides syntax highlighting and validation for YAML files.
- trybick.terminal-zoom: Zoom the terminal in and out using the keyboard.
- wraith13.zoombar-vscode: Provides a zoom bar for the editor.
- yzhang.markdown-all-in-one: Provides a range of tools for working with Markdown files, including table of contents, math typesetting, and more.


<details><summary>settings.json</summary>
<p>

```json
{
  "workbench.colorTheme": "Andromeda",
  "update.mode": "start",
  "liveshare.presence": false,
  "git.autofetch": false,
  "json-to-go.inputSource": "clipboard",
  "terminal.integrated.fontSize": 15,
  "window.zoomLevel": -2,
  "files.autoSave": "afterDelay",
  "editor.stickyScroll.enabled": true,
  "editor.formatOnSave": true,
  "editor.minimap.enabled": false,
  "editor.formatOnPaste": true,
  "editor.fontSize": 18,
  "editor.renderWhitespace": "selection",
  "workbench.activityBar.visible": true,
  "workbench.tree.indent": 10,
  "workbench.preferredLightColorTheme": "Brackets Light Pro",
  "workbench.preferredDarkColorTheme": "Andromeda",
  "workbench.sideBar.location": "right",
  "workbench.editor.highlightModifiedTabs": true,
  "diffEditor.ignoreTrimWhitespace": false,
  "diffEditor.maxComputationTime": 0,
  "diffEditor.renderSideBySide": true,
  "debug.allowBreakpointsEverywhere": true,
  "debug.inlineValues": "on",
  "debug.toolBarLocation": "docked",
  "debug.console.closeOnEnd": true,
  "editor.cursorBlinking": "phase",
  "editor.rulers": [
    80
  ],
  "workbench.colorCustomizations": {
    "[Andromeda]": {
      "tab.activeBackground": "#0b4c5e",
      "tree.indentGuidesStroke": "#ffffff",
      "statusBar.background": "#0b4c5e",
      "breadcrumb.background": "#0b4c5e",
      "activityBar.background": "#0b4c5e",
      "tab.inactiveBackground": "#062730",
      "sideBar.foreground": "#fffefc",
      "menu.selectionBackground": "#0b4c5e",
      "menu.selectionBorder": "#ffffff",
      "list.hoverBackground": "#168eaf",
      "contrastBorder": "#08333f",
      "focusBorder": "#0a3f4e",
      "foreground": "#ffffff",
      "widget.shadow": "#207f99",
      "scrollbarSlider.background": "#186d85",
      "scrollbarSlider.hoverBackground": "#186d85",
      "sideBar.background": "#0e3e4b",
      "editorGroup.emptyBackground": "#0e3e4b",
    }
  },
  "gitlens.currentLine.format": "${author, } | ${date} | ${working} ${message}",
  "gitlens.codeLens.recentChange.command": "gitlens.showQuickCommitDetails",
  "gitlens.codeLens.authors.command": "gitlens.showQuickCommitDetails",
  "gitlens.statusBar.format": "| ${author}, | ${agoOrDate}${' via 'pullRequest} |",
  "gitlens.blame.format": "${message|50?} ${agoOrDate|14-}${tips}${originalPath}",
  "remote.SSH.defaultExtensions": [
    "gitpod.gitpod-remote-ssh"
  ],
  "go.toolsManagement.autoUpdate": true,
  "go.useLanguageServer": true,
  "gopls": {
    "formatting.gofumpt": true,
  },
  "peacock.favoriteColors": [
    {
      "name": "Angular Red",
      "value": "#dd0531"
    },
    {
      "name": "Vue Green",
      "value": "#42b883"
    }
  ]
}
```

</p>
</details>

<details><summary>settings.json explained</summary>
<p>

#### Items
- "workbench.colorTheme": "Andromeda": Sets the color theme of the IDE to Andromeda.
- "update.mode": "start": Configures the update mode to check for updates at startup.
- "liveshare.presence": false: Disables the presence feature in Live Share.
- "git.autofetch": false: Disables automatic fetching of Git repositories.
- "json-to-go.inputSource": "clipboard": Sets the input source for the JSON to Go extension to the clipboard.
- "terminal.integrated.fontSize": 15: Sets the font size of the integrated terminal to 15.
- "window.zoomLevel": -2: Sets the zoom level of the IDE to -2.
- "files.autoSave": "afterDelay": Enables auto-saving of files after a delay.
- "editor.stickyScroll.enabled": true: Enables sticky scroll behavior for the editor.
- "editor.formatOnSave": true: Enables formatting of the editor contents on save.
- "editor.minimap.enabled": false: Disables the minimap in the editor.
- "editor.formatOnPaste": true: Enables formatting of pasted contents in the editor.
- "editor.fontSize": 18: Sets the font size of the editor to 18.
- "editor.renderWhitespace": "selection": Renders whitespace characters only for the selected line.
- "workbench.activityBar.visible": true: Makes the activity bar visible in the IDE.
- "workbench.tree.indent": 10: Sets the indentation for the workbench tree to 10 pixels.
- "workbench.preferredLightColorTheme": "Brackets Light Pro": Sets the preferred light color theme of the IDE to Brackets Light Pro.
- "workbench.preferredDarkColorTheme": "Andromeda": Sets the preferred dark color theme of the IDE to Andromeda.
- "workbench.sideBar.location": "right": Sets the location of the sidebar to the right.
- "workbench.editor.highlightModifiedTabs": true: Highlights modified tabs in the editor.
- "diffEditor.ignoreTrimWhitespace": false: Enables consideration of whitespace characters in the diff editor.
- "diffEditor.maxComputationTime": 0: Sets the maximum computation time for the diff editor to 0.
- "diffEditor.renderSideBySide": true: Enables rendering of the diff editor side by side.
- "debug.allowBreakpointsEverywhere": true: Allows setting breakpoints everywhere in the IDE.
- "debug.inlineValues": "on": Enables inline display of values during debugging.
- "debug.toolBarLocation": "docked": Sets the location of the debug toolbar to docked.
- "debug.console.closeOnEnd": true: Closes the debug console when debugging ends.
- "editor.cursorBlinking": "phase": Configures the cursor blinking style to phase.
- "editor.rulers": [80]: Sets the rulers for the editor to 80 pixels.
- "workbench.colorCustomizations": {...}: Customizes the color theme of the IDE for the Andromeda theme.
- "gitlens.currentLine.format": "${author, } | ${date} | ${working} ${message}": Configures the format of the GitLens current line.
- "gitlens.codeLens.recentChange.command": "gitlens.showQuickCommitDetails": Configures the command for the recent changes GitLens code lens.
- "gitlens.codeLens.authors.command": "gitlens.showQuickCommitDetails": Configures the command for the authors


</p>
</details>