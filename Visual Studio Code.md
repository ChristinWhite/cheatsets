title: Visual Studio Code Cheatsheet

# Visual Studio Code

##  Hotkeys

| Name | Command | Note |
| :--- | :------ | ---- |
|      |         |      |

---

##  Commands

|      |      |      |
| ---- | ---- | ---- |
|      |      |      |
|      |      |      |

---

# Extensions

## File Management

### Advanced New File

[Marketplace](https://marketplace.visualstudio.com/items?itemName=dkundel.vscode-new-file) • [Repo](https://github.com/dkundel/vscode-new-file) 

> An easier way of creating a new file inside a project.

#### Hotkeys

| Name              | Hotkey | Note |
| ----------------- | ------ | ---- |
| Advanced New File | `⌘⌥ N` |      |

#### Commands

| Name              | Command                    | Note |
| ----------------- | -------------------------- | ---- |
| Advanced New File | `Files: Advanced New File` |      |

#### Settings

| Setting                                  | Type    | Note                                     |
| ---------------------------------------- | ------- | ---------------------------------------- |
| `"newFile.defaultBaseFileName": "newFile",` | String  | Set the default filename.                |
| `"newFile.relativeTo": "file",`          | Option  | Set's where the new file will be relative to. Values are `file`, `root` or `project`. |
| `"newFile.defaultFileExtension": ".ts",` | String  | Set the default file extension.          |
| `"newFile.rootDirectory": "~",`          | String  | Set the path to the root directory.      |
| `"newFile.showPathRelativeTo": "root",`  | Option  | Values are `root`, `project` or `none`.  |
| `"newFile.expandBraces": false`          | Boolean | Setting to true will allow for creating multiple files such as `new-folder/{file1,file2}.js` |

## Status Bar

### Active File in StatusBar

[Marketplace](https://www.alfredforum.com/topic/3447-alfred-maestro-keyboard-maestro-integration-for-alfred/?tab=comments#comment-20153) • [Repo](https://github.com/RoscoP/ActiveFileInStatusBar) 

> Add statusbar entry to show path for currently active file.

#### Settings

| Setting                                  | Type/Option | Note                                     |
| ---------------------------------------- | ----------- | ---------------------------------------- |
| `"ActiveFileInStatusBar.enable": true,`  | Boolean     | Enable/Disable ActiveFileInStatusBar     |
| `"ActiveFileInStatusBar.fullpath": true,` | Boolean     | Show fullpath or relative path in status bar. |
| `"ActiveFileInStatusBar.revealFile": false,` | Boolean     | Reveal the active file in the file system. |

