title: Visual Studio Code Cheatsheet

# Visual Studio Code

On `editor.action.webvieweditor.hideFind`

---

# Commands

## Build

| Description    | Command          | Keybinding | Where | Extension |
| -------------- | ---------------- | ---------- | ----- | --------- |
| Run Build Task | `Run Build Task` | `⇧⌘ B`     |       | Core      |
| Toggle Output  | `Toggle Output`  | `⇧⌘ U`     |       | Core      |

## Commands

| Description     | Command           | Keybinding      | Where | Extension |
| --------------- | ----------------- | --------------- | ----- | --------- |
| Command Palette | Show All Commands | `⇧⌘ P ` \| `F1` |       | Core      |

## Development Tools

| Description             | Command | Keybinding | Where            | Extension |
| ----------------------- | ------- | ---------- | ---------------- | --------- |
| Show Find   |         | `⌘ F`      | Extension Editor Webview | Core      |
| Show Next Find Term     |         | `⌥ ↓`      | Extension Editor | Core      |
| Show Previous Find Term |         | `⌥ ↑`      | Extension Editor | Core      |

## Editor

### Code Navigation

| Description | Command | Keybinding | Where | Extension |
| ----------- | ------- | ---------- | ----- | --------- |
| Move Cursor Up   |                    | `↑` \| `^ P` | Editor | Core      |
| Move Cursor Right | | `→` \| `^ F` | Editor | Core |
| Move Cursor Down |                    | `↓` \| `^ N` | Editor | Core      |
| Move Cursor Left | | `←` \| `^ B` | Editor | Core |

#### Navigate by History

| Description | Command | Keybinding | Where  | Extension |
| ----------- | ------- | ---------- | ------ | --------- |
| Cursor Undo |         | `⌘ U`      | Editor | Core      |

#### Navigate by Context

| Description             | Command                   | Keybinding | Where  | Extension |
| ----------------------- | ------------------------- | ---------- | ------ | --------- |
| Add Cursor to Line Ends | `Add Cursor to Line Ends` | `⇧⌥ I`     | Editor | Core      |
| Go to Bracket           | `Go to Bracket`           | `⇧⌘ \`     | Editor | Core      |

#### Navigate by Column

| Description      | Command            | Keybinding   | Where  | Extension |
| ---------------- | ------------------ | ------------ | ------ | --------- |
| Add Cursor Above | `Add Cursor Above` | `⌥⌘ ↑`       | Editor | Core      |
| Add Cursor Below | `Add Cursor Below` | `⌥⌘ ↓`       | Editor | Core      |

#### Navigate by Word

| Description       | Command | Keybinding | Where  | Extension |
| ----------------- | ------- | ---------- | ------ | --------- |
| Cursor Word Right |         | `⌥ →`      | Editor | Core      |
| Cursor Word Left  |         | `⌥ ←`      | Editor | Core      |

#### Navigate by Line

| Description           | Command         | Keybinding | Where  | Extension |
| --------------------- | --------------- | ---------- | ------ | --------- |
| Move to Start of Line |                 | `^ A`      | Editor | Core      |
| Move to End of Line   |                 | `^ E`      | Editor | Core      |
| Go to Line...         | `Go to Line...` | `^ G`      |        | Core      |

#### Navigate by Screen

| Description   | Command | Keybinding   | Where  | Extension |
| ------------- | ------- | ------------ | ------ | --------- |
| Move to Start |         | `⌘ ←` \| `↖` | Editor | Core      |
| Move to End   |         | `⌘ →` \| `↘` | Editor | Core      |
| Page Up       |         | `⇞`          | Editor | Core      |
| Page Down     |         | `⇟`          | Editor | Core      |

#### Navigate by File

| Description           | Command | Keybinding | Where  | Extension |
| --------------------- | ------- | ---------- | ------ | --------- |
| Move Cursor to Top    |         | `⌘ ↑`      | Editor | Core      |
| Move Cursor to Bottom |         | `⌘ ↓`      | Editor | Core      |

### Code Selection

| Description         | Command | Keybinding | Where  | Extension |
| ------------------- | ------- | ---------- | ------ | --------- |
| Select Cursor Up    |         | `⇧ ↑`      | Editor | Core      |
| Select Cursor Right |         | `⇧ →`      | Editor | Core      |
| Select Cursor Down  |         | `⇧ ↓`      | Editor | Core      |
| Select Cursor Left  |         | `⇧ ←`      | Editor | Core      |

#### Select by Context

| Description                            | Command                                  | Keybinding    | Where  | Extension |
| -------------------------------------- | ---------------------------------------- | ------------- | ------ | --------- |
| Expand Selection                       | `Expand Select`                          | `^⇧⌘ →`       | Editor | Core      |
| Shrink Selection                       | Shrink Select                            | `^⇧⌘ ←`       | Editor | Core      |
| Add Next Occurrence                    | `Add Selection To Next Find Match`       | `⌘ D`         | Editor | Core      |
| Move Last Selection to Next Find Match | `Move Last Selection To Next Find Match` | `⌘ K` + `⌘ D` | Editor | Core      |
| Select All Occurrences of First Match  | `Select All Occurrences of First Match`  | `⇧⌘ L`        | Editor | Core      |
| Change All Occurrences                 | `Change All Occurrences`                 | `⌘ F2`        | Editor | Core      |

#### Select by Column

| Description         | Command | Keybinding | Where  | Extension |
| ------------------- | ------- | ---------- | ------ | --------- |
| Column Select Up    |         | `⇧⌥⌘ ↑`    | Editor | Core      |
| Column Select Right |         | `⇧⌥⌘ →`    | Editor | Core      |
| Column Select Down  |         | `⇧⌥⌘ ↓`    | Editor | Core      |
| Column Select Left  |         | `⇧⌥⌘ ←`    | Editor | Core      |
| Column Select Page Up  |         | `⇧⌥⌘ ⇞`    | Editor | Core |
| Column Select PageDown |         | `⇧⌥⌘ ⇟`    | Editor | Core |

#### Select by Word

| Description       | Command | Keybinding | Where  | Extension |
| ----------------- | ------- | ---------- | ------ | --------- |
| Select Word Right |         | `⇧⌥ →`     | Editor | Core      |
| Select Word Left  |         | `⇧⌥ ←`     | Editor | Core      |

#### Select by Line

| Description                 | Command                    | Keybinding      | Where  | Extension        |
| --------------------------- | -------------------------- | --------------- | ------ | ---------------- |
| Select to Beginning of Line |                            | `⇧⌘ ←` \| `⇧ ↖` | Editor | Core             |
| Select to End of Line       |                            | `⇧⌘ →` \| `⇧ ↘` | Editor | Core             |
| Expand Selection to Line    | `Expand Selection to Line` | `⌘ L`           | Editor | Sublime Commands |
| Expand Selection to Line    |                            | `⌘ L` \| `⇧⌘ L` | Editor | Core             |

#### Select by Screen

| Description            | Command | Keybinding | Where | Extension |
| ---------------------- | ------- | ---------- | ----- | --------- |
|Select Page Up||`⇧ ⇞`|Editor|Core|
|Select Page Down||`⇧ ⇟`|Editor|Core|

#### Select by File

| Description      | Command | Keybinding | Where  | Extension |
| ---------------- | ------- | ---------- | ------ | --------- |
| Select All       |         | `⌘ A`      | Editor | Core      |
| Select to Top    |         | `⇧⌘ ↑`     | Editor | Core      |
| Select to Bottom |         | `⇧⌘ ↓`     | Editor | Core      |

### Code Manipulation

| Description  | Command | Keybinding                     | Where  | Extension |
| ------------ | ------- | ------------------------------ | ------ | --------- |
| Copy                               | `Copy`                               | `⌘ C`      | Editor | Core             | When no selection copy current line.     |
| Cut                                | `Cut`                                | `⌘ X`      | Editor | Core             | When no selection cut current line.      |
| Paste                              | `Paste`                              | `⌘ V`      | Editor | Core             |                                          |
| Delete Left  |         | `⌫` \| `⇧ ⌫` \| `^ ⌫` \| `^ H` | Editor | Core      |
| Delete Right |         | `⌦` \| `^ ⌦` \| `^ D`          | Editor | Core      |

#### Manipulate by Context

| Description                        | Command                              | Keybinding | Where  | Extension        | Note                                     |
| ---------------------------------- | ------------------------------------ | ---------- | ------ | ---------------- | ---------------------------------------- |
| Transpose                          | `Transpose`                          | `^ T`      | Editor | Sublime Commands |                                          |
| Transpose                          | `Transpose Letters`                  | `^ T`      | Editor | Core             |                                          |
| Transpose Characters Around Cursor | `Transpose Characters Around Cursor` |            |        | Core             |                                          |
| Toggle Block Comment               | `Toggle Block Comment`               | `⇧⌥ A`     | Editor | Core             | Inserts appropriate syntax for language. |

#### Manipulate by Word

| Description       | Command | Keybinding | Where  | Extension |
| ----------------- | ------- | ---------- | ------ | --------- |
| Delete Word Left  |         | `⌥ ⌫`      | Editor | Core      |
| Delete Word Right |         | `⌥ ⌦`      | Editor | Core      |

#### Manipulate by Line

| Description         | Command               | Keybinding     | Where  | Extension        |
| ------------------- | --------------------- | -------------- | ------ | ---------------- |
| Move Line Up        | `Move Line Up`        | `⌥ ↑`          | Editor | Core             |
| Move Line Down      | `Move Line Down`      | `⌥ ↓`          | Editor | Core             |
| Insert Line Above   | `Insert Line Above`   | `⇧⌘ ↵`         | Editor | Core             |
| Insert Line Below   | `Insert Line Below`   | `⌘ ↵`          | Editor | Core             |
| Copy Line Up        | `Copy Line Up`        | `⇧⌥ ↑`         | Editor | Core             |
| Copy Line Down      | `Copy Line Down`      | `⇧⌥ ↓`         | Editor | Core             |
| Toggle Line Comment | `Toggle Line Comment` | `⌘ /`          | Editor | Core             |
| Comment Line        | `Add Line Comment`    | `⌘ K` + `⌘ C`  | Editor | Core             |
| Uncomment Line      | `Remove Line Comment` | `⌘ K` + `⌘ U`  | Editor | Core             |
| Indent Line         | `Indent Line`         | `⌘ ]`          | Editor | Core             |
| Outdent Line        | `Outdent Line`        | `⌘ [`          | Editor | Core             |
| Split               | `Split into Lines`    | `⇧⌘ L`         | Editor | Sublime Commands |
| Join                | `Join Lines`          | `⌘ J`          | Editor | Sublime Commands |
| Join                | `Join Lines`          | `⌘ J` \| `^ J` |        | Core             |
| Delete All Left     | `Delete All Left`     | `⌘ ⌫`          | Editor | Core             |
| Delete All Right    | `Delete All Right`    | `⌘ ⌦` \| `^ K` | Editor | Core             |
| Delete Line         | `Delete Line`         | `⇧⌘ K`         | Editor | Core             |

#### Manipulation by File

| Description              | Command                    | Keybinding    | Where  | Extension |
| ------------------------ | -------------------------- | ------------- | ------ | --------- |
| Trim Trailing Whitespace | `Trim Trailing Whitespace` | `⌘ K` + `⌘ X` | Editor | Core      |

### Folding

| Description             | Command                   | Keybinding         | Where  | Extension |
| ----------------------- | ------------------------- | ------------------ | ------ | --------- |
| Fold                    | `Fold`                    | `⌥⌘ [`             | Editor | Core      |
| Unfold                  | `Unfold`                  | `⌥⌘ [`             | Editor | Core      |
| Fold All                | `Fold All`                | `⌘ K` + `⌘ 0`      | Editor | Core      |
| Unfold All              | `Unfold All`              | `⌘ K` + `⌘ J`      | Editor | Core      |
| Fold Recursively        | `Fold Recursively`        | `⌘ K` + `⌘ [`      | Editor | Core      |
| Unfold Recursively      | `Unfold Recursively`      | `⌘ K` + `⌘ ]`      | Editor | Core      |
| Fold All Block Comments | `Fold All Block Comments` | `⌘ K` + `⌘ /`      | Editor | Core      |
| Fold All Regions        | `Fold All Regions`        | `⌘ K` + `⌘ 8`      | Editor | Core      |
| Unfold All Regions      | `Unfold All Regions`      | `⌘ K` + `⌘ 9`      | Editor | Core      |
| Fold Level # {1-7}      | `Fold Level #{1-7}`       | `⌘ K` + `⌘ #{1-7}` | Editor | Core      |

## Extensions

| Description | Command   | Keybinding    | Where | Extension | Note                                             |
| ----------- | --------- | ------------- | ----- | --------- | ------------------------------------------------ |
| Show Extensions | `Show Extensions` | `⇧⌘ X`     |       | Core      |
| Keymaps     | `Keymaps` | `⌘ K` + `⌘ M` |       | Core      | Searches extensions for all recommended keymaps. |

## Find & Replace

| Description                 | Command                       | Keybinding       | Where                        | Extension |
| --------------------------- | ----------------------------- | ---------------- | ---------------------------- | --------- |
| Find                        | `Find`                        | `⌘ F` \| `⌘ E`   |                              | Core      |
| Find Next                   | `Find Next`                   | `⌘ G` \| `F3`    | Editor                       | Core      |
| Find Previous               | `Find Previous`               | `⇧⌘ G` \| `⇧ F3` | Editor                       | Core      |
| Find Next Selection         | `Find Next Selection`         | `⌘ G` \| `⌘ F3`  | Editor                       | Core      |
| Find Previous Selection     | `Find Previous Selection`     | `⇧⌘ F3`          | Editor                       | Core      |
| Find in Files               | `Find in Files`               | `⇧⌘ F`           | Search Input                 | Core      |
| Show Next Find Term         | `Show Next Find Term`         | `⌥ ↓`            | Editor & Find Input          | Core      |
| Show Previous Find Term     | `Show Previous Find Term`     | `⌥ ↑`            | Editor & Find Input          | Core      |
| Select All Matches          |                               | `⌥ ↵`            | Editor & Find Widget Visible | Core      |
| Replace                     | `Replace`                     | `⌥⌘ F`           |                              | Core      |
| Replace One                 |                               | `⇧⌘ 1`           | Editor & Find Widget Visible | Core      |
| Replace All                 |                               | `⌥⌘ ↵`           | Editor & Find Widget Visible | Core      |
| Replace in Files            | `Replace in Files`            | `⇧⌘ H`           |                              | Core      |
| Replace with Next Value     | `Replace with Next Value`     | `⇧⌘ .`           | Editor                       | Core      |
| Replace with Previous Value | `Replace with Previous Value` | `⇧⌘ ,`           | Editor                       | Core      |

## Intelligence

| Description                     | Command                           | Keybinding    | Where                                | Extension |
| ------------------------------- | --------------------------------- | ------------- | ------------------------------------ | --------- |
| Go to Definition                | `Go to Definition`                | `F12`         | Has Definition Provider & Editor     | Core      |
| Peek Definition                 | `Peek Definition`                 | `⌥ F12`       | Has Definition Provider & Editor     | Core      |
| Open Definition to the Side     | `Open Definition to the Side`     | `⌘ K` + `F12` | Has Definition Provider & Editor     | Core      |
| Go to Implementation            | `Go to Implementation`            | `⌘ F12`       | Has Implementation Provider & Editor | Core      |
| Peek Implementation             | `Peek Implementation`             | `⇧⌘ F12`      | Has Implementation Provider & Editor | Core      |
| Find All References             | `Find All References`             | `⇧ F12`       | Has Reference Provider & Editor      | Core      |
| Quick Fix                       | `Quick Fix`                       | `⌘ .`         | Has Code Actions Provider & Editor   | Core      |
| Refactor                        | `Refactor`                        | `^⇧ R`        | Has Code Actions Provider & Editor   | Core      |


### Diagnostics & Linting

| Description                                   | Command                                         | Keybinding | Where | Extension |
| --------------------------------------------- | ----------------------------------------------- | ---------- | ----- | --------- |
| Toggle Problems | `Toggle Problems (Errors, Warnings, Infos)` | `⇧⌘ M` | | Core |
| Go to Next Problem (Error, Warning, Info)     | `Go to Next Problem (Error, Warning, Info)`     | `F8`       |       | Core      |
| Go to Previous Problem (Error, Warning, Info) | `Go to Previous Problem (Error, Warning, Info)` | `⇧ F8`     |       | Core      |

### Formatting

| Description      | Command            | Keybinding    | Where              | Extension |
| ---------------- | ------------------ | ------------- | ------------------ | --------- |
| Format Document  | `Format Document`  | `⇧⌥ F`        | Editor             | Core      |
| Format Selection | `Format Selection` | `⌘ K` + `⌘ F` | Selection & Editor | Core      |

### Symbols

| Description | Command | Keybinding | Where | Extension |
| ----------- | ------- | ---------- | ----- | --------- |
| Go to Symbol in Workspace...    | `Go to Symbol in Workspace...`    | `⌘ T`         |                                      | Core      |
| Go to Symbol in File...         | `Go to Symbol in File...`         | `⇧⌘ O`        |                                      | Core      |
| Go to Next Symbol Highlight     | `Go to Next Symbol Highlight`     | `F7`          | Has Highlight & Editor               | Core      |
| Go to Previous Symbol Highlight | `Go to Previous Symbol Highlight` | `⇧ F7`        | Has Highlight & Editor               | Core      |
| Rename Symbol                   | `Rename Symbol`                   | `F2`          | Has Rename Provider & Editor         | Core      |

## Language Specific

### JavaScript

#### JSON

| Description       | Command | Keybinding    | Where         | Extension |
| ----------------- | ------- | ------------- | ------------- | --------- |
| Define Keybinding |         | `⌘ K` + `⌘ K` | Editor & JSON | Core      |

### Markdown

| Description                      | Command                                      | Keybinding            | Where             | Extension           |
| -------------------------------- | -------------------------------------------- | --------------------- | ----------------- | ------------------- |
| Toggle Bold                      |                                              | `⌘ B`                 | Editor & Markdown | Markdown All In One |
| Toggle Italic                    |                                              | `⌘ I`                 | Editor & Markdown | Markdown All In One |
| Toggle Code Span                 | `Markdown: Toggle code span`                 |                       |                   | Markdown All In One |
| Toggle Strikethrough             | `Markdown: Toggle strikethrough`             |                       |                   | Markdown All In One |
| Toggle Heading Up                |                                              | `^⇧ ]`                | Editor & Markdown | Markdown All In One |
| Toggle Heading Down              |                                              | `^⇧ [`                | Editor & Markdown | Markdown All In One |
| Toggle Task Status               |                                              | `⌥ C`                 |                   | Markdown All In One |
| Create Table of Contents         | `Markdown: Create Table of Contents`         |                       |                   | Markdown All In One |
| Update Table of Contents         | `Markdown: Update Table of Contents`         |                       |                   | Markdown All In One |
| Open Preview                     | `Markdown: Open Preview`                     | `⇧⌘ V`                | Markdown          | Core                |
| Open Preview to the Side         | `Markdown: Open Preview to the Side`         | `^⇧ M` \| `⌘ K` + `V` | Markdown          | Core                |
| Open Locked Preview to the Side  | `Markdown: Open Locked Preview to the Side`  |                       |                   | Core                |
| Toggle Preview Locking           | `Markdown: Toggle Preview Locking`           |                       |                   | Core                |
| Refresh Preview                  | `Markdown: Refresh Preview`                  |                       |                   | Core                |
| Change Preview Security Settings | `Markdown: Change Preview Security Settings` |                       |                   | Core                |
| Show Source                      | `Markdown: Show Source`                      |                       |                   | Core                |
| Print to HTML                    | `Markdown: Print current document to HTML`   |                       |                   | Markdown All In One |

### Regex

| Description    | Command          | Note                                          | Extension                 |
| -------------- | ---------------- | --------------------------------------------- | ------------------------- |
| RegExp Preview | `RegExp Preview` | Preview selected regular expression.          | RegExp Preview and Editor |
| RegExp Editor  | `RegExp Editor`  | Open a regular expression editor and preview. | RegExp Preview and Editor |

## Notifications

| Description                 | Command                       | Keybinding   | Where        | Extension |
| --------------------------- | ----------------------------- | ------------ | ------------ | --------- |
| Show Explorer              | `Show Explorer`              | `⇧⌘ E`      |       | Core      |
| Focus on Open Editors View | `Focus on Open Editors View` | `⌘ K` + `E` |       | Core      |

## Panel

| Description     | Command                      | Keybinding | Where | Extension |
| --------------- | ---------------------------- | ---------- | ----- | --------- |
| Toggle Panel    | `Toggle Panel`               | `⌘ J`      |       | Core      |
| Toggle Problems | `Toggle Problems (Errors, Warnings, Infos)` | `⇧⌘ M` | | Core |
| Toggle Output  | `Toggle Output`  | `⇧⌘ U`     |       | Core      |
| Toggle Debug Console    | `Debug Console`            | `⇧⌘ Y`        |                     | Core      |
| Toggle Terminal | `Toggle Integrated Terminal` | ``^ ` ``   |       | Core      |

## Projects & Files

### Explorer

| Description                    | Command    | Keybinding | Where | Extension |
| ------------------------------ | ---------- | ---------- | ----- | --------- |
| Show Explorer              | `Show Explorer`              | `⇧⌘ E`      |       | Core      |
| Focus on Open Editors View | `Focus on Open Editors View` | `⌘ K` + `E` |       | Core      |
| Delete File |  | `⌥⌘ ⌫` | Explorer | Core |

### File Management

| Description       | Command                    | Keybinding | Where    | Extension         |
| ----------------- | -------------------------- | ---------- | -------- | ----------------- |
| New File          | `New Untitled File`        | `⌘ N`      |          | Core              |
| Advanced New File | `Files: Advanced New File` | `⌘⌥ N`     |          | Advanced New File |
| Open...           | `Open...`                  | `⌘ O`      |          | Core              |
| Open Recent...    | `Open Recent...`           | `^ R`      |          | Core              |
| Copy File Path    |                            | `⌥⌘ C`     | Explorer | Core              |
| Save All          | `Save All`                 | `⌥⌘ S`     |          | Core              |

### File Settings

| Description          | Command                | Keybinding  | Where | Extension |
| -------------------- | ---------------------- | ----------- | ----- | --------- |
| Change Language Mode | `Change Language Mode` | `⌘ K` + `M` |       | Core      |

## Reference

| Description                  | Command                        | Keybinding    | Where  | Extension | Note                         |
| ---------------------------- | ------------------------------ | ------------- | ------ | --------- | ---------------------------- |
| Keyboard Shortcuts Reference | `Keyboard Shortcuts Reference` | `⌘ K` + `⌘ R` |        | Core      | Opens cheatsheet in browser. |
| Show Accessibility Help      | `Show Accessibility Help`      | `⌥ F1`        | Editor | Core      |                              |
| Hide Interface Overview  | `Hide Interface Overview`  | `⎋`            | Interface Overview | Core      |

### Interactive Playground

| Description        | Command              | Keybinding | Where                           | Extension |
| ------------------ | -------------------- | ---------- | ------------------------------- | --------- |
| Scroll Up (Line)   | `Scroll Up (Line)`   | `↑`        | Interactive Playground & Editor | Core      |
| Scroll Down (Line) | `Scroll Down (Line)` | `↓`        | Interactive Playground & Editor | Core      |
| Scroll Up (Page)   | `Scroll Up (Page)`   | `⇞`        | Interactive Playground & Editor | Core      |
| Scroll Down (Page) | `Scroll Down (Page)` | `⇟`        | Interactive Playground & Editor | Core      |

## Run

| Description             | Command                    | Keybinding    | Where               | Extension |
| ----------------------- | -------------------------- | ------------- | ------------------- | --------- |
| Start Debugging         | `Start Debugging`          | `F5`          | Not in Debug Mode   | Core      |
| Start Without Debugging | `Start Without Debugging`  | `^ F5`        | Not in Debug Mode   | Core      |
| Continue                | `Continue`                 | `F5`          | Debug Mode          | Core      |
| Step Into               | `Step Into`                | `F11`         | Debug Mode          | Core      |
| Step Out                | `Step Out`                 | `⇧ F11`       | Debug Mode          | Core      |
| Step Over               | `Step Over`                | `F10`         | Debug Mode          | Core      |
| Pause                   | `Pause`                    | `F6`          | Debug Mode          | Core      |
| Stop                    | `Stop`                     | `⇧ F5`        | Debug Mode          | Core      |
| Restart                 | `Restart`                  | `⇧⌘ F5`       | Debug Mode          | Core      |
| Debug Console           | `Debug Console`            | `⇧⌘ Y`        |                     | Core      |
| Show Hover in Debug     | `Debug: Show Hover`        | `⌘ K` + `⌘ I` | Editor & Debug Mode | Core      |
| Open Loaded Script      | `Open Loaded Script`       | `⌘ F4`        | Debug Mode          | Core      |
| Show Debug  | `Show Debug` | `⇧⌘ D`     |       | Core      |

#### Breakpoints

| Description | Command | Keybinding | Where | Extension |
| ----------- | ------- | ---------- | ----- | --------- |
| Toggle Breakpoint       | `Debug: Toggle Breakpoint` | `F9`          | Editor              | Core      |
| ↳ Toggle Breakpoint |  | `Space` | Breakpoint | Core |
| Open Breakpoint to Side |  | `⌥ ↵` \| `⌘ ↵` | Breakpoint | Core |
| Remove Breakpoint |  | `⌘ ⌫` | Breakpoint | Core |

#### Debug REPL

| Description       | Command             | Keybinding | Where               | Extension |
| ----------------- | ------------------- | ---------- | ------------------- | --------- |
| REPL Accept Input | `REPL Accept Input` | `↵`        | Debug Repl & Editor | Core      |
| History Next      | `History Next`      | `↓`        | Debug Repl          | Core      |
| History Previous  | `History Previous`  | `↑`        | Debug Repl          | Core      |

#### Variables

| Description  | Command | Keybinding | Where    | Extension |
| ------------ | ------- | ---------- | -------- | --------- |
| Set Variable |         | `↵`        | Variable | Core      |

#### Watch Expressions

| Description             | Command | Keybinding | Where            | Extension |
| ----------------------- | ------- | ---------- | ---------------- | --------- |
| Remove Watch Expression |         | `⌘ ⌫`      | Watch Expression | Core      |
| Rename Watch Expression |         | `↵`        | Watch Expression | Core      |

## Settings

| Description                | Command                      | Keybinding    | Where | Extension |
| -------------------------- | ---------------------------- | ------------- | ----- | --------- |
| Open User Settings         | `Open User Settings`         | `⌘ ,`         |       | Core      |
| Open Keyboard Shortcuts    | `Open Keyboard Shortcuts`    | `⌘ K` + `⌘ S` |       | Core      |
| Toggle Tab Key Moves Focus | `Toggle Tab Key Moves Focus` | `^⇧ M`        |       | Core      |

## Side Bar

| Description        | Command               | Keybinding | Where | Extension |
| ------------------ | --------------------- | ---------- | ----- | --------- |
| Toggle Side Bar Visibility | `Toggle Side Bar Visibility` | `⌘ B` \| `⌘ \` \| `⌘ K + ⌘ B` |  | Core |
| Focus into Sidebar | `Focus into Side Bar` | `⌘ 0`      |       | Core      |
| Show Explorer              | `Show Explorer`              | `⇧⌘ E`      |       | Core      |
| Show Search | `Show Search` | `⇧⌘ F` |  | Core |
| Show Source Control Management | `Show SCM` | `^⇧ G`     |       | Core      |
| Show Debug  | `Show Debug` | `⇧⌘ D`     |       | Core      |
| Show Extensions | `Show Extensions` | `⇧⌘ X`     |       | Core      |

## Search

| Description | Command | Keybinding | Where | Extension |
| ----------- | ------- | ---------- | ----- | --------- |
| Show Search | `Show Search` | `⇧⌘ F` |  | Core |
| Focus Next Search Result     | `Focus Next Search Result`     | `F4`             |              | Core      |
| Focus Previous Search Result | `Focus Previous Search Result` | `⇧ F4`           |              | Core      |
| Show Next Search Term | `Show Next Search Term` | `⌥ ↓` | Search Input | Core |
| Show Previous Search Term | `Show Previous Search Term` | `⌥ ↑` | Search Input | Core |
| Show Next Search Include Pattern | `Show Next Search Include Pattern` | `⌥ ↓` | Search Include Input | Core |
| Show Previous Search Include Pattern | `Show Previous Search Include Pattern` | `⌥ ↑` | Search Include Input | Core |
| Show Next Search Exclude Pattern | `Show Next Search Exclude Pattern` | `⌥ ↓` | Search Exclude Input | Core |
| Show Previous Search Exclude Pattern | `Show Previous Search Exclude Pattern` | `⌥ ↑` | Search Exclude Input | Core |

## Snippets

### Emmet

| Description               | Command                      | Keybinding | Where                     | Extension |
| ------------------------- | ---------------------------- | ---------- | ------------------------- | --------- |
| Expand Emmet Abbreviation | `Emmet: Expand Abbreviation` | `⇥`        | Emmet Configured & Editor | Core      |

## Source Control & Comparisons

| Description                    | Command    | Keybinding | Where | Extension |
| ------------------------------ | ---------- | ---------- | ----- | --------- |
| Show Source Control Management | `Show SCM` | `^⇧ G`     |       | Core      |

### Changes

| Description          | Command                | Keybinding | Where  | Extension |
| -------------------- | ---------------------- | ---------- | ------ | --------- |
| Show Next Change     | `Show Next Change`     | `⌥ F3`     | Editor | Core      |
| Show Previous Change | `Show Previous Change` | `⇧⌥ F3`    | Editor | Core      |

### Compare

| Description                        | Command                              | Keybinding  | Where       | Extension |
| ---------------------------------- | ------------------------------------ | ----------- | ----------- | --------- |
| Compare Active File with Clipboard | `Compare Active File with Clipboard` | `⌘ K` + `C` |             | Core      |
| Go to Next Difference              | `Go to Next Difference`              | `F7`        | Diff Editor | Core      |
| Go to Previous Difference          | `Go to Previous Difference`          | `⇧ F7`      | Diff Editor | Core      |

## Terminal

| Description         | Command                          | Keybinding   | Where    | Extension |
| ------------------- | -------------------------------- | ------------ | -------- | --------- |
| Toggle Terminal | `Toggle Integrated Terminal` | ``^ ` `` |  | Core |
| Create New Terminal | `Create New Integrated Terminal` | ``^⇧ ` ``    |          | Core      |
| Scroll Up (Line) | `Scroll Up (Line)` | `⌘ ↑` | Terminal | Core |
| Scroll Down (Line) | `Scroll Down (Line)` | `⌘ ↓` | Terminal | Core |
| Scroll Up (Page) | `Scroll Up (Page)` | `⇞` | Terminal | Core |
| Scroll Down (Page) | `Scroll Down (Page)` | `⇟` | Terminal | Core |
| Scroll to Top | `Scroll to Top` | `⌘ ↖` | Terminal | Core |
| Scroll to Bottom | `Scroll to Bottom` | `⌘ ↘` | Terminal | Core |
| Move to Line End   | `Move To Line End` | `⌘ →`      | Terminal | Core      |
| Move to Line Start | `Move To Line Start` | `⌘ ←`      | Terminal | Core      |
| Delete Word Left    | `Delete Word Left`               | `⌥ ⌫`        | Terminal | Core      |
| Delete Word Right   | `Delete Word Right`              | `⌥ ⌦`        | Terminal | Core      |
| Clear               | `Clear`                          | `⌘ K`        | Terminal | Core      |
| Select All  | `Select All` | `⌘ A`      | Terminal | Core      |
| Copy Selection      | `Terminal: Copy Selection`       | `⌘ C`        | Terminal | Core      |
| Focus Find Widget   | `Focus Find Widget`              | `⌘ F`        | Terminal | Core      |
| Show Next Find Term         | `Show Next Find Term`         | `⌥ ↓`            | Editor & Find Input | Core      |
| Show Previous Find Term     | `Show Previous Find Term`     | `⌥ ↑`            | Editor & Find Input | Core      |
| Hide Find Widget    | `Hide Find Widget`               | `⎋` \| `⇧ ⎋` | Terminal | Core      |

## Tracking

| Description                     | Command                    | Note                                                               | Extension |
| ------------------------------- | -------------------------- | ------------------------------------------------------------------ | --------- |
| Open WakaTime Dashboard         | `WakaTime Dashboard`       | Opens in default browser                                           | WakaTime  |
| Toggle WakaTime Status Bar Icon | `WakaTime Status Bar Icon` | Allows you to show or hide the small clock icon in the status bar. | WakaTime  |
| WakaTime API Key                | `WakaTime API Key`         | Set or edit the API key                                            | WakaTime  |
| WakaTime Proxy                  | `WakaTime Proxy`           | Set or edit a WakaTime proxy setting.                              | WakaTime  |
| Toggle Debug for WakaTime       | `WakaTime Debug`           | Exposes WakaTime debug information to the developer tools console. | WakaTime  |

## UI

| Description      | Command                  | Keybinding    | Where | Extension |
| ---------------- | ------------------------ | ------------- | ----- | --------- |
| Color Theme      | `Color Theme`            | `⌘ K` + `⌘ T` |       | Core      |
| Toggle Word Wrap | `View: Toggle Word Wrap` | `⌥ Z`         |       | Core      |
| Toggle Zen Mode  | `Toggle Zen Mode`        | `⌘ K` + `Z`   |       | Core      |
| Toggle Tab Visibility      | `Toggle Tab Visibility`      | `^⌘ W`        |       | Core      |

### Contextual UI

| Description | Command | Keybinding | Where | Extension |
| ----------- | ------- | ---------- | ----- | --------- |
| Show Editor Context Menu | `Show Editor Context Menu` | `⇧ F10`        | Editor             | Core      |
| Show Hover               | `Show Hover`               | `⌘ K` \| `⌘ I` | Editor             | Core      |
| Trigger Parameter Hints | `Trigger Parameter Hints` | `⇧⌘ Space` | Has Signature Provider & Editor | Core |
| Trigger Suggest | `Trigger Suggest` | `^ Space` | Has Completion Item Provider & Editor | Core |

### Zoom

| Description | Command      | Keybinding                       | Where | Extension |
| ----------- | ------------ | -------------------------------- | ----- | --------- |
| Zoom In     | `Zoom In`    | `⌘ =` \| `⇧⌘ +` \| `⌘ +{NumPad}` |       | Core      |
| Zoom Out    | `Zoom Out`   | `⌘ -` \| `⇧⌘ _` \| `⌘ -{NumPad}` |       | Core      |
| Reset Zoom  | `Reset Zoom` | `⌘ 0{NumPad}`                    |       | Core      |

## Windows

| Description                    | Command                          | Keybinding      | Where      | Extension | Note                                                         |
| ------------------------------ | -------------------------------- | --------------- | ---------- | --------- | ------------------------------------------------------------ |
| New Window                     | `New Window`                     | `⇧⌘ N`          |            | Core      |                                                              |
| Open Active File in New Window | `Open Active File in New Window` | `⌘ K` + `O`     |            | Core      |                                                              |
| Switch Window...               | `Switch Window...`               | `^ W`           |            | Core      |                                                              |
| Quick Open View                | `Quick Open View`                | `^ Q`           |            | Core      | Lists and switches between open windows that switches when you release `^` command-tab style. |
| Select Next in Quick Open      | `Select Next in Quick Open`      | `^ N`           | Quick Open | Core      |                                                              |
| Select Previous in Quick Open  | `Select Previous in Quick Open`  | `^ P`           | Quick Open | Core      |                                                              |
| Toggle Full Screen             | `Toggle Full Screen`             | `^⌘ F`          |            | Core      |                                                              |
| Close Window                   | `Close Window`                   | `⌘ W` \| `⇧⌘ W` |            | Core      |                                                              |

### Editors

| Description                                 | Command                                          | Keybinding       | Where | Extension |
| ------------------------------------------- | ------------------------------------------------ | ---------------- | ----- | --------- |
| Focus First Editor Group                    | `Focus First Editor Group`                       | `⌘ 1`            |       | Core      |
| Focus Second Editor Group                   | `Focus Second Editor Group`                      | `⌘ 2`            |       | Core      |
| Focus Third Editor Group                    | `Focus Third Editor Group`                       | `⌘ 3`            |       | Core      |
| Focus Next Group                            | `Focus Next Group`                               | `⌘ K` + `⌘ →`    |       | Core      |
| Focus Previous Group                        | `Focus Previous Group`                           | `⌘ K` + `⌘ ←`    |       | Core      |
| Open Last Editor in Group                   | `Open Last Editor in Group`                      | `⌘ 9` \| `^ 0`   |       | Core      |
| Open Next Recently Used Editor in Group     | `Open Next Recently Used Editor in Group`        | `^ ⇥`            |       | Core      |
| Open Previous Recently Used Editor in Group | `Open Previous Recently Used Editor in Group`    | `^⇧ ⇥`           |       | Core      |
| Open Next Editor                            | `Open Next Editor`                               | `⌥⌘ →` \| `⇧⌘ ]` |       | Core      |
| Open Previous Editor                        | `Open Previous Editor`                           | `⌥⌘ ←` \| `⇧⌘ [` |       | Core      |
| Reopen Closed Editor                        | `Reopen Closed Editor`                           | `⇧⌘ T`           |       | Core      |
| Move Editor into First Group                | `Move Editor into First Group`                   | `^⌘ 1`           |       | Core      |
| Move Editor into Second Group               | `Move Editor into Second Group`                  | `^⌘ 2`           |       | Core      |
| Move Editor into Third Group                | `Move Editor into Third Group`                   | `^⌘ 3`           |       | Core      |
| Move Editor into Next Group                 | `Move Editor into Next Group`                    | `^⌘ →`           |       | Core      |
| Move Editor into Previous Group             | `Move Editor into Previous Group`                | `^⌘ ←`           |       | Core      |
| Move Editor Group Left                      | `Move Editor Group Left`                         | `⌘ K` + `←`      |       | Core      |
| Move Editor Group Right                     | `Move Editor Group Right`                        | `⌘ K` + `→`      |       | Core      |
| Move Editor Left                            | `Move Editor Left`                               | `⌘ K` + `⇧⌘ ←`   |       | Core      |
| Move Editor Right                           | `Move Editor Right`                              | `⌘ K` + `⇧⌘ →`   |       | Core      |
| Split Editor                                | `Split Editor`                                   | `⌘ \`            |       | Core      |
| Toggle Split Orientation                    | `Toggle Editor Group Vertical/Horizontal Layout` | `⌥⌘ 0`           |       | Core      |
| Show All Editors                            | `Show All Editors`                               | `⌥⌘ ⇥`           |       | Core      |
| Close All Editors                           | `Close All Editors`                              | `⌘ K` + `⌘ W`    |       | Core      |

### History

| Description | Command      | Keybinding | Where | Extension |
| ----------- | ------------ | ---------- | ----- | --------- |
| Go Back     | `Go Back`    | `^ -`      |       | Core      |
| Go Forward  | `Go Forward` | `^⇧ -`     |       | Core      |

### Workspace

| Description     | Command           | Keybinding  | Where | Extension |
| --------------- | ----------------- | ----------- | ----- | --------- |
| Close Workspace | `Close Workspace` | `⌘ K` + `F` |       | Core      |

---

# Extensions

## Code

### Code Checking

#### EditorConfig for VS Code

[Marketplace](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) | [Repo](https://github.com/editorconfig/editorconfig-vscode.git)

> EditorConfig Support for Visual Studio Code

Supported properties:

- `indent_style`
- `indent_size`
- `tab_width`
- `end_of_line`
- `insert_final_newline`
- `trim_trailing_whitespace`

### Code Manipulation

#### Sublime Commands

[Marketplace](https://marketplace.visualstudio.com/items?itemName=Zarel.sublime-commands) | [Repo](https://github.com/Zarel/vscode-sublime-commands.git)

> Adds commands from Sublime Text to VS Code: Transpose, Expand Selection to Line, Split into Lines, Join Lines

| Description    | Command                    | Keybinding | When   |
| -------------- | -------------------------- | ---------- | ------ |
| Transpose      | `Transpose`                | `^ T`      | Editor |
| Expand to Line | `Expand Selection to Line` | `⌘ L`      | Editor |
| Split          | ``Split into Lines``       | `⇧⌘ L`     | Editor |
| Join           | `Join Lines`               | `⌘ J`      | Editor |

## Keymapping

### Atom Keymap

[Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings) | [Repo](https://github.com/Microsoft/vscode-atom-keybindings.git)

> Popular Atom keybindings for Visual Studio Code

| Description                   | Command                                | Keybinding               | When     | Note                                                                                                                    |
| ----------------------------- | -------------------------------------- | ------------------------ | -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Preferences                   | `Preferences: Open User Settings`      | `⌘ ,`                    |          |                                                                                                                         |
| Toggle Full Screen            | `View: Toggle Full Screen`             | `^⌘ F`                   |          |                                                                                                                         |
| Toggle Zen Mode               | `View: Toggle Zen Mode`                | `^⇧⌘ F`                  |          | Full screen view with minimal UI.                                                                                       |
| Toggle Sidebar                | `View: Toggle Sidebar Visibility`      | `⌘ \` \| `⌘ K` + `⌘ B`   |          |                                                                                                                         |
| Toggle Terminal               | `View: Toggle Integrated Terminal`     | `^⌥ T`                   |          |                                                                                                                         |
| Split Editor                  | `View: Split Editor`                   | `⌘ K` + `←`              |          |                                                                                                                         |
| Zoom In                       | `View: Zoom In`                        | `⌘ =`                    |          | Increases size of all UI elements including editor text.                                                                |
| Zoom Out                      | `View: Zoom Out`                       | `⌘ -`                    |          | Decreases size of all UI elements including editor text.                                                                |
| Go to File...                 | `Go to File...`                        | `⌘ T`                    |          | Technically the command appears to be a menu item, not a proper command.                                                |
| Show All Editors              | `View: Show All Editors`               | `⌘ B`                    |          | Basically `Go to File...` but only listing open files.                                                                  |
| Open Editor at Index # {1-9}  |                                        | `⌘ #{1-9}`               |          | Selects editor or tab by index number                                                                                   |
| Redo                          |                                        | `⌘ Y`                    |          |                                                                                                                         |
| Open File or Folder           | `Open...`                              | `⌘⇧ O`                   |          |                                                                                                                         |
| New File                      |                                        | `A`                      | Explorer |                                                                                                                         |
| New Folder                    |                                        | `⇧ A`                    | Explorer |                                                                                                                         |
| Copy                          |                                        | `⌘ C`                    | Explorer |                                                                                                                         |
| Open to Side                  |                                        | `⌘ 1`                    | Explorer | Open's highlighted file as a new pane to the right of existing panes.                                                   |
| Move File to Trash            |                                        | `⌫`                      | Explorer |                                                                                                                         |
| Collapse List                 |                                        | `H`                      | Explorer |                                                                                                                         |
| Expand List                   |                                        | `L`                      | Explorer |                                                                                                                         |
| Focus Down List               |                                        | `J`                      | Explorer |                                                                                                                         |
| Focus Up List                 |                                        | `K`                      | Explorer |                                                                                                                         |
| Reveal Active File in Sidebar | `File: Reveal Active File in Sidebar`  | `⌥⌘ \`                   |          |                                                                                                                         |
| Copy Path of Active File      |                                        | `^⇧ C`                   |          |                                                                                                                         |
| Change Language Mode          | `Change Language Mode`                 | `^⇧ L`                   |          | Set language/syntax                                                                                                     |
| Open Preview to Side          | `Open Preview to Side`                 | `^⇧ M`                   |          |                                                                                                                         |
| Go to Symbol                  | `Go to Symbol in File...`              | `⌘ R`                    |          |                                                                                                                         |
| Go to Bracket                 | `Go To Bracket`                        | `^ M`                    | Editor   |                                                                                                                         |
| Column Select Up              |                                        | `^⇧ ↑`                   | Editor   | Expand or contract selection up by column.                                                                              |
| Column Select Down            |                                        | `^⇧ ↓`                   | Editor   | Expand or contract selection down by column.                                                                            |
| Select All Occurrences        | `Select All Occurrences of Find Match` | `^⌘ G`                   | Editor   |                                                                                                                         |
| Insert Cursor at Line Ends    | `Add Cursors to Line Ends`             | `⇧⌘ L`                   | Editor   |                                                                                                                         |
| Fold                          | `Fold`                                 | `⌥⌘ [`                   | Editor   | Redundant.                                                                                                              |
| Unfold                        | `Unfold`                               | `⌥⌘ ]`                   | Editor   | Redundant.                                                                                                              |
| Fold All                      | `Fold All`                             | `⌥⇧⌘ [`                  | Editor   |                                                                                                                         |
| Unfold All                    | `Unfold All`                           | `⌥⇧⌘ ]` \| `⌘ K` + `⌘ 0` | Editor   |                                                                                                                         |
| Fold Level # {1-5}            | `Fold Level #{1-5}`                    | `⌘ K` + `⌘ #{1-5}`       | Editor   | Redundant.                                                                                                              |
| Open Link                     | `Open Link`                            | `^⇧ O`                   |          |                                                                                                                         |
| Move Line Up                  | `Move Line Up`                         | `^⌘ ↑`                   | Editor   |                                                                                                                         |
| Move Line Down                | `Move Line Down`                       | `^⌘ ↓`                   | Editor   |                                                                                                                         |
| Copy Line Up                  | `Copy Line Up`                         | `⇧⌥ ↑`                   | Editor   |                                                                                                                         |
| Copy Line Down                | `Copy Line Down`                       | `⇧⌘ D`                   | Editor   |                                                                                                                         |
| Delete Line                   | `Delete Line`                          | `^⇧ K`                   | Editor   |                                                                                                                         |
| Join Lines                    | `Join Lines`                           | `⌘ J`                    |          |                                                                                                                         |
| Comment Line                  | `Add Line Comment`                     | `⇧⌘ 7`                   | Editor   |                                                                                                                         |
| Format Document               | `Format Document`                      | `^⌥ B`                   |          |                                                                                                                         |
| Toggle Dev Tools              | `Developer: Toggle Developer Tools`    | `⌥⌘ I`                   |          |                                                                                                                         |
| Reload Window                 | `Reload Window`                        | ` ^⌥⌘ L`                 |          |                                                                                                                         |
| ~~Show Snippets~~             |                                        | ~~⌥⇧ S~~                 |          | This command has been [renamed](https://github.com/Microsoft/vscode/issues/18314) and the package has not been updated. |
| ~~Switch to Open File~~       |                                        | `⌘ B`                    |          | This no longer appears to be a command and was likely renamed `Show All Editors`                                        |

| Setting                       | Type    | Default | Note                                  |
| ----------------------------- | ------- | ------- | ------------------------------------- |
| `atomKeymap.promptV3Features` | Boolean | `null`  | Controls whether the prompt will show |

## Language Specific

### Markdown

#### Markdown All In One

[Marketplace](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) | [Repo](https://github.com/neilsustc/vscode-markdown)

> All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)

| Description              | Command                                    | Keybinding | When              |
| ------------------------ | ------------------------------------------ | ---------- | ----------------- |
| Toggle Bold              |                                            | `⌘ B`      | Editor & Markdown |
| Toggle Italic            |                                            | `⌘ I`      | Editor & Markdown |
| Toggle Code Span         | `Markdown: Toggle code span`               |            |                   |
| Toggle Strikethrough     | `Markdown: Toggle strikethrough`           |            |                   |
| Toggle Heading Up        |                                            | `^⇧ ]`     | Editor & Markdown |
| Toggle Heading Down      |                                            | `^⇧ [`     | Editor & Markdown |
| Toggle Task Status       |                                            | `⌥ C`      | Editor & Markdown |
| Create Table of Contents | `Markdown: Create Table of Contents`       |            |                   |
| Update Table of Contents | `Markdown: Update Table of Contents`       |            |                   |
| Print to HTML            | `Markdown: Print current document to HTML` |            |                   |

| Setting                                              | Type    | Default    | Note                                                                                |
| ---------------------------------------------------- | ------- | ---------- | ----------------------------------------------------------------------------------- |
| `"markdown.extension.quickStyling"`                  | Boolean | `false`    | Toggle bold/italic without selecting words.                                         |
| `"markdown.extension.showExplorer"`                  | Boolean | `true`     | Show outline view in explorer panel.                                                |
| `"markdown.extension.italic.indicator"`              | Option  | `*`        | Use `*` or `_` to wrap italic text.                                                 |
| `"markdown.extension.orderedList.marker"`            | Option  | ` ordered` | `ordered` for sequential, `one`: always use `1.` as ordered list marker.            |
| `"markdown.extension.print.absoluteImgPath"`         | Boolean | `true`     | Convert image path to absolute path.                                                |
| `"markdown.extension.toc.levels"`                    | String  | `1..6`     | Control the heading levels to show in the table of contents.                        |
| `"markdown.extension.toc.orderedList"`               | Boolean | `false`    | Use ordered list in the table of contents.                                          |
| `"markdown.extension.toc.unorderedList.marker"`      | Option  | `-`        | Use `-`, `*` or `+` in the table of contents (for unordered list).                  |
| `"markdown.extension.toc.plaintext"`                 | Boolean | `false`    | Just plain text.                                                                    |
| `"markdown.extension.toc.encodeUri"`                 | Boolean | `true`     | You might want to set this to `false` if you have some non-Latin characters in TOC. |
| `"markdown.extension.toc.updateOnSave"`              | Boolean | `false`    | Automatically update the table of contents on save.                                 |
| `"markdown.extension.preview.autoShowPreviewToSide"` | Boolean | `false`    | Automatically show preview when opening a Markdown file.                            |

```json
	// Markdown All In One
	"markdown.extension.quickStyling": true,
	"markdown.extension.italic.indicator": "_",
	"markdown.extension.print.absoluteImgPath": false,
	"markdown.extension.toc.orderedList": true,
	"markdown.extension.toc.updateOnSave": true,
```

### Regex

#### RegExp Preview and Editor

[Marketplace](https://marketplace.visualstudio.com/items?itemName=le0zh.vscode-regexp-preivew) | [Repo](https://github.com/le0zh/vscode-regexp-preivew.git)

> VSCode extension based on regexper-static

| Description    | Command          | Note                                          |
| -------------- | ---------------- | --------------------------------------------- |
| RegExp Preview | `RegExp Preview` | Preview selected regular expression.          |
| RegExp Editor  | `RegExp Editor`  | Open a regular expression editor and preview. |

## Projects & Files

### Files

#### Advanced New File

[Marketplace](https://marketplace.visualstudio.com/items?itemName=dkundel.vscode-new-file) • [Repo](https://github.com/dkundel/vscode-new-file)

> An easier way of creating a new file inside a project.

| Description       | Command                    | Keybinding |
| ----------------- | -------------------------- | ---------- |
| Advanced New File | `Files: Advanced New File` | `⌘⌥ N`     |

| Setting                          | Type    | Default     | Note                                                                                         |
| -------------------------------- | ------- | ----------- | -------------------------------------------------------------------------------------------- |
| `"newFile.defaultBaseFileName"`  | String  | `"newFile"` | Set the default filename.                                                                    |
| `"newFile.relativeTo"`           | Option  | `"file"`    | Set's where the new file will be relative to. Values are `file`, `root` or `project`.        |
| `"newFile.defaultFileExtension"` | String  | `".ts"`     | Set the default file extension.                                                              |
| `"newFile.rootDirectory"`        | String  | `"~"`       | Set the path to the root directory.                                                          |
| `"newFile.showPathRelativeTo"`   | Option  | `"root"`    | Values are `root`, `project` or `none`.                                                      |
| `"newFile.expandBraces"`         | Boolean | `false`     | Setting to true will allow for creating multiple files such as `new-folder/{file1,file2}.js` |

```json
	// Advanced New File
	"newFile.defaultFileExtension": ".js",
	"newFile.rootDirectory": "~/Source",
	"newFile.expandBraces": true,
```

## Tracking

### WakaTime

[Marketplace](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime) | [Repo](https://github.com/wakatime/vscode-wakatime.git)  | [Home](https://wakatime.com/)

> Metrics, insights, and time tracking automatically generated from your programming activity.

| Description                     | Command                    | Note                                                               |
| ------------------------------- | -------------------------- | ------------------------------------------------------------------ |
| Open WakaTime Dashboard         | `WakaTime Dashboard`       | Opens in default browser                                           |
| Toggle WakaTime Status Bar Icon | `WakaTime Status Bar Icon` | Allows you to show or hide the small clock icon in the status bar. |
| WakaTime API Key                | `WakaTime API Key`         | Set or edit the API key                                            |
| WakaTime Proxy                  | `WakaTime Proxy`           | Set or edit a WakaTime proxy setting.                              |
| Toggle Debug for WakaTime       | `WakaTime Debug`           | Exposes WakaTime debug information to the developer tools console. |

## UI

### Status Bar

#### Active File in StatusBar

[Marketplace](https://www.alfredforum.com/topic/3447-alfred-maestro-keyboard-maestro-integration-for-alfred/?tab=comments#comment-20153) • [Repo](https://github.com/RoscoP/ActiveFileInStatusBar)

> Add statusbar entry to show path for currently active file.

| Setting                              | Type    | Default | Note                                               |
| ------------------------------------ | ------- | ------- | -------------------------------------------------- |
| `"ActiveFileInStatusBar.color"`      | String  | `""`    | Set text color for the filename in the status bar. |
| `"ActiveFileInStatusBar.enable"`     | Boolean | `true`  | Enable/Disable ActiveFileInStatusBar               |
| `"ActiveFileInStatusBar.fullpath"`   | Boolean | `true`  | Show full-path or relative path in status bar.     |
| `"ActiveFileInStatusBar.revealFile"` | Boolean | `false` | Reveal the active file in the file system.         |

### Theme

#### An Old Hope Theme

[Marketplace](https://marketplace.visualstudio.com/items?itemName=dustinsanders.an-old-hope-theme-vscode)

> vscode theme inspired by a galaxy far far away...

![palette](https://raw.githubusercontent.com/JesseLeite/an-old-hope-syntax-atom/master/palette.jpg)
