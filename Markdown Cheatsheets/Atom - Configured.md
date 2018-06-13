title: Atom Cheatsheet

# Atom

---

# Commands

## Actions

| Name           | Command                | Keybinding            |
| -------------- | ---------------------- | --------------------- |
| Confirm        | `Core: Confirm`        | `↵`                   |
| Cancel         | `Core: Cancel`         | `⎋`                   |
| Focus Next     | `Core: Focus Next`     | `⇥`                   |
| Focus Previous | `Core: Focus Previous` | `⇧ ⇥`                 |
| Delete         | `Core: Delete`         | `⌦` \| `⇧ ⌦` \| `^ D` |
| Backspace      | `Core: Backspace`      | `⌫` \| `⇧ ⌫` \| `^ H` |
| Close          | `Core: Close`          | `⌘ W`                 |
| Undo           | `Core: Undo`           | `⌘ Z`                 |
| Redo           | `Core: Redo`           | `⌘ Y` \| `⇧⌘ Z`       |
| Unfocus Panels | `Tool Panel: Unfocus`  | `⎋`                   |

### Application

| Name                   | Command                          | Keybinding | Note                                                       |
| ---------------------- | -------------------------------- | ---------- | ---------------------------------------------------------- |
| Quit                   | `Application: Quit`              | `⌘ Q`      |                                                            |
| Install Update         | `Application: Install Update`    |            |                                                            |
| Install Shell Commands | `Window: Install Shell Commands` |            | Install's Atom's APM shell commands for managing packages. |
| Open License           | `Application: Open License`      |            | Opens Atom's application license in a file.                |

### Autocomplete

| Name                              | Command                                                | Keybinding    |                                                                    |
| --------------------------------- | ------------------------------------------------------ | ------------- | ------------------------------------------------------------------ |
| Activate                          | `Autocomplete Plus: Activate`                          | `^ ␣ (Space)` |                                                                    |
| Cancel                            | `Autocomplete Plus: Cancel`                            | `⎋`           |                                                                    |
| Confirm                           | `Autocomplete Plus: Confirm`                           | `⇥` \| `↵`    |                                                                    |
| Confirm if Non-Default            | `Autocomplete Plus: confirmIfNonDefault`               | `⇥` \| `↵`    | This is used conditionally based on context, don't worry about it. |
| Navigate to Description More Link | `Autocomplete Plus: Navigate To Description More Link` | `F1`          |                                                                    |

### Bookmarks

| Name                         | Command                                  | Keybinding |
| ---------------------------- | ---------------------------------------- | ---------- |
| Toggle Bookmark              | `Bookmarks: Toggle Bookmark`             | `⌘ F2`     |
| Jump to Next Bookmark        | `Bookmarks: Jump To Next Bookmark`       | `F2`       |
| Jump to Previous Bookmark    | `Bookmarks: Jump To Previous Bookmark`   | `⇧ F2`     |
| Select to Next Bookmark      | `Bookmarks: Select To Next Bookmark`     |            |
| Select to Previous Bookmarks | `Bookmarks: Select To Previous Bookmark` |            |
| Clear Bookmarks              | `Bookmarks: Clear Bookmarks`             | `⇧⌘ F2`    |
| View All                     | `Bookmarks: View All`                    | `^ F2`     |

### Browser

| Name               | Command                     | Keybinding | Note                                                                            | Package   |
| ------------------ | --------------------------- | ---------- | ------------------------------------------------------------------------------- | --------- |
| Open Link          | `Link: Open`                | `^⇧ O`     | Opens http(s) links under cursor. [Package Info](https://github.com/atom/link). |           |
| Toggle             | `Atom Browser: ShowHide`    | `⌥⌘ V`     |                                                                                 | Community |
| Preview            | `Atom Browser: Preview`     |            | Opens file in browser, can also be opened from right click tree view menu.      | Community |
| Search             | `Atom Browser: Search`      | `^⌘ S`     |                                                                                 | Community |
| Reload             | `Atom Browser: Reload`      | `⌥⌘ R`     |                                                                                 | Community |
| Browser Dev Tools  | `Atom Browser: Devtools`    | `⌥⌘ X`     |                                                                                 | Community |
| View Release Notes | `About: View Release Notes` |            |                                                                                 |           |

### Build

#### Static Site

| Name                   | Command                                   | Keybinding | Package   |
| ---------------------- | ----------------------------------------- | ---------- | --------- |
| New Post               | `Markdown Writer: New Post`               |            | Community |
| New Draft              | `Markdown Writer: New Draft`              |            | Community |
| Manage Post Tags       | `Markdown Writer: Manage Post Tags`       |            | Community |
| Manage Post Categories | `Markdown Writer: Manage Post Categories` |            | Community |
| Publish Draft          | `Markdown Writer: Publish Draft`          |            | Community |

### Clipboard

| Name                       | Command                              | Keybinding | Note                                                                                  |
| -------------------------- | ------------------------------------ | ---------- | ------------------------------------------------------------------------------------- |
| Copy                       | `Core: Copy`                         | `⌘ C`      |                                                                                       |
| Cut                        | `Core: Cut`                          | `⌘ X`      |                                                                                       |
| Paste                      | `Core: Paste`                        | `⌘ V`      |                                                                                       |
| Copy Selection             | `Editor: Copy Selection`             |            | I'm not sure if this is any different from the core copy command.                     |
| Cut to End of Line         | `Editor: Cut To End Of Line`         | `^ K`      |                                                                                       |
| Cut to End of Buffer Line  | `Editor: Cut To End Of Buffer Line`  |            | If code is selected cut selection, otherwise, cut from cursor to the end of the line. |
| Paste Without Reformatting | `Editor: Paste Without Reformatting` | `⇧⌘ V`     |                                                                                       |

#### Paths

| Name              | Command                     | Keybinding | Note                                               |
| ----------------- | --------------------------- | ---------- | -------------------------------------------------- |
| Copy Path         | `Editor: Copy Path`         | `^⇧ C`     | Copy current file's absolute path.                 |
| Copy Project Path | `Editor: Copy Project Path` |            | Copy current file's path relative to project root. |

### Command Palette

| Name                   | Command                                 | Keybinding |
| ---------------------- | --------------------------------------- | ---------- |
| Toggle Command Palette | `Command Palette: Toggle`               | `⇧⌘ P`     |
| Show Hidden Commands   | `Command Palette: Show Hidden Commands` |            |

### Console

| Name           | Command           | Keybinding | Note                                               | Package   |
| -------------- | ----------------- | ---------- | -------------------------------------------------- | --------- |
| Clear Console  | `Console: Clear`  | `^ L`      | This command is for Atom IDE's console, not Atom's | Community |
| Toggle Console | `Console: Toggle` | `⌥⌘ J`     | This command is for Atom IDE's console, not Atom's | Community |

### Debug

#### Node

| Name              | Command                          | Keybinding | Package   |
| ----------------- | -------------------------------- | ---------- | --------- |
| Start Resume      | Node Debugger: Start Resume      | F5         | Community |
| Start Active File | Node Debugger: Start Active File | ^ F5       | Community |
| Stop              | Node Debugger: Stop              | ⇧ F5       | Community |
| Toggle Breakpoint | Node Debugger: Toggle Breakpoint | F9         | Community |
| Step Next         | Node Debugger: Step Next         | F10        | Community |
| Step In           | Node Debugger: Step In           | F11        | Community |
| Step Out          | Node Debugger: Step Out          | ⇧ F11      | Community |
| Attach            | Node Debugger: Attach            |            | Community |
| Toggle Debugger   | Node Debugger: Toggle Debugger   | F12        | Community |

#### Swift

| Name       | Command                      | Keybinding | Package   |
| ---------- | ---------------------------- | ---------- | --------- |
| Breakpoint | `Swift Debugger: Breakpoint` | `⌥⇧ R`     | Community |
| Toggle     | `Swift Debugger: Toggle`     | `⌥ R`      | Community |

### Developer

More information about [Hacking Atom](http://flight-manual.atom.io/hacking-atom/).

| Name                               | Command                                        | Keybinding | Note                                                                                                                                                                                               | Package   |
| ---------------------------------- | ---------------------------------------------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Reload Window                      | `Window: Reload`                               | `^⌥⌘ L`    | Completely reloads window. Some info in Atom Flight Manual in the [Creating a Syntax Theme](http://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#creating-a-syntax-theme) section. |           |
| Dev Live Reload                    | `Dev Live Reload: Reload All`                  | `^⇧⌘ R`    | Live reload atom themes and packages. [Package Info](https://atom.io/packages/dev-live-reload).                                                                                                    |           |
| Toggle Dev Tools                   | `Window: Toggle Dev Tools`                     | `⌥⌘ I`     | Toggle's Dev Tools like Chrome's. [Atom Flight Manual: Developer Tools](http://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#developer-tools).                                     |           |
| Log Cursor Scope                   | `Editor: Log Cursor Scope`                     | `⌥⌘ P`     | Easy way to display your cursor scope. [Atom Flight Manual: Scopes](http://flight-manual.atom.io/behind-atom/sections/scoped-settings-scopes-and-scope-descriptors/).                              |           |
| Styleguide                         | `Styleguide: Show`                             | `^⇧⌘ G`    | Exercises all UI components and acts as a styleguide. [Package Info](https://atom.io/packages/styleguide).                                                                                         |           |
| Generate Package                   | `Package Generator: Generate Package`          |            | Generates and opens a new sample package. [Package Info](https://atom.io/packages/package-generator).                                                                                              |           |
| Generate Language Package          | `Package Generator: Generate Language Package` |            | Generates and opens a new sample language. [Package Info](https://atom.io/packages/package-generator).                                                                                             |           |
| Generate Syntax Theme              | `Package Generator: Generate Syntax Theme`     |            | Generates and opens a new sample syntax theme. [Package Info](https://atom.io/packages/package-generator).                                                                                         |           |
| Generate Minimap Babel Plugin      | `Minimap: Generate Babel Plugin`               |            | For developing a minimap plugin.                                                                                                                                                                   | Community |
| Generate Minimap Coffee Plugin     | `Minimap: Generate Coffee Plugin`              |            | For developing a minimap plugin.                                                                                                                                                                   | Community |
| Generate Minimap Javascript Plugin | `Minimap: Generate Javascript Plugin`          |            | For developing a minimap plugin.                                                                                                                                                                   | Community |
| Update Package Dependencies        | `Update Package Dependencies: Update`          |            | Runs `apm install` for the current project. [Package Info](https://atom.io/packages/update-package-dependencies).                                                                                  |           |
| Run Package Specs                  | `Window: Run Package Specs`                    | `^⌥⌘ P`    | This will run all the specs in the current project's `spec` directory. [Atom Flight Manual: Writing Specs](http://flight-manual.atom.io/hacking-atom/sections/writing-specs/).                     |           |
| Log Deprecation Warnings           | `Window: Log Deprecation Warnings`             |            | Logs deprecation warnings to Atom's console.                                                                                                                                                       |           |
| Timecop                            | `Timecop: View`                                |            | Displays information about where time is spent while Atom loads. [Package Info](https://atom.io/packages/timecop).                                                                                 |           |
| Run Benchmarks                     | `Window: Run Benchmarks`                       |            | Opens Benchmarks window.                                                                                                                                                                           |           |
| Show Waterfall Diagnostics         | `GitHub: Show Waterfall Diagnostics`           |            | Opens the GitHub Package Timings view.                                                                                                                                                             |           |
| Incompatible Packages              | `Incompatible Packages: View`                  |            | Show incompatible packages. [Package Info](https://atom.io/packages/incompatible-packages).                                                                                                        |           |
| Clear Update State                 | `About: Clear Update State`                    |            | If I'm reading the [pull request](https://github.com/atom/about/pull/66) correctly it lets you tell Atom not to update to the current version, at least in dev mode.                               |           |

### Editor

#### Casing

| Name       | Command              | Keybinding    |
| ---------- | -------------------- | ------------- |
| Upper Case | `Editor: Upper Case` | `⌘ K` + `⌘ U` |
| Lower Case | `Editor: Lower Case` | `⌘ K` + `⌘ L` |

#### Color

| Name                                | Command                         | Note                                                             | Package   |
| ----------------------------------- | ------------------------------- | ---------------------------------------------------------------- | --------- |
| Show Palette                        | `Pigments: Show Palette`        | Shows a global color palette for project.                        | Community |
| Find Colors                         | `Pigments: Find Colors`         | Search for all of the colors in project.                         | Community |
| Convert Color To \*Format\*         | `Pigments: Convert To *Format*` | Converts color to Hex, HSL/HSLA and RGB/RGBA.                    | Community |
| Copy Color As \*Format\*            | `Pigments: Copy as *Format*`    | Copy color as Hex, HSL/HSLA and RGB/RGBA.                        | Community |
| Pigments Project Settings           | `Pigments: Project-Settings`    | Open project specific Pigments settings.                         | Community |
| Reload Pigments                     | `Pigments: Reload`              | Force reload all Pigments variables for the project.             | Community |
| Generate Information for Bug Report | `Pigments: Report`              | Generates a JSON array of information for a Pigments bug report. | Community |

#### Documentation

AtomDocr is a fork of Docblockr customized for AtomDoc style but it only works on JavaScript and CoffeeScript.

| Name               | Command                         | Keybinding      | Note                                                                                                                       | Package   |
| ------------------ | ------------------------------- | --------------- | -------------------------------------------------------------------------------------------------------------------------- | --------- |
| Comment Line       | `Editor: Toggle Line Comments`  | `⌘ /`           |                                                                                                                            | Community |
| Toggle Comment     | `Emmet: Toggle Comment`         | `⌘ /` \| `^⇧ /` | When there’s no selection, editor’s action toggles comment on current line while Emmet’s one do this on _current context_. | Community |
| Parse Tab          | `AtomDocr: Parse Tab`           | `⇥`             |                                                                                                                            | Community |
| Parse Lines        | `AtomDocr: Parse Lines`         | `⇧ ↵`           |                                                                                                                            | Community |
| Parse Enter        | `AtomDocr: Parse Enter`         | `↵`             |                                                                                                                            | Community |
| Reparse            | `AtomDocr: Reparse`             |                 |                                                                                                                            | Community |
| Join               | `AtomDocr: Join`                |                 |                                                                                                                            | Community |
| Wrap Lines         | `AtomDocr: Wrap Lines`          |                 |                                                                                                                            | Community |
| Decorate           | `AtomDocr: Decorate`            |                 | Wraps line in symbols for emphasis.                                                                                        | Community |
| Decorate Multiline | `AtomDocr: Decorate Multiline`  |                 | Wraps multiple lines in symbols for emphasis.                                                                              | Community |
| Parse Tab          | `Docblockr: Parse Tab`          | `⌥ ⇥`           |                                                                                                                            | Community |
| Parse Lines        | `Docblockr: Parse Lines`        | `⌥⇧ ↵`          |                                                                                                                            | Community |
| Parse Enter        | `Docblockr: Parse Enter`        | `⌥ ↵`           |                                                                                                                            | Community |
| Reparse            | `Docblockr: Reparse`            |                 |                                                                                                                            | Community |
| Join               | `Docblockr: Join`               |                 |                                                                                                                            | Community |
| Wrap Lines         | `Docblockr: Wrap Lines`         |                 |                                                                                                                            | Community |
| Decorate           | `Docblockr: Decorate`           |                 | Wraps line in symbols for emphasis.                                                                                        | Community |
| Decorate Multiline | `Docblockr: Decorate Multiline` |                 | Wraps multiple lines in symbols for emphasis.                                                                              | Community |

#### Deletion

##### Delete by Subword

| Name                           | Command                                  | Keybinding       |
| ------------------------------ | ---------------------------------------- | ---------------- |
| Delete to Beginning of Subword | `Editor: Delete To Beginning Of Subword` | `^⌥ ⌫` \| `^⌥ H` |
| Delete to End of Subword       | `Editor: Delete To End Of Subword`       | `^⌥ ⌦` \| `^⌥ D` |

##### Delete by Word

| Name                             | Command                                    | Keybinding     |
| -------------------------------- | ------------------------------------------ | -------------- |
| Delete to Beginning of Word      | `Editor: Delete To Beginning Of Word`      | `⌥ ⌫` \| `⌥ H` |
| Delete to End of Word            | `Editor: Delete To End Of Word`            | `⌥ ⌦` \| `⌥ D` |
| Delete to Next Word Boundary     | `Editor: Delete To Next Word Boundary`     |                |
| Delete to Previous Word Boundary | `Editor: Delete To Previous Word Boundary` |                |

##### Delete by Line

| Name                        | Command                               | Keybinding      |
| --------------------------- | ------------------------------------- | --------------- |
| Delete Line                 | `Editor: Delete Line`                 | `^⇧ K`          |
| Delete to Beginning of Line | `Editor: Delete To Beginning Of Line` | `⌘ ⌫` \| `⇧⌘ ⌫` |
| Delete to End of Line       | `Editor: Delete To End Of Line`       | `⌘ ⌦`           |

#### Folding

| Name                         | Command                               | Keybinding               |
| ---------------------------- | ------------------------------------- | ------------------------ |
| Fold Current Row             | `Editor: Fold Current Row`            | `⌥⌘ [`                   |
| Unfold Current Row           | `Editor: Unfold Current Row`          | `⌥⌘ ]`                   |
| Fold Selection               | `Editor: Fold Selection`              | `^⌥⌘ F`                  |
| Fold All                     | `Editor: Fold All`                    | `⌥⇧⌘ {`                  |
| Unfold All                   | `Editor: Unfold All`                  | `⌥⇧⌘ }` \| `⌘ K` + `⌘ 0` |
| Fold at Indent Level # (1-9) | `Editor: Fold At Indent Level #(1-9)` | `⌘ K` + `⌘ #(1-9)`       |

#### Formatting

| Name                           | Command                                       | Keybinding | Note                                                                                                                            | Package   |
| ------------------------------ | --------------------------------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Autoflow                       | `Autoflow: Reflow Selection`                  | `⌥⌘ Q`     | Hard wraps at no more than preferred line length (80 characters by default). [Package Info](https://atom.io/packages/autoflow). |           |
| Fix File                       | `EditorConfig: Fix File`                      |            | Fixes `indent_style` and `end_of_line` issues for the current editor.                                                           | Community |
| Show State                     | `EditorConfig: Show State`                    |            | Shows the current state of EditorConfig for your current editor.                                                                | Community |
| Generate Config                | `EditorConfig: Generate Config`               |            | Generates an initial `.editorconfig` for your project.                                                                          | Community |
| Format Code                    | `Code Format: Format Code`                    | `⇧⌘ C`     |                                                                                                                                 | Community |
| Beautify Editor                | `Atom Beautify: Beautify Editor`              | `^⌥ B`     | Based on grammar.                                                                                                               | Community |
| Beautify Language \*Language\* | `Atom Beautify: Beautify Language *Language*` |            |                                                                                                                                 | Community |
| Open Settings                  | `Atom Beautify: Open Settings`                |            |                                                                                                                                 | Community |
| Migrate Settings               | `Atom Beautify: Migrate Settings`             |            |                                                                                                                                 | Community |
| Help Debug Editor              | `Atom Beautify: Help Debug Editor`            |            |                                                                                                                                 | Community |
| Format with Prettier           | `Prettier: Format`                            | `^⌥ F`     |                                                                                                                                 | Community |

#### Images

| Name                            | Command                         | Keybinding      | Note                                                                                                                                       | Package   |
| ------------------------------- | ------------------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | --------- |
| Encode/Decode Image to data:URL | `Emmet: Encode Decode Data URL` | `^⇧ I` \| `^ '` | HTML and CSS allows you to embed external resources right into base using [data:URL](http://en.wikipedia.org/wiki/Data_URI_scheme) scheme. | Community |

#### Indentation

| Name                  | Command                         | Keybinding     | Note                                            |
| --------------------- | ------------------------------- | -------------- | ----------------------------------------------- |
| Indent                | `Editor: Indent`                | `⇥`            | Keybinding activates only at beginning of line. |
| Indent Selected Rows  | `Editor: Indent Selected Rows`  | `⌘ ]`          |                                                 |
| Outdent Selected Rows | `Editor: Outdent Selected Rows` | `⌘ [` \| `⇧ ⇥` |                                                 |

#### Information

| Name                      | Command                      | Keybinding  | Package   |
| ------------------------- | ---------------------------- | ----------- | --------- |
| Toggle Datatip            | `Datatip: Toggle`            | `⌥` \| `⌘⌥` | Community |
| Copy Datatip to Clipboard | `Datatip: Copy To Clipboard` | `^⌥ C`      | Community |
| View Signature Help       | `Signature Help: View`       |             | Community |

#### Manipulation

##### File Manipulation

| Name         | Command                        | Keybinding | Note                                        | Package   |
| ------------ | ------------------------------ | ---------- | ------------------------------------------- | --------- |
| Tabify       | `Tabs to Spaces: Tabify`       |            | Converts leading whitespace to tabs         | Community |
| Untabify     | `Tabs to Spaces: Untabify`     |            | Converts leading whitespace to spaces       | Community |
| Untabify All | `Tabs to Spaces: Untabify All` |            | Converts all whitespace on a line to spaces | Community |

##### Line Manipulation

| Name                             | Command                                   | Keybinding            | Note                                                                                                                       | Package   |
| -------------------------------- | ----------------------------------------- | --------------------- | -------------------------------------------------------------------------------------------------------------------------- | --------- |
| Newline                          | `Editor: Newline`                         | `↵` \| `⇧ ↵` \| `⌥ ↵` |                                                                                                                            |           |
| Newline Above                    | `Editor: Newline Above`                   | `⌘ ↵`                 |                                                                                                                            |           |
| Newline Below                    | `Editor: Newline Below`                   | `⇧⌘ ↵`                |                                                                                                                            |           |
| Insert Formatted Line Break      | `Emmet: Insert Formatted Line Break`      |                       |                                                                                                                            | Community |
| Insert Formatted Line Break Only | `Emmet: Insert Formatted Line Break Only` | `↵`                   |                                                                                                                            | Community |
| Duplicate Lines                  | `Editor: Duplicate Lines`                 | `⇧⌘ D`                |                                                                                                                            |           |
| Duplicate                        | `Duplicate Line or Selection: Duplicate`  | `^⇧ D` \| `⇧⌘ D`      | Sublime style duplication.                                                                                                 | Community |
| Join Lines                       | `Editor: Join Lines`                      | `⌘ J`                 |                                                                                                                            |           |
| Merge Lines                      | `Emmet: Merge Lines`                      | `⇧⌘ M` \| `^⇧ M`      | Merges selected lines into a single one. But when there’s no selection, Emmet will match context HTML tag.                 | Community |
| Split                            | `Editor: Split Selections Into Lines`     | `⇧⌘ L`                |                                                                                                                            |           |
| Comment Line                     | `Editor: Toggle Line Comments`            | `⌘ /`                 |                                                                                                                            |           |
| Toggle Comment                   | `Emmet: Toggle Comment`                   | `⌘ /` \| `^⇧ /`       | When there’s no selection, editor’s action toggles comment on current line while Emmet’s one do this on _current context_. | Community |

##### Tag Manipulation

| Name              | Command                    | Keybinding          | Note                                                                                                                                              | Package   |
| ----------------- | -------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Remove Tag        | `Emmet: Remove Tag`        | `⌘ '` \| `^⇧ ;`     | Quickly removes tag, found by “[Balance](https://docs.emmet.io/actions/match-pair/)” action from current caret position, and adjusts indentation. | Community |
| Update Tag        | `Emmet: Update Tag`        | `^⇧ U` \| `^⇧ '`    | Rename a tag at both opening and closing tags.                                                                                                    | Community |
| Split/Join Tag    | `Emmet: Split Join Tag`    | `⇧⌘ J` \| ``^⇧ ` `` | Splits and joins tag definition, e.g. converts from `<tag/>` to `<tag></tag>`.                                                                    | Community |
| Update Image Size | `Emmet: Update Image Size` | `^ I` \| `^ U`      | Simply place caret inside `<img>` tag and run this action to add/update width and height attributes.                                              | Community |
| Reflect CSS Value | `Emmet: Reflect Css Value` | `⇧⌘ R` \| `^⇧ R`    | Takes value of CSS property under caret and copies it into vendor-prefixed variations                                                             | Community |

##### Number Manipulation

| Name                     | Command                            | Keybinding  | Note   | Package                                                                       |           |
| ------------------------ | ---------------------------------- | ----------- | ------ | ----------------------------------------------------------------------------- | --------- |
| Evaluate Math Expression | `Emmet: Evaluate Math Expressions` | `⇧⌘ Y` \\   | `^⇧ Y` | Evaluates simple math expression like `2*4` or `10/2` and outputs its result. | Community |
| Increment Number by 0.1  | `Emmet: Increment Number By 01`    | `^⌥ ↑` \\   | `⌥ ↑`  | Increments number under caret by 0.1.                                         | Community |
| Decrement Number by 0.1  | `Emmet: Decrement Number By 01`    | `^⌥ ↓` \\   | `⌥ ↓`  | Decrements number under caret by 0.1.                                         | Community |
| Increment Number by 1    | `Emmet: Increment Number By 1`     | `^⌥⌘ ↑` \\  | `^ ↑`  | Increments number under caret by 1.                                           | Community |
| Decrement Number by 1    | `Emmet: Decrement Number By 1`     | `^⌥⌘ ↓` \\  | `^ ↓`  | Decrements number under caret by 1.                                           | Community |
| Increment Number by 10   | `Emmet: Increment Number By 10`    | `^⌥⇧⌘ ↑` \\ | `⌥⇧ ↑` | Increments number under caret 10.                                             | Community |
| Decrement Number by 10   | `Emmet: Decrement Number By 10`    | `^⌥⇧⌘ ↓` \\ | `⌥⇧ ↓` | Decrements number under caret by 10.                                          | Community |

##### Character Manipulation

| Name   | Command                 | Keybinding | Note                                             | Package   |
| ------ | ----------------------- | ---------- | ------------------------------------------------ | --------- |
| Toggle | `Toggle Quotes: Toggle` | `⌘⇧ '`     | Quickly toggle between single and double quotes. | Community |

#### Move Text

##### Move by Context

| Name      | Command                     | Keybinding      | Note                                          | Packages  |
| --------- | --------------------------- | --------------- | --------------------------------------------- | --------- |
| Transpose | `Atom Transpose: Transpose` | `⌥ T` \| `^⇧ T` | A more fully featured Sublime-like transpose. | Community |

##### Move by Character

| Name                 | Command                        | Keybinding | Note                                                                                   |
| -------------------- | ------------------------------ | ---------- | -------------------------------------------------------------------------------------- |
| Move Selection Left  | `Editor: Move Selection Left`  | `^⌘ ←`     |                                                                                        |
| Move Selection Right | `Editor: Move Selection Right` | `^⌘ →`     |                                                                                        |
| Transpose            | `Editor: Transpose`            | `^ T`      | Switches character on left of cursor with that on right or reverses text if selection. |

##### Move by Line

| Name           | Command                  | Keybinding |
| -------------- | ------------------------ | ---------- |
| Move Line Up   | `Editor: Move Line Up`   | `^⌘ ↑`     |
| Move Line Down | `Editor: Move Line Down` | `^⌘ ↓`     |

#### Navigation

| Name             | Command                    | Keybinding            |
| ---------------- | -------------------------- | --------------------- |
| Move Up          | `Core: Move Up`            | `↑` \| `^ ↑` \| `^ P` |
| Move Right       | `Core: Move Right`         | `→` \| `^ F`          |
| Move Down        | `Core: Move Down`          | `↓` \| `^ ↓` \| `^ N` |
| Move Left        | `Core: Move Left`          | `←` \| `^ B`          |
| Scroll to Cursor | `Editor: Scroll To Cursor` | `⇧⌘ <`                |

##### Code Peek

| Name           | Command                        | Keybinding | Package   |
| -------------- | ------------------------------ | ---------- | --------- |
| Peek Function  | `Code Peek: PeekFunction`      | `⌥⌘ E`     | Community |
| Hide Code Peek | `Code Peek: ToggleCodePeekOff` | `⇧ ⎋`      | Community |

##### Move by History

| Name                                  | Command                              | Keybinding | Note                                                   | Package   |
| ------------------------------------- | ------------------------------------ | ---------- | ------------------------------------------------------ | --------- |
| Next Cursor History                   | `Cursor History: Next`               | `^⌥ R`     | Go to next point in history.                           | Community |
| Previous Cursor History               | `Cursor History: Prev`               | `^ =`      | Go to previous point in history.                       | Community |
| Next Cursor History Within Editor     | `Cursor History: Next Within Editor` | `^⌘ -`     | Go to next point in history within current editor.     | Community |
| Previous Cursor History Within Editor | `Cursor History: Prev Within Editor` | `^⌘ =`     | Go to previous point in history within current editor. | Community |
| Clear Cursor History                  | `Cursor History: Clear`              |            |                                                        | Community |

##### Move by Context

| Name                    | Command                                    | Keybinding      | Note                                                                    | Package   |
| ----------------------- | ------------------------------------------ | --------------- | ----------------------------------------------------------------------- | --------- |
| Go to Matching Bracket  | `Bracket Matcher: Go To Matching Bracket`  | `^ M`           | Goes to the nearest enclosing bracket when there's no adjacent bracket. |           |
| Go to Enclosing Bracket | `Bracket Matcher: Go To Enclosing Bracket` |                 |                                                                         |           |
| Go to Matching Pair     | `Emmet: Matching Pair`                     | `^⌥ J`          | Traverse between opening and closing tag:                               | Community |
| Next Edit Point         | `Emmet: Next Edit Point`                   | `^ →` \| `^⌥ →` | Moves cursor to edit points in code by context.                         | Community |
| Previous Edit Point     | `Emmet: Prev Edit Point`                   | `^ ←` \| `^⌥ ←` | Moves cursor to edit points in code by context.                         | Community |

##### Move by Subword

| Name                              | Command                                     | Keybinding       |
| --------------------------------- | ------------------------------------------- | ---------------- |
| Move to Previous Subword Boundary | `Editor: Move To Previous Subword Boundary` | `^⌥ ←` \| `^⌥ B` |
| Move to Next Subword Boundary     | `Editor: Move To Next Subword Boundary`     | `^⌥ →` \| `^⌥ F` |

##### Move by Word

| Name                           | Command                                  | Keybinding     |
| ------------------------------ | ---------------------------------------- | -------------- |
| Move to Beginning of Word      | `Editor: Move To Beginning Of Word`      | `⌥ ←` \| `⌥ B` |
| Move to End of Word            | `Editor: Move To End Of Word`            | `⌥ →` \| `⌥ F` |
| Move to Previous Word Boundary | `Editor: Move To Previous Word Boundary` |                |
| Move to Next Word Boundary     | `Editor: Move To Next Word Boundary`     |                |
| Move to Beginning of Next Word | `Editor: Move To Beginning Of Next Word` |                |

##### Move by Line

| Name                             | Command                                    | Keybinding                   | Note              |
| -------------------------------- | ------------------------------------------ | ---------------------------- | ----------------- |
| Move to First Character of Line  | `Editor: Move To First Character Of Line`  | `⌘ ←` \| `^ A` \| `↖` (Home) | After whitespace. |
| Move to Beginning of Line        | `Editor: Move To Beginning Of Line`        |                              |                   |
| Move to End of Line              | `Editor: Move To End Of Line`              | `^ E`                        |                   |
| Move to Beginning of Screen Line | `Editor: Move To Beginning Of Screen Line` |                              |                   |
| Move to End of Screen Line       | `Editor: Move To End Of Screen Line`       | `⌘ →` \| `↘` (End)           |                   |

##### Move by Paragraph or Block

| Name                                    | Command                                           | Keybinding | Note                               | Package   |
| --------------------------------------- | ------------------------------------------------- | ---------- | ---------------------------------- | --------- |
| Move to Beginning of Previous Paragraph | `Editor: Move To Beginning Of Previous Paragraph` |            |                                    |           |
| Move to Beginning of Next Paragraph     | `Editor: Move To Beginning Of Next Paragraph`     |            |                                    |           |
| Move Up by Block                        | `Block Travel: Move Up`                           | `⌥ ↑`      | Travel up through blocks of code   | Community |
| Move Down by Block                      | `Block Travel: Move Down`                         | `⌥ ↓`      | Travel down through blocks of code | Community |

##### Move by Screen

| Name         | Command           | Keybinding                     | Note                                      | Package   |
| ------------ | ----------------- | ------------------------------ | ----------------------------------------- | --------- |
| Page Down    | `Core: Page Up`   | `⇞` (Pageup)                   |                                           |           |
| Page Up      | `Core: Page Down` | `⇟` (Pagedown)                 |                                           |           |
| Toggle Jumpy | `Jumpy: Toggle`   | `⇧ ↩`                          | Toggle dynamic hotkeys to navigate panes. | Community |
| Reset Jumpy  | `Jumpy: Reset`    | `⌫`                            |                                           | Community |
| Clear Jumpy  | `Jumpy: Clear`    | `↩`, `⎋`, `⇧ ↩` \| `␣` (Space) |                                           | Community |

##### Move by File

| Name           | Command                | Keybinding |
| -------------- | ---------------------- | ---------- |
| Move to Top    | `Core: Move To Bottom` | `⌘ ↑`      |
| Move to Bottom | `Core: Move To Bottom` | `⌘ ↓`      |

##### Go To Line

| Name       | Command              | Keybinding | Note               |
| ---------- | -------------------- | ---------- | ------------------ |
| Go To Line | `Go To Line: Toggle` | `^ G`      |                    |
| Cancel     | `Core: Cancel`       | `⌘ W`      | Contextual hotkey. |

#### Selection

| Name                   | Command                          | Keybinding         | Note                                                              | Package   |
| ---------------------- | -------------------------------- | ------------------ | ----------------------------------------------------------------- | --------- |
| Consolidate Selections | `Editor: Consolidate Selections` | `⎋`                | Reduce multiple selections to the least recently added selection. |           |
| Column Select          |                                  | `⌥` + `Left Click` | Sublime style 'Column Selection.'                                 | Community |

##### Select by Context

Syntax Node commands only work with limited grammars for now, more information [here](http://blog.atom.io/2018/02/13/atom-1-24.html).

| Name                           | Command                                           | Keybinding       | Note                                                                                                                          | Package   |
| ------------------------------ | ------------------------------------------------- | ---------------- | ----------------------------------------------------------------------------------------------------------------------------- | --------- |
| Select Inside Brackets         | `Bracket Matcher: Select Inside Brackets`         | `^⌘ M`           |                                                                                                                               |           |
| Select Matching Brackets       | `Bracket Matcher: Select Matching Brackets`       | `^ M`            |                                                                                                                               |           |
| Remove Brackets from Selection | `Bracket Matcher: Remove Brackets From Selection` | `^ ]`            |                                                                                                                               |           |
| Balance Outward                | `Emmet: Balance Outward`                          | `^ D` \| `^⇧ E`  | Select outward by context.                                                                                                    | Community |
| Balance Inward                 | `Emmet: Balance Inward`                           | `⌥ D` \| `^⇧ 0`  | Select inward by context.                                                                                                     | Community |
| Select Next Item               | `Emmet: Select Next Item`                         | `^⇧ →` \| `^⇧ .` | Action is similar to [“Go to Edit Point”](https://docs.emmet.io/actions/go-to-edit-point/), but selects important code parts. | Community |
| Select Previous Item           | `Emmet: Select Previous Item`                     | `^⇧ ←` \| `^⇧ ,` | Action is similar to [“Go to Edit Point”](https://docs.emmet.io/actions/go-to-edit-point/), but selects important code parts. | Community |
| Select Larger Syntax Node      | `Editor: Select Larger Syntax Node`               | `⌥ ↑`            |                                                                                                                               |           |
| Select Smaller Syntax Node     | `Editor: Select Smaller Syntax Node`              | `⌥ ↓`            |                                                                                                                               |           |

##### Select by Character

| Name         | Command              | Keybinding      |
| ------------ | -------------------- | --------------- |
| Select Left  | `Core: Select Left`  | `⇧ ←` \| `^⇧ B` |
| Select Right | `Core: Select Right` | `⇧ →` \| `^⇧ F` |

##### Select by Subword

| Name                                | Command                                       | Keybinding         |
| ----------------------------------- | --------------------------------------------- | ------------------ |
| Select to Next Subword Boundary     | `Editor: Select To Next Subword Boundary`     | `^⌥⇧ →` \| `^⌥⇧ F` |
| Select to Previous Subword Boundary | `Editor: Select To Previous Subword Boundary` | `^⌥⇧ ←` \| `^⌥⇧ B` |

##### Select by Word

| Name                             | Command                                    | Keybinding       |
| -------------------------------- | ------------------------------------------ | ---------------- |
| Select Word                      | `Editor: Select Word`                      | `^⇧ W`           |
| Select to Beginning of Word      | `Editor: Select To Beginning Of Word`      | `⌥⇧ ←` \| `⌥⇧ B` |
| Select to End of Word            | `Editor: Select To End Of Word`            | `⌥⇧ →` \| `⌥⇧ B` |
| Select to Previous Word Boundary | `Editor: Select To Previous Word Boundary` |                  |
| Select to Next Word Boundary     | `Editor: Select To Next Word Boundary`     |                  |
| Select to Beginning of Next Word | `Editor: Select To Beginning Of Next Word` |                  |

##### Select by Line

| Name                              | Command                                     | Keybinding                       | Note                                                   |
| --------------------------------- | ------------------------------------------- | -------------------------------- | ------------------------------------------------------ |
| Select Line                       | `Editor: Select Line`                       | `⌘ L`                            |                                                        |
| Select to First Character of Line | `Editor: Select To First Character Of Line` | `⇧⌘ ←` \| `^⇧ A` \| `⇧ ↖` (Home) | After whitespace.                                      |
| Select to Beginning of Line       | `Editor: Select To Beginning Of Line`       |                                  | Before whitespace.                                     |
| Select to End of Line             | `Editor: Select To End Of Line`             | `⇧⌘ →` \| `^⇧ E` \| `⇧ ↘` (End)  |                                                        |
| Select Up                         | `Core: Select Up`                           | `⇧ ↑` \| `^⇧ P`                  |                                                        |
| Select Down                       | `Core: Select Down`                         | `⇧ ↓` \| `^⇧ N`                  |                                                        |
| Add Selection Above               | `Editor: Add Selection Above`               | `^⇧ ↑`                           | Expands the current selection up one line by column.   |
| Add Selection Below               | `Editor: Add Selection Below`               | `^⇧ ↓`                           | Expands the current selection down one line by column. |

##### Select by Paragraph or Block

| Name                                      | Command                                             | Keybinding | Note                                          | Package   |
| ----------------------------------------- | --------------------------------------------------- | ---------- | --------------------------------------------- | --------- |
| Select to Beginning of Previous Paragraph | `Editor: Select To Beginning Of Previous Paragraph` |            |                                               |           |
| Select to Beginning of Next Paragraph     | `Editor: Select To Beginning Of Next Paragraph`     |            |                                               |           |
| Select Up by Block                        | `Block Travel: Select Up`                           | `⇧⌥ ↑`     | Travel and select up through blocks of code   | Community |
| Select Down by Block                      | `Block Travel: Select Down`                         | `⇧⌥ ↓`     | Travel and select down through blocks of code | Community |

##### Select by Screen

| Name             | Command                  | Keybinding       |
| ---------------- | ------------------------ | ---------------- |
| Select Page Up   | `Core: Select Page Up`   | `⇧ ⇞` (Pageup)   |
| Select Page Down | `Core: Select Page Down` | `⇧ ⇟` (Pagedown) |

##### Select By File

| Name             | Command                  | Keybinding |
| ---------------- | ------------------------ | ---------- |
| Select All       | `Core: Select All`       | `⌘ A`      |
| Select to Top    | `Core: Select To Bottom` | `⇧⌘ ↑`     |
| Select to Bottom | `Core: Select To Bottom` | `⇧⌘ ↓`     |

#### Whitespace

Note that these commands may not be available if you've installed the excellent [EditorConfig](https://atom.io/packages/editorconfig) package and disabled the conflicting built-in [whitespace](https://atom.io/packages/whitespace) package.

| Name                             | Command                                        |
| -------------------------------- | ---------------------------------------------- |
| Convert Tabs to Spaces           | `Whitespace: Convert Tabs To Spaces`           |
| Convert Spaces to Tabs           | `Whitespace: Convert Spaces To Tabs`           |
| Convert All Tabs to Spaces       | `Whitespace: Convert All Tabs To Spaces`       |
| Remove Trailing Whitespace       | `Whitespace: Remove Trailing Whitespace`       |
| Save with Trailing Whitespace    | `Whitespace: Save With Trailing Whitespace`    |
| Save without Trailing Whitespace | `Whitespace: Save without Trailing Whitespace` |

#### XML & HTML

| Name                     | Command                                     | Note   |
| ------------------------ | ------------------------------------------- | ------ |
| Close Tag                | `Bracket Matcher: Close Tag`                | `⌥⌘ .` |
| Remove Matching Brackets | `Bracket Matcher: Remove Matching Brackets` | `^ ⌫`  |

### Evaluation

| Name     | Command              | Keybinding | Note                 | Package   |
| -------- | -------------------- | ---------- | -------------------- | --------- |
| Run Code | `Evaluate: Run Code` | `⌥⌘ R`     | Also in context menu | Community |
| Eval JavaScript | `Eval JavaScript: Eval JavaScript` | `⌘ I`      | | Community |

###Environment & Shell

| Name                              | Command                    | Package   |
| --------------------------------- | -------------------------- | --------- |
| Load Shell Environment Variables  | `Project Shell Env: Load`  | Community |
| Reset Shell Environment Variables | `Project Shell Env: Reset` | Community |

### Files

#### New

| Name                      | Command                      | Keybinding      | Note                                                     | Package   |
| ------------------------- | ---------------------------- | --------------- | -------------------------------------------------------- | --------- |
| New File                  | `Application: New File`      | `⌘ N` \| `⌘ T`  |                                                          |           |
| Toggle New File Plus      | `New File Plus: Toggle`      | `⌘ N` \| `⌘⌥ N` | Create multiple files at once using `{brace}` expansion! | Community |
| Toggle Advanced Open File | `Advanced Open File: Toggle` | `⌥⌘ O`          | Opens interface for opening and creating files.          | Community |

#### Open

| Name                              | Command                            | Keybinding                     | Note                                              | Package   |
| --------------------------------- | ---------------------------------- | ------------------------------ | ------------------------------------------------- | --------- |
| Open                              | `Application: Open`                | `⌘ O`                          |                                                   |           |
| Open File                         | `Application: Open File`           |                                |                                                   |           |
| Open Folder                       | `Application: Open Folder`         |                                |                                                   |           |
| Open Recent \*File or Directory\* | `Open Recent: *File or Directory*` | Open recent files and folders. |                                                   | Community |
| Toggle Advanced Open File         | `Advanced Open File: Toggle`       | `⌥⌘ O`                         | Opens interface for opening and creating files.   | Community |
| Open Safe                         | `Application: Open Safe`           |                                | Appears to open a folder or project in safe mode. |           |
| Open Dev                          | `Application: Open Dev`            |                                | Appears to open a folder or project in dev mode.  |           |

#### Save

| Name       | Command            | Keybinding | Note                                                 |
| ---------- | ------------------ | ---------- | ---------------------------------------------------- |
| Save       | `Core: Save`       | `⌘ S`      |                                                      |
| Save As    | `Core: Save As`    | `⇧⌘ S`     |                                                      |
| Save All   | `Window: Save All` | `⌥⌘ S`     |                                                      |
| Save Items | `Pane: Save Items` |            | This saves items in a pane, not a file specifically. |

#### Close

##### Panes

Note that these commands close panes, not files. Depending on your focus they may not close the file you're working on but not currently in focus.

| Name               | Command                    | Keybinding     |
| ------------------ | -------------------------- | -------------- |
| Close              | `Pane: Close`              | `⌘ K` + `⌘ W`  |
| Close Other Items  | `Pane: Close Other Items`  | `⌘ K` + `⌥⌘ W` |
| Reopen Closed Item | `Pane: Reopen Closed Item` | `⇧⌘ T`         |

##### Tabs

| Name                | Command                       | Package   |
| ------------------- | ----------------------------- | --------- |
| Close Tab           | `Tabs: Close Tab`             |           |
| Close Tabs to Left  | `Tabs: Close Tabs To Left`    |           |
| Close Tabs to Right | `Tabs: Close Tabs To Right`   |           |
| Close Saved Tabs    | `Tabs: Close Saved Tabs`      |           |
| Close Other Tabs    | `Tabs: Close All Tabs`        |           |
| Close All Tabs      | `Tabs: Close All Tabs`        |           |
| Close Unpinned Tabs | `Pinned Tabs: Close Unpinned` | Community |

##### Window

| Name         | Command         | Keybinding |
| ------------ | --------------- | ---------- |
| Close Window | `Window: Close` | `⇧⌘ W`     |

#### File Bookmarks

| Name                                | Command                                  | Keybinding | Package   |
| ----------------------------------- | ---------------------------------------- | ---------- | --------- |
| Add File Bookmark                   | `File Bookmark: Add`                     |            | Community |
| Remove File Bookmark                | `File Bookmark: Remove`                  |            | Community |
| Toggle File Bookmark                | `File Bookmark: Toggle Bookmark`         | `⌘ ;`      | Community |
| Toggle File Bookmark Panel          | `File Bookmark: Toggle Panel`            | `^⌘ :`     | Community |
| Toggle File Bookmark Shortcut Icons | `File Bookmark: Toggle Shortcut Icons`   |            | Community |
| Load Git Modified Files             | `File Bookmark: Load Git Modified Files` |            | Community |

#### File Properties

| Name                          | Command                                 | Keybinding | Note                                                     | Package   |
| ----------------------------- | --------------------------------------- | ---------- | -------------------------------------------------------- | --------- |
| Grammar Selector              | `Grammar Selector: Show`                | `^⇧ L`     | Select language or syntax for file.                      |           |
| Set Syntax to \*Syntax Name\* | `Set Syntax: *Syntax Name*`             |            |                                                          | Community |
| Select Encoding               | `Encoding Selector: Show`               | `^⇧ U`     |                                                          |           |
| Line Ending Selector          | `Line Ending Selector: Show`            |            |                                                          |           |
| Convert To CRLF               | `Line Ending Selector: Convert To CRLF` |            |                                                          |           |
| Convert To LF                 | `Line Ending Selector: Convert To LF`   |            |                                                          |           |
| Toggle Soft Tabs              | `Editor: Toggle Soft Tabs`              |            | This does not modify the file, just future tab behavior. |           |
| Show Tab Control              | `Tab Control: Show`                     |            |                                                          | Community |

#### Fuzzy Finder

| Name                     | Command                                  | Keybinding     | Note                                 |
| ------------------------ | ---------------------------------------- | -------------- | ------------------------------------ |
| Invert Confirm           | `Fuzzy Finder: Invert Confirm`           | `⇧ ↵`          |                                      |
| Toggle Buffer Finder     | `Fuzzy Finder: Toggle Buffer Finder`     | `⌘ B`          | Select Open File.                    |
| Toggle File Finder       | `Fuzzy Finder: Toggle File Finder`       | `⌘ P` \| `⌘ T` | Select Project File.                 |
| Toggle Git Status Finder | `Fuzzy Finder: Toggle Git Status Finder` | `⇧⌘ B`         | Select Modified and Untracked Files. |

#### Tree View

| Name                                | Command                                         | Keybinding                   | Note                                                              | Package   |
| ----------------------------------- | ----------------------------------------------- | ---------------------------- | ----------------------------------------------------------------- | --------- |
| Copy                                | `Tree View: Copy`                               | `⌘ C`                        |                                                                   |           |
| Cut                                 | `Tree View: Cut`                                | `⌘ X`                        |                                                                   |           |
| Paste                               | `Tree View: Paste`                              | `⌘ V`                        |                                                                   |           |
| Duplicate                           | `Tree View: Duplicate`                          | `D`                          |                                                                   |           |
| Rename                              | `Tree View: Rename`                             |                              |                                                                   |           |
| Move                                | `Tree View: Move`                               | `M` \| `F2`                  |                                                                   |           |
| Add File                            | `Tree View: Add File`                           | `A`                          |                                                                   |           |
| Add Folder                          | `Tree View: Add Folder`                         | `⇧ A`                        |                                                                   |           |
| Remove                              | `Tree View: Remove`                             | `⌫` \| `⌦`                   |                                                                   |           |
| Remove Project Folder               | `Tree View: Remove Project Folder`              |                              |                                                                   |           |
| Expand Item                         | `Tree View: Expand Item`                        | `→` \| `^ ]` \| `^ F` \| `L` |                                                                   |           |
| Collapse Directory                  | `Tree View: Collapse Directory`                 | `←` \| `^ [` \| `^ B` \| `H` |                                                                   |           |
| Recursively Expand Directory        | `Tree View: Recursive Collapse Directory`       | `⌥ →` \| `^⌥ ]`              |                                                                   |           |
| Recursively Collapse Directory      | `Tree View: Recursive Collapse Directory`       | `⌥ ←` \| `^⌥ [`              |                                                                   |           |
| Collapse All                        | `Tree View: Collapse All`                       |                              |                                                                   |           |
| Reveal Active File                  | `Tree View: Reveal Active File`                 | `⌘ |`                        |                                                                   |           |
| Show Current File in File Manager   | `Tree View: Show Current File In File Manager`  |                              |                                                                   |           |
| Show in File Manager                | `Tree View: Show In File Manager`               |                              |                                                                   |           |
| Open Selected Entry                 | `Tree View: Open Selected Entry`                | `↵`                          |                                                                   |           |
| Open Selected Entry Up              | `Tree View: Open Selected Entry Up`             | `⌘ K` + `↑` \| `⌘ K` + `K`   |                                                                   |           |
| Open Selected Entry Right           | `Tree View: Open Selected Entry Right`          | `⌘ K` + `→` \| `⌘ K` +  `L`  |                                                                   |           |
| Open Selected Entry Down            | `Tree View: Open Selected Entry Down`           | `⌘ K` + `↓` \| `⌘ K` + `J`   |                                                                   |           |
| Open Selected Entry Left            | `Tree View: Open Selected Entry Left`           | `⌘ K` + `←` \| `⌘ K` + `H`   |                                                                   |           |
| Open Selected Entry in Pane # (1-9) | `Tree View: Open Selected Entry In Pane #(1-9)` | `⌘ #(1-9)`                   |                                                                   |           |
| Open in New Window                  | `Tree View: Open In New Window`                 |                              |                                                                   |           |
| Copy Full Path                      | `Tree View: Copy Full Path`                     | `^⇧ C`                       |                                                                   |           |
| Copy Project Path                   | `Tree View: Copy Project Path`                  |                              |                                                                   |           |
| Move Up                             | `Core: Move Up`                                 | `K`                          | Contextual hotkey.                                                |           |
| Move Down                           | `Core: Move Down`                               | `J`                          | Contextual Hotkey.                                                |           |
| Move to Top                         | `Core: Move To Top`                             | `↖` (Home)                   | Contextual hotkey.                                                |           |
| Move to Bottom                      | `Core: Move To Bottom`                          | `↘` (End)                    | Contextual hotkey.                                                |           |
| Activate Tree View Filter           | `Tree View Filter: Activate`                    | `^⌥⇧ F`                      | Limits files in the tree-view to those matching certain patterns. |           |
| Toggle Tree View Filter             | `Tree View Filter: Toggle`                      | `⌥⇧⌘ F`                      | Toggle tree view filter UI.                                       | Community |
| Toggle Tree View                    | `Tree View: Toggle`                             | ``⌘ ` `` \| `⌘ K` + `⌘ B`    |                                                                   | Community |
| Toggle Tree View Focus              | `Tree View: Toggle Focus`                       | `^ 0`                        |                                                                   |           |
| Show Tree View                      | `Tree View: Show`                               |                              |                                                                   |           |
| Unfocus Tree View                   | `Tree View: Unfocus`                            | `⎋`                          |                                                                   |           |

### Find and Replace

> With a regular expression search, the replacement syntax to refer back to search groups is `$1`, `$2`, … `$&` (…)
>
> You can limit a search to a subset of the files in your project by entering a [glob pattern](https://en.wikipedia.org/wiki/Glob_%28programming%29) into the "File/Directory pattern" text box. For example, the pattern `src/*.js` would restrict the search to javascript files in the `src` directory. The "globstar" pattern (`**`) can be used to match arbitrarily many subdirectories. For example, `docs/**/*.md` will match `docs/a/foo.md`, `docs/a/b/foo.md`, etc.

― [Atom Flight Manual: Find and Replace](https://flight-manual.atom.io/using-atom/sections/find-and-replace/)

| Name                    | Command                                           | Keybinding | Note                      |
| ----------------------- | ------------------------------------------------- | ---------- | ------------------------- |
| Find Selection          | `Find And Replace: Use Selection As Find Pattern` | `⌘ E`      |                           |
| Find Next               | `Find And Replace: Find Next`                     | `⌘ G`      |                           |
| Find Previous           | `Find And Replace: Find Previous`                 | `⇧⌘ G`     |                           |
| Show Previous           | `Find and Replace: Show Previous`                 | `⇧ ↵`      |                           |
| Find Next Selected      | `Find And Replace: Find Next Selected`            | `⌘ F3`     |                           |
| Find Previous Selected  | `Find And Replace: Find Previous Selected`        | `⇧⌘ F3`    |                           |
| Find All                | `Find And Replace: Find All`                      | `⌥ ↵`      |                           |
| Replace Next            | `Find And Replace: Replace Next`                  | `⌥⌘ E`     |                           |
| Replace All             | `Find And Replace: Replace All`                   | `⌘ ↵`      |                           |
| Select Next             | `Find And Replace: Select Next`                   | `⌘ D`      |                           |
| Select All              | `Find And Replace: Select All`                    | `^⌘ G`     |                           |
| Clear History           | `Find And Replace: Clear History`                 |            |                           |
| Toggle Find and Replace | `Find And Replace: Toggle`                        |            |                           |
| Show Find               | `Find And Replace: Show`                          | `⌘ F`      | Focuses on Find field.    |
| Show Replace            | `Find And Replace: Show Replace`                  | `⌥⌘ F`     | Focuses on Replace field. |

#### Find and Replace Settings

| Name                      | Command                                       | Keybinding | Note                   |
| ------------------------- | --------------------------------------------- | ---------- | ---------------------- |
| Toggle Regex Option       | `Find And Replace: Toggle Regex Option`       | `⌥⌘ /`     | Regex allowed.         |
| Toggle Case Option        | `Find And Replace: Toggle Case Option`        | `⌥⌘ C`     | Case sensitivity.      |
| Toggle Selection Option   | `Find And Replace: Toggle Selection Option`   | `⌥⌘ S`     | Find within selection. |
| Toggle Whole World Option | `Find And Replace: Toggle Whole World Option` | `⌥⌘ W`     | Find whole words only. |

#### Find in Project

| Name                      | Command                                   | Note   |
| ------------------------- | ----------------------------------------- | ------ |
| Replace All               | `Project Find: Replace All`               | `⌘ ↵`  |
| Find in Project           | `Project Find: Show`                      | `⇧⌘ F` |
| Find in Current Directory | `Project Find: Show In Current Directory` |        |
| Toggle Find in Project    | `Project Find: Toggle`                    |        |

#### Find in Project Settings

| Name                      | Command                                   | Keybinding | Note                   |
| ------------------------- | ----------------------------------------- | ---------- | ---------------------- |
| Toggle Regex Option       | `Project Find: Toggle Regex Option`       | `⌥⌘ /`     | Regex allowed.         |
| Toggle Case Option        | `Project Find: Toggle Case Option`        | `⌥⌘ C`     | Case sensitivity.      |
| Toggle Selection Option   | `Project Find: Toggle Selection Option`   | `⌥⌘ S`     | Find within selection. |
| Toggle Whole World Option | `Project Find: Toggle Whole World Option` | `⌥⌘ W`     | Find whole words only. |

### Hyperclick

| Name           | Command                      | Keybinding            | Note                 |
| -------------- | ---------------------------- | --------------------- | -------------------- |
| Confirm Cursor | `Hyperclick: Confirm Cursor` | `⌥⌘ ↵`                | Executes hyperclick. |
| Trigger Key    |                              | `⌥⌘ Left Mouse Click` |                      |

### Image View

| Name        | Command                 | Note            |
| ----------- | ----------------------- | --------------- |
| Zoom In     | Image View: Zoom In     | `⌘ =` \| `⇧⌘ +` |
| Zoom Out    | Image View: Zoom Out    | `⌘ -` \| `⇧⌘ _` |
| Reset Zoom  | Image View: Reset Zoom  | `⌘ 0`           |
| Zoom to Fit | Image View: Zoom To Fit | `⌘ 9`           |

### Intentions

Intentions are a dependency for the Linter package but they appear to be useful beyond linting if other packages use them.

| Name                 | Command                 | Keybinding | Note                         |
| -------------------- | ----------------------- | ---------- | ---------------------------- |
| Hide Intentions      | `Intentions: Hide`      |            |                              |
| Show Intentions      | `Intentions: Show`      | `^ ↵`      | Trigger list of intentions   |
| Highlight Intentions | `Intentions: Highlight` | `⌥`        | Trigger intentions highlight |

### Language Specific

#### AppleScript

| Name                  | Command                           | Note                                                                                                                                                                                                                                          |           |
| --------------------- | --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| Decompile AppleScript | `Language Applescript: Decompile` | Mimic the behavior of Apple's [Script Editor](http://help.apple.com/applescript/mac/10.9/#apscrpt1067) by automatically decompiling .scpt files using the native `osadecompile` utility[\*](https://atom.io/packages/language-applescript#F1) | Community |
| Recompile AppleScript | `Language Applescript: Recompile` | Mimic the behavior of Apple's [Script Editor](http://help.apple.com/applescript/mac/10.9/#apscrpt1067) by automatically recompiling .scpt files using the native `osacompile` utility[\*](https://atom.io/packages/language-applescript#F1)   | Community |

#### JavaScript

##### Docblocks

| Name                 | Command                      | Package   |
| -------------------- | ---------------------------- | --------- |
| Fold All Docblocks   | `Fold Docblocks: Fold All`   | Community |
| Unfold All Docblocks | `Fold Docblocks: Unfold All` | Community |

##### REPL

| Name             | Command             | Package   |
| ---------------- | ------------------- | --------- |
| Toggle Node REPL | `Node Repl: Toggle` | Community |
| Run Node REPL    | `Node Repl: Run`    | Community |
| Clear Node REPL  | `Node Repl: Clear`  | Community |

#### Markdown

| Name                         | Command                                         | Keybinding    | Note                                                            | Package   |
| ---------------------------- | ----------------------------------------------- | ------------- | --------------------------------------------------------------- | --------- |
| Jump to Next Heading         | `Markdown Writer: Jump to Next Heading`         | `⌘ J` + `⌘ N` |                                                                 | Community |
| Jump to Previous Heading     | `Markdown Writer: Jump to Previous Heading`     | `⌘ J` + `⌘ P` |                                                                 | Community |
| Jump to Reference Definition | `Markdown Writer: Jump to Reference Definition` | `⌘ J` + `⌘ D` |                                                                 | Community |
| Fold Heading                 | `Markdown Folding: Cycle`                       | `⌥⌘ [`        |                                                                 | Community |
| Fold all Level 1 Headings    | `Markdown Folding: Foldall H1`                  |               |                                                                 | Community |
| Insert New Line              | `Markdown Writer: Insert New Line`              |               |                                                                 | Community |
| Link                         | `Markdown: Link`                                | `⌘ K` \| `@`  | Inserts inline.                                                 | Community |
| Insert Link                  | `Markdown Writer: Insert Link`                  | `⌥⌘ K`        | Uses menu.                                                      | Community |
| Image                        | `Markdown: Image`                               | `^⌥ I` \| `!` | Inserts inline.                                                 | Community |
| Insert Image                 | `Markdown Writer: Insert Image`                 | `^⌥⌘ I`       | Uses menu.                                                      | Community |
| Insert Image Clipboard       | `Markdown Writer: Insert Image Clipboard`       |               | Uses menu.                                                      | Community |
| Insert Image File            | `Markdown Writer: Insert Image File`            |               | Uses menu.                                                      | Community |
| Insert Footnote              | `Markdown Writer: Insert Footnote`              |               |                                                                 | Community |
| Toggle H#(1-5)               | `Markdown Writer: Toggle H#(1-5)`               | `⌥⌘ #(1-5)`   |                                                                 | Community |
| Toggle Italic Text           | `Markdown Writer: Toggle Italic Text`           | `⌘ I`         |                                                                 | Community |
| Toggle Bold Text             | `Markdown Writer: Toggle Bold Text`             | `⌘ B`         |                                                                 | Community |
| Toggle Code Text             | `Markdown Writer: Toggle Code Text`             | `⌘⌥ C`        |                                                                 | Community |
| Toggle Keystroke Text        | `Markdown Writer: Toggle Keystroke Text`        |               |                                                                 | Community |
| Toggle Strikethrough Text    | `Markdown Writer: Toggle Strikethrough Text`    |               |                                                                 | Community |
| Toggle Blockquote            | `Markdown Writer: Toggle Blockquote`            | `⇧⌘ >`        |                                                                 | Community |
| Toggle Codeblock Text        | `Markdown Writer: Toggle Codeblock Text`        | `^⌘ C`        |                                                                 | Community |
| Toggle Unordered List        | `Markdown Writer: Toggle UL`                    | `⌥⌘ L`        |                                                                 | Community |
| Toggle Ordered List          | `Markdown Writer: Toggle OL`                    | `^⌘ L`        |                                                                 | Community |
| Toggle Task                  | `Markdown Writer: Toggle Task`                  | `^⌘ T`        |                                                                 | Community |
| Toggle Task                  | `Markdown: Toggle Task`                         | `⌥⌘ T`        | Toggle's status                                                 | Community |
| Indent List Item             | `Markdown: Indent List Item`                    | `⇥`           |                                                                 | Community |
| Outdent List Item            | `Markdown: Outdent List Item`                   | `⇧ ⇥`         |                                                                 | Community |
| Correct Order List Numbers   | `Markdown Writer: Correct Order List Numbers`   |               |                                                                 | Community |
| Open Link in Browser         | `Markdown Writer: Open Link In Browser`         |               |                                                                 | Community |
| Open in Marked               | `Marked: Open`                                  | `⇧⌘ M`        |                                                                 | Community |
| Open in iA Writer            | `Open in Ia Writer: Open`                       | `⇧⌘ I`        |                                                                 | Community |
| Toggle Taskdone              | `Markdown Writer: Toggle Taskdone`              |               | _Wrong behavior for completed task, prefer Language Markdown's_ | Community |
| Indent List Line             | `Markdown Writer: Indent List Line`             |               | _Prefer Lanaguage Markdown's_                                   | Community |
| Emphasis                     | `Markdown: Emphasis`                            | `_`           | _Prefer Markdown Writer's_                                      | Community |
| Strong                       | `Markdown: Strong Emphasis`                     | `*`           | _Prefer Markdown Writer's_                                      | Community |
| Strike Through               | `Markdown: Strike Through`                      | `~`           | _Prefer Markdown Writer's_                                      | Community |

##### Markdown Preview

| Name                           | Command                                            | Keybinding      |
| ------------------------------ | -------------------------------------------------- | --------------- |
| Preview File                   | `Markdown Preview: Preview File`                   |                 |
| Copy HTML                      | `Markdown Preview: Copy HTML`                      |                 |
| Save as HTML                   | `Markdown Preview: Save As HTML`                   |                 |
| Zoom In                        | `Markdown Preview: Zoom In`                        | `⌘ =` \| `⇧⌘ +` |
| Zoom Out                       | `Markdown Preview: Zoom Out`                       | `⌘ -` \| `⇧⌘ _` |
| Reset Zoom                     | `Markdown Preview: Reset Zoom`                     | `⌘ 0`           |
| Toggle                         | `Markdown Preview: Toggle`                         | `^⇧ M`          |
| Toggle Break On Single Newline | `Markdown Preview: Toggle Break On Single Newline` |                 |
| Toggle GitHub Style            | `Markdown Preview: Toggle GitHub Style`            |                 |

##### Tables

| Name                    | Command                                        | Keybinding | Note                                     | Packages  |
| ----------------------- | ---------------------------------------------- | ---------- | ---------------------------------------- | --------- |
| Insert Table            | `Markdown Writer: Insert Table`                |            |                                          | Community |
| Next Cell               | `Markdown Table Editor: Next Cell`             | `⇥`        | Move to the next cell                    | Community |
| Previous Cell           | `Markdown Table Editor: Previous Cell`         | `⇧ ⇥`      | Move to the previous cell                | Community |
| Next Row                | `Markdown Table Editor: Next Row`              | `↵`        | Move to the next row                     | Community |
| Move Up                 | `Markdown Table Editor: Move Up`               |            | Move to the upper cell                   | Community |
| Move Right              | `Markdown Table Editor: Move Right`            |            | Move to the right cell                   | Community |
| Move Down               | `Markdown Table Editor: Move Down`             |            | Move to the lower cell                   | Community |
| Move Left               | `Markdown Table Editor: Move Left`             |            | Move to the left cell                    | Community |
| Select Cell             | `Markdown Table Editor: Select Cell`           |            | Select the cell content                  | Community |
| Move Row Up             | `Markdown Table Editor: Move Row Up`           |            | Move the row up                          | Community |
| Move Row Down           | `Markdown Table Editor: Move Row Down`         |            | Move the row down                        | Community |
| Move Column Left        | `Markdown Table Editor: Move Column Left`      |            | Move the column left                     | Community |
| Move Column Right       | `Markdown Table Editor: Move Column Right`     |            | Move the column right                    | Community |
| Insert Row              | `Markdown Table Editor: Insert Row`            |            | Insert an empty row                      | Community |
| Delete Row              | `Markdown Table Editor: Delete Row`            |            | Delete the row                           | Community |
| Insert Column           | `Markdown Table Editor: Insert Column`         |            | Insert an empty column                   | Community |
| Delete Column           | `Markdown Table Editor: Delete Column`         |            | Delete the column                        | Community |
| Escape                  | `Markdown Table Editor: Escape`                | `⎋`        | Escape from the table                    | Community |
| Align Left              | `Markdown Table Editor: Align Left`            |            | Left-align the column                    | Community |
| Align Center            | `Markdown Table Editor: Align Center`          |            | Center-align the column                  | Community |
| Align Right             | `Markdown Table Editor: Align Right`           |            | Right-align the column                   | Community |
| Align None              | `Markdown Table Editor: Align None`            |            | Unset alignment of the column            | Community |
| Format                  | `Markdown Table Editor: Format`                |            | Just format the table                    | Community |
| Format All              | `Markdown Table Editor: Format All`            |            | Format all the tables in the text editor | Community |
| Switch Format Type      | `Markdown Table Editor: Switch Format Type`    |            | Switch "Format Type" config              | Community |
| Toggle Format on Save   | `Markdown Table Editor: Toggle Format On Save` |            | Toggle "Format On Save" config           | Community |
| Jump to Next Table Cell | `Markdown Writer: Jump to Next Table Cell`     |            | _Prefer Markdown Table Editor's_         | Community |
| Format Table            | `Markdown Writer: Format Table`                |            | _Prefer Markdown Table Editor's_         | Community |

#### Python

##### Kite

| Name                       | Command                            | Package   |
| -------------------------- | ---------------------------------- | --------- |
| Open Sidebar               | `Kite: Open Sidebar`               | Community |
| Close Sidebar              | `Kite: Close Sidebar`              | Community |
| Open Settings              | `Kite: Open Settings`              | Community |
| Toggle Sidebar             | `Kite: Toggle Sidebar`             | Community |
| Open Permissions           | `Kite: Open Permissions`           | Community |
| Test Autocorrect UI        | `Kite: Test Autocorrect UI`        | Community |
| Open Autocorrect Sidebar   | `Kite: Open Autocorrect Sidebar`   | Community |
| Close Autocorrect Sidebar  | `Kite: Close Autocorrect Sidebar`  | Community |
| Toggle Autocorrect Sidebar | `Kite: Toggle Autocorrect Sidebar` | Community |

### Linting

#### Atom IDE

| Name                            | Command                                        | Keybinding | Package   |
| ------------------------------- | ---------------------------------------------- | ---------- | --------- |
| Go to First Diagnostic          | `Diagnostics: Go To First Diagnostic`          | `^⌥⇧ <`    | Community |
| Go to Last Diagnostic           | `Diagnostics: Go To Last Diagnostic`           | `^⌥⇧ >`    | Community |
| Go to Next Diagnostic           | `Diagnostics: Go To Next`                      | `⌥⇧ >`     | Community |
| Go to Previous Diagnostic       | `Diagnostics: Go To Previous`                  | `⌥⇧ <`     | Community |
| Go to Next Diagnostic Trace     | `Diagnostics: Go To Next Diagnostic Trace`     | `⌥⇧⌘ .`    | Community |
| Go to Previous Diagnostic Trace | `Diagnostics: Go To Previous Diagnostic Trace` | `⌥⇧⌘ ,`    | Community |
| Show Code Actions               | `Diagnostics: Show Actions At Position`        | `⌥ A`      | Community |
| Apply Diagnostic Fixes          | `Diagnostics: Fix All In Current File`         | `⌥⇧ A`     | Community |
| Open All Files with Errors      | `Diagnostics: Open All Files With Errors`      |            | Community |
| Toggle Diagnostics              | `Diagnostics: Toggle Table`                    | `⌥⇧ D`     | Community |

### Reference

#### Code

| Name                                      | Command                             | Keybinding        | Note                                                              | Package   |
| ----------------------------------------- | ----------------------------------- | ----------------- | ----------------------------------------------------------------- | --------- |
| Search Dash by Language                   | `Dash: Shortcut`                    | `^ H`             | This uses a scoped search based on the filename and syntax.       | Community |
| Search Dash                               | `Dash: Shortcut Alt`                | `^⌥⇧ H` \| `^⌥ H` | Search all documentation across grammars.                         | Community |
| Search Dash by Language in the Background | `Dash: Shortcut Background`         | `^⇧ H`            | Same as shortcut but in the background.                           | Community |
| Search Dash in the Background             | `Dash: Shortcut Alt Background`     |                   | Same as shortcut alt but in the background.                       | Community |
| Search Dash Context Menu Item             | `Dash: Context Menu`                |                   | Seems to be same as shortcut, there is a right click menu option. | Community |
| Open Cheat Sheet                          | `Markdown Writer: Open Cheat Sheet` |                   |                                                                   | Community |

#### Keybindings

| Name                         | Command                         | Keybinding | Note                                      | Package   |
| ---------------------------- | ------------------------------- | ---------- | ----------------------------------------- | --------- |
| Toggle Keybinding Cheatsheet | `Keybinding Cheatsheet: Toggle` | `^⌥ /`     | Quickly view and filter atom keybindings. | Community |

#### Packages

| Name          | Command          | Note                                                   | Package   |
| ------------- | ---------------- | ------------------------------------------------------ | --------- |
| IDE HTML Help | `Ide Html: Help` | Notification with version, FAQ and create issue links. | Community |
| IDE YAML Help | `Ide Yaml: Help` | Notification with version, FAQ and create issue links. | Community |

### References & Definitions

| Name            | Command                     | Keybinding | Package   |
| --------------- | --------------------------- | ---------- | --------- |
| Find References | `Find References: Activate` | `⌥⇧⌘ F`    | Community |

### Packages & Settings

| Name                  | Command                       | Note                                                 | Package   |
| --------------------- | ----------------------------- | ---------------------------------------------------- | --------- |
| Fork Settings         | `Sync Settings: Fork`         | Fork existing settings from a different GitHub user. | Community |
| Backup Settings       | `Sync Settings: Backup`       | Backup all settings.                                 | Community |
| Restore Settings      | `Sync Settings: Restore`      | Restore all settings.                                | Community |
| View Settings Backup  | `Sync Settings: View Backup`  | View your online backup.                             | Community |
| Check Settings Backup | `Sync Settings: Check Backup` | Check the latest backup is applied.                  | Community |

### Platform Specific

#### Sketch

| Name                         | Command                         | Keybinding | Package   |
| ---------------------------- | ------------------------------- | ---------- | --------- |
| Toggle Sketchplugin Language | `Language-Sketchplugin: Toggle` | `^⌥ O`     | Community |
| Run Sketch Script            | `Sketchapp Scripter RunScript`  | `^ R`      | Community |

### Projects

| Name                      | Command                                         | Keybinding | Note                                 | Package   |
| ------------------------- | ----------------------------------------------- | ---------- | ------------------------------------ | --------- |
| Reopen Project            | `Application: Reopen Project`                   |            |                                      |           |
| Add Project Folder        | `Application: Add Project Folder`               | `⇧⌘ O`     |                                      |           |
| Promote Folder to Project | `Promote Folder To Project: Add Project Folder` |            | Add folders to your current project. | Community |
| Clear Project History     | `Application: Clear Project History`            |            | Clears the reopen project list.      |           |

#### Git Projects

| Name                  | Command                    | Keybinding | Package   |
| --------------------- | -------------------------- | ---------- | --------- |
| Toggle Git Projects   | `Git Projects: Toggle`     | `^⌥ O`     | Community |
| Add Project to Window | `GIt Projects: Toggle Add` | `^⌥⇧ O`    | Community |

#### Project Manager

| Name            | Command                            | Keybinding | Note                                                                                                                                          | Package   |
| --------------- | ---------------------------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| List Projects   | `Project Manager: List Projects`   | `^⌘ P`     | Projects can be filtered by `title`, `group` and `template` by typing `group: atom` which would give all projects with the `atom` group.      | Community |
| Edit Project    | `Project Manager: Edit Project`    |            | Open a page where you can edit the current project. It currently only supports certain fields.                                                | Community |
| Save Project    | `Project Manager: Save Project`    |            | Write the title you want to save the project as.                                                                                              | Community |
| Edit Projects   | `Project Manager: Edit Projects`   |            | All projects are saved in a `.cson` file which you can easily reach by searching for `Project Manager: Edit Projects` in the Command Palette. | Community |
| Update Projects | `Project Manager: Update Projects` |            |                                                                                                                                               | Community |

#### Todos & Notes

| Name                      | Command                               | Keybinding    | Note                            | Package   |
| ------------------------- | ------------------------------------- | ------------- | ------------------------------- | --------- |
| Toggle Todo               | `Todo: Toggle`                        | `^ K` + `^ T` | Opens todo search sidebar list. | Community |
| Tasks                     | `Imdone Atom: Tasks`                  | `⌥ T`         |                                 | Community |
| Board Zoom In             | `Imdone Atom: Board Zoom In`          | `⌥ .`         |                                 | Community |
| Board Zoom Out            | `Imdone Atom: Board Zoom Out`         | `⌥ ,`         |                                 | Community |
| Today's Journal           | `Imdone Atom: Todays Journal`         | `⌥ J`         |                                 | Community |
| Today's Project Journal   | `Imdone Atom: Todays Project Journal` | `⌥ P`         |                                 | Community |
| Find Todos in Active File | `Todo Show: Find In Active File`      |               |                                 | Community |
| Find Todos in Open Files  | `Todo Show: Find In Open Files`       |               |                                 | Community |
| Find Todos in Workspace   | `Todo Show: Find In Workspace`        |               |                                 | Community |
| Find Todos in Project     | `Todo Show: Find In Project`          |               |                                 | Community |
| Toggle Todo Show          | `Todo Show: Toggle`                   | `^⇧ T`        |                                 | Community |

### Snippets

A basic CSON snippet from [Atom Flight Manual: Snippets](https://flight-manual.atom.io/using-atom/sections/snippets/):

```coffeescript
'.source.js':
 'console.log':
   'prefix': 'log'
   'body': 'console.log(${1:"crash"});$2'
```

Use the `snip` trigger in your snippets file for a snippet for defining snippets.

| Name                      | Command                       | Keybinding |
| ------------------------- | ----------------------------- | ---------- |
| Expand Snippet            | `Snippets: Expand`            | `⇥`        |
| Next Tab Stop             | `Previous Tab Stop`           | `⇥`        |
| Previous Tab Stop         | `Snippets: Previous Tab Stop` | `⇧ ⇥`      |
| Toggle Available Snippets | `Snippets: Available`         |            |

#### Snippet Conversion

| Name                                               | Command                                               | Keybinding    | Package   |
| -------------------------------------------------- | ----------------------------------------------------- | ------------- | --------- |
| Toggle Atom Format                                 | `Atomizr: Toggle Atom Format`                         | `^ A` + `^ A` | Community |
| Automatic Snippet Conversion                       | `Atomizr: Automatic Conversion`                       | `^ C` + `^ C` | Community |
| Sublime Text Snippet Subformat                     | `Atomizr: Sublime Subformat`                          | `^ S` + `^ S` | Community |
| Convert Atom Snippet to Sublime Text               | `Atomizr: Convert Atom to Sublime Text`               | `^ A` + `^ S` | Community |
| Convert Atom Snippet to TextMate                   | `Atomizr: Convert Atom to Textmate`                   | `^ A` + `^ T` | Community |
| Convert Atom Snippet to Visual Studio Code         | `Atomizr: Convert Atom to Visual Studio Code`         | `^ A` + `^ V` | Community |
| Convert Sublime Text Snippet to Atom               | `Atomizr: Convert Sublime Text to Atom`               | `^ S` + `^ A` | Community |
| Convert Sublime Text Snippet to Textmate           | `Atomizr: Convert Sublime Text to Textmate`           | `^ S` + `^ T` | Community |
| Convert Sublime Text Snippet to Visual Studio Code | `Atomizr: Convert Sublime Text to Visual Studio Code` | `^ A` + `^ V` | Community |
| Convert TextMate Snippet to Atom                   | `Atomizr: Convert Textmate to Atom`                   | `^ T` + `^ A` | Community |
| Convert Textmate Snippet to Sublime Text           | `Atomizr: Convert Textmate to Sublime Text`           | `^ T` + `^ S` | Community |
| Convert Textmate Snippet to Visual Studio Code     | `Atomizr: Convert Textmate to Visual Studio Code`     | `^ T` + `^ V` | Community |
| Convert Visual Studio Code Snippet to Atom         | `Atomizr: Convert Visual Studio Code to Atom`         | `^ V` + `^ A` | Community |
| Convert Visual Studio Code Snippet to Sublime Text | `Atomizr: Convert Visual Studio Code to Sublime Text` | `^ V` + `^ S` | Community |
| Convert Visual Studio Code Snippet to Textmate     | `Atomizr: Convert Visual Studio Code to Textmate`     | `^ V` + `^ T` | Community |
| Open Atomizr Package Settings                      | `Atomizr: Open Package Settings`                      |               | Community |

#### Emmet

| Name                              | Command                                  | Keybinding       | Note                                                                                                                                                      |
| --------------------------------- | ---------------------------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Expand Abbreviation               | `Emmet: Expand Abbreviation`             | `⇧⌘ E` \| `^ E`  | Expands [CSS-like abbreviations](https://docs.emmet.io/abbreviations/) into HTML/XML/CSS code, depending on current document’s syntax.                    |
| Expand Abbreviation (Interactive) | `Emmet: Interactive Expand Abbreviation` | `⌥⌘ ↵` \| `^⌥ ↵` | Expands [CSS-like abbreviations](https://docs.emmet.io/abbreviations/) into HTML/XML/CSS code, depending on current document’s syntax.                    |
| Expand Abbreviation with Tab      | `Emmet: Expand Abbreviation With Tab`    | `⇥`              | Expands [CSS-like abbreviations](https://docs.emmet.io/abbreviations/) into HTML/XML/CSS code, depending on current document’s syntax.                    |
| Wrap with Abbreviation            | `Emmet: Wrap with Abbreviation`          | `^ W` \| `^⌥ W`  | Takes an [abbreviation](https://docs.emmet.io/abbreviations/), expands it and places currently selected content in the last element of generated snippet. |

### Source Control

By default a lot of source control contextual information is shown in the status bar and clicking on the icons will often give you quick access to commands like switching branches.

| Name                                  | Command                                         | Keybinding     | Note               |
| ------------------------------------- | ----------------------------------------------- | -------------- | ------------------ |
| Fetch                                 | `GitHub: Fetch`                                 | `⌥ G` + `F`    |                    |
| Pull                                  | `GitHub: Pull`                                  | `⌥ G` + `⇧ F`  |                    |
| Commit                                | `GitHub: Commit`                                | `⌥ G` + `↵`    |                    |
|                                       | `GitHub: Commit`                                | `⌘ ↵` \| `^ ↵` | Contextual hotkey. |
| Push                                  | `GitHub: Push`                                  | `⌥ G` + `P`    |                    |
| Force Push                            | `GitHub: Force Push`                            | `⌥ G` + `⇧ P`  |                    |
| Clone                                 | `GitHub: Clone`                                 | `⌥ G` + `=`    |                    |
| Checkout Head Revision                | `Editor: Checkout Head Revision`                | `⌥⌘ Z`         |                    |
| Discard All Changes                   | `GitHub: Discard All Changes`                   |                |                    |
| Undo Last Discard in Git Tab          | `GitHub: Undo Last Discard In Git Tab`          |                |                    |
| Stage All Changes                     | `GitHub: Stage All Changes`                     |                |                    |
| Unstage All Changes                   | `GitHub: Unstage All Changes`                   |                |                    |
| Resolve as Ours                       | `GitHub: Resolve As Ours`                       | `⌥ M` + `1`    |                    |
| Resolve as Theirs                     | `GitHub: Resolve As Theirs`                     | `⌥ M` + `2`    |                    |
| Resolve as Base                       | `GitHub: Resolve As Base`                       | `⌥ M` + `3`    |                    |
| Resolve as Current                    | `GitHub: Resolve As Base`                       | `⌥ M` + `4`    |                    |
| Toggle Expanded Commit Message Editor | `GitHub: Toggle Expanded Commit Message Editor` |                |                    |
| Toggle Git Tab                        | `GitHub: Toggle Git Tab`                        | `^⇧ 9`         |                    |
| Toggle GitHub Tab                     | `GitHub: Toggle GitHub Tab`                     | `^⇧ 8`         |                    |
| Toggle Git Tab Focus                  | `GitHub: Toggle Git Tab Focus`                  | `^ 9`          |                    |
| Toggle GitHub Tab Focus               | `GitHub: Toggle GitHub Tab Focus`               | `^ 8`          |                    |

#### File Patch View

| Name                        | Command                               | Keybinding |
| --------------------------- | ------------------------------------- | ---------- |
| Open File                   | `GitHub: Open File`                   | `O`        |
| Discard Selected Lines      | `GitHub: Discard Selected Lines`      | `⌘ ⌫`      |
| Select Previous Hunk        | `GitHub: Select Previous Hunk`        | `⇧ ⇥`      |
| Select Next Hunk            | `GitHub: Select Next Hunk`            | `⇥`        |
| Move Focus to Staging View  | `GitHub: Move Right`                  | `→`        |
| Toggle Patch Selection Mode | `GitHub: Toggle Patch Selection Mode` | `/`        |
| Close All Diff Views        | `GitHub: Close All Diff Views`        |            |
| Close Empty Diff Views      | `GitHub: Close Empty Diff Views`      |            |

#### GitHub

| Name                       | Command                              | Note                                 |
| -------------------------- | ------------------------------------ | ------------------------------------ |
| Open Issue or Pull Request | `GitHub: Open Issue Or Pull Request` | Pass it the URL for any issue or PR. |
| Logout                     | `GitHub: Logout`                     |                                      |

#### Git Diff

| Name                  | Command                           | Keybinding  |
| --------------------- | --------------------------------- | ----------- |
| Move to Next Diff     | `Git Diff: Move To Next Diff`     | `⌥ G` + `↓` |
| Move to Previous Diff | `Git Diff: Move To Previous Diff` | `⌥ G` + `↑` |
| Toggle Diff List      | `Git Diff: Toggle Diff List`      | `⌥ G` + `D` |

#### Open External Tool

| Name                  | Command                       | Keybinding | Note                           | Package   |
| --------------------- | ----------------------------- | ---------- | ------------------------------ | --------- |
| Open Project in Tower | `Open Project In Tower: Open` | `^⌥ R`     | Open current project in Tower. | Community |

#### Local History

| Name                  | Command                              | Note                     | Package   |
| --------------------- | ------------------------------------ | ------------------------ | --------- |
| Purge Local History   | Local History: Purge                 |                          | Community |
| Current File History  | Local History: Current File          |                          | Community |
| Difftool Current File | Local History: Difftool Current File | Set to use Kaleidoscope. | Community |

#### Open on GitHub

| Name           | Command                          | Keybinding  |
| -------------- | -------------------------------- | ----------- |
| File           | `Open On GitHub: File`           | `⌥ G` + `O` |
| File on Master | `Open On GitHub: File On Master` |             |
| Copy URL       | `Open On GitHub: Copy URL`       | `⌥ G` + `C` |
| Branch Compare | `Open On GitHub: Branch Compare` | `⌥ G` + `R` |
| Blame          | `Open On GitHub: Blame`          | `⌥ G` + `B` |
| History        | `Open On GitHub: History`        | `⌥ G` + `H` |
| Issues         | `Open On GitHub: Issues`         | `⌥ G` + `I` |
| Pull Requests  | `Open On GitHub: Pull Requests`  | `⌥ G` + `P` |
| Repository     | `Open On GitHub: Repository`     | `⌥ G` + `G` |

#### Staging View

| Name                                   | Command                                          | Keybinding     |
| -------------------------------------- | ------------------------------------------------ | -------------- |
| Open File                              | `GitHub: Open File`                              | `O`            |
| Show Diff View                         | `GitHub: Show Diff View`                         |                |
| Discard Changes in Selected Files      | `GitHub: Discard Changes In Selected Files`      | `⌘ ⌫` \| `^ ⌫` |
| Focus Next List                        | `GitHub: Focus Next`                             | `⇥`            |
| Focus Previous List                    | `GitHub: Focus Previous`                         | `⇧ ⇥`          |
| Move Focus to File Patch View          | `GitHub: Move Focus to File Patch View`          | `←`            |
| View Stage Changes for Current File    | `GitHub: View Staged Changes For Current File`   |                |
| View Unstaged Changes for Current File | `GitHub: View Unstaged Changes For Current File` |                |

### Spell Check

| Name                  | Command                            | Keybinding | Note              |
| --------------------- | ---------------------------------- | ---------- | ----------------- |
| Correct Misspelling   | `Spell Check: Correct Misspelling` | `⌘ :`      |                   |
| Confirm               | `Core: Confirm`                    | `⇥`        | Contextual hotkey |
| Cancel                | `Core: Cancel`                     | `⌘ :`      | Contextual hotkey |
| Toggle Spell Checking | `Spell Check: Toggle`              |            |                   |

### Symbols

| Name                    | Command                                 | Keybinding |
| ----------------------- | --------------------------------------- | ---------- |
| Go To Declaration       | `Symbols View: Go To Declaration`       | `⌥⌘ ↓`     |
| Return From Declaration | `Symbols View: Return From Declaration` | `⌥⌘ ↑`     |
| Toggle File Symbols     | `Symbols View: Toggle File Symbols`     | `⌘ R`      |
| Toggle Project Symbols  | `Symbols View: Toggle Project Symbols`  | `⇧⌘ R`     |

### Terminal

| Name                       | Command                                              | Keybinding | Note                                                        | Package   |
| -------------------------- | ---------------------------------------------------- | ---------- | ----------------------------------------------------------- | --------- |
| New Terminal               | `Platformio Ide Terminal: New`                       | `⇧⌘ T`     |                                                             | Community |
| Next Terminal              | `Platformio Ide Terminal: Next`                      | ⇧⌘ K       |                                                             | Community |
| Previous Terminal          | `Platformio Ide Terminal: Prev`                      | `⇧⌘ J`     |                                                             | Community |
| Copy                       | `Platformio Ide Terminal: Copy`                      | `⌘ C`      |                                                             | Community |
| Paste                      | `Platformio Ide Terminal: Paste`                     | `⌘ V`      |                                                             | Community |
| Insert Text                | `Platformio Ide Terminal: Insert Text`               |            |                                                             | Community |
| Insert Selected Text       | `Platformio Ide Terminal: Insert Selected Text`      | `^ ↵`      |                                                             | Community |
| Insert Custom Text # (1-8) | `Platformio Ide Terminal: Insert Custom Text #(1-8)` |            |                                                             | Community |
| Clear Terminal             | `Platformio Ide Terminal: Clear`                     |            |                                                             | Community |
| Rename Terminal            | `Platformio Ide Terminal: Rename`                    |            |                                                             | Community |
| Focus Terminal             | `Platformio Ide Terminal: Focus`                     | `⌥⌘ F`     |                                                             | Community |
| Fullscreen                 | `Platformio Ide Terminal: Fullscreen`                |            |                                                             | Community |
| Close Terminal             | `Platformio Ide Terminal: Close`                     | `⇧⌘ X`     |                                                             | Community |
| Close All Terminals        | `Platformio Ide Terminal: Close All`                 |            |                                                             | Community |
| Toggle Terminal            | `Platformio Ide Terminal: Copy`                      | ``^ ` ``   |                                                             | Community |
| Edit Config                | `Terminal Commands: Edit Config`                     |            |                                                             | Community |
| Load Config                | `Terminal Commands: Load Config`                     |            |                                                             | Community |
| \*Command\*                | `*Command Prefix*: *Command*`                        |            | You define commands and their prefixes in your config file. | Community |
| Open Terminal              | `Terminal: Open`                                     | `⇧⌘ T`     |                                                             | Community |
| Copy in Terminal           | `Terminal: Copy`                                     | `⌘ C`      |                                                             | Community |
| Paste in Terminal          | `Terminal: Paste`                                    | `⌘ V`      |                                                             | Community |
| Clear Terminal             | `Terminal: Clear`                                    | `⌘ K`      |                                                             | Community |

### Visualization

| Name                           | Command                           | Keybinding    | Package   |
| ------------------------------ | --------------------------------- | ------------- | --------- |
| Show Regex Railroad Diagram    | `Regex Railroad Diagram: Show`    | `⌘ R` + `⌘ R` | Community |
| Enable Regex Railroad Diagram  | `Regex Railroad Diagram: Enable`  |               | Community |
| Disable Regex Railroad Diagram | `Regex Railroad Diagram: Disable` |               | Community |

#### Tracking & Productivity

| Name                | Command                | Note                                                              | Package   |
| ------------------- | ---------------------- | ----------------------------------------------------------------- | --------- |
| Toggle Editor Stats | `Editor Stats: Toggle` | Display a graph of keyboard and mouse usage for the last 6 hours. | Community |

## Settings

### Configuration

| Name                  | Command                              | Note                                                                     | Package   |
| --------------------- | ------------------------------------ | ------------------------------------------------------------------------ | --------- |
| Open Your Config      | `Application: Open Your Config`      |                                                                          |           |
| Open Your Init Script | `Application: Open Your Init Script` |                                                                          |           |
| Open Your Keymap      | `Application: Open Your Keymap`      |                                                                          |           |
| Open Your Snippets    | `Application: Open Your Snippets`    |                                                                          |           |
| Open Your Stylesheet  | `Application: Open Your Stylesheet`  |                                                                          |           |
| Show Menu Manager     | `Menu Manager: Show`                 | Menu Manager shows main menu items and all context menu items from Atom. | Community |

#### Backup

| Name                  | Command                       | Note                                                 | Package   |
| --------------------- | ----------------------------- | ---------------------------------------------------- | --------- |
| Fork Settings         | `Sync Settings: Fork`         | Fork existing settings from a different GitHub user. | Community |
| Backup Settings       | `Sync Settings: Backup`       | Backup all settings.                                 | Community |
| Restore Settings      | `Sync Settings: Restore`      | Restore all settings.                                | Community |
| View Settings Backup  | `Sync Settings: View Backup`  | View your online backup.                             | Community |
| Check Settings Backup | `Sync Settings: Check Backup` | Check the latest backup is applied.                  | Community |

### Editor

| Name                                                   | Command                                           | Keybinding      | Note                                   | Package   |
| ------------------------------------------------------ | ------------------------------------------------- | --------------- | -------------------------------------- | --------- |
| Toggle Auto Indent                                     | `Editor: Auto Indent`                             |                 |                                        |           |
| Toggle Auto Indent for Window                          | `Window: Toggle Auto Indent`                      |                 |                                        |           |
| Toggle Soft Tabs                                       | `Editor: Toggle Soft Tabs`                        |                 |                                        |           |
| Toggle Invisibles                                      | `Window: Toggle Invisibles`                       |                 | Shows symbols representing whitespace. |           |
| Toggle Indent Guide                                    | `Editor: Toggle Indent Guide`                     |                 |                                        |           |
| Toggle Current Line Underline Highlight                | `Highlight Line: Toggle Underline`                | `⇧⌘ U`          |                                        | Community |
| Toggle Current Line Background Highlight               | `Highlight Line: Toggle Background`               | `⌥⇧⌘ U`         |                                        | Community |
| Toggle Current Line Selection Borders Highlight        | `Highlight Line: Toggle Selection Borders`        | `⌥⇧⌘ H`         |                                        | Community |
| Toggle Hide Current Line Highlight on Select Highlight | `Highlight Line: Toggle Hide Highlight On Select` | `⌥⇧⌘ H`         |                                        | Community |
| Toggle Highlight Selected                              | `Highlight Selected: Toggle`                      | `^⌘ H`          |                                        | Community |
| Toggle Line Numbers                                    | `Editor: Toggle Line Numbers`                     |                 |                                        | Community |
| Toggle Minimap                                         | `Minimap: Toggle`                                 |                 | A preview of the full source code.     | Community |
| Toggle Minimap Bookmarks                               | `Minimap: Toggle Bookmarks`                       |                 |                                        | Community |
| Toggle Minimap Codeglance                              | `Minimap: Toggle Codeglance`                      |                 |                                        | Community |
| Toggle Minimap Cursorline                              | `Minimap: Toggle Cursorline`                      |                 |                                        | Community |
| Toggle Minimap Find and Replace                        | `Minimap: Toggle Find and Replace`                |                 |                                        | Community |
| Toggle Minimap Git Diff                                | `Minimap: Toggle Git Diff`                        |                 |                                        | Community |
| Toggle Minimap Highlight Selected                      | `Minimap: Toggle Highlight Selected`              |                 |                                        | Community |
| Toggle Minimap Linter                                  | `Minimap: Toggle Linter`                          |                 |                                        | Community |
| Toggle Minimap Pigments                                | `Minimap: Toggle Pigments`                        |                 |                                        | Community |
| Toggle Minimap Quick Highlight                         | `Minimap: Toggle Quick Highlight`                 |                 |                                        | Community |
| Toggle Minimap Selection                               | `Minimap: Toggle Selection`                       |                 |                                        | Community |
| Toggle Minimap Split Diff                              | `Minimap: Toggle Split Diff`                      |                 |                                        | Community |
| Toggle Soft Wrap                                       | `Editor: Toggle Soft Wrap`                        |                 |                                        |           |
| Toggle Spell Check                                     | `Spell Check: Toggle`                             |                 |                                        |           |
| Increase Font Size                                     | `Window: Increase Font Size`                      | `⌘ =` \| `⌘⇧ +` |                                        |           |
| Decrease Font Size                                     | `Window: Decrease Font Size`                      | `⌘ -` \| `⇧⌘ _` |                                        |           |
| Reset Font Size                                        | `Window: Reset Font Size`                         | `⌘ 0`           |                                        |           |

### Find and Replace

| Name                      | Command                                       | Keybinding | Note                  |
| ------------------------- | --------------------------------------------- | ---------- | --------------------- |
| Toggle Regex Option       | `Find And Replace: Toggle Regex Option`       | `⌥⌘ /`     | Regex allowed         |
| Toggle Case Option        | `Find And Replace: Toggle Case Option`        | `⌥⌘ C`     | Case sensitivity      |
| Toggle Selection Option   | `Find And Replace: Toggle Selection Option`   | `⌥⌘ S`     | Find within selection |
| Toggle Whole World Option | `Find And Replace: Toggle Whole World Option` | `⌥⌘ W`     | Find whole words only |

#### Project Find

| Name                      | Command                                   | Keybinding | Note                  |
| ------------------------- | ----------------------------------------- | ---------- | --------------------- |
| Toggle Regex Option       | `Project Find: Toggle Regex Option`       | `⌥⌘ /`     | Regex allowed         |
| Toggle Case Option        | `Project Find: Toggle Case Option`        | `⌥⌘ C`     | Case sensitivity      |
| Toggle Selection Option   | `Project Find: Toggle Selection Option`   | `⌥⌘ S`     | Find within selection |
| Toggle Whole World Option | `Project Find: Toggle Whole World Option` | `⌥⌘ W`     | Find whole words only |

### Keymap

| Name                 | Command                         | Keybinding | Note                                                                      |
| -------------------- | ------------------------------- | ---------- | ------------------------------------------------------------------------- |
| Open Your Keymap     | `Application: Open Your Keymap` |            |                                                                           |
| Key Binding Resolver | `Key Binding Resolver: Toggle`  | `⌘ .`      | Toggles panel that shows you all commands associated with pressed hotkeys |

### Language Specific

#### Markdown

| Name                   | Command                                        | Keybinding | Note                           | Packages  |
| ---------------------- | ---------------------------------------------- | ---------- | ------------------------------ | --------- |
| Switch Format Type     | `Markdown Table Editor: Switch Format Type`    |            | Switch "Format Type" config    | Community |
| Toggle Format on Save  | `Markdown Table Editor: Toggle Format On Save` |            | Toggle "Format On Save" config | Community |
| Create Default Keymaps | `Markdown Writer: Create Default Keymaps`      |            |                                | Community |
| Create Project Configs | `Markdown Writer: Create Project Configs`      |            |                                | Community |

### Preferences

| Name                             | Command                                      | Keybinding |
| -------------------------------- | -------------------------------------------- | ---------- |
| Preferences                      | `Application: Show Preferences`              | `⌘ ,`      |
|                                  | `Application: Show Settings`                 |            |
|                                  | `Settings View: Open`                        |            |
| Core Section                     | `Settings View: Core`                        |            |
| Editor Section                   | `Settings View: Editor`                      |            |
| Keybindings Section              | `Settings View: Show Keybindings`            |            |
| Package Section                  | `Settings View: View Installed Packages`     |            |
| Focus Filter in Packages Section | `Settings View: Uninstall Packages`          |            |
| Themes Section                   | `Settings View: View Installed Themes`       |            |
| Focus Filter in Themes Section   | `Settings View: Change Themes`               |            |
|                                  | `Settings View: Uninstall Themes`            |            |
| Updates Section                  | `Settings View: Check For Package Updates`   |            |
| Install Section                  | `Settings View: Install Packages And Themes` |            |

### Snippets

| Name               | Command                           |
| ------------------ | --------------------------------- |
| Open Your Snippets | `Application: Open Your Snippets` |

### Tool Bar

| Name                     | Command                     | Package   |
| ------------------------ | --------------------------- | --------- |
| Position Tool Bar Top    | `Tool Bar: Position Top`    | Community |
| Position Tool Bar Left   | `Tool Bar: Position Left`   | Community |
| Position Tool Bar Right  | `Tool Bar: Position Right`  | Community |
| Position Tool Bar Bottom | `Tool Bar: Position Bottom` | Community |

### Tree View

| Name                     | Command                               | Keybinding | Note                                   |
| ------------------------ | ------------------------------------- | ---------- | -------------------------------------- |
| Toggle Ignored Names     | `Tree View: Toggle Ignored Names`     |            |                                        |
| Toggle VCS Ignored Files | `Tree View: Toggle VCS Ignored Files` | `I`        | Respects .gitignore. Hotkey contextual |

## UI

### Menus

| Name                         | Command                     | Package   |
| ---------------------------- | --------------------------- | --------- |
| Add File Context Menu Item   | `New File Plus: Add File`   | Community |
| Add Folder Context Menu Item | `New File Plus: Add Folder` | Community |

### Pages

| Name                  | Command                         | Keybinding | Note                     |
| --------------------- | ------------------------------- | ---------- | ------------------------ |
| Preferences           | `Application: Show Preferences` | `⌘ ,`      |                          |
|                       | `Application: Show Preferences` |            |                          |
| Welcome               | `Welcome: Show`                 |            | Opens both welcome pages |
| About                 | `Application: About`            |            |                          |
| Incompatible Packages | `Incompatible Packages: View`   |            |                          |
| Timecop               | `Timecop: View`                 |            |                          |

#### Markdown Preview

| Name                     | Command                                  | Keybinding     |
| ------------------------ | ---------------------------------------- | -------------- |
| Invert Confirm           | `Fuzzy Finder: Invert Confirm`           | `⇧ ↵`          |
| Toggle Buffer Finder     | `Fuzzy Finder: Toggle Buffer Finder`     | `⌘ B`          |
| Toggle File Finder       | `Fuzzy Finder: Toggle File Finder`       | `⌘ P` \| `⌘ T` |
| Toggle Git Status Finder | `Fuzzy Finder: Toggle Git Status Finder` | `⇧⌘ B`         |

### Palettes

#### Advanced Open File

| Name                      | Command                      | Keybinding | Note                                            | Package   |
| ------------------------- | ---------------------------- | ---------- | ----------------------------------------------- | --------- |
| Toggle Advanced Open File | `Advanced Open File: Toggle` | `⌥⌘ O`     | Opens interface for opening and creating files. | Community |

#### Command Palette

| Name                   | Command                                 | Keybinding |
| ---------------------- | --------------------------------------- | ---------- |
| Toggle Command Palette | `Command Palette: Toggle`               | `⇧⌘ P`     |
| Show Hidden Commands   | `Command Palette: Show Hidden Commands` |            |

#### Bookmarks

| Name             | Command               | Keybinding |
| ---------------- | --------------------- | ---------- |
| Toggle Bookmarks | `Bookmarks: View All` | `⌘ F2`     |

#### Fuzzy Finder

| Name                     | Command                                  | Keybinding     | Note                                 |
| ------------------------ | ---------------------------------------- | -------------- | ------------------------------------ |
| Toggle Buffer Finder     | `Fuzzy Finder: Toggle Buffer Finder`     | `⌘ B`          | Select Open File.                    |
| Toggle File Finder       | `Fuzzy Finder: Toggle File Finder`       | `⌘ P` \| `⌘ T` | Select Project File.                 |
| Toggle Git Status Finder | `Fuzzy Finder: Toggle Git Status Finder` | `⇧⌘ B`         | Select Modified and Untracked Files. |

#### Go To Line

| Name              | Command              | Keybinding |
| ----------------- | -------------------- | ---------- |
| Toggle Go To Line | `Go To Line: Toggle` | `^ G`      |

#### Grammar Selector

| Name                    | Command                  | Keybinding | Note                                |
| ----------------------- | ------------------------ | ---------- | ----------------------------------- |
| Toggle Grammar Selector | `Grammar Selector: Show` | `^⇧ L`     | Select language or syntax for file. |

#### Git Diff

| Name             | Command                      | Keybinding  |
| ---------------- | ---------------------------- | ----------- |
| Toggle Diff List | `Git Diff: Toggle Diff List` | `⌥ G` + `D` |

#### Git Projects

| Name                | Command                | Keybinding | Package   |
| ------------------- | ---------------------- | ---------- | --------- |
| Toggle Git Projects | `Git Projects: Toggle` | `^⌥ O`     | Community |

#### Line Ending Selector

| Name                        | Command                      |
| --------------------------- | ---------------------------- |
| Toggle Line Ending Selector | `Line Ending Selector: Show` |

#### List Projects

| Name          | Command                          | Keybinding | Note                                                                                                                                     | Package   |
| ------------- | -------------------------------- | ---------- | ---------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| List Projects | `Project Manager: List Projects` | `^⌘ P`     | Projects can be filtered by `title`, `group` and `template` by typing `group: atom` which would give all projects with the `atom` group. | Community |

#### New File Plus

| Name                 | Command                 | Keybinding      | Note                                                     | Package   |
| -------------------- | ----------------------- | --------------- | -------------------------------------------------------- | --------- |
| Toggle New File Plus | `New File Plus: Toggle` | `⌘ N` \| `⌘⌥ N` | Create multiple files at once using `{brace}` expansion! | Community |

#### Snippets

| Name                      | Command               |
| ------------------------- | --------------------- |
| Toggle Available Snippets | `Snippets: Available` |

#### Symbols

| Name                   | Command                                | Keybinding |
| ---------------------- | -------------------------------------- | ---------- |
| Toggle File Symbols    | `Symbols View: Toggle File Symbols`    | `⌘ R`      |
| Toggle Project Symbols | `Symbols View: Toggle Project Symbols` | `⇧⌘ R`     |

#### Tab Control

| Name             | Command             | Package   |
| ---------------- | ------------------- | --------- |
| Show Tab Control | `Tab Control: Show` | Community |

### Panels and Docks

| Name               | Command                      |
| ------------------ | ---------------------------- |
| Toggle Left Dock   | `Window: Toggle Left Dock`   |
| Toggle Bottom Dock | `Window: Toggle Bottom Dock` |
| Toggle Right Dock  | `Window: Toggle Right Dock`  |

#### Atom IDE

| Name                | Command                     | Keybinding | Package   |
| ------------------- | --------------------------- | ---------- | --------- |
| Toggle Console      | `Console: Toggles`          | `⌥⌘ J`     | Community |
| Toggle Diagnostics  | `Diagnostics: Toggle Table` | `⌥⇧ D`     | Community |
| Toggle Outline View | `Outline View: Toggle`      | `⌥ O`      | Community |

#### Codenav

| Name | Command | Keybinding | Package |
| ---- | ------- | ---------- | ---------- |
| Toggle Codenav | `Codenav: Toggle` | `^⌥ O`     | Community |

#### Bars

| Name              | Command              | Keybinding | Package   |
| ----------------- | -------------------- | ---------- | --------- |
| Toggle Status Bar | `Status Bar: Toggle` |            |           |
| Toggle Tool Bar   | `Tool Bar: Toggle`   | `^⌥ T`     | Community |

#### Document Outline

| Name                    | Command                   | Package   |
| ----------------------- | ------------------------- | --------- |
| Toggle Document Outline | Document Outline: Toggles | Community |

#### Editor Stats

| Name                | Command                | Note                                                              | Package   |
| ------------------- | ---------------------- | ----------------------------------------------------------------- | --------- |
| Toggle Editor Stats | `Editor Stats: Toggle` | Display a graph of keyboard and mouse usage for the last 6 hours. | Community |

#### File Bookmark

| Name                       | Command                       | Keybinding | Package   |
| -------------------------- | ----------------------------- | ---------- | --------- |
| Toggle File Bookmark Panel | `File Bookmark: Toggle Panel` | `^⌘ :`     | Community |

#### Find and Replace

| Name                    | Command                          | Keybinding | Note                     |
| ----------------------- | -------------------------------- | ---------- | ------------------------ |
| Toggle Find and Replace | `Find And Replace: Toggle`       |            |                          |
| Show Find and Replace   | `Find And Replace: Show`         | `⌘ F`      | Focuses on Find field    |
| Show Replace            | `Find And Replace: Show Replace` | `⌥⌘ F`     | Focuses on Replace field |

##### Find in Project

| Name                   | Command                | Keybinding |
| ---------------------- | ---------------------- | ---------- |
| Toggle Find in Project | `Project Find: Toggle` |            |
| Show Find in Project   | `Project Find: Show`   | `⇧⌘ F`     |

#### Keybinding Cheatsheet

| Name                         | Command                         | Keybinding | Note                                      | Package   |
| ---------------------------- | ------------------------------- | ---------- | ----------------------------------------- | --------- |
| Toggle Keybinding Cheatsheet | `Keybinding Cheatsheet: Toggle` | `^⌥ /`     | Quickly view and filter atom keybindings. | Community |

#### Key Binding Resolver

| Name                        | Command                        | Keybinding |
| --------------------------- | ------------------------------ | ---------- |
| Toggle Key Binding Resolver | `Key Binding Resolver: Toggle` | `⌘ .`      |

#### Node REPL

| Name             | Command             | Package   |
| ---------------- | ------------------- | --------- |
| Toggle Node REPL | `Node Repl: Toggle` | Community |

#### Notifications

| Name                     | Command                     |
| ------------------------ | --------------------------- |
| Toggle Notifications Log | `Notifications: Toggle Log` |

#### Symbols Navigator

| Name                           | Command                           | Keybinding | Package   |
| ------------------------------ | --------------------------------- | ---------- | --------- |
| Toggle Symbols Navigator       | `Symbols Navigator: Toggle`       | `^⌥ O`     | Community |
| Toggle Symbols Navigator Focus | `Symbols Navigator: Toggle Focus` |            | Community |

### Regex Railroad Diagram

| Name                        | Command                        | Keybinding    | Package   |
| --------------------------- | ------------------------------ | ------------- | --------- |
| Show Regex Railroad Diagram | `Regex Railroad Diagram: Show` | `⌘ R` + `⌘ R` | Community |

#### Source Control

| Name                    | Command                           | Keybinding |
| ----------------------- | --------------------------------- | ---------- |
| Toggle Git Tab          | `GitHub: Toggle Git Tab`          | `^⇧ 9`     |
| Toggle GitHub Tab       | `GitHub: Toggle GitHub Tab`       | `^⇧ 8`     |
| Toggle Git Tab Focus    | `GitHub: Toggle Git Tab Focus`    | `^ 9`      |
| Toggle GitHub Tab Focus | `GitHub: Toggle GitHub Tab Focus` | `^ 8`      |
| Activate Next List      | `GitHub: Activate Next List`      | `⇥`        |
| Activate Previous List  | `GitHub: Activate Previous List`  | `⇧ ⇥`      |
| Close All Diff Views    | `GitHub: Close All Diff Views`    |            |
| Close Empty Diff Views  | `GitHub: Close Empty Diff Views`  |            |

#### Tree View

| Name                   | Command                   | Keybinding                |
| ---------------------- | ------------------------- | ------------------------- |
| Toggle Tree View       | `Tree View: Toggle`       | ``⌘ ` `` \| `⌘ K` + `⌘ B` |
| Toggle Tree View Focus | `Tree View: Toggle Focus` | `^ 0`                     |
| Show Tree View         | `Tree View: Show`         |                           |
| Unfocus Tree View      | `Tree View: Unfocus`      | `⎋`                       |

### Panes

| Name                             | Command                                  | Keybinding                                  | Note                                                                    | Package   |
| -------------------------------- | ---------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------- | --------- |
| Show Next Item                   | `Pane: Show Next Item`                   | `⌥⌘ →` \| `⇧⌘ }` \| `^ ⇟` (Pagedown)        |                                                                         |           |
| Show Previous Item               | `Pane: Show Previous Item`               | `⌥⌘ ←` \| `⇧⌘ {` \| `^ ⇞` (Pageup)          |                                                                         |           |
| Show Item # (1-9)                | `Pane: Show Item #(1-9)`                 | `⌘ #(1-9)`                                  |                                                                         |           |
| Show Next Recently Used Item     | `Pane: Show Next Recently Used Item`     | `^ ⇥`                                       |                                                                         |           |
| Show Previous Recently Used Item | `Pane: Show Previous Recently Used Item` | `^⇧ ⇥`                                      |                                                                         |           |
| Toggle Expose                    | `Expose: Toggle`                         | `⌘⇧ E`                                      | Quick tab overview of open files.                                       | Community |
| Next Expose Item                 |                                          | `⇥`                                         |                                                                         | Community |
| Previous Expose Item             |                                          | `⇧ ⇥`                                       |                                                                         | Community |
| Maximize Pane                    | `Maximize Panes: Maximize`               | `⌘⇧ ↩`                                      | Maximize panes to occupy the entire window without closing other panes. | Community |
| Save Items                       | `Pane: Save Items`                       |                                             |                                                                         |           |
| Close                            | `Pane: Close`                            | `⌘ K` + `⌘ W`                               |                                                                         |           |
| Close Other Items                | `Pane: Close Other Items`                | `⌘ K` + `⌥⌘ W`                              |                                                                         |           |
| Reopen Closed Item               | `Pane: Reopen Closed Item`               | `⇧⌘ T`                                      |                                                                         |           |
| Move Active Item to Top of Stack | `Pane: Move Active Item To Top Of Stack` | `^ ⇥` + `Release ^` \| `^⇧ ⇥` + `Release ^` |                                                                         |           |
| Increase Size                    | `Pane: Increase Size`                    | `⌥⌘ =`                                      |                                                                         |           |
| Decrease Size                    | `Pane: Decrease Size`                    | `⌥⌘ -`                                      |                                                                         |           |

#### Copy Items

| Name                              | Command                                     |
| --------------------------------- | ------------------------------------------- |
| Copy Active Item to Pane Above    | `Window: Copy Active Item To Pane Above`    |
| Copy Active Item to Pane on Right | `Window: Copy Active Item To Pane On Right` |
| Copy Active Item to Pane Below    | `Window: Copy Active Item To Pane Below`    |
| Copy Active Item to Pane on Left  | `Window: Copy Active Item To Pane On Left`  |

#### Focus

| Name                | Command                       | Keybinding    |
| ------------------- | ----------------------------- | ------------- |
| Focus Next Pane     | `Window: Focus Next Pane`     | `⌘ K` + `⌘ N` |
| Focus Previous Pane | `Window: Focus Previous Pane` | `⌘ K` + `⌘ P` |
| Focus Pane Above    | `Window: Focus Pane Above`    | `⌘ K` + `⌘ ↑` |
| Focus Pane on Left  | `Window: Focus Pane On Right` | `⌘ K` + `⌘ →` |
| Focus Pane Below    | `Window: Focus Pane Below`    | `⌘ K` + `⌘ ↓` |
| Focus Pane on Right | `Window: Focus Pane On Left`  | `⌘ K` + `⌘ ←` |

#### Move Items

| Name                               | Command                                     | Keybinding |
| ---------------------------------- | ------------------------------------------- | ---------- |
| Move Item Left                     | `Pane: Move Item Left`                      | `^⇧ ←`     |
| Move Item Right                    | `Pane: Move Item Right`                     | `^⇧ →`     |
| Move Active Item to Panel Above    | `Window: Move Active Item To Pane Above`    |            |
| Move Active Item to Panel on Right | `Window: Move Active Item To Pane On Right` |            |
| Move Active Item to Panel Below    | `Window: Move Active Item To Pane Below`    |            |
| Move Active Item to Panel on Left  | `Window: Move Active Item To Pane On Left`  |            |

#### Split Panes

| Name                             | Command                                  | Keybinding  |
| -------------------------------- | ---------------------------------------- | ----------- |
| Split Up                         | `Pane: Split Up`                         |             |
| Split Right                      | `Pane: Split Right`                      |             |
| Split Down                       | `Pane: Split Down`                       |             |
| Split Left                       | `Pane: Split Left`                       |             |
| Split Up and Copy Active Item    | `Pane: Split Up And Copy Active Item`    | `⌘ K` + `↑` |
| Split Right and Copy Active Item | `Pane: Split Right And Copy Active Item` | `⌘ K` + `→` |
| Split Down and Copy Active Item  | `Pane: Split Down And Copy Active Item`  | `⌘ K` + `↓` |
| Split Left and Copy Active Item  | `Pane: Split Left And Copy Active Item`  | `⌘ K` + `←` |
| Split Up and Move Active Item    | `Pane: Split Up And Move Active Item`    |             |
| Split Right and Move Active Item | `Pane: Split Right And Move Active Item` |             |
| Split Down and Move Active Item  | `Pane: Split Down And Move Active Item`  |             |
| Split Left and Move Active Item  | `Pane: Split Left And Move Active Item`  |             |

#### Tabs

| Name                | Command                       | Keybinding | Note                                    | Package   |
| ------------------- | ----------------------------- | ---------- | --------------------------------------- | --------- |
| Keep Pending Tab    | `Tabs: Keep Pending Tab`      |            | Turns a previewed tab into an open one. |           |
| Pin Active Tab      | `Pinned Tabs: Pin Active`     | `^⌥ P`     | Chrome-style tab pinning.               | Community |
| Close Tab           | `Tabs: Close Tab`             |            |                                         |           |
| Close Tabs to Left  | `Tabs: Close Tabs To Left`    |            |                                         |           |
| Close Tabs to Right | `Tabs: Close Tabs To Right`   |            |                                         |           |
| Close Saved Tabs    | `Tabs: Close Saved Tabs`      |            |                                         |           |
| Close Other Tabs    | `Tabs: Close All Tabs`        |            |                                         |           |
| Close Unpinned Tabs | `Pinned Tabs: Close Unpinned` |            |                                         | Community |
| Close All Tabs      | `Tabs: Close All Tabs`        |            |                                         |           |
| Split Up            | `Tabs: Split Up`              |            |                                         |           |
| Split Right         | `Tabs: Split Right`           |            |                                         |           |
| Split Down          | `Tabs: Split Down`            |            |                                         |           |
| Split Left          | `Tabs: Split Left`            |            |                                         |           |
| Open in New Window  | `Tabs: Open In New Window`    |            |                                         |           |

### Window

| Name                       | Command                                   | Keybinding |
| -------------------------- | ----------------------------------------- | ---------- |
| New Window                 | `Application: New Window`                 | `⇧⌘ N`     |
| Full Screen                | `Window: Toggle Full Screen`              | `^⌘ F`     |
| Zoom                       | `Application: Zoom`                       | `^⌥⌘ M`    |
| Hide                       | `Application: Hide`                       | `⌘ H`      |
| Hide Other Applications    | `Application: Hide Other Applications`    | `⌥⌘ H`     |
| Unhide All Applications    | `Application: Unhide All Applications`    |            |
| Minimize                   | `Application: Minimize`                   | `⌘ M`      |
| Close                      | `Window: Close`                           | `⇧⌘ W`     |
| Bring All Windows to Front | `Application: Bring All Windows to Front` |            |
| Toggle Dev Tools           | `Window: Toggle Dev Tools`                | `⌥⌘ I`     |
| Reload Window              | `Window: Reload`                          | `^⌥⌘ L`    |

---

# Community Packages

## Browser

### Atom Browser

[Atom Packages](https://atom.io/packages/atom-browser) | [Repo](https://github.com/sean-codes/atom-browser)

> Atom-Browser is the plugin to browse the web, preview files, auto-reload, and search Google within Atom

| Name              | Command                  | Keybinding | Note                                                                       |
| ----------------- | ------------------------ | ---------- | -------------------------------------------------------------------------- |
| Toggle            | `Atom Browser: ShowHide` | `⌥⌘ V`     |                                                                            |
| Preview           | `Atom Browser: Preview`  |            | Opens file in browser, can also be opened from right click tree view menu. |
| Search            | `Atom Browser: Search`   | `^⌘ S`     |                                                                            |
| Reload            | `Atom Browser: Reload`   | `⌥⌘ R`     |                                                                            |
| Browser Dev Tools | `Atom Browser: Devtools` | `⌥⌘ X`     |                                                                            |

## Code

### Atom Transpose

[Atom Packages](https://atom.io/packages/atom-transpose) | [Repo](https://github.com/lyfeyaj/atom-transpose)

> Transpose your text. Behave transpose action like Sublime Text 2/3.

| Name      | Command                     | Keybinding      | Note                                          |
| --------- | --------------------------- | --------------- | --------------------------------------------- |
| Transpose | `Atom Transpose: Transpose` | `⌥ T` \| `^⇧ T` | A more fully featured Sublime-like transpose. |

### Connect

#### Livestyle Atom

[Atom Packages](https://atom.io/packages/livestyle-atom) | [Repo](https://github.com/livestyle/atom)

> Atom plugin for Emmet LiveStyle

| Name         | Command                 | Note                                                                                                     |
| ------------ | ----------------------- | -------------------------------------------------------------------------------------------------------- |
| Hide Widget  | LiveStyle: Hide Widget  | Hides the LiveStyle Analyzer code hints in Atom                                                          |
| Show Widget  | LiveStyle: Show Widget  | Shows the LiveStyle Analyzer code hints in Atom                                                          |
| Show Outline | LiveStyle: Show Outline | Display current stylesheet tree and its resolved CSSdisplay current stylesheet tree and its resolved CSS |

### Docblockr

[Atom Packages](https://atom.io/packages/docblockr) | [Repo](https://github.com/nikhilkalige/docblockr)

> A helper package for writing documentation

| Name               | Command                         | Keybinding | Note                                          |
| ------------------ | ------------------------------- | ---------- | --------------------------------------------- |
| Parse Tab          | `Docblockr: Parse Tab`          | `⌥ ⇥`      |                                               |
| Parse Lines        | `Docblockr: Parse Lines`        | `⌥⇧ ↵`     |                                               |
| Parse Enter        | `Docblockr: Parse Enter`        | `⌥ ↵`      |                                               |
| Reparse            | `Docblockr: Reparse`            |            |                                               |
| Join               | `Docblockr: Join`               |            |                                               |
| Wrap Lines         | `Docblockr: Wrap Lines`         |            |                                               |
| Decorate           | `Docblockr: Decorate`           |            | Wraps line in symbols for emphasis.           |
| Decorate Multiline | `Docblockr: Decorate Multiline` |            | Wraps multiple lines in symbols for emphasis. |

#### AtomDocr

[Atom Packages](https://atom.io/packages/atomdocr) | [Repo](https://github.com/GarthDB/atomdocr)

> A helper package for writing AtomDoc style documentation

This is a fork of Docblockr customized for AtomDoc style but it only works on JavaScript and CoffeeScript.

| Name               | Command                        | Keybinding | Note                                          |
| ------------------ | ------------------------------ | ---------- | --------------------------------------------- |
| Parse Tab          | `AtomDocr: Parse Tab`          | `⇥`        |                                               |
| Parse Lines        | `AtomDocr: Parse Lines`        | `⇧ ↵`      |                                               |
| Parse Enter        | `AtomDocr: Parse Enter`        | `↵`        |                                               |
| Reparse            | `AtomDocr: Reparse`            |            |                                               |
| Join               | `AtomDocr: Join`               |            |                                               |
| Wrap Lines         | `AtomDocr: Wrap Lines`         |            |                                               |
| Decorate           | `AtomDocr: Decorate`           |            | Wraps line in symbols for emphasis.           |
| Decorate Multiline | `AtomDocr: Decorate Multiline` |            | Wraps multiple lines in symbols for emphasis. |

### Duplicate Line or Selection

[Atom Packages](https://atom.io/packages/duplicate-line-or-selection) | [Repo](https://github.com/nick/duplicate-line-or-selection)

> Sublime style duplication.

| Name      | Command                                  | Keybinding       | Note                       |
| --------- | ---------------------------------------- | ---------------- | -------------------------- |
| Duplicate | `Duplicate Line or Selection: Duplicate` | `^⇧ D` \| `⇧⌘ D` | Sublime style duplication. |

### EditorConfig

[Atom Packages](https://atom.io/packages/editorconfig) | [Repo](https://github.com/sindresorhus/atom-editorconfig)

> Helps developers maintain consistent coding styles between different editors

#### Supported properties

- `root`
- `indent_style`
- `indent_size` / `tab_width` _(`indent_size` takes precedence over `tab_width`)_
- `charset` _(supported values: `latin1`, `utf-8`, `utf-16be`, `utf-16le`)*
- `end_of_line` *(supported values: `lf`, `crlf`)_
- `trim_trailing_whitespace` _(supported values: `true`, `false`)_
- `insert_final_newline` _(supported values: `true`, `false`; Setting this to `false` strips final newlines)_
- `max_line_length`

| Name            | Command                         | Note                                                                  |
| --------------- | ------------------------------- | --------------------------------------------------------------------- |
| Fix File        | `EditorConfig: Fix File`        | Fixes `indent_style` and `end_of_line` issues for the current editor. |
| Show State      | `EditorConfig: Show State`      | Shows the current state of EditorConfig for your current editor.      |
| Generate Config | `EditorConfig: Generate Config` | Generates an initial `.editorconfig` for your project.                |

### Emmet

[Atom Packages](https://atom.io/packages/emmet) | [Repo](https://github.com/emmetio/emmet-atom)

> Emmet – the essential tool for web developers

#### Note

> Currently, Emmet expands abbreviations by Tab key only for HTML, CSS, Sass/SCSS and LESS syntaxes. Tab handler scope is limited because it overrides default snippets.

| Name                              | Command                                   | Keybinding          | Note                                                                                                                                                      |
| --------------------------------- | ----------------------------------------- | ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Expand Abbreviation               | `Emmet: Expand Abbreviation`              | `⇧⌘ E` \| `^ E`     | Expands [CSS-like abbreviations](https://docs.emmet.io/abbreviations/) into HTML/XML/CSS code, depending on current document’s syntax.                    |
| Expand Abbreviation (Interactive) | `Emmet: Interactive Expand Abbreviation`  | `⌥⌘ ↵` \| `^⌥ ↵`    | Expands [CSS-like abbreviations](https://docs.emmet.io/abbreviations/) into HTML/XML/CSS code, depending on current document’s syntax.                    |
| Expand Abbreviation with Tab      | `Emmet: Expand Abbreviation With Tab`     | `⇥`                 | Expands [CSS-like abbreviations](https://docs.emmet.io/abbreviations/) into HTML/XML/CSS code, depending on current document’s syntax.                    |
| Balance Outward                   | `Emmet: Balance Outward`                  | `^ D` \| `^⇧ E`     | Select outward by context.                                                                                                                                |
| Balance Inward                    | `Emmet: Balance Inward`                   | `⌥ D` \| `^⇧ 0`     | Select inward by context.                                                                                                                                 |
| Go to Matching Pair               | `Emmet: Matching Pair`                    | `^⌥ J`              | Traverse between opening and closing tag:                                                                                                                 |
| Wrap with Abbreviation            | `Emmet: Wrap with Abbreviation`           | `^ W` \| `^⌥ W`     | Takes an [abbreviation](https://docs.emmet.io/abbreviations/), expands it and places currently selected content in the last element of generated snippet. |
| Next Edit Point                   | `Emmet: Next Edit Point`                  | `^ →` \| `^⌥ →`     | Moves cursor to edit points in code by context.                                                                                                           |
| Previous Edit Point               | `Emmet: Prev Edit Point`                  | `^ ←` \| `^⌥ ←`     | Moves cursor to edit points in code by context.                                                                                                           |
| Select Next Item                  | `Emmet: Select Next Item`                 | `^⇧ →` \| `^⇧ .`    | Action is similar to [“Go to Edit Point”](https://docs.emmet.io/actions/go-to-edit-point/), but selects important code parts.                             |
| Select Previous Item              | `Emmet: Select Previous Item`             | `^⇧ ←` \| `^⇧ ,`    | Action is similar to [“Go to Edit Point”](https://docs.emmet.io/actions/go-to-edit-point/), but selects important code parts.                             |
| Toggle Comment                    | `Emmet: Toggle Comment`                   | `⌘ /` \| `^⇧ /`     | When there’s no selection, editor’s action toggles comment on current line while Emmet’s one do this on *current context*.                                |
| Split/Join Tag                    | `Emmet: Split Join Tag`                   | `⇧⌘ J` \| ``^⇧ ` `` | Splits and joins tag definition, e.g. converts from `<tag/>` to `<tag></tag>`.                                                                            |
| Remove Tag                        | `Emmet: Remove Tag`                       | `⌘ '` \| `^⇧ ;`     | Quickly removes tag, found by “[Balance](https://docs.emmet.io/actions/match-pair/)” action from current caret position, and adjusts indentation.         |
| Update Tag                        | `Emmet: Update Tag`                       | `^⇧ U` \| `^⇧ '`    | Rename a tag at both opening and closing tags.                                                                                                            |
| Merge Lines                       | `Emmet: Merge Lines`                      | `⇧⌘ M` \| `^⇧ M`    | Merges selected lines into a single one. But when there’s no selection, Emmet will match context HTML tag.                                                |
| Update Image Size                 | `Emmet: Update Image Size`                | `^ I` \| `^ U`      | Simply place caret inside `<img>` tag and run this action to add/update width and height attributes.                                                      |
| Evaluate Math Expression          | `Emmet: Evaluate Math Expressions`        | `⇧⌘ Y` \| `^⇧ Y`    | Evaluates simple math expression like `2*4` or `10/2` and outputs its result.                                                                             |
| Increment Number by 0.1           | `Emmet: Increment Number By 01`           | `^⌥ ↑` \| `⌥ ↑`     | Increments number under caret by 0.1.                                                                                                                     |
| Decrement Number by 0.1           | `Emmet: Decrement Number By 01`           | `^⌥ ↓` \| `⌥ ↓`     | Decrements number under caret by 0.1.                                                                                                                     |
| Increment Number by 1             | `Emmet: Increment Number By 1`            | `^⌥⌘ ↑` \| `^ ↑`    | Increments number under caret by 1.                                                                                                                       |
| Decrement Number by 1             | `Emmet: Decrement Number By 1`            | `^⌥⌘ ↓` \| `^ ↓`    | Decrements number under caret by 1.                                                                                                                       |
| Increment Number by 10            | `Emmet: Increment Number By 10`           | `^⌥⇧⌘ ↑` \| `⌥⇧ ↑`  | Increments number under caret 10.                                                                                                                         |
| Decrement Number by 10            | `Emmet: Decrement Number By 10`           | `^⌥⇧⌘ ↓` \| `⌥⇧ ↓`  | Decrements number under caret by 10.                                                                                                                      |
| Reflect CSS Value                 | `Emmet: Reflect Css Value`                | `⇧⌘ R` \| `^⇧ R`    | Takes value of CSS property under caret and copies it into vendor-prefixed variations                                                                     |
| Encode/Decode Image to data:URL   | `Emmet: Encode Decode Data URL`           | `^⇧ I` \| `^ '`     | HTML and CSS allows you to embed external resources right into base using [data:URL](http://en.wikipedia.org/wiki/Data_URI_scheme) scheme.                |
| Insert Formatted Line Break       | `Emmet: Insert Formatted Line Break`      |                     |                                                                                                                                                           |
| Insert Formatted Line Break Only  | `Emmet: Insert Formatted Line Break Only` | `↵`                 |                                                                                                                                                           |

### Tabs to Spaces

[Atom Packages](https://atom.io/packages/tabs-to-spaces) | [Repo](https://github.com/lee-dohm/tabs-to-spaces)

> Provides the ability to convert between leading tabs and spaces in a document

| Name         | Command                        | Note                                        |
| ------------ | ------------------------------ | ------------------------------------------- |
| Tabify       | `Tabs to Spaces: Tabify`       | Converts leading whitespace to tabs         |
| Untabify     | `Tabs to Spaces: Untabify`     | Converts leading whitespace to spaces       |
| Untabify All | `Tabs to Spaces: Untabify All` | Converts all whitespace on a line to spaces |

### Tab Control

[Atom Packages](https://atom.io/packages/tab-control) | [Repo](https://github.com/lexicalunit/tab-control)

> Control and view status of indentation settings.

I don't switch my settings often enough to really need the command but I do like seeing the current setting in the status bar so I know what a file I didn't create is set to.

| Name             | Command             |
| ---------------- | ------------------- |
| Show Tab Control | `Tab Control: Show` |

### Toggle Quotes

[Atom Packages](https://atom.io/packages/toggle-quotes) | [Repo](https://github.com/atom/toggle-quotes)

> Quickly toggle between single and double quotes

| Name   | Command                 | Keybinding | Note                                             |
| ------ | ----------------------- | ---------- | ------------------------------------------------ |
| Toggle | `Toggle Quotes: Toggle` | `⌘⇧ '`     | Quickly toggle between single and double quotes. |

## Evaluation

### Eval and Replace

[Atom Packages](https://atom.io/packages/eval-and-replace) | [Repo](https://github.com/MoritzKn/atom-eval-and-replace) | ꐇ Testing

> Execute CoffeeScript, JavaScript or Shell code from the Atom editor and replace the code with the result

| Name                  | Command                      | Keybinding                     |
| --------------------- | ---------------------------- | ------------------------------ |
| Evaluate CoffeeScript | Eval and Replace: Coffee     | `^⇧ E` + `^⇧ C` \| `^K` + `^E` |
| Evaluate JavaScript   | Eval and Replace: JavaScript | `^⇧ E` + `^⇧ J`                |
| Evaluate Shell Script | Eval and Replace: Shell      | `^⇧ E` + `^⇧ S`                |

### Eval JavaScript

[Atom Packages](https://atom.io/packages/eval-javascript) | [Repo](https://github.com/douglascalhoun/eval-javascript) | ꐇ Testing

> Runs JavaScript in Atom

| Name            | Command                            | Keybinding |
| --------------- | ---------------------------------- | ---------- |
| Eval JavaScript | `Eval JavaScript: Eval JavaScript` | `⌘ I`      |

### Evaluate

[Atom Packages](https://atom.io/packages/evaluate) | [Repo](https://github.com/idleberg/atom-evaluate) | ꐇ Testing

> Runs JavaScript, TypeScript, CoffeeScript and LiveScript directly in Atom

| Name     | Command              | Keybinding | Note                 |
| -------- | -------------------- | ---------- | -------------------- |
| Run Code | `Evaluate: Run Code` | `⌥⌘ R`     | Also in context menu |

## Files & Project

### Advanced Open File

[Atom Packages](https://atom.io/packages/advanced-open-file) | [Repo](https://github.com/Osmose/advanced-open-file)

> Open and create files and directories easily. Type in a path (with autocomplete) and view directory contents.

| Name                      | Command                      | Keybinding | Note                                            |
| ------------------------- | ---------------------------- | ---------- | ----------------------------------------------- |
| Toggle Advanced Open File | `Advanced Open File: Toggle` | `⌥⌘ O`     | Opens interface for opening and creating files. |

### File Bookmark

[Atom Packages](https://atom.io/packages/file-bookmark) | [Repo](https://github.com/akalajzi/atom-file-bookmark)

> Bookmark files in your project for quick access

| Name                                | Command                                  | Keybinding |
| ----------------------------------- | ---------------------------------------- | ---------- |
| Add File Bookmark                   | `File Bookmark: Add`                     |            |
| Remove File Bookmark                | `File Bookmark: Remove`                  |            |
| Toggle File Bookmark                | `File Bookmark: Toggle Bookmark`         | `⌘ ;`      |
| Toggle File Bookmark Panel          | `File Bookmark: Toggle Panel`            | `^⌘ :`     |
| Toggle File Bookmark Shortcut Icons | `File Bookmark: Toggle Shortcut Icons`   |            |
| Load Git Modified Files             | `File Bookmark: Load Git Modified Files` |            |

### Git Projects

[Atom Packages](https://atom.io/packages/git-projects) | [Repo](https://github.com/prrrnd/atom-git-projects)

> List and open your local Git projects in Atom.

#### Settings:

| Key               | Default value                                                                  | Possible values                                          |
| ----------------- | ------------------------------------------------------------------------------ | -------------------------------------------------------- |
| `rootPath`        | `~/repos`                                                                      | One or more directories containing projects, sep. by `;` |
| `ignoredPath`     | ``                  | One or more directories containing projects, sep. by `;` |                                                          |
| `ignoredPatterns` | `node_modules;.git`                                                            | One or more patterns to ignore, sep. by `;`              |
| `sortBy`          | `"Project name"`                                                               | `"Project name"`, `"Last modification date"`, `"Size"`   |
| `openInDevMode`   | `false`                                                                        | `true`, `false`                                          |
| `showGitInfo`     | `true`                                                                         | `true`, `false`                                          |
| `maxDepth`        | `5`                                                                            | Max number of directories to traverse from root          |

| Name                  | Command                    | Keybinding |
| --------------------- | -------------------------- | ---------- |
| Toggle Git Projects   | `Git Projects: Toggle`     | `^⌥ O`     |
| Add Project to Window | `GIt Projects: Toggle Add` | `^⌥⇧ O`    |

### Imdone Atom

[Atom Packages](https://atom.io/packages/imdone-atom) | [Repo](https://github.com/imdone/imdone-atom) | ꐇ Testing

> A kanban board with cards and lists that are made from TODOs in your code, markdown and text files.

| Name                    | Command                               | Keybinding |
| ----------------------- | ------------------------------------- | ---------- |
| Tasks                   | `Imdone Atom: Tasks`                  | `⌥ T`      |
| Board Zoom In           | `Imdone Atom: Board Zoom In`          | `⌥ .`      |
| Board Zoom Out          | `Imdone Atom: Board Zoom Out`         | `⌥ ,`      |
| Today's Journal         | `Imdone Atom: Todays Journal`         | `⌥ J`      |
| Today's Project Journal | `Imdone Atom: Todays Project Journal` | `⌥ P`      |

### Imdone Atom Harbour

[Atom Packages](https://atom.io/packages/imdone-atom-harbour) | [Repo](https://github.com/hernad/imdone-atom-harbour) | ꐇ Testing

> A TODO comment task-board that does your issue tracking so you can stay in the zone.

| Name                    | Command                               | Keybinding |
| ----------------------- | ------------------------------------- | ---------- |
| Tasks                   | `Imdone Atom: Tasks`                  | `⌥ T`      |
| Board Zoom In           | `Imdone Atom: Board Zoom In`          | `⌥ .`      |
| Board Zoom Out          | `Imdone Atom: Board Zoom Out`         | `⌥ ,`      |
| Today's Journal         | `Imdone Atom: Todays Journal`         | `⌥ J`      |
| Today's Project Journal | `Imdone Atom: Todays Project Journal` | `⌥ P`      |

### Local History

[Atom Packages](https://atom.io/packages/local-history) | [Repo](https://github.com/Nicolab/atom-local-history)

> Maintaining local history of files (history of your changes to the code files).

| Name                  | Command                              | Note                    |
| --------------------- | ------------------------------------ | ----------------------- |
| Purge Local History   | Local History: Purge                 |                         |
| Current File History  | Local History: Current File          |                         |
| Difftool Current File | Local History: Difftool Current File | Set to use Kaleidoscope |

### New File Plus

[Atom Packages](https://atom.io/packages/new-file-plus) | [Repo](https://github.com/sedabull/new-file-plus)

> Create multiple files at once using {brace} expansion!

#### Examples

> ```
> a{b,c,d}.txt => ab.txt, ac.txt, ad.txt
> a{1..3}.txt => a1.txt, a2.txt, a3.txt
> a{M..P}.txt => aM.txt, aN.txt, aO.txt, aP.txt
> a{b,c{1..3},d}.txt => ab.txt, ac1.txt, ac2.txt, ac3.txt, ad.txt
> a{b..d}{1,2}.txt => ab1.txt, ab2.txt, ac1.txt, ac2.txt, ad1.txt, ad2.txt
> ```

| Name                         | Command                     | Keybinding       | Note                                                     |
| ---------------------------- | --------------------------- | ---------------- | -------------------------------------------------------- |
| Add File Context Menu Item   | `New File Plus: Add File`   |                  |                                                          |
| Add Folder Context Menu Item | `New File Plus: Add Folder` |                  |                                                          |
| Toggle New File Plus         | `New File Plus: Toggle`     | `⌘ N` \| ` ⌘⌥ N` | Create multiple files at once using `{brace}` expansion! |

### Open Recent

[Atom Packages](https://atom.io/packages/open-recent) | [Repo](https://github.com/Zren/atom-open-recent)

> Open recent files in the current window, and recent folders (optionally) in a new window.

| Name                              | Command                            | Note                           |
| --------------------------------- | ---------------------------------- | ------------------------------ |
| Open Recent \*File or Directory\* | `Open Recent: *File or Directory*` | Open recent files and folders. |

### Path Hyperclick

[Atom Packages](https://atom.io/packages/path-hyperclick) | [Repo](https://github.com/wingyplus/path-hyperclick)

> File jumper with hyperclick

### Project Manager

[Atom Packages](https://atom.io/packages/project-manager) | [Repo](https://github.com/danielbrodin/atom-project-manager)

> Project Manager for easy access and switching between projects in Atom.

#### Project Settings

| setting    | Type      | Description                                                                                                                                                                                                                                    | Default                |
| ---------- | --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- |
| `title`    | `string`  | Projects title. Used in the projects list                                                                                                                                                                                                      | `''`                   |
| `paths`    | `array`   | The folders that will open in the tree view. First path is the main one that counts as the project.                                                                                                                                            | `[]`                   |
| `settings` | `Object`  | Enables you to set project specific settings. Everything that goes in the `config.cson` file can go here. It also supports scoped settings.                                                                                                    | `{}`                   |
| `icon`     | `string`  | Icon that shows in the projects list. It's class-based so can either be a class already provided by Atom like `icon-squirrel` or a class of your own. You can find a list of all icons on [octicons.github.com](https://octicons.github.com/). | `'icon-chevron-right'` |
| `devMode`  | `boolean` | `true` if project should open in dev mode. [Look here](https://atom.io/docs/api/v1.11.2/AtomEnvironment#instance-open) for more info.                                                                                                          | `false`                |
| `group`    | `string`  | Adds a group to the projects list that can be used to group and filter projects                                                                                                                                                                | `null`                 |
| `template` | `string`  | If you add a project in the `projects.cson` file without `paths` it will count as a template. This way you can easily share settings between projects                                                                                          | `null`                 |

| Name            | Command                            | Keybinding | Note                                                                                                                                          |
| --------------- | ---------------------------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| List Projects   | `Project Manager: List Projects`   | `^⌘ P`     | Projects can be filtered by `title`, `group` and `template` by typing `group: atom` which would give all projects with the `atom` group.      |
| Edit Project    | `Project Manager: Edit Project`    |            | Open a page where you can edit the current project. It currently only supports certain fields.                                                |
| Save Project    | `Project Manager: Save Project`    |            | Write the title you want to save the project as.                                                                                              |
| Edit Projects   | `Project Manager: Edit Projects`   |            | All projects are saved in a `.cson` file which you can easily reach by searching for `Project Manager: Edit Projects` in the Command Palette. |
| Update Projects | `Project Manager: Update Projects` |            |                                                                                                                                               |

### Promote Folder to Project

[Atom Packages](https://atom.io/packages/promote-folder-to-project) | [Repo](https://github.com/forivall/atom-promote-folder-to-project)

> Add folders to your current project by right clicking on them in the tree view

| Name               | Command                                         | Note                                 |
| ------------------ | ----------------------------------------------- | ------------------------------------ |
| Add Project Folder | `Promote Folder To Project: Add Project Folder` | Add folders to your current project. |

### Prompt Big File

[Atom Packages](https://atom.io/packages/prompt-big-file) | [Repo](https://github.com/ajuste/atom-prompt-big-file)

> Avoid opening big files by accident which might cause Atom to stop responding

The default file threshold is 1Mb but can be changed.

### Set Syntax

[Atom Packages](https://atom.io/packages/set-syntax) | [Repo](https://atom.io/packages/set-syntax)

> Creates easy Command Palette commands for setting the syntax of the current file

| Name                          | Command                     |
| ----------------------------- | --------------------------- |
| Set Syntax to \*Syntax Name\* | `Set Syntax: *Syntax Name*` |

### Todo

[Atom Packages](https://atom.io/packages/todo) | [Repo](https://github.com/reergymerej/todo) | ꐇ Testing

> an Atom package for finding TODO statements

| Name        | Command        | Keybinding    | Note                            |
| ----------- | -------------- | ------------- | ------------------------------- |
| Toggle Todo | `Todo: Toggle` | `^ K` + `^ T` | Opens todo search sidebar list. |

### Todo Show

[Atom Packages](https://atom.io/packages/todo-show) | [Repo](https://github.com/mrodalgaard/atom-todo-show) | ꐇ Testing

> Finds all the TODOs, FIXMEs, CHANGEDs, etc. in your project.

#### Settings

| Name                 | Default                                                                                                            | Description                                                                                                                                                                                                                                                                                                                                                     |
| -------------------- | ------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| *autoRefresh*        | `true`                                                                                                             | Automatic refresh of todo list after saving                                                                                                                                                                                                                                                                                                                     |
| *findTheseTodos*     | `['FIXME', 'TODO', 'CHANGED', 'XXX', 'IDEA', 'HACK', 'NOTE', 'REVIEW', 'NB', 'BUG', 'QUESTION', 'COMBAK', 'TEMP']` | An array of todo types used by the search regex                                                                                                                                                                                                                                                                                                                 |
| *findUsingRegex*     | See 'Regular Expression Search' section                                                                            | Regex string used to find all your todos. `${TODOS}` is replaced with `FindTheseTodos` from above                                                                                                                                                                                                                                                               |
| *ignoreThesePaths*   | `['node_modules', 'vendor', 'bower_components', '*.pdf']`                                                          | An array of files / folders to exclude (syntax according to [scandal](https://github.com/atom/scandal) used internally by Atom). ⚬ *globally*: `Ignored Names` from atom core settings. ⚬ *locally*: Ignores anything in your `.gitignore` file, if the current project is a valid git repository and atom core setting `Exclude VCS Ignored Paths` is checked. |
| *showInTable*        | `['Text', 'Type', 'Path']`                                                                                         | An array of properties to show for each todo in table                                                                                                                                                                                                                                                                                                           |
| *sortBy*             | `'Text'`                                                                                                           | Sort table by this todo property                                                                                                                                                                                                                                                                                                                                |
| *sortAscending*      | `true`                                                                                                             | Sort table in ascending or descending order                                                                                                                                                                                                                                                                                                                     |
| *saveOutputAs*       | `'List'`                                                                                                           | Choose which format to use for saved markdown                                                                                                                                                                                                                                                                                                                   |
| *statusBarIndicator* | `false`                                                                                                            | Show todo count in status bar (this is only shown and updated when the 'Todo Show' tab is open)                                                                                                                                                                                                                                                                 |

| Name                | Command                          | Keybinding |
| ------------------- | -------------------------------- | ---------- |
| Find in Active File | `Todo Show: Find In Active File` |            |
| Find in Open Files  | `Todo Show: Find In Open Files`  |            |
| Find in Workspace   | `Todo Show: Find In Workspace`   |            |
| Find in Project     | `Todo Show: Find In Project`     |            |
| Toggle              | `Todo Show: Toggle`              | `^⇧ T`     |

## IDE Features

### Atom IDE

#### Atom IDE UI

[Atom Packages](https://atom.io/packages/atom-ide-ui) | [Repo](https://github.com/facebook-atom/atom-ide-ui)

> A collection of Atom UIs to support language services.

| Name                            | Command                                        | Keybinding  |
| ------------------------------- | ---------------------------------------------- | ----------- |
| Format Code                     | `Code Format: Format Code`                     | `⇧⌘ C`      |
| Clear Console                   | `Console: Clear`                               | `^ L`       |
| Toggle Console                  | `Console: Toggle`                              | `⌥⌘ J`      |
| Toggle Datatip                  | `Datatip: Toggle`                              | `⌥` \| `⌘⌥` |
| Copy Datatip to Clipboard       | `Datatip: Copy To Clipboard`                   | `^⌥ C`      |
| Toggle Diagnostics              | `Diagnostics: Toggle Table`                    | `⌥⇧ D`      |
| Go to First Diagnostic          | `Diagnostics: Go To First Diagnostic`          | `^⌥⇧ <`     |
| Go to Last Diagnostic           | `Diagnostics: Go To Last Diagnostic`           | `^⌥⇧ >`     |
| Go to Next Diagnostic           | `Diagnostics: Go To Next`                      | `⌥⇧ >`      |
| Go to Previous Diagnostic       | `Diagnostics: Go To Previous`                  | `⌥⇧ <`      |
| Go to Next Diagnostic Trace     | `Diagnostics: Go To Next Diagnostic Trace`     | `⌥⇧⌘ .`     |
| Go to Previous Diagnostic Trace | `Diagnostics: Go To Previous Diagnostic Trace` | `⌥⇧⌘ ,`     |
| Show Code Actions               | `Diagnostics: Show Actions At Position`        | `⌥ A`       |
| Apply Diagnostic Fixes          | `Diagnostics: Fix All In Current File`         | `⌥⇧ A`      |
| Open All Files with Errors      | `Diagnostics: Open All Files With Errors`      |             |
| Find References                 | `Find References: Activate`                    | `⌥⇧⌘ F`     |
| Hyperclick                      | `Hyperclick: Confirm Cursor`                   | `⌥⌘ ↵`      |
| Toggle Outline View             | `Outline View: Toggle`                         | `⌥ O`       |
| View Signature Help             | `Signature Help: View`                         |             |

### Kite

[Home](https://kite.com) | [Atom Packages](https://atom.io/packages/kite) | [Repo](https://github.com/kiteco/atom-plugin)

> Python programming copilot — Kite shows cloud-powered completions, documentation, and examples.

| Name                       | Command                            |
| -------------------------- | ---------------------------------- |
| Open Sidebar               | `Kite: Open Sidebar`               |
| Close Sidebar              | `Kite: Close Sidebar`              |
| Open Settings              | `Kite: Open Settings`              |
| Toggle Sidebar             | `Kite: Toggle Sidebar`             |
| Open Permissions           | `Kite: Open Permissions`           |
| Test Autocorrect UI        | `Kite: Test Autocorrect UI`        |
| Open Autocorrect Sidebar   | `Kite: Open Autocorrect Sidebar`   |
| Close Autocorrect Sidebar  | `Kite: Close Autocorrect Sidebar`  |
| Toggle Autocorrect Sidebar | `Kite: Toggle Autocorrect Sidebar` |

### Contextual Editing

[Atom Packages](https://atom.io/packages/code-peek) | [Repo](https://github.com/DFreds/code-peek-atom)

> Quickly peek and edit functions in separate files from the context of your current editor.

| Name           | Command                        | Keybinding |
| -------------- | ------------------------------ | ---------- |
| Peek Function  | `Code Peek: PeekFunction`      | `⌥⌘ E`     |
| Hide Code Peek | `Code Peek: ToggleCodePeekOff` | `⇧ ⎋`      |

### Formatting

#### Atom Beautify

[Atom Packages](https://atom.io/packages/atom-beautify) | [Repo](https://github.com/Glavin001/atom-beautify)

> Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom

| Name                           | Command                                       | Keybinding | Note              |
| ------------------------------ | --------------------------------------------- | ---------- | ----------------- |
| Beautify Editor                | `Atom Beautify: Beautify Editor`              | `^⌥ B`     | Based on grammar. |
| Beautify Language \*Language\* | `Atom Beautify: Beautify Language *Language*` |            |                   |
| Open Settings                  | `Atom Beautify: Open Settings`                |            |                   |
| Migrate Settings               | `Atom Beautify: Migrate Settings`             |            |                   |
| Help Debug Editor              | `Atom Beautify: Help Debug Editor`            |            |                   |

#### Prettier

[Atom Packages](https://atom.io/packages/prettier-atom) | [Repo](https://github.com/prettier/prettier-atom)

> Atom plugin for formatting JavaScript using prettier with (optional) prettier-eslint integration

| Name   | Command            | Keybinding |
| ------ | ------------------ | ---------- |
| Format | `Prettier: Format` | `^⌥ F`     |

### Linting

#### Linter

[Atom Packages](%7Bclipboad%7D) | [Repo](https://github.com/steelbrain/linter)

> A Base Linter with Cow Powers

| Name                            | Command                        |
| ------------------------------- | ------------------------------ |
| Lint                            | `Linter: Lint`                 |
| Enable Linter                   | `Linter: Enable Linter`        |
| Disable Linter                  | `Linter: Disable Linter`       |
| Toggle Linting in Active Editor | `Linter: Toggle Active Editor` |
| Debug                           | `Linter: Debug`                |

#### Linter UI Default

[Atom Packages](%7Bclipboad%7D) | [Repo](https://github.com/steelbrain/linter-ui-default)

> Default UI for the Linter package

| Name                             | Command                                               | Note                                                                   |     |     |
| -------------------------------- | ----------------------------------------------------- | ---------------------------------------------------------------------- | --- | --- |
| Next                             | `Linter UI Default: Next`                             |                                                                        |     |     |
| Previous                         | `Linter UI Default: Previous`                         |                                                                        |     |     |
| Next Error                       | `Linter UI Default: Next Error`                       |                                                                        |     |     |
| Previous Error                   | `Linter UI Default: Previous Error`                   |                                                                        |     |     |
| Next Warning                     | `Linter UI Default: Next Warning`                     |                                                                        |     |     |
| Previous Warning                 | `Linter UI Default: Previous Warning`                 |                                                                        |     |     |
| Next Info                        | `Linter UI Default: Next Info`                        |                                                                        |     |     |
| Previous Info                    | `Linter UI Default: Previous Info`                    |                                                                        |     |     |
| Apply All Solutions              | `Linter UI Default: Apply All Solutions`              |                                                                        |     |     |
| Next in Current File             | `Linter UI Default: Next In Current File`             |                                                                        |     |     |
| Previous in Current File         | `Linter UI Default: Previous In Current File`         |                                                                        |     |     |
| Next Error in Current File       | `Linter UI Default: Next Error In Current File`       |                                                                        |     |     |
| Previous Error in Current File   | `Linter UI Default: Previous Error In Current File`   |                                                                        |     |     |
| Next Warning in Current File     | `Linter UI Default: Next Warning In Current File`     |                                                                        |     |     |
| Previous Warning in Current File | `Linter UI Default: Previous Warning in Current File` |                                                                        |     |     |
| Next Info in Current File        | `Linter UI Default: Next Info In Current File`        |                                                                        |     |     |
| Previous Info in Current File    | `Linter UI Default: Previous Info In Current File`    |                                                                        |     |     |
| Expand Tooltip                   | `Linter UI Default: Expand Tooltip`                   | This is a placeholder command and has no operation outside of tooltip. |     |     |
| Collapse Tooltip                 | `Linter UI Default: Collapse Tooltip`                 | This is a placeholder command and has no operation outside of tooltip. |     |     |
| Toggle Panel                     | `Linter UI Default: Toggle Panel`                     |                                                                        |     |     |

### Terminal

#### Platformio IDE Terminal

[Atom Packages](https://atom.io/packages/platformio-ide-terminal) | [Repo](https://github.com/platformio/platformio-atom-ide-terminal)

> A terminal package for Atom, complete with themes, API and more for PlatformIO IDE. Fork of terminal-plus.

| Name                       | Command                                              | Keybinding |
| -------------------------- | ---------------------------------------------------- | ---------- |
| New Terminal               | `Platformio Ide Terminal: New`                       | `⇧⌘ T`     |
| Next Terminal              | `Platformio Ide Terminal: Next`                      | ⇧⌘ K       |
| Previous Terminal          | `Platformio Ide Terminal: Prev`                      | `⇧⌘ J`     |
| Copy                       | `Platformio Ide Terminal: Copy`                      | `⌘ C`      |
| Paste                      | `Platformio Ide Terminal: Paste`                     | `⌘ V`      |
| Insert Text                | `Platformio Ide Terminal: Insert Text`               |            |
| Insert Selected Text       | `Platformio Ide Terminal: Insert Selected Text`      | `^ ↵`      |
| Insert Custom Text # (1-8) | `Platformio Ide Terminal: Insert Custom Text #(1-8)` |            |
| Clear Terminal             | `Platformio Ide Terminal: Clear`                     |            |
| Rename Terminal            | `Platformio Ide Terminal: Rename`                    |            |
| Focus Terminal             | `Platformio Ide Terminal: Focus`                     | `⌥⌘ F`     |
| Fullscreen                 | `Platformio Ide Terminal: Fullscreen`                |            |
| Close Terminal             | `Platformio Ide Terminal: Close`                     | `⇧⌘ X`     |
| Close All Terminals        | `Platformio Ide Terminal: Close All`                 |            |
| Toggle Terminal            | `Platformio Ide Terminal: Copy`                      | ``^ ` ``   |

#### Project Shell Env

[Atom Packages](https://atom.io/packages/000-project-shell-env) | [Repo](https://github.com/ddiachkov/atom-project-shell-env)

> Atom package to load shell env variables from project directory

| Name                              | Command                    |
| --------------------------------- | -------------------------- |
| Load Shell Environment Variables  | `Project Shell Env: Load`  |
| Reset Shell Environment Variables | `Project Shell Env: Reset` |

#### Terminal Commands

[Atom Packages](https://atom.io/packages/terminal-commands) | [Repo](https://github.com/UziTech/terminal-commands)

> Setup commands to run in the terminal

Commands should be added to this cheat sheet as they are created.

| Name        | Command                          | Note                                                        |
| ----------- | -------------------------------- | ----------------------------------------------------------- |
| Edit Config | `Terminal Commands: Edit Config` |                                                             |
| Load Config | `Terminal Commands: Load Config` |                                                             |
| \*Command\* | `*Command Prefix*: *Command*`    | You define commands and their prefixes in your config file. |

#### Terminal Tab

[Atom Packages](https://atom.io/packages/terminal-tab) | [Repo](https://github.com/jsmecham/atom-terminal-tab)

> A simple terminal for panes and docks.

| Name              | Command           | Keybinding |
| ----------------- | ----------------- | ---------- |
| Open Terminal     | `Terminal: Open`  | `⇧⌘ T`     |
| Copy in Terminal  | `Terminal: Copy`  | `⌘ C`      |
| Paste in Terminal | `Terminal: Paste` | `⌘ V`      |
| Clear Terminal    | `Terminal: Clear` | `⌘ K`      |

## Language Specific

### AppleScript

#### Language AppleScript

[Atom Packages](https://atom.io/packages/language-applescript) | [Repo](https://github.com/franzheidl/atom-applescript)

> AppleScript language support for Atom. Converted from https://github.com/textmate/applescript.tmbundle.

| Name                  | Command                           | Note                                                                                                                                                                                                                                         |
| --------------------- | --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Decompile AppleScript | `Language Applescript: Decompile` | Mimic the behavior of Apple's [Script Editor](http://help.apple.com/applescript/mac/10.9/#apscrpt1067) by automatically decompiling .scpt files using the native `osadecompile` utility[*](https://atom.io/packages/language-applescript#F1) |
| Recompile AppleScript | `Language Applescript: Recompile` | Mimic the behavior of Apple's [Script Editor](http://help.apple.com/applescript/mac/10.9/#apscrpt1067) by automatically recompiling .scpt files using the native `osacompile` utility[*](https://atom.io/packages/language-applescript#F1)   |

### CSS

#### IDE CSS

[Atom Packages](https://atom.io/packages/ide-css) | [Repo](https://github.com/liuderchi/ide-css)

> Atom-IDE for CSS, LESS and SCSS language

#### Linter Stylelint

[Atom Packages](https://atom.io/packages/linter-stylelint) | [Repo](https://github.com/AtomLinter/linter-stylelint)

> A plugin for Atom Linter providing an interface to stylelint.

#### Less

##### Linter Less

[Atom Packages](https://atom.io/packages/linter-less) | [Repo](https://github.com/josa42/atom-linter-less)

> Lint `less` on the fly, using less

### HTML

#### IDE HTML

[Atom Packages](https://atom.io/packages/ide-html) | [Repo](https://github.com/liuderchi/ide-html)

> Atom-IDE for HTML, Go Template, Mustache and other Templates

| Name          | Command          | Note                                                   |
| ------------- | ---------------- | ------------------------------------------------------ |
| IDE HTML Help | `Ide Html: Help` | Notification with version, FAQ and create issue links. |

#### Linter HTMLHint

[Atom Packages](https://atom.io/packages/linter-htmlhint) | [Repo](https://github.com/AtomLinter/linter-htmlhint)

> A plugin for Atom Linter providing an interface to HTMLHint.

#### Linter Selective

[Atom Packages](https://atom.io/packages/linter-selective) | [Repo](https://github.com/ChristianMurphy/linter-selective)

> Atom bindings for selective

#### Linter Tidy

[Atom Packages](https://atom.io/packages/linter-tidy) | [Repo](https://github.com/AtomLinter/linter-tidy)

> Linter plugin for HTML, using tidy

#### Haml

##### Language Haml

[Atom Packages](https://atom.io/packages/language-haml) | [Repo](https://github.com/HarlemSquirrel/language-haml)

> HAML package for Atom

##### Linter Haml

[Atom Packages](https://atom.io/packages/linter-haml) | [Repo](https://github.com/AtomLinter/linter-haml)

> Atom linter plugin for HAML, using haml-lint

#### Pug

##### Linter Pug

[Atom Packages](https://atom.io/packages/linter-pug) | [Repo](https://github.com/AtomLinter/atom-linter-pug)

> Linter plugin for Pug, using `pug-lint`.

### JavaScript

#### Atom Ternjs

[Atom Packages](https://atom.io/packages/atom-ternjs) | [Repo](https://github.com/tststs/atom-ternjs) | ꐇ Testing

> JavaScript code intelligence for atom with Tern. Adds support for ES5, ES6 (JavaScript 2015), Node.js, jQuery & Angular. Extendable via plugins. Uses suggestion provider by autocomplete-plus.

Project Configuration:

- Open any JavaScript file from within your project
- Navigate to Packages -> Atom Ternjs -> Configure project
- The config view appears.
- Hit "Save & Restart Server" to create/update the .tern-project file

| Name             | Command                      | Keybinding     | Note |
| ---------------- | ---------------------------- | -------------- | ---- |
| Definition       | Atom Ternjs: Definition      | `^⌥⇧ D`        |      |
| Rename           | Atom Ternjs: Rename          | `^⌥ C`         |      |
| Reference        | Atom Ternjs: Reference       | `^⇧ R`         |      |
| Documentation    | Atom Ternjs: Documentation   | `⌥  O`         |      |
| Start Completion | Atom Ternjs: StartCompletion | `^⌥ ␣` (Space) |      |
| Navigate Back    | Atom Ternjs: NavigateBack    | `^⇧⌘ ←`        |      |
| Navigate Forward | Atom Ternjs: NavigateForward | `^⇧⌘ →`        |      |
| List Files       | Atom Ternjs: ListFiles       |                |      |
| Open Config      | Atom Ternjs: OpenConfig      |                |      |
| Flush            | Atom Ternjs: Flush           |                |      |
| Restart          | Atom Ternjs: Restart         |                |      |

#### Codenav

[Atom Packages](https://atom.io/packages/codenav) | [Repo](https://github.com/brumm/codenav)

> do interesting stuff with a javascript file's AST

| Name           | Command           | Keybinding |
| -------------- | ----------------- | ---------- |
| Toggle Codenav | `Codenav: Toggle` | `^⌥ O`     |

#### IDE Flowtype

[Atom Packages](https://atom.io/packages/ide-flowtype) | [Repo](https://github.com/flowtype/ide-flowtype)

> Flow-typed JavaScript support for Atom IDE

#### IDE Typescript

[Atom Packages](https://atom.io/packages/ide-typescript) | [Repo](https://github.com/atom/ide-typescript)

> TypeScript and JavaScript language support for Atom-IDE.

#### Language Babel

[Atom Packages](https://atom.io/packages/language-babel) | [Repo](https://github.com/gandm/language-babel)

> JavaScript ES201x, React JSX, Flow and GraphQL Grammar. Babel Transpiler

#### Language Documentation

[Atom Packages](https://atom.io/packages/language-documentation) | [Repo](https://github.com/DHedgecock/language-documentation)

> Atom grammar package for writing JS documentation

| Name                 | Command                      |
| -------------------- | ---------------------------- |
| Fold All Docblocks   | `Fold Docblocks: Fold All`   |
| Unfold All Docblocks | `Fold Docblocks: Unfold All` |

#### Linter ESLint

[Atom Packages](https://atom.io/packages/linter-eslint) | [Repo](https://github.com/AtomLinter/linter-eslint)

> Lint JavaScript on the fly, using ESLint

#### Linter Flow

[Atom Packages](https://atom.io/packages/linter-flow) | [Repo](https://github.com/AtomLinter/linter-flow)

> Lint JavaScript on the fly, using Flow

#### CoffeeScript

##### Linter Coffeelint

[Atom Packages](https://atom.io/packages/linter-coffeelint) | [Repo](https://github.com/AtomLinter/linter-coffeelint)

> Lint CoffeeScript on the fly, using coffeelint

#### JSON

##### IDE JSON

[Atom Packages](https://atom.io/packages/ide-json) | [Repo](https://github.com/atom/ide-json)

> JSON language support for Atom-IDE

##### Linter JSONLint

[Atom Packages](https://atom.io/packages/linter-jsonlint) | [Repo](https://github.com/AtomLinter/linter-jsonlint)

> A plugin for Atom Linter providing an interface to jsonlint

#### JavaScript for Automation (JXA)

##### Build OSA

[Atom Packages](https://atom.io/packages/build-osa) | [Repo](https://github.com/idleberg/atom-build-osa)

> Atom Build provider for Apple's Open Scripting Architecture, runs or compiles AppleScript and JavaScript for Automation (JXA)

###### Targets:

> Before you can build, select an active target with your preferred build option.

- `AppleScript: Compile Application`
- `AppleScript: Compile Script`
- `AppleScript: Compile Script Bundle`
- `AppleScript: Run Script`
- `JXA: Compile Application`
- `JXA: Compile Script`
- `JXA: Compile Script Bundle`
- `JXA: Run Script`

##### Language JavaScript JXA

[Atom Packages](https://atom.io/packages/language-javascript-jxa) | [Repo](https://github.com/danielbayley/atom-language-javascript-jxa)

> JavaScript for Automation (JXA) language support in Atom.

#### Node

##### Autocomplete Modules

[Atom Packages](https://atom.io/packages/autocomplete-modules) | [Repo](https://github.com/nkt/atom-autocomplete-modules)

> Autocomplete for require/import statements

##### Node Debugger

[Atom Packages](https://atom.io/packages/node-debugger) | [Repo](Debugger For Nodejs)

> https://github.com/kiddkai/atom-node-debugger

| Name              | Command                          | Keybinding |
| ----------------- | -------------------------------- | ---------- |
| Start Resume      | Node Debugger: Start Resume      | F5         |
| Start Active File | Node Debugger: Start Active File | ^ F5       |
| Stop              | Node Debugger: Stop              | ⇧ F5       |
| Toggle Breakpoint | Node Debugger: Toggle Breakpoint | F9         |
| Step Next         | Node Debugger: Step Next         | F10        |
| Step In           | Node Debugger: Step In           | F11        |
| Step Out          | Node Debugger: Step Out          | ⇧ F11      |
| Attach            | Node Debugger: Attach            |            |
| Toggle Debugger   | Node Debugger: Toggle Debugger   | F12        |

##### Node REPL

[Atom Packages](https://atom.io/packages/node-repl) | [Repo](https://github.com/tpae/node-repl)

> JavaScript Read-Eval-Print-Loop (REPL) for Atom

| Name             | Command             |
| ---------------- | ------------------- |
| Toggle Node REPL | `Node Repl: Toggle` |
| Run Node REPL    | `Node Repl: Run`    |
| Clear Node REPL  | `Node Repl: Clear`  |

### Markdown

#### Document Outline

[Atom Packages](https://atom.io/packages/document-outline) | [Repo](https://github.com/mangecoeur/document-outline)

> Show a hierarchical outline of a text document

| Name                    | Command                   |
| ----------------------- | ------------------------- |
| Toggle Document Outline | Document Outline: Toggles |

#### Hyperclick Markdown

[Atom Packages]({clipboad}) | [Repo](https://github.com/ewnd9/hyperclick-markdown)

> Hyperclick markdown provider

#### Language Markdown

[Atom Packages]({clipboad}) | [Repo](https://github.com/burodepeper/language-markdown)

> Adds grammar support for Markdown (including Github flavored, AtomDoc, Markdown Extra, CriticMark, YAML/TOML front-matter, and R Markdown), and smart context-aware behavior to lists, and keyboard shortcuts for inline emphasis.

| Name                       | Command                                | Keybinding    | Note            |
| -------------------------- | -------------------------------------- | ------------- | --------------- |
| Compile Grammar and Reload | `Markdown: Compile Grammar and Reload` |               |                 |
| Image                      | `Markdown: Image`                      | `^⌥ I` \| `!` | Inserts inline. |
| Link                       | `Markdown: Link`                       | `⌘ K` \| `@`  | Inserts inline. |
| Emphasis                   | `Markdown: Emphasis`                   | `_`           |                 |
| Strong                     | `Markdown: Strong Emphasis`            | `*`           |                 |
| Strike Through             | `Markdown: Strike Through`             | `~`           |                 |
| Toggle Task                | `Markdown: Toggle Task`                | `⌥⌘ T`        |                 |
| Indent List Item           | `Markdown: Indent List Item`           | `⇥`           |                 |
| Outdent List Item          | `Markdown: Outdent List Item`          | `⇧ ⇥`         |                 |

#### Linter Markdown

[Atom Packages](https://atom.io/packages/linter-markdown) | [Repo](https://github.com/AtomLinter/linter-markdown)

> Lint markdown on the fly, using remark-lint

#### Markdown Badges Snippets

[Atom Packages](https://atom.io/packages/markdown-badges-snippets) | [Repo](https://github.com/sabertazimi/markdown-badges-snippets/blob/master/snippets/markdown-badges-snippets.cson)

> Awesome markdown snippets for markdown to insert badges elegantly

#### Markdown Folding

[Atom Packages](https://atom.io/packages/markdown-folding) | [Repo](https://atom.io/packages/markdown-folding)

> Folds and unfolds markdown headings

| Name                      | Command                        | Keybinding |
| ------------------------- | ------------------------------ | ---------- |
| Fold Heading              | `Markdown Folding: Cycle`      | `⌥⌘ [`     |
| Fold all Level 1 Headings | `Markdown Folding: Foldall H1` |            |

#### Markdown Table Editor

[Atom Packages](AtomDoc) | [Repo](https://github.com/susisu/atom-markdown-table-editor)

> Markdown table editor/formatter

| Name                  | Command                                        | Keybinding | Note                                     |
| --------------------- | ---------------------------------------------- | ---------- | ---------------------------------------- |
| Next Cell             | `Markdown Table Editor: Next Cell`             | `⇥`        | Move to the next cell                    |
| Previous Cell         | `Markdown Table Editor: Previous Cell`         | `⇧ ⇥`      | Move to the previous cell                |
| Next Row              | `Markdown Table Editor: Next Row`              | `↵`        | Move to the next row                     |
| Move Up               | `Markdown Table Editor: Move Up`               |            | Move to the upper cell                   |
| Move Right            | `Markdown Table Editor: Move Right`            |            | Move to the right cell                   |
| Move Down             | `Markdown Table Editor: Move Down`             |            | Move to the lower cell                   |
| Move Left             | `Markdown Table Editor: Move Left`             |            | Move to the left cell                    |
| Select Cell           | `Markdown Table Editor: Select Cell`           |            | Select the cell content                  |
| Move Row Up           | `Markdown Table Editor: Move Row Up`           |            | Move the row up                          |
| Move Row Down         | `Markdown Table Editor: Move Row Down`         |            | Move the row down                        |
| Move Column Left      | `Markdown Table Editor: Move Column Left`      |            | Move the column left                     |
| Move Column Right     | `Markdown Table Editor: Move Column Right`     |            | Move the column right                    |
| Insert Row            | `Markdown Table Editor: Insert Row`            |            | Insert an empty row                      |
| Delete Row            | `Markdown Table Editor: Delete Row`            |            | Delete the row                           |
| Insert Column         | `Markdown Table Editor: Insert Column`         |            | Insert an empty column                   |
| Delete Column         | `Markdown Table Editor: Delete Column`         |            | Delete the column                        |
| Escape                | `Markdown Table Editor: Escape`                | `⎋`        | Escape from the table                    |
| Align Left            | `Markdown Table Editor: Align Left`            |            | Left-align the column                    |
| Align Center          | `Markdown Table Editor: Align Center`          |            | Center-align the column                  |
| Align Right           | `Markdown Table Editor: Align Right`           |            | Right-align the column                   |
| Align None            | `Markdown Table Editor: Align None`            |            | Unset alignment of the column            |
| Format                | `Markdown Table Editor: Format`                |            | Just format the table                    |
| Format All            | `Markdown Table Editor: Format All`            |            | Format all the tables in the text editor |
| Switch Format Type    | `Markdown Table Editor: Switch Format Type`    |            | Switch "Format Type" config              |
| Toggle Format on Save | `Markdown Table Editor: Toggle Format On Save` |            | Toggle "Format On Save" config           |

#### Markdown Writer

[Atom Packages](https://atom.io/packages/markdown-writer) | [Repo](https://github.com/zhuochun/md-writer)

> Make Atom a better Markdown editor and an easier static blogging tool.

| Name                         | Command                                         | Keybinding  |
| ---------------------------- | ----------------------------------------------- | ----------- |
| New Post                     | `Markdown Writer: New Post`                     |             |
| New Draft                    | `Markdown Writer: New Draft`                    |             |
| Manage Post Tags             | `Markdown Writer: Manage Post Tags`             |             |
| Manage Post Categories       | `Markdown Writer: Manage Post Categories`       |             |
| Publish Draft                | `Markdown Writer: Publish Draft`                |             |
| Open Cheat Sheet             | `Markdown Writer: Open Cheat Sheet`             |             |
| Create Default Keymaps       | `Markdown Writer: Create Default Keymaps`       |             |
| Create Project Configs       | `Markdown Writer: Create Project Configs`       |             |
| Insert New Line              | `Markdown Writer: Insert New Line`              |             |
| Insert Link                  | `Markdown Writer: Insert Link`                  | `⌥⌘ K`      |
| Insert Footnote              | `Markdown Writer: Insert Footnote`              |             |
| Insert Image                 | `Markdown Writer: Insert Image`                 |             |
| Insert Image Clipboard       | `Markdown Writer: Insert Image Clipboard`       |             |
| Insert Image File            | `Markdown Writer: Insert Image File`            |             |
| Insert Table                 | `Markdown Writer: Insert Table`                 |             |
| Toggle H#(1-5)               | `Markdown Writer: Toggle H#(1-5)`               | `⌥⌘ #(1-5)` |
| Toggle Italic Text           | `Markdown Writer: Toggle Italic Text`           | `⌘ I`       |
| Toggle Bold Text             | `Markdown Writer: Toggle Bold Text`             | `⌘ B`       |
| Toggle Code Text             | `Markdown Writer: Toggle Code Text`             | `⌘⌥ C`      |
| Toggle Keystroke Text        | `Markdown Writer: Toggle Keystroke Text`        |             |
| Toggle Strikethrough Text    | `Markdown Writer: Toggle Strikethrough Text`    |             |
| Toggle Blockquote            | `Markdown Writer: Toggle Blockquote`            | `⇧⌘ >`      |
| Toggle Codeblock Text        | `Markdown Writer: Toggle Codeblock Text`        | `^⌘ C`      |
| Toggle Unordered List        | `Markdown Writer: Toggle UL`                    | `⌥⌘ L`      |
| Toggle Ordered List          | `Markdown Writer: Toggle OL`                    | `^⌘ L`      |
| Toggle Task                  | `Markdown Writer: Toggle Task`                  | `^⌘ T`      |
| Toggle Taskdone              | `Markdown Writer: Toggle Taskdone`              |             |
| Indent List Line             | `Markdown Writer: Indent List Line`             |             |
| Format Table                 | `Markdown Writer: Format Table`                 |             |
| Correct Order List Numbers   | `Markdown Writer: Correct Order List Numbers`   |             |
| Open Link in Browser         | `Markdown Writer: Open Link In Browser`         |             |
| Jump to Previous Heading     | `Markdown Writer: Jump to Previous Heading`     |             |
| Jump to Next Heading         | `Markdown Writer: Jump to Next Heading`         |             |
| Jump to Reference Definition | `Markdown Writer: Jump to Reference Definition` |             |
| Jump to Next Table Cell      | `Markdown Writer: Jump to Next Table Cell`      |             |

#### Marked

[Atom Packages](https://atom.io/packages/marked) | [Repo](https://github.com/cliffrowley/atom-marked)

> Opens the current file in Marked.app (Mac only!)

| Name           | Command        | Keybinding |
| -------------- | -------------- | ---------- |
| Open in Marked | `Marked: Open` | `⇧⌘ M`     |

#### Open in iA Writer

[Atom Packages](https://atom.io/packages/open-in-ia-writer) | [Repo](https://github.com/cliffrowley/atom-open-in-ia-writer)

> Open the current file in iA Writer

| Name              | Command                   | Keybinding |
| ----------------- | ------------------------- | ---------- |
| Open in iA Writer | `Open in Ia Writer: Open` | `⇧⌘ I`     |

### Property List (PLIST)

#### Property List Converter

[Atom Packages](https://atom.io/packages/plist-converter) | [Repo](https://github.com/danielbayley/atom-plist-converter)

> Automatically convert binary `.plist` files on macOS.

### Regex

#### Language Regexp

[Atom Packages](https://atom.io/packages/language-regexp) | [Repo](https://github.com/Alhadis/language-regexp)

> Bleeding edge, engine-agnostic highlighting for regular expression data.

#### Regex Railroad Diagram

[Atom Packages](https://atom.io/packages/regex-railroad-diagram) | [Repo](https://github.com/klorenz/atom-regex-railroad-diagrams)

> Display railroad diagram of regex under cursor.

| Name                           | Command                           | Keybinding    |
| ------------------------------ | --------------------------------- | ------------- |
| Show Regex Railroad Diagram    | `Regex Railroad Diagram: Show`    | `⌘ R` + `⌘ R` |
| Enable Regex Railroad Diagram  | `Regex Railroad Diagram: Enable`  |               |
| Disable Regex Railroad Diagram | `Regex Railroad Diagram: Disable` |               |

### Sass

#### Linter Sass Lint

[Atom Packages](https://atom.io/packages/linter-sass-lint) | [Repo](https://github.com/AtomLinter/linter-sass-lint)

> Atom Linter plugin to lint your Sass/SCSS with pure node sass-lint

### Shell

#### Linter Shellcheck

[Atom Packages](https://atom.io/packages/linter-shellcheck) | [Repo](Lint Bash on the fly, using shellcheck)

> https://github.com/AtomLinter/linter-shellcheck

### Swift

#### AutoComplete Swift

[Atom Packages](https://atom.io/packages/autocomplete-swift) | [Repo](https://github.com/steelbrain/autocomplete-swift)

> Autocomplete provider for swift

#### Kitura

[Atom Packages](https://atom.io/packages/kitura) | [Repo](https://github.com/tetodorov/atom-kitura)

> Kitura package for Atom

#### Language Swift

[Atom Packages](https://atom.io/packages/language-swift) | [Repo](https://github.com/freebroccolo/atom-language-swift)

> Swift language support in Atom

#### Language Swif 89

[Atom Packages](https://atom.io/packages/language-swift-89) | [Repo](https://github.com/kelvin13/atom-swift-89)

> Comprehensive Swift syntax highlighting in Atom <3

#### Linter Swift Package Manager

[Atom Packages](https://atom.io/packages/linter-swift-package-manager) | [Repo](https://github.com/pk11/linter-swift-package-manager)

> Lint Swift using Swift Package Manager

#### Linter Swiftc

[Atom Packages](https://atom.io/packages/linter-swiftc) | [Repo](https://github.com/AtomLinter/linter-swiftc)

> Lint Swift using swiftc

#### Linter SwiftLint

[Atom Packages](https://atom.io/packages/linter-swiftlint) | [Repo](https://github.com/AtomLinter/linter-swiftlint)

> Lint Swift files using swiftlint to offer style advice

#### Swift Debugger

[Atom Packages](https://atom.io/packages/swift-debugger) | [Repo](https://github.com/aciidb0mb3r/atom-swift-debugger)

> Develop and Debug swift projects

| Name       | Command                      | Keybinding |
| ---------- | ---------------------------- | ---------- |
| Breakpoint | `Swift Debugger: Breakpoint` | `⌥⇧ R`     |
| Toggle     | `Swift Debugger: Toggle`     | `⌥ R`      |

#### Swiftkit

[Atom Packages](https://atom.io/packages/swiftkit) | [Repo](https://github.com/vdka/atom-swiftkit)

> Code Completion for Swift

### XML

#### Linter xmllint

[Atom Packages](https://atom.io/packages/linter-xmllint) | [Repo](https://github.com/AtomLinter/linter-xmllint)

> Lint XML on the fly, using xmllint

### YAML

#### IDE YAML

[Atom Packages](https://atom.io/packages/ide-yaml) | [Repo](https://github.com/liuderchi/ide-yaml)

> Atom-IDE support for YAML language

| Name          | Command          | Note                                                   |
| ------------- | ---------------- | ------------------------------------------------------ |
| IDE YAML Help | `Ide Yaml: Help` | Notification with version, FAQ and create issue links. |

#### Linter JS Yaml

[Atom Packages](https://atom.io/packages/linter-js-yaml) | [Repo](https://github.com/AtomLinter/linter-js-yaml)

> Linter plugin for YAML, using js-yaml

## Linter

[Atom Packages]({clipboad}) | [Repo](https://github.com/steelbrain/linter)

> A Base Linter with Cow Powers

| Name                            | Command                        |
| ------------------------------- | ------------------------------ |
| Lint                            | `Linter: Lint`                 |
| Enable Linter                   | `Linter: Enable Linter`        |
| Disable Linter                  | `Linter: Disable Linter`       |
| Toggle Linting in Active Editor | `Linter: Toggle Active Editor` |
| Debug                           | `Linter: Debug`                |

### Linter Mixed Indent

[Atom Packages](https://atom.io/packages/linter-mixed-indent) | [Repo](https://github.com/sirbrillig/linter-mixed-indent)

> An Atom editor linter plugin to mark lines that have differing indentation.

### Linter UI Default

[Atom Packages]({clipboad}) | [Repo](https://github.com/steelbrain/linter-ui-default)

> Default UI for the Linter package

## Package Management, Keybindings & Settings

### Auto-Update-Packages

[Atom Packages](https://atom.io/packages/auto-update-packages) | [Repo](https://github.com/yujinakayama/atom-auto-update-packages)

> Keep your Atom packages up to date.

Auto updates Atom packages every six hours or by a set interval.

| Name                | Command                            |
| ------------------- | ---------------------------------- |
| Update Packages Now | `Auto Update Packages: Update Now` |

### Keybinding Cheatsheet

[Atom Packages](https://atom.io/packages/keybinding-cheatsheet) | [Repo](https://github.com/jkasky/atom-keybinding-cheatsheet)

> Quickly view and filter atom keybindings.

| Name                         | Command                         | Keybinding | Note                                      |
| ---------------------------- | ------------------------------- | ---------- | ----------------------------------------- |
| Toggle Keybinding Cheatsheet | `Keybinding Cheatsheet: Toggle` | `^⌥ /`     | Quickly view and filter atom keybindings. |

### Sync Settings

[Atom Packages](https://atom.io/packages/sync-settings) | [Repo](https://github.com/atom-community/sync-settings)

> Synchronize package settings, keymap and installed packages

This package uses a GitHub Gist to sync your settings and requires a Personal Access Token for GitHub and a Gist ID to use.

| Name                  | Command                       | Note                                                 |
| --------------------- | ----------------------------- | ---------------------------------------------------- |
| Fork Settings         | `Sync Settings: Fork`         | Fork existing settings from a different GitHub user. |
| Backup Settings       | `Sync Settings: Backup`       | Backup all settings.                                 |
| Restore Settings      | `Sync Settings: Restore`      | Restore all settings.                                |
| View Settings Backup  | `Sync Settings: View Backup`  | View your online backup.                             |
| Check Settings Backup | `Sync Settings: Check Backup` | Check the latest backup is applied.                  |

## Platform Specific

### Sketch

#### Language Sketchplugin

[Atom Packages](https://atom.io/packages/language-sketchplugin) | [Repo](https://github.com/daneden/language-sketchplugin)

> Correct syntax highlighting for .sketchplugin files

| Name                         | Command                         | Keybinding |
| ---------------------------- | ------------------------------- | ---------- |
| Toggle Sketchplugin Language | `Language-Sketchplugin: Toggle` | `^⌥ O`     |

#### Sketchapp Scripter

[Atom Packages](https://atom.io/packages/sketchapp-scripter) | [Repo](https://github.com/timuric/sketchapp-scripter)

> Run scketch scripts from Atom

| Name              | Command                        | Keybinding |
| ----------------- | ------------------------------ | ---------- |
| Run Sketch Script | `Sketchapp Scripter RunScript` | `^ R`      |

## Reference

### Dash

[Atom Packages](https://atom.io/packages/dash) | [Repo](https://github.com/blakeembrey/atom-dash)

> Dash documentation integration with Atom

| Name                                      | Command                          | Keybinding         | Note                                                              |
| ----------------------------------------- | -------------------------------- | ------------------ | ----------------------------------------------------------------- |
| Search Dash by Language                   | `Dash: Shortcut`                 | `^ H`              | This uses a scoped search based on the filename and syntax.       |
| Search Dash                               | `Dash: Shortcut Alt`             | ` ^⌥⇧ H` \| `^⌥ H` | Search all documentation across grammars.                         |
| Search Dash by Language in the Background | `Dash: Shortcut Background`      | `^⇧ H`             | Same as shortcut but in the background.                           |
| Search Dash in the Background             | `Dash:  Shortcut Alt Background` |                    | Same as shortcut alt but in the background.                       |
| Search Dash Context Menu Item             | `Dash: Context Menu`             |                    | Seems to be same as shortcut, there is a right click menu option. |

## Scripts & Task Runners

### Script

[Atom Packages](https://atom.io/packages/script) | [Repo](https://github.com/rgbkrk/atom-script)

> Run code in Atom!

For a list of supported grammars and dependencies open settings, package or repo.

| Name               | Command                      | Keybinding   | Note                                                                          |
| ------------------ | ---------------------------- | ------------ | ----------------------------------------------------------------------------- |
| Run                | `Script: Run`                | `⌘ I`        | If text is selected a "Selection Based" is used instead of a "File Based" run |
| Run by Line Number | `Script: Run by Line Number` | `⇧⌘ J`       | If text is selected the line number will be the last                          |
| Run Options        | `Script: Run Options`        | `⇧⌘ I`       | Runs the selection or whole file with the given options                       |
| Run with Profile   | `Script: Run with Profile`   | `⇧⌘ K`       | Runs the selection or whole file with the specified profile                   |
| Close View         | `Script: Close View`         | `⎋` \| `^ W` | Closes the script view window                                                 |
| Kill Process       | `Script: Kill Process`       | `^ C`        | Kills the current script process                                              |

## Snippets

### Atomizr

[Atom Packages](https://atom.io/packages/atomizr) | [Repo](https://github.com/idleberg/atom-atomizr)

> Converts snippets for Atom, Sublime Text, TextMate, and Visual Studio Code

| Name                                               | Command                                               | Keybinding    |
| -------------------------------------------------- | ----------------------------------------------------- | ------------- |
| Toggle Atom Format                                 | `Atomizr: Toggle Atom Format`                         | `^ A` + `^ A` |
| Automatic Snippet Conversion                       | `Atomizr: Automatic Conversion`                       | `^ C` + `^ C` |
| Sublime Text Snippet Subformat                     | `Atomizr: Sublime Subformat`                          | `^ S` + `^ S` |
| Convert Atom Snippet to Sublime Text               | `Atomizr: Convert Atom to Sublime Text`               | `^ A` + `^ S` |
| Convert Atom Snippet to TextMate                   | `Atomizr: Convert Atom to Textmate`                   | `^ A` + `^ T` |
| Convert Atom Snippet to Visual Studio Code         | `Atomizr: Convert Atom to Visual Studio Code`         | `^ A` + `^ V` |
| Convert Sublime Text Snippet to Atom               | `Atomizr: Convert Sublime Text to Atom`               | `^ S` + `^ A` |
| Convert Sublime Text Snippet to Textmate           | `Atomizr: Convert Sublime Text to Textmate`           | `^ S` + `^ T` |
| Convert Sublime Text Snippet to Visual Studio Code | `Atomizr: Convert Sublime Text to Visual Studio Code` | `^ A` + `^ V` |
| Convert TextMate Snippet to Atom                   | `Atomizr: Convert Textmate to Atom`                   | `^ T` + `^ A` |
| Convert Textmate Snippet to Sublime Text           | `Atomizr: Convert Textmate to Sublime Text`           | `^ T` + `^ S` |
| Convert Textmate Snippet to Visual Studio Code     | `Atomizr: Convert Textmate to Visual Studio Code`     | `^ T` + `^ V` |
| Convert Visual Studio Code Snippet to Atom         | `Atomizr: Convert Visual Studio Code to Atom`         | `^ V` + `^ A` |
| Convert Visual Studio Code Snippet to Sublime Text | `Atomizr: Convert Visual Studio Code to Sublime Text` | `^ V` + `^ S` |
| Convert Visual Studio Code Snippet to Textmate     | `Atomizr: Convert Visual Studio Code to Textmate`     | `^ V` + `^ T` |
| Open Atomizr Package Settings                      | `Atomizr: Open Package Settings`                      |               |

## Source Control

### Open Project in Tower

[Atom Packages](https://atom.io/packages/open-project-in-tower) | [Repo](https://github.com/jwohlfeil/atom-open-project-in-tower)

> Open current project in Tower

| Name                  | Command                       | Keybinding | Note                           |
| --------------------- | ----------------------------- | ---------- | ------------------------------ |
| Open Project in Tower | `Open Project In Tower: Open` | `^⌥ R`     | Open current project in Tower. |

## Text Editor

### Block Travel

[Atom Packages](https://atom.io/packages/block-travel) | [Repo](https://github.com/efatsi/block-travel)

> Quickly travel up/down between blocks of code

| Name                 | Command                     | Keybinding | Note                                          |
| -------------------- | --------------------------- | ---------- | --------------------------------------------- |
| Move Up by Block     | `Block Travel: Move Up`     | `⌥ ↑`      | Travel up through blocks of code              |
| Move Down by Block   | `Block Travel: Move Down`   | `⌥ ↓`      | Travel down through blocks of code            |
| Select Up by Block   | `Block Travel: Select Up`   | `⇧⌥ ↑`     | Travel and select up through blocks of code   |
| Select Down by Block | `Block Travel: Select Down` | `⇧⌥ ↓`     | Travel and select down through blocks of code |

### Cursor History

[Atom Packages](https://atom.io/packages/cursor-history) | [Repo](https://atom.io/packages/cursor-history)

> Cursor position history manager

| Name                                  | Command                              | Keybinding | Note                                                   |
| ------------------------------------- | ------------------------------------ | ---------- | ------------------------------------------------------ |
| Next Cursor History                   | `Cursor History: Next`               | `^⌥ R`     | Go to next point in history.                           |
| Previous Cursor History               | `Cursor History: Prev`               | `^ =`      | Go to previous point in history.                       |
| Next Cursor History Within Editor     | `Cursor History: Next Within Editor` | `^⌘ -`     | Go to next point in history within current editor.     |
| Previous Cursor History Within Editor | `Cursor History: Prev Within Editor` | `^⌘ =`     | Go to previous point in history within current editor. |
| Clear Cursor History                  | `Cursor History: Clear`              |            |                                                        |

### Highlight Line

[Atom Packages](https://atom.io/packages/highlight-line) | [Repo](https://github.com/richrace/highlight-line)

> Highlights the current line in the editor

| Name                                                   | Command                                           | Keybinding |
| ------------------------------------------------------ | ------------------------------------------------- | ---------- |
| Toggle Current Line Underline Highlight                | `Highlight Line: Toggle Underline`                | `⇧⌘ U`     |
| Toggle Current Line Background Highlight               | `Highlight Line: Toggle Background`               | `⌥⇧⌘ U`    |
| Toggle Current Line Selection Borders Highlight        | `Highlight Line: Toggle Selection Borders`        | `⌥⇧⌘ H`    |
| Toggle Hide Current Line Highlight on Select Highlight | `Highlight Line: Toggle Hide Highlight On Select` | `⌥⇧⌘ H`    |

### Highlight Selected

[Atom Packages](https://atom.io/packages/highlight-selected) | [Repo](https://github.com/richrace/highlight-selected)

> Highlights the current word selected when double clicking

| Name                      | Command                      | Keybinding |
| ------------------------- | ---------------------------- | ---------- |
| Toggle Highlight Selected | `Highlight Selected: Toggle` | `^⌘ H`     |

### Indent Guide Improved

[Atom Packages](https://atom.io/packages/indent-guide-improved) | [Repo](https://github.com/harai/indent-guide-improved)

> This draws indent guide more correctly and understandably.

### Jumpy

[Atom Packages](https://atom.io/packages/jumpy) | [Repo](https://github.com/DavidLGoldberg/jumpy)

> An Atom package that creates dynamic hotkeys to jump around files across visible panes.

| Name         | Command         | Keybinding                     | Note                                      |
| ------------ | --------------- | ------------------------------ | ----------------------------------------- |
| Toggle Jumpy | `Jumpy: Toggle` | `⇧ ↩`                          | Toggle dynamic hotkeys to navigate panes. |
| Reset Jumpy  | `Jumpy: Reset`  | `⌫`                            |                                           |
| Clear Jumpy  | `Jumpy: Clear`  | `↩`, `⎋`, `⇧ ↩` \| `␣` (Space) |                                           |

### Pigmets

[Atom Packages](https://atom.io/packages/pigments) | [Repo](https://github.com/abe33/atom-pigments)

> A package to display colors in project and files.

| Name                                | Command                         | Note                                                             |
| ----------------------------------- | ------------------------------- | ---------------------------------------------------------------- |
| Show Palette                        | `Pigments: Show Palette`        | Shows a global color palette for project.                        |
| Find Colors                         | `Pigments: Find Colors`         | Search for all of the colors in project.                         |
| Convert Color To \*Format\*         | `Pigments: Convert To *Format*` | Converts color to Hex, HSL/HSLA and RGB/RGBA.                    |
| Copy Color As \*Format\*            | `Pigments: Copy as *Format*`    | Copy color as Hex, HSL/HSLA and RGB/RGBA.                        |
| Pigments Project Settings           | `Pigments: Project-Settings`    | Open project specific Pigments settings.                         |
| Reload Pigments                     | `Pigments: Reload`              | Force reload all Pigments variables for the project.             |
| Generate Information for Bug Report | `Pigments: Report`              | Generates a JSON array of information for a Pigments bug report. |

### Sublime Style Column Selection

[Atom Packages](https://atom.io/packages/Sublime-Style-Column-Selection) | [Repo](https://github.com/bigfive/atom-sublime-select)

> Enable Sublime style 'Column Selection'. Just hold 'alt' while you select, or select using your middle mouse button. Also similar to Texmate's 'Multiple Carets', or BBEdit's 'Block Select'

| Name          | Keybinding         | Note                              |
| ------------- | ------------------ | --------------------------------- |
| Column Select | `⌥` + `Left Click` | Sublime style 'Column Selection.' |

## Theme

### File Icons

[Atom Packages](https://atom.io/packages/file-icons) | [Repo](https://github.com/file-icons/atom)

> Assign file extension icons and colours for improved visual grepping

## Tracking & Productivity

### Editor Stats

[Atom Packages](https://atom.io/packages/editor-stats) | [Repo](https://github.com/atom/editor-stats)

> Display a graph of keyboard and mouse usage for the last 6 hours.

| Name                | Command                | Note                                                              |
| ------------------- | ---------------------- | ----------------------------------------------------------------- |
| Toggle Editor Stats | `Editor Stats: Toggle` | Display a graph of keyboard and mouse usage for the last 6 hours. |

### WakaTime

[Atom Packages](https://atom.io/packages/wakatime) | [Repo](https://github.com/wakatime/atom-wakatime)

> Fitbit for programmers. Get automated metrics and insights about your programming.

## UI

### Ctags Status

[Atom Packages]( Repo) | [Repo](https://github.com/mrkschan/ctags-status)

> Show the class/function/scope name of the current line on the status bar.

### Expose

[Atom Packages](https://atom.io/packages/expose) | [Repo](https://github.com/mrodalgaard/atom-expose)

> Quick tab overview of open files

| Name                 | Command          | Keybinding | Note                              |
| -------------------- | ---------------- | ---------- | --------------------------------- |
| Toggle Expose        | `Expose: Toggle` | `⌘⇧ E`     | Quick tab overview of open files. |
| Next Expose Item     |                  | `⇥`        |                                   |
| Previous Expose Item |                  | `⇧ ⇥`      |                                   |

### Hyperclick

[Atom Packages]({clipboad}) | [Repo](https://github.com/facebook-atom/hyperclick)

> Pluggable text-clicking UI for Atom

| Name           | Command                      | Keybinding            | Note                 |
| -------------- | ---------------------------- | --------------------- | -------------------- |
| Confirm Cursor | `Hyperclick: Confirm Cursor` | `⌥⌘ ↵`                | Executes hyperclick. |
| Trigger Key    |                              | `⌥⌘ Left Mouse Click` |                      |

### Hyperlink Hyperclick

[Atom Packages](https://atom.io/packages/hyperlink-hyperclick) | [Repo](https://github.com/UziTech/hyperlink-hyperclick)

> Hyperlink plugin for the Atom Hyperclick package

### Line Count Status

[Atom Packages](https://atom.io/packages/line-count-status) | [Repo](https://github.com/olmokramer/atom-line-count-status)

> Line counter in the status bar

### Maximize Panes

[Atom Packages](https://atom.io/packages/maximize-panes) | [Repo](https://github.com/santip/maximize-panes)

> Maximize panes to occupy the entire window without closing other panes

| Name          | Command                    | Keybinding | Note                                                                    |
| ------------- | -------------------------- | ---------- | ----------------------------------------------------------------------- |
| Maximize Pane | `Maximize Panes: Maximize` | `⌘⇧ ↩`     | Maximize panes to occupy the entire window without closing other panes. |

### Menu Manager

[Atom Packages](https://atom.io/packages/menu-manager) | [Repo](https://github.com/jerone/menu-manager)

> Menu Manager shows main menu items and all context menu items from Atom.

| Name              | Command              | Note                                                                     |
| ----------------- | -------------------- | ------------------------------------------------------------------------ |
| Show Menu Manager | `Menu Manager: Show` | Menu Manager shows main menu items and all context menu items from Atom. |

### Minimap

[Atom Packages](https://atom.io/packages/minimap) | [Repo](https://github.com/atom-minimap/minimap)

> A preview of the full source code.

| Name                               | Command                               | Note                               |
| ---------------------------------- | ------------------------------------- | ---------------------------------- |
| Toggle Minimap                     | `Minimap: Toggle`                     | A preview of the full source code. |
| Generate Minimap Babel Plugin      | `Minimap: Generate Babel Plugin`      | For developing a minimap plugin.   |
| Generate Minimap Coffee Plugin     | `Minimap: Generate Coffee Plugin`     | For developing a minimap plugin.   |
| Generate Minimap Javascript Plugin | `Minimap: Generate Javascript Plugin` | For developing a minimap plugin.   |

#### Minimap Bookmarks

[Atom Packages](https://atom.io/packages/minimap-bookmarks) | [Repo](https://github.com/atom-minimap/minimap-bookmarks)

> Displays Atom bookmarks in the minimap

| Name                     | Command                     |
| ------------------------ | --------------------------- |
| Toggle Minimap Bookmarks | `Minimap: Toggle Bookmarks` |

#### Minimap Codeglance

[Atom Packages](https://atom.io/packages/minimap-codeglance) | [Repo](https://github.com/olmokramer/atom-minimap-codeglance)

> Codeglance like functionality for Atom

| Name                      | Command                      |
| ------------------------- | ---------------------------- |
| Toggle Minimap Codeglance | `Minimap: Toggle Codeglance` |

#### Minimap Cursorline

[Atom Packages](https://atom.io/packages/minimap-cursorline) | [Repo](https://github.com/atom-minimap/minimap-cursorline)

> Displays Atom cursorline in the minimap

| Name                      | Command                      |
| ------------------------- | ---------------------------- |
| Toggle Minimap Cursorline | `Minimap: Toggle Cursorline` |

#### Minimap Find and Replace

[Atom Packages](https://atom.io/packages/minimap-find-and-replace) | [Repo](https://github.com/atom-minimap/minimap-find-and-replace)

> Minimap bindings for the find and replace package

| Name                            | Command                            |
| ------------------------------- | ---------------------------------- |
| Toggle Minimap Find and Replace | `Minimap: Toggle Find and Replace` |

#### Minimap Git Diff

[Atom Packages](https://atom.io/packages/minimap-git-diff) | [Repo](https://github.com/atom-minimap/minimap-git-diff)

> A minimap binding for the git diff package

| Name                    | Command                    |
| ----------------------- | -------------------------- |
| Toggle Minimap Git Diff | `Minimap: Toggle Git Diff` |

#### Minimap Highlight Selected

[Atom Packages](https://atom.io/packages/minimap-highlight-selected) | [Repo](https://github.com/atom-minimap/minimap-highlight-selected)

> A minimap binding for the highlight-selected package

| Name                              | Command                              |
| --------------------------------- | ------------------------------------ |
| Toggle Minimap Highlight Selected | `Minimap: Toggle Highlight Selected` |

#### Minimap Linter

[Atom Packages](https://atom.io/packages/minimap-linter) | [Repo](https://github.com/AtomLinter/atom-minimap-linter)

> Minimap display for Linter messages

| Name                  | Command                  |
| --------------------- | ------------------------ |
| Toggle Minimap Linter | `Minimap: Toggle Linter` |

#### Minimap Pigments

[Atom Packages](https://atom.io/packages/minimap-pigments) | [Repo](https://github.com/abe33/minimap-pigments)

> An Atom plugin to display pigments colors in the Minimap.

| Name                    | Command                    |
| ----------------------- | -------------------------- |
| Toggle Minimap Pigments | `Minimap: Toggle Pigments` |

#### Minimap Selection

[Atom Packages](https://atom.io/packages/minimap-selection) | [Repo](https://github.com/atom-minimap/minimap-selection)

> Display the buffer's selections on the minimap

| Name                     | Command                     |
| ------------------------ | --------------------------- |
| Toggle Minimap Selection | `Minimap: Toggle Selection` |

#### Minimap Split Diff

[Atom Packages](https://atom.io/packages/minimap-split-diff) | [Repo](https://github.com/mupchrch/minimap-split-diff)

> A minimap plugin for the Split Diff package

| Name                      | Command                      |
| ------------------------- | ---------------------------- |
| Toggle Minimap Split Diff | `Minimap: Toggle Split Diff` |

### Move Status Items

[Atom Packages](https://atom.io/packages/move-status-items) | [Repo](https://github.com/olmokramer/atom-move-status-items)

> Reorder status bar items by dragging them with the mouse

### Pinned Tabs

[Atom Packages](https://atom.io/packages/pinned-tabs) | [Repo](https://github.com/ericcornelissen/pinned-tabs-for-atom)

> An Atom package that allows you to pin tabs

| Name                | Command                       | Keybinding | Note                      |
| ------------------- | ----------------------------- | ---------- | ------------------------- |
| Pin Active Tab      | `Pinned Tabs: Pin Active`     | `^⌥ P`     | Chrome-style tab pinning. |
| Close Unpinned Tabs | `Pinned Tabs: Close Unpinned` |            |                           |

### Rename Tabs

[Atom Packages](https://atom.io/packages/rename-tabs) | [Repo](https://github.com/jprichardson/atom-rename-tabs)

> Rename tabs titles with previous directory. Consistent with Sublime Text Editor behavior.

> Renames your Atom Text Editor tab titles to more useful names if there are many instances of the same file name open. This is consistent with Sublime Text editor tab title behavior.
>
> Atom's tab naming isn't very helpful if there are multiple files with the same name open. This package is useful if you write Node.js app with a lot of files named `index.js`. Atom would title the tabs `index.js - /my/project...`. That's not very helpful. Assuming you have two files: `/my/project/foo/index.js` and`/my/project/bar/index.js` the tabs to `index.js - foo` and `index.js - bar` respectively.
>
> To be clear, this isn't only for Node.js developers. This is for those who like Sublime Text editor's tab title convention.

### Symbols Navigator

[Atom Packages](https://atom.io/packages/symbols-navigator) | [Repo](https://github.com/lejsue/symbols-navigator)

> A symbols navigator to explore symbols in the current file

| Name                           | Command                           | Keybinding |
| ------------------------------ | --------------------------------- | ---------- |
| Toggle Symbols Navigator       | `Symbols Navigator: Toggle`       | `^⌥ O`     |
| Toggle Symbols Navigator Focus | `Symbols Navigator: Toggle Focus` |            |

### Tab Title

[Atom Packages](https://atom.io/packages/tab-title) | [Repo](https://github.com/erikjansson/atom-tab-title)

> Give your unsaved tabs better names. Because "Untitled" is about as useful as dinosaur repellent.

> The behavior is heavily inspired from Sublime Text.

Basically just mirrors the beginning of the text in the editor until you give it a real filename.

### Tool Bar

[Atom Packages](https://atom.io/packages/tool-bar) | [Repo](https://github.com/suda/tool-bar)

> Package providing customizable tool bar

| Name                     | Command                     | Keybinding |
| ------------------------ | --------------------------- | ---------- |
| Toggle Tool Bar          | `Tool Bar: Toggle`          | `^⌥ T`     |
| Position Tool Bar Top    | `Tool Bar: Position Top`    |            |
| Position Tool Bar Left   | `Tool Bar: Position Left`   |            |
| Position Tool Bar Right  | `Tool Bar: Position Right`  |            |
| Position Tool Bar Bottom | `Tool Bar: Position Bottom` |            |

### Toolbar Almighty

[Atom Packages](https://atom.io/packages/tool-bar-almighty) | [Repo](https://github.com/varemenos/atom-toolbar-almighty)

> A tool-bar plugin that adds an 'almighty toolbar' with many commonly used actions

I've used this to customize the toolbar pretty heavily, it works better than customizing the Tool Bar package directly.

### Tree View Filter

[Atom Packages](https://atom.io/packages/tree-view-filter) | [Repo](https://github.com/monsterkodi/tree-view-filter)

> Limits files in the tree-view to those matching certain patterns

> Press `ctrl-alt-shift-f` or invoke `Tree View Filter:Activate` to focus the filter editor, enter your pattern and press `enter`/`return` to confirm.
>
> The filter shows only files that match the provided pattern(s): e.g. `md coffee` shows all files that have _md_ or _coffee_ in their filename.
>
> You can reverse the search by prepending an exclamation mark: e.g. `!*.md !.*` hides all _markdown_ and _dotfiles.
>
> Note that the `Fuzzy search` option only works in the first case.
>
> To restore the tree view to its unfiltered state:
> either press `escape` when the filter has focus or click on the `(x)` button to the right.

| Name                      | Command                      | Keybinding | Note                                                              |
| ------------------------- | ---------------------------- | ---------- | ----------------------------------------------------------------- |
| Activate Tree View Filter | `Tree View Filter: Activate` | `^⌥⇧ F`    | Limits files in the tree-view to those matching certain patterns. |
| Toggle Tree View Filter   | `Tree View Filter: Toggle`   | `⌥⇧⌘ F`    | Toggle tree view filter UI.                                       |

## Utilities & Dependencies

### Busy Signal

[Atom Packages](https://atom.io/packages/busy-signal) | [Repo](https://github.com/steelbrain/busy-signal) | Dependency for [Linter](#linter)

> A package that provides an easy to use API to show your package is performing a task

### Intentions

[Atom Packages](https://atom.io/packages/intentions) | [Repo](https://github.com/steelbrain/intentions) | Dependency or [Linter](#linter)

> Base package for showing intentions in Atom

| Name                 | Command                 | Keybinding | Note                         |
| -------------------- | ----------------------- | ---------- | ---------------------------- |
| Hide Intentions      | `Intentions: Hide`      |            |                              |
| Show Intentions      | `Intentions: Show`      | `^ ↵`      | Trigger list of intentions   |
| Highlight Intentions | `Intentions: Highlight` | `⌥`        | Trigger intentions highlight |

# Command Line

## Launching Atom

> Another way to open a file in Atom is from the command line using the `atom` command. …
>
> You can run the `atom` command with one or more file paths to open up those files in Atom.

```shell
atom --help
Atom Editor v1.8.0
Usage: atom [options] [path ...]
One or more paths to files or folders may be specified. If there is an
existing Atom window that contains all of the given folders, the paths
will be opened in that window. Otherwise, they will be opened in a new
window.
...
```

― [Atom Flight Manual: Atom Basics - Opening a File](http://flight-manual.atom.io/getting-started/sections/atom-basics/#opening-a-file)

### Dev Mode

> **Tip:** You can avoid reloading to see changes you make by opening an Atom window in Dev Mode. To open a Dev Mode Atom window run `atom --dev .` in the terminal, or use the _View > Developer > Open in Dev Mode_ menu. When you edit your theme, changes will instantly be reflected!

```shell
atom --dev .
```
― [Atom Flight Manual: Creating a Theme - Creating a Syntax Theme](http://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#creating-a-syntax-theme)

### Safe Mode

> A large part of Atom's functionality comes from packages you can install. Atom will also execute the code in your [init script](http://flight-manual.atom.io/hacking-atom/sections/the-init-file) on startup. In some cases, these packages and the code in the init script might be causing unexpected behavior, problems, or performance issues.

```shell
atom --safe
```

> This starts Atom, but does not load packages from `~/.atom/packages` or `~/.atom/dev/packages` and disables loading of your init script. If you can no longer reproduce the problem in safe mode, it's likely it was caused by one of the packages or the init script.

― [Atom Flight Manual: Debugging - Using Safe Mode](http://flight-manual.atom.io/hacking-atom/sections/debugging/#using-safe-mode)

### Profiling Startup Performance

> If the time for loading the window looks high, you can create a CPU profile for that period using the `--profile-startup` command line flag when starting Atom:

```shell
atom --profile-startup .
```
> This will automatically capture a CPU profile as Atom is loading and open the Developer Tools once Atom loads.

― [Atom Flight Manual: Debugging - Profiling Startup Performance](https://flight-manual.atom.io/hacking-atom/sections/debugging/#profiling-startup-performance)

## Clearing Save State

> Atom saves a number of things about your environment when you exit in order to restore Atom to the same configuration when you next launch the program. In some cases the state that gets saved can be something undesirable that prevents Atom from working properly. In these cases, you may want to clear the state that Atom has saved.

```shell
atom --clear-window-state
```

― [Atom Flight Manual: Debugging - Clearing Save State](http://flight-manual.atom.io/hacking-atom/sections/debugging/#clearing-saved-state)

## Making Atom Portable

> Executing atom with the `--portable` option will take the `.atom` directory you have in the default location (`~/.atom`) and copy the relevant contents for your configuration to a new home directory in the Portable Mode location. This enables easily moving from the default location to a portable operation without losing the customization you have already set up.

```shell
atom --portable
```

― [Atom Flight Manual: Basic Customization - Taking Your Customization with you with Portable Mode](https://flight-manual.atom.io/using-atom/sections/basic-customization/#taking-your-customization-with-you-with-portable-mode)

## APM: Atom Package Manager

> You can also install packages or themes from the command line using `apm`.

To list commands use:

```shell
apm help
```

Note that many of the commands are just aliases of other commands so you can use your preferred keywords that may match other package managers you're used to.

To see information on a specific command use:

```shell
apm help *command*
```

― [Atom Flight Manual: Atom Packages - Command Line](https://flight-manual.atom.io/using-atom/sections/atom-packages/#command-line)

Commands:

| Command                    | Aliases                               | Description                                                                                                                                                          |
| -------------------------- | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `apm clean`                |                                       | Deletes all packages in the `node_modules` folder that are not referenced as a dependency in the package.json file.                                                  |
| `apm config`               |                                       | Pass-through to `npm config`: Manage the npm configuration files. From the relevant [pull request](https://github.com/atom/apm/pull/258).                            |
| `apm dedupe`               |                                       | Reduce duplication in the `node_modules` folder in the current directory.                                                                                            |
| `apm develop`              | `dev`                                 | Clone the given package's Git repository to the directory specified, install its dependencies, and link it for development to `~/.atom/dev/packages/<package_name>`. |
| `apm disable`              |                                       | Disables the named package(s).                                                                                                                                       |
| `apm docs`                 | `open`                                | Open a package's homepage in the default browser.                                                                                                                    |
| `apm enable`               |                                       | Enables the named package(s).                                                                                                                                        |
| `apm init`                 |                                       | Generates code scaffolding for either a theme or package depending on the option selected.                                                                           |
| `apm install`              | `i`                                   | Install the given Atom package to `~/.atom/packages/<package_name>`.                                                                                                 |
| `apm link`                 | `ln`                                  | Create a symlink for the package in `~/.atom/packages`. The package in the current working directory is linked if no path is given.                                  |
| `apm links`                | `linked`, `lns`                       | List all of the symlinked atom packages in `~/.atom/packages` and `~/.atom/dev/packages`.                                                                            |
| `apm list`                 | `ls`                                  | List all the installed packages and also the packages bundled with Atom.                                                                                             |
| `apm login`                |                                       | Enter your Atom.io API token and save it to the keychain. This token will be used to identify you when publishing packages to atom.io.                               |
| `apm publish`              |                                       | Publish a new version of the package in the current working directory.                                                                                               |
| `apm rebuild`              |                                       | Rebuild the given modules currently installed in the `node_modules` folder in the current working directory.                                                         |
| `apm rebuild-module-cache` |                                       | Rebuild the module cache for all the packages installed to `~/.atom/packages`                                                                                        |
| `apm search`               |                                       | Search for Atom packages/themes on the atom.io registry.                                                                                                             |
| `apm star`                 |                                       | Star the given packages on <https://atom.io>                                                                                                                         |
| `apm stars`                | `starred`                             | List or install starred Atom packages and themes.                                                                                                                    |
| `apm test`                 |                                       | Runs the package's tests contained within the spec directory (relative to the current working directory).                                                            |
| `apm uninstall`            | `deinstall`, `delete`, `remove`, `rm` | Delete the installed package(s) from the `~/.atom/packages` directory.                                                                                               |
| `apm unlink`               |                                       | Delete the symlink in `~/.atom/packages` for the package. The package in the current working directory is unlinked if no path is given.                              |
| `apm unpublish`            |                                       | Remove a published package or package version from the atom.io registry.                                                                                             |
| `apm unstar`               |                                       | Unstar the given packages on <https://atom.io>                                                                                                                       |
| `apm upgrade`              | `outdated`, `update`                  | Upgrade out of date packages installed to `~/.atom/packages`                                                                                                         |
| `apm view`                 | `show`                                | View information about a package/theme in the atom.io registry.                                                                                                      |

All descriptions except for `apm config` from `apm help *command*`. See help commands for usage examples and further information.
