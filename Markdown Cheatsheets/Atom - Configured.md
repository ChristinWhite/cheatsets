 title: Atom Cheatsheet

# Atom

---

#  Commands

## Actions

| Name           | Command                | Hotkey                |
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

| Name                   | Command                          | Hotkey | Note                                                       |
| ---------------------- | -------------------------------- | ------ | ---------------------------------------------------------- |
| Quit                   | `Application: Quit`              | `⌘ Q`  |                                                            |
| Install Update         | `Application: Install Update`    |        |                                                            |
| Install Shell Commands | `Window: Install Shell Commands` |        | Install's Atom's APM shell commands for managing packages. |
| Open License           | `Application: Open License`      |        | Opens Atom's application license in a file.                |

### Bookmarks

| Name                         | Command                                  | Hotkey  |
| ---------------------------- | ---------------------------------------- | ------- |
| Toggle Bookmark              | `Bookmarks: Toggle Bookmark`             | `⌘ F2`  |
| Jump to Next Bookmark        | `Bookmarks: Jump To Next Bookmark`       | `F2`    |
| Jump to Previous Bookmark    | `Bookmarks: Jump To Previous Bookmark`   | `⇧ F2`  |
| Select to Next Bookmark      | `Bookmarks: Select To Next Bookmark`     |         |
| Select to Previous Bookmarks | `Bookmarks: Select To Previous Bookmark` |         |
| Clear Bookmarks              | `Bookmarks: Clear Bookmarks`             | `⇧⌘ F2` |
| View All                     | `Bookmarks: View All`                    | `^ F2`  |

### Browser

| Name  | Command              | Hotkey | Note       |
| ----- | -------------------- | ---------- | ---------- |
| Open Link | `Link: Open` | `^⇧ O` | Opens http(s) links under cursor. [Package Info](https://github.com/atom/link). |
| View Release Notes | `About: View Release Notes` |                                              |                                              |
### Clipboard

| Name                       | Command                              | Hotkey | Note                                                         |
| -------------------------- | ------------------------------------ | ------ | ------------------------------------------------------------ |
| Copy                       | `Core: Copy`                         | `⌘ C`  |                                                              |
| Cut                        | `Core: Cut`                          | `⌘ X`  |                                                              |
| Paste                      | `Core: Paste`                        | `⌘ V`  |                                                              |
| Copy Selection             | `Editor: Copy Selection`             |        | I'm not sure if this is any different from the core copy command. |
| Cut to End of Line         | `Editor: Cut To End Of Line`         | `^ K`  |                                                              |
| Cut to End of Buffer Line  | `Editor: Cut To End Of Buffer Line`  |        | If code is selected cut selection, otherwise, cut from cursor to the end of the line. |
| Paste Without Reformatting | `Editor: Paste Without Reformatting` | `⇧⌘ V` |                                                              |

#### Paths

| Name              | Command                     | Hotkey | Note                                               |
| ----------------- | --------------------------- | ------ | -------------------------------------------------- |
| Copy Path         | `Editor: Copy Path`         | `^⇧ C` | Copy current file's absolute path.                 |
| Copy Project Path | `Editor: Copy Project Path` |        | Copy current file's path relative to project root. |

### Command Palette

| Name                   | Command                                 | Hotkey |
| ---------------------- | --------------------------------------- | ------ |
| Toggle Command Palette | `Command Palette: Toggle`               | `⇧⌘ P` |
| Show Hidden Commands   | `Command Palette: Show Hidden Commands` |        |

### Developer

More information about [Hacking Atom](http://flight-manual.atom.io/hacking-atom/).

| Name                        | Command                                        | Hotkey  | Note                                                         |
| --------------------------- | ---------------------------------------------- | ------- | ------------------------------------------------------------ |
| Reload Window               | `Window: Reload`                               | `^⌥⌘ L` | Completely reloads window. Some info in Atom Flight Manual in the [Creating a Syntax Theme](http://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#creating-a-syntax-theme) section. |
| Dev Live Reload             | `Dev Live Reload: Reload All`                  | `^⇧⌘ R` | Live reload atom themes and packages. [Package Info](https://atom.io/packages/dev-live-reload). |
| Toggle Dev Tools            | `Window: Toggle Dev Tools`                     | `⌥⌘ I`  | Toggle's Dev Tools like Chrome's. [Atom Flight Manual: Developer Tools](http://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#developer-tools). |
| Log Cursor Scope            | `Editor: Log Cursor Scope`                     | `⌥⌘ P`  | Easy way to display your cursor scope. [Atom Flight Manual: Scopes](http://flight-manual.atom.io/behind-atom/sections/scoped-settings-scopes-and-scope-descriptors/). |
| Styleguide                  | `Styleguide: Show`                             | `^⇧⌘ G` | Exercises all UI components and acts as a styleguide. [Package Info](https://atom.io/packages/styleguide). |
| Generate Package            | `Package Generator: Generate Package`          |         | Generates and opens a new sample package. [Package Info](https://atom.io/packages/package-generator). |
| Generate Language Package   | `Package Generator: Generate Language Package` |         | Generates and opens a new sample language. [Package Info](https://atom.io/packages/package-generator). |
| Generate Syntax Theme       | `Package Generator: Generate Syntax Theme`     |         | Generates and opens a new sample syntax theme. [Package Info](https://atom.io/packages/package-generator). |
| Update Package Dependencies | `Update Package Dependencies: Update`          |         | Runs `apm install` for the current project. [Package Info](https://atom.io/packages/update-package-dependencies). |
| Run Package Specs           | `Window: Run Package Specs`                    | `^⌥⌘ P` | This will run all the specs in the current project's `spec` directory. [Atom Flight Manual: Writing Specs](http://flight-manual.atom.io/hacking-atom/sections/writing-specs/). |
| Log Deprecation Warnings    | `Window: Log Deprecation Warnings`             |         | Logs deprecation warnings to Atom's console.                 |
| Timecop                     | `Timecop: View`                                |         | Displays information about where time is spent while Atom loads. [Package Info](https://atom.io/packages/timecop). |
| Run Benchmarks              | `Window: Run Benchmarks`                       |         | Opens Benchmarks window.                                     |
| Show Waterfall Diagnostics  | `GitHub: Show Waterfall Diagnostics`           |         | Opens the GitHub Package Timings view.                       |
| Incompatible Packages       | `Incompatible Packages: View`                  |         | Show incompatible packages. [Package Info](https://atom.io/packages/incompatible-packages). |
| Clear Update State          | `About: Clear Update State`                    |         | If I'm reading the [pull request](https://github.com/atom/about/pull/66) correctly it lets you tell Atom not to update to the current version, at least in dev mode. |

### Editor

#### Bracket Matching

| Name                           | Command | Note |
| ------------------------------ | ------- | ---- |
| Close Tag                      |         |      |
| Go to Enclosing Bracket        |         |      |
| Go to Matching Bracket         |         |      |
| Remove Brackets from Selection |         |      |
| Remove Matching Brackets       |         |      |
| Select Inside Brackets         |         |      |
| Select Matching Brackets       |         |      |

#### Casing

| Name       | Command              | Hotkey        |
| ---------- | -------------------- | ------------- |
| Upper Case | `Editor: Upper Case` | `⌘ K` + `⌘ U` |
| Lower Case | `Editor: Lower Case` | `⌘ K` + `⌘ L` |

#### Deletion

##### Delete by Subword

| Name                           | Command                                  | Hotkey           |
| ------------------------------ | ---------------------------------------- | ---------------- |
| Delete to Beginning of Subword | `Editor: Delete To Beginning Of Subword` | `^⌥ ⌫` \| `^⌥ H` |
| Delete to End of Subword       | `Editor: Delete To End Of Subword`       | `^⌥ ⌦` \| `^⌥ D` |

##### Delete by Word

| Name                             | Command                                    | Hotkey         |
| -------------------------------- | ------------------------------------------ | -------------- |
| Delete to Beginning of Word      | `Editor: Delete To Beginning Of Word`      | `⌥ ⌫` \| `⌥ H` |
| Delete to End of Word            | `Editor: Delete To End Of Word`            | `⌥ ⌦` \| `⌥ D` |
| Delete to Next Word Boundary     | `Editor: Delete To Next Word Boundary`     |                |
| Delete to Previous Word Boundary | `Editor: Delete To Previous Word Boundary` |                |

##### Delete by Line

| Name                        | Command                               | Hotkey          |
| --------------------------- | ------------------------------------- | --------------- |
| Delete Line                 | `Editor: Delete Line`                 | `^⇧ K`          |
| Delete to Beginning of Line | `Editor: Delete To Beginning Of Line` | `⌘ ⌫` \| `⇧⌘ ⌫` |
| Delete to End of Line       | `Editor: Delete To End Of Line`       | `⌘ ⌦`           |

#### Folding

| Name                         | Command                               | Hotkey                   |
| ---------------------------- | ------------------------------------- | ------------------------ |
| Fold Current Row             | `Editor: Fold Current Row`            | `⌥⌘ [`                   |
| Unfold Current Row           | `Editor: Unfold Current Row`          | `⌥⌘ ]`                   |
| Fold Selection               | `Editor: Fold Selection`              | `^⌥⌘ F`                  |
| Fold All                     | `Editor: Fold All`                    | `⌥⇧⌘ {`                  |
| Unfold All                   | `Editor: Unfold All`                  | `⌥⇧⌘ }` \| `⌘ K` + `⌘ 0` |
| Fold at Indent Level # (1-9) | `Editor: Fold At Indent Level #(1-9)` | `⌘ K` + `⌘ #(1-9)`       |

#### Formatting

| Name     | Command                      | Hotkey | Note                                                         |
| -------- | ---------------------------- | ------ | ------------------------------------------------------------ |
| Autoflow | `Autoflow: Reflow Selection` | `⌥⌘ Q` | Hard wraps at no more than preferred line length (80 characters by default). [Package Info](https://atom.io/packages/autoflow). |

#### Indentation

| Name                  | Command                         | Hotkey         | Note                                        |
| --------------------- | ------------------------------- | -------------- | ------------------------------------------- |
| Indent                | `Editor: Indent`                | `⇥`            | Hotkey activates only at beginning of line. |
| Indent Selected Rows  | `Editor: Indent Selected Rows`  | `⌘ ]`          |                                             |
| Outdent Selected Rows | `Editor: Outdent Selected Rows` | `⌘ [` \| `⇧ ⇥` |                                             |

#### Line Manipulation

| Name            | Command                               | Hotkey                |
| --------------- | ------------------------------------- | --------------------- |
| Newline         | `Editor: Newline`                     | `↵` \| `⇧ ↵` \| `⌥ ↵` |
| Newline Above   | `Editor: Newline Above`               | `⌘ ↵`                 |
| Newline Below   | `Editor: Newline Below`               | `⇧⌘ ↵`                |
| Duplicate Lines | `Editor: Duplicate Lines`             | `⇧⌘ D`                |
| Join Lines      | `Editor: Join Lines`                  | `⌘ J`                 |
| Split           | `Editor: Split Selections Into Lines` | `⇧⌘ L`                |
| Comment Line    | `Editor: Toggle Line Comments`        | `⌘ /`                 |

#### Move Text

##### Move by Character

| Name                 | Command                        | Hotkey | Note                                                         |
| -------------------- | ------------------------------ | ------ | ------------------------------------------------------------ |
| Move Selection Left  | `Editor: Move Selection Left`  | `^⌘ ←` |                                                              |
| Move Selection Right | `Editor: Move Selection Right` | `^⌘ →` |                                                              |
| Transpose            | `Editor: Transpose`            | `^ T`  | Switches character on left of cursor with that on right or reverses text if selection. |

##### Move by Line

| Name           | Command                  | Hotkey |
| -------------- | ------------------------ | ------ |
| Move Line Up   | `Editor: Move Line Up`   | `^⌘ ↑` |
| Move Line Down | `Editor: Move Line Down` | `^⌘ ↓` |

#### Navigation

| Name             | Command                    | Hotkey                |
| ---------------- | -------------------------- | --------------------- |
| Move Up          | `Core: Move Up`            | `↑` \| `^ ↑` \| `^ P` |
| Move Right       | `Core: Move Right`         | `→` \| `^ F`          |
| Move Down        | `Core: Move Down`          | `↓` \| `^ ↓` \| `^ N` |
| Move Left        | `Core: Move Left`          | `←` \| `^ B`          |
| Scroll to Cursor | `Editor: Scroll To Cursor` | `⇧⌘ <`                |

##### Move by Subword

| Name                              | Command                                     | Hotkey           |
| --------------------------------- | ------------------------------------------- | ---------------- |
| Move to Previous Subword Boundary | `Editor: Move To Previous Subword Boundary` | `^⌥ ←` \| `^⌥ B` |
| Move to Next Subword Boundary     | `Editor: Move To Next Subword Boundary`     | `^⌥ →` \| `^⌥ F` |

##### Move by Word

| Name                           | Command                                  | Hotkey         |
| ------------------------------ | ---------------------------------------- | -------------- |
| Move to Beginning of Word      | `Editor: Move To Beginning Of Word`      | `⌥ ←` \| `⌥ B` |
| Move to End of Word            | `Editor: Move To End Of Word`            | `⌥ →` \| `⌥ F` |
| Move to Previous Word Boundary | `Editor: Move To Previous Word Boundary` |                |
| Move to Next Word Boundary     | `Editor: Move To Next Word Boundary`     |                |
| Move to Beginning of Next Word | `Editor: Move To Beginning Of Next Word` |                |

##### Move by Line

| Name                             | Command                                    | Hotkey                       | Note              |
| -------------------------------- | ------------------------------------------ | ---------------------------- | ----------------- |
| Move to First Character of Line  | `Editor: Move To First Character Of Line`  | `⌘ ←` \| `^ A` \| `↖` (Home) | After whitespace. |
| Move to Beginning of Line        | `Editor: Move To Beginning Of Line`        |                              |                   |
| Move to End of Line              | `Editor: Move To End Of Line`              | `^ E`                        |                   |
| Move to Beginning of Screen Line | `Editor: Move To Beginning Of Screen Line` |                              |                   |
| Move to End of Screen Line       | `Editor: Move To End Of Screen Line`       | `⌘ →` \| `↘` (End)           |                   |

##### Move by Paragraph

| Name                                    | Command                                           |
| --------------------------------------- | ------------------------------------------------- |
| Move to Beginning of Previous Paragraph | `Editor: Move To Beginning Of Previous Paragraph` |
| Move to Beginning of Next Paragraph     | `Editor: Move To Beginning Of Next Paragraph`     |

##### Move by Screen

| Name      | Command           | Hotkey         |
| --------- | ----------------- | -------------- |
| Page Down | `Core: Page Up`   | `⇞` (Pageup)   |
| Page Up   | `Core: Page Down` | `⇟` (Pagedown) |

##### Move by File

| Name           | Command                | Hotkey |
| -------------- | ---------------------- | ------ |
| Move to Top    | `Core: Move To Bottom` | `⌘ ↑`  |
| Move to Bottom | `Core: Move To Bottom` | `⌘ ↓`  |

##### Go To Line

| Name | Command | Hotkey | Note |
| ---- | ------- | ---- | ---- |
| Go To Line                       | `Go To Line: Toggle`                       | `^ G`             |                   |
| Cancel                           | `Core: Cancel`                             | `⌘ W`                  | Contextual hotkey. |

#### Selection

| Name                   | Command                          | Hotkey | Note                                                         |
| ---------------------- | -------------------------------- | ------ | ------------------------------------------------------------ |
| Consolidate Selections | `Editor: Consolidate Selections` | `⎋`    | Reduce multiple selections to the least recently added selection. |

##### Select by Context

Syntax Node commands only work with limited grammars for now, more information [here](http://blog.atom.io/2018/02/13/atom-1-24.html).

| Name | Command | Hotkey |
| ---- | ------- | ---- |
| Select Inside Brackets | `Bracket Matcher: Select Inside Brackets` | `^⌘ M` |
| Select Matching Brackets | `Bracket Matcher: Select Matching Brackets` | `^ M` |
| Remove Brackets from Selection | `Bracket Matcher: Remove Brackets From Selection` | `^ ]` |
| Select Larger Syntax Node  | `Editor: Select Larger Syntax Node` | `⌥ ↑`    |
| Select Smaller Syntax Node | `Editor: Select Smaller Syntax Node` | `⌥ ↓` |

##### Select by Character

| Name         | Command              | Hotkey          |
| ------------ | -------------------- | --------------- |
| Select Left  | `Core: Select Left`  | `⇧ ←` \| `^⇧ B` |
| Select Right | `Core: Select Right` | `⇧ →` \| `^⇧ F` |

##### Select by Subword

| Name                                | Command                                       | Hotkey             |
| ----------------------------------- | --------------------------------------------- | ------------------ |
| Select to Next Subword Boundary     | `Editor: Select To Next Subword Boundary`     | `^⌥⇧ →` \| `^⌥⇧ F` |
| Select to Previous Subword Boundary | `Editor: Select To Previous Subword Boundary` | `^⌥⇧ ←` \| `^⌥⇧ B` |

##### Select by Word

| Name                             | Command                                    | Hotkey           |
| -------------------------------- | ------------------------------------------ | ---------------- |
| Select Word                      | `Editor: Select Word`                      | `^⇧ W`           |
| Select to Beginning of Word      | `Editor: Select To Beginning Of Word`      | `⌥⇧ ←` \| `⌥⇧ B` |
| Select to End of Word            | `Editor: Select To End Of Word`            | `⌥⇧ →` \| `⌥⇧ B` |
| Select to Previous Word Boundary | `Editor: Select To Previous Word Boundary` |                  |
| Select to Next Word Boundary     | `Editor: Select To Next Word Boundary`     |                  |
| Select to Beginning of Next Word | `Editor: Select To Beginning Of Next Word` |                  |

##### Select by Line

| Name                              | Command                                     | Hotkey                           | Note                                                   |
| --------------------------------- | ------------------------------------------- | -------------------------------- | ------------------------------------------------------ |
| Select Line                       | `Editor: Select Line`                       | `⌘ L`                            |                                                        |
| Select to First Character of Line | `Editor: Select To First Character Of Line` | `⇧⌘ ←` \| `^⇧ A` \| `⇧ ↖` (Home) | After whitespace.                                      |
| Select to Beginning of Line       | `Editor: Select To Beginning Of Line`       |                                  | Before whitespace.                                     |
| Select to End of Line             | `Editor: Select To End Of Line`             | `⇧⌘ →` \| `^⇧ E` \| `⇧ ↘` (End)  |                                                        |
| Select Up                         | `Core: Select Up`                           | `⇧ ↑` \| `^⇧ P`                  |                                                        |
| Select Down                       | `Core: Select Down`                         | `⇧ ↓` \| `^⇧ N`                  |                                                        |
| Add Selection Above               | `Editor: Add Selection Above`               | `^⇧ ↑`                           | Expands the current selection up one line by column.   |
| Add Selection Below               | `Editor: Add Selection Below`               | `^⇧ ↓`                           | Expands the current selection down one line by column. |

##### Select by Paragraph

| Name                                      | Command                                             |
| ----------------------------------------- | --------------------------------------------------- |
| Select to Beginning of Previous Paragraph | `Editor: Select To Beginning Of Previous Paragraph` |
| Select to Beginning of Next Paragraph     | `Editor: Select To Beginning Of Next Paragraph`     |

##### Select by Screen

| Name             | Command                  | Hotkey           |
| ---------------- | ------------------------ | ---------------- |
| Select Page Up   | `Core: Select Page Up`   | `⇧ ⇞` (Pageup)   |
| Select Page Down | `Core: Select Page Down` | `⇧ ⇟` (Pagedown) |

##### Select By File

| Name             | Command                  | Hotkey |
| ---------------- | ------------------------ | ------ |
| Select All       | `Core: Select All`       | `⌘ A`  |
| Select to Top    | `Core: Select To Bottom` | `⇧⌘ ↑` |
| Select to Bottom | `Core: Select To Bottom` | `⇧⌘ ↓` |

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

### Files

#### New

| Name     | Command                 | Hotkey         |
| -------- | ----------------------- | -------------- |
| New File | `Application: New File` | `⌘ N` \| `⌘ T` |

#### Open

| Name        | Command                    | Hotkey | Note                                              |
| ----------- | -------------------------- | ------ | ------------------------------------------------- |
| Open        | `Application: Open`        | `⌘ O`  |                                                   |
| Open File   | `Application: Open File`   |        |                                                   |
| Open Folder | `Application: Open Folder` |        |                                                   |
| Open Safe   | `Application: Open Safe`   |        | Appears to open a folder or project in safe mode. |
| Open Dev    | `Application: Open Dev`    |        | Appears to open a folder or project in dev mode.  |

#### Save

| Name       | Command            | Hotkey | Note                                                 |
| ---------- | ------------------ | ------ | ---------------------------------------------------- |
| Save       | `Core: Save`       | `⌘ S`  |                                                      |
| Save As    | `Core: Save As`    | `⇧⌘ S` |                                                      |
| Save All   | `Window: Save All` | `⌥⌘ S` |                                                      |
| Save Items | `Pane: Save Items` |        | This saves items in a pane, not a file specifically. |

#### Close

##### Panes

Note that these commands close panes, not files. Depending on your focus they may not close the file you're working on but not currently in focus.

| Name               | Command                    | Hotkey         |
| ------------------ | -------------------------- | -------------- |
| Close              | `Pane: Close`              | `⌘ K` + `⌘ W`  |
| Close Other Items  | `Pane: Close Other Items`  | `⌘ K` + `⌥⌘ W` |
| Reopen Closed Item | `Pane: Reopen Closed Item` | `⇧⌘ T`         |

##### Tabs

| Name | Command |
| ---- | ------- |
| Close Tab           | `Tabs: Close Tab`         |
| Close Tabs to Left  | `Tabs: Close Tabs To Left` |
| Close Tabs to Right | `Tabs: Close Tabs To Right` |
| Close Saved Tabs    | `Tabs: Close Saved Tabs`  |
| Close Other Tabs    | `Tabs: Close All Tabs`    |
| Close All Tabs      | `Tabs: Close All Tabs`    |

##### Window

| Name         | Command         | Hotkey |
| ------------ | --------------- | ------ |
| Close Window | `Window: Close` | `⇧⌘ W` |

#### File Properties

| Name                 | Command                                 | Hotkey | Note                                                     |
| -------------------- | --------------------------------------- | ------ | -------------------------------------------------------- |
| Grammar Selector     | `Grammar Selector: Show`                | `^⇧ L` | Select language or syntax for file.                      |
| Select Encoding      | `Encoding Selector: Show`               | `^⇧ U` |                                                          |
| Line Ending Selector | `Line Ending Selector: Show`            |        |                                                          |
| Convert To CRLF      | `Line Ending Selector: Convert To CRLF` |        |                                                          |
| Convert To LF        | `Line Ending Selector: Convert To LF`   |        |                                                          |
| Toggle Soft Tabs     | `Editor: Toggle Soft Tabs`              |        | This does not modify the file, just future tab behavior. |

#### Fuzzy Finder

| Name                     | Command                                  | Hotkey         | Note                                 |
| ------------------------ | ---------------------------------------- | -------------- | ------------------------------------ |
| Invert Confirm           | `Fuzzy Finder: Invert Confirm`           | `⇧ ↵`          |                                      |
| Toggle Buffer Finder     | `Fuzzy Finder: Toggle Buffer Finder`     | `⌘ B`          | Select Open File.                    |
| Toggle File Finder       | `Fuzzy Finder: Toggle File Finder`       | `⌘ P` \| `⌘ T` | Select Project File.                 |
| Toggle Git Status Finder | `Fuzzy Finder: Toggle Git Status Finder` | `⇧⌘ B`         | Select Modified and Untracked Files. |

#### Tree View

| Name                                | Command                                         | Hotkey                       | Note              |
| ----------------------------------- | ----------------------------------------------- | ---------------------------- | ----------------- |
| Copy                                | `Tree View: Copy`                               | `⌘ C`                        |                   |
| Cut                                 | `Tree View: Cut`                                | `⌘ X`                        |                   |
| Paste                               | `Tree View: Paste`                              | `⌘ V`                        |                   |
| Duplicate                           | `Tree View: Duplicate`                          | `D`                          |                   |
| Rename                              | `Tree View: Rename`                             |                              |                   |
| Move                                | `Tree View: Move`                               | `M` \| `F2`                  |                   |
| Add File                            | `Tree View: Add File`                           | `A`                          |                   |
| Add Folder                          | `Tree View: Add Folder`                         | `⇧ A`                        |                   |
| Remove                              | `Tree View: Remove`                             | `⌫` \| `⌦`                   |                   |
| Remove Project Folder               | `Tree View: Remove Project Folder`              |                              |                   |
| Expand Item                         | `Tree View: Expand Item`                        | `→` \| `^ ]` \| `^ F` \| `L` |                   |
| Collapse Directory                  | `Tree View: Collapse Directory`                 | `←` \| `^ [` \| `^ B` \| `H` |                   |
| Recursively Expand Directory        | `Tree View: Recursive Collapse Directory`       | `⌥ →` \| `^⌥ ]`              |                   |
| Recursively Collapse Directory      | `Tree View: Recursive Collapse Directory`       | `⌥ ←` \| `^⌥ [`              |                   |
| Collapse All                        | `Tree View: Collapse All`                       |                              |                   |
| Reveal Active File                  | `Tree View: Reveal Active File`                 | `⌘ |`                        |                   |
| Show Current File in File Manager   | `Tree View: Show Current File In File Manager`  |                              |                   |
| Show in File Manager                | `Tree View: Show In File Manager`               |                              |                   |
| Open Selected Entry                 | `Tree View: Open Selected Entry`                | `↵`                          |                   |
| Open Selected Entry Up              | `Tree View: Open Selected Entry Up`             | `⌘ K` + `↑` \| `⌘ K` + `K`   |                   |
| Open Selected Entry Right           | `Tree View: Open Selected Entry Right`          | `⌘ K` + `→` \| `⌘ K` +  `L`  |                   |
| Open Selected Entry Down            | `Tree View: Open Selected Entry Down`           | `⌘ K` + `↓` \| `⌘ K` + `J`   |                   |
| Open Selected Entry Left            | `Tree View: Open Selected Entry Left`           | `⌘ K` + `←` \| `⌘ K` + `H`   |                   |
| Open Selected Entry in Pane # (1-9) | `Tree View: Open Selected Entry In Pane #(1-9)` | `⌘ #(1-9)`                   |                   |
| Open in New Window                  | `Tree View: Open In New Window`                 |                              |                   |
| Copy Full Path                      | `Tree View: Copy Full Path`                     | `^⇧ C`                       |                   |
| Copy Project Path                   | `Tree View: Copy Project Path`                  |                              |                   |
| Move Up                             | `Core: Move Up`                                 | `K`                          | Contextual hotkey. |
| Move Down                           | `Core: Move Down`                               | `J`                          | Contextual Hotkey. |
| Move to Top                         | `Core: Move To Top`                             | `↖` (Home)                   | Contextual hotkey. |
| Move to Bottom                      | `Core: Move To Bottom`                          | `↘` (End)                    | Contextual hotkey. |
| Toggle Tree View                    | `Tree View: Toggle`                             | `⌘ \` \| `⌘ K` + `⌘ B`       |                   |
| Toggle Tree View Focus              | `Tree View: Toggle Focus`                       | `^ 0`                        |                   |
| Show Tree View         | `Tree View: Show`         |      | |
| Unfocus Tree View      | `Tree View: Unfocus`      | `⎋` | |

### Find and Replace

| Name                    | Command                                           | Hotkey  | Note                      |
| ----------------------- | ------------------------------------------------- | ------- | ------------------------- |
| Find Selection          | `Find And Replace: Use Selection As Find Pattern` | `⌘ E`   |                           |
| Find Next               | `Find And Replace: Find Next`                     | `⌘ G`   |                           |
| Find Previous           | `Find And Replace: Find Previous`                 | `⇧⌘ G`  |                           |
| Show Previous           | `Find and Replace: Show Previous`                 | `⇧ ↵`   |                           |
| Find Next Selected      | `Find And Replace: Find Next Selected`            | `⌘ F3`  |                           |
| Find Previous Selected  | `Find And Replace: Find Previous Selected`        | `⇧⌘ F3` |                           |
| Find All                | `Find And Replace: Find All`                      | `⌥ ↵`   |                           |
| Replace Next            | `Find And Replace: Replace Next`                  | `⌥⌘ E`  |                           |
| Replace All             | `Find And Replace: Replace All`                   | `⌘ ↵`   |                           |
| Select Next             | `Find And Replace: Select Next`                   | `⌘ D`   |                           |
| Select All              | `Find And Replace: Select All`                    | `^⌘ G`  |                           |
| Clear History           | `Find And Replace: Clear History`                 |         |                           |
| Toggle Find and Replace | `Find And Replace: Toggle`                        |         |                           |
| Show Find               | `Find And Replace: Show`                          | `⌘ F`   | Focuses on Find field.    |
| Show Replace            | `Find And Replace: Show Replace`                  | `⌥⌘ F`  | Focuses on Replace field. |

#### Find and Replace Settings

| Name | Command | Hotkey | Note |
| ---- | ------- | ------ | ---- |
| Toggle Regex Option       | `Find And Replace: Toggle Regex Option`       | `⌥⌘ /` | Regex allowed.        |
| Toggle Case Option        | `Find And Replace: Toggle Case Option`        | `⌥⌘ C` | Case sensitivity.     |
| Toggle Selection Option   | `Find And Replace: Toggle Selection Option`   | `⌥⌘ S` | Find within selection. |
| Toggle Whole World Option | `Find And Replace: Toggle Whole World Option` | `⌥⌘ W` | Find whole words only. |

#### Find in Project

| Name                      | Command                                   | Note   |
| ------------------------- | ----------------------------------------- | ------ |
| Replace All               | `Project Find: Replace All`               | `⌘ ↵`  |
| Find in Project           | `Project Find: Show`                      | `⇧⌘ F` |
| Find in Current Directory | `Project Find: Show In Current Directory` |        |
| Toggle Find in Project    | `Project Find: Toggle`                    |        |

#### Find in Project Settings

| Name                      | Command                                   | Hotkey | Note                   |
| ------------------------- | ----------------------------------------- | ------ | ---------------------- |
| Toggle Regex Option       | `Project Find: Toggle Regex Option`       | `⌥⌘ /` | Regex allowed.         |
| Toggle Case Option        | `Project Find: Toggle Case Option`        | `⌥⌘ C` | Case sensitivity.      |
| Toggle Selection Option   | `Project Find: Toggle Selection Option`   | `⌥⌘ S` | Find within selection. |
| Toggle Whole World Option | `Project Find: Toggle Whole World Option` | `⌥⌘ W` | Find whole words only. |

### Image View

| Name        | Command                 | Note            |
| ----------- | ----------------------- | --------------- |
| Zoom In     | Image View: Zoom In     | `⌘ =` \| `⇧⌘ +` |
| Zoom Out    | Image View: Zoom Out    | `⌘ -` \| `⇧⌘ _` |
| Reset Zoom  | Image View: Reset Zoom  | `⌘ 0`           |
| Zoom to Fit | Image View: Zoom To Fit | `⌘ 9`           |

### Markdown Preview

| Name                           | Command                                            | Hotkey          |
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

### Projects

| Name                  | Command                         | Hotkey                     | Note                           |
| --------------------- | ---------------------------------- | ------------------------------ | ------------------------------ |
| Reopen Project | `Application: Reopen Project` |  |  |
| Add Project Folder | `Application: Add Project Folder` | `⇧⌘ O` |      |
| Clear Project History | `Application: Clear Project History` |  | Clears the reopen project list. |

### Snippets

| Name                      | Command                       | Hotkey |
| ------------------------- | ----------------------------- | ------ |
| Expand Snippet            | `Snippets: Expand`            | `⇥`    |
| Next Tab Stop             | `Previous Tab Stop`           | `⇥`    |
| Previous Tab Stop         | `Snippets: Previous Tab Stop` | `⇧ ⇥`  |
| Toggle Available Snippets | `Snippets: Available`         |        |

### Source Control

| Name                                  | Command                                         | Hotkey         | Note               |
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

| Name                        | Command                               | Hotkey        |
| --------------------------- | ------------------------------------- | ------------- |
| Open File                   | `GitHub: Open File`                   | `O`           |
| Discard Selected Lines      | `GitHub: Discard Selected Lines`      | `⌘ ⌫` | `^ ⌫` |
| Select Previous Hunk        | `GitHub: Select Previous Hunk`        | `⇧ ⇥`         |
| Select Next Hunk            | `GitHub: Select Next Hunk`            | `⇥`           |
| Move Focus to Staging View  | `GitHub: Move Right`                  | `→`           |
| Toggle Patch Selection Mode | `GitHub: Toggle Patch Selection Mode` | `/`           |
| Close All Diff Views    | `GitHub: Close All Diff Views`    |        |
| Close Empty Diff Views  | `GitHub: Close Empty Diff Views`  |        |

#### GitHub

| Name                       | Command                              | Note                                 |
| -------------------------- | ------------------------------------ | ------------------------------------ |
| Open Issue or Pull Request | `GitHub: Open Issue Or Pull Request` | Pass it the URL for any issue or PR. |
| Logout                     | `GitHub: Logout`                     |                                      |

#### Git Diff

| Name                  | Command                           | Hotkey      |
| --------------------- | --------------------------------- | ----------- |
| Move to Next Diff     | `Git Diff: Move To Next Diff`     | `⌥ G` + `↓` |
| Move to Previous Diff | `Git Diff: Move To Previous Diff` | `⌥ G` + `↑` |
| Toggle Diff List      | `Git Diff: Toggle Diff List`      | `⌥ G` + `D` |

#### Open on GitHub

| Name           | Command                          | Hotkey      |
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

| Name                              | Command                                     | Hotkey         |
| --------------------------------- | ------------------------------------------- | -------------- |
| Open File                         | `GitHub: Open File`                         | `O`            |
| Show Diff View                    | `GitHub: Show Diff View`                    |                |
| Discard Changes in Selected Files | `GitHub: Discard Changes In Selected Files` | `⌘ ⌫` \| `^ ⌫` |
| Focus Next List                   | `GitHub: Focus Next`                        | `⇥`            |
| Focus Previous List               | `GitHub: Focus Previous`                    | `⇧ ⇥`          |
| Move Focus to File Patch View     | `GitHub: Move Focus to File Patch View`     | `←`            |
| View Stage Changes for Current File    | `GitHub: View Staged Changes For Current File`   |      |
| View Unstaged Changes for Current File | `GitHub: View Unstaged Changes For Current File` |      |

### Spell Check

| Name                  | Command                            | Hotkey | Note              |
| --------------------- | ---------------------------------- | ------ | ----------------- |
| Correct Misspelling   | `Spell Check: Correct Misspelling` | `⌘ :`  |                   |
| Confirm               | `Core: Confirm`                    | `⇥`    | Contextual hotkey |
| Cancel                | `Core: Cancel`                     | `⌘ :`  | Contextual hotkey |
| Toggle Spell Checking | `Spell Check: Toggle`              |        |                   |

### Symbols

| Name                    | Command                                 | Hotkey |
| ----------------------- | --------------------------------------- | ------ |
| Go To Declaration       | `Symbols View: Go To Declaration`       | `⌥⌘ ↓` |
| Return From Declaration | `Symbols View: Return From Declaration` | `⌥⌘ ↑` |
| Toggle File Symbols     | `Symbols View: Toggle File Symbols`     | `⌘ R`  |
| Toggle Project Symbols  | `Symbols View: Toggle Project Symbols`  | `⇧⌘ R` |

## Settings

### Configuration

| Name                  | Command                              |
| --------------------- | ------------------------------------ |
| Open Your Config      | `Application: Open Your Config`      |
| Open Your Init Script | `Application: Open Your Init Script` |
| Open Your Keymap      | `Application: Open Your Keymap`      |
| Open Your Snippets    | `Application: Open Your Snippets`    |
| Open Your Stylesheet  | `Application: Open Your Stylesheet`  |

### Editor

| Name                          | Command                       | Hotkey          | Note                                   |
| ----------------------------- | ----------------------------- | --------------- | -------------------------------------- |
| Toggle Auto Indent            | `Editor: Auto Indent`         |                 |                                        |
| Toggle Auto Indent for Window | `Window: Toggle Auto Indent`  |                 |                                        |
| Toggle Soft Tabs              | `Editor: Toggle Soft Tabs`    |                 |                                        |
| Toggle Invisibles             | `Window: Toggle Invisibles`   |                 | Shows symbols representing whitespace. |
| Toggle Indent Guide           | `Editor: Toggle Indent Guide` |                 |                                        |
| Toggle Line Numbers           | `Editor: Toggle Line Numbers` |                 |                                        |
| Toggle Soft Wrap              | `Editor: Toggle Soft Wrap`    |                 |                                        |
| Toggle Spell Check            | `Spell Check: Toggle`         |                 |                                        |
| Increase Font Size            | `Window: Increase Font Size`  | `⌘ =` \| `⌘⇧ +` |                                        |
| Decrease Font Size            | `Window: Decrease Font Size`  | `⌘ -` \| `⇧⌘ _` |                                        |
| Reset Font Size               | `Window: Reset Font Size`     | `⌘ 0`           |                                        |

### Find and Replace

| Name                      | Command                                       | Hotkey | Note                  |
| ------------------------- | --------------------------------------------- | ------ | --------------------- |
| Toggle Regex Option       | `Find And Replace: Toggle Regex Option`       | `⌥⌘ /` | Regex allowed         |
| Toggle Case Option        | `Find And Replace: Toggle Case Option`        | `⌥⌘ C` | Case sensitivity      |
| Toggle Selection Option   | `Find And Replace: Toggle Selection Option`   | `⌥⌘ S` | Find within selection |
| Toggle Whole World Option | `Find And Replace: Toggle Whole World Option` | `⌥⌘ W` | Find whole words only |

#### Project Find

| Name                      | Command                                   | Hotkey | Note                  |
| ------------------------- | ----------------------------------------- | ------ | --------------------- |
| Toggle Regex Option       | `Project Find: Toggle Regex Option`       | `⌥⌘ /` | Regex allowed         |
| Toggle Case Option        | `Project Find: Toggle Case Option`        | `⌥⌘ C` | Case sensitivity      |
| Toggle Selection Option   | `Project Find: Toggle Selection Option`   | `⌥⌘ S` | Find within selection |
| Toggle Whole World Option | `Project Find: Toggle Whole World Option` | `⌥⌘ W` | Find whole words only |

### Keymap

| Name                 | Command                         | Hotkey | Note                                                         |
| -------------------- | ------------------------------- | ------ | ------------------------------------------------------------ |
| Open Your Keymap     | `Application: Open Your Keymap` |        |                                                              |
| Key Binding Resolver | `Key Binding Resolver: Toggle`  | `⌘ .`  | Toggles panel that shows you all commands associated with pressed hotkeys |

### Preferences

| Name                             | Command                                      | Hotkey |
| -------------------------------- | -------------------------------------------- | ------ |
| Preferences                      | `Application: Show Preferences`              | `⌘ ,`  |
|                                  | `Application: Show Settings`                 |        |
|                                  | `Settings View: Open`                        |        |
| Core Section                     | `Settings View: Core`                        |        |
| Editor Section                   | `Settings View: Editor`                      |        |
| Keybindings Section              | `Settings View: Show Keybindings`            |        |
| Packages Section                 | `Settings View: View Installed Packages`     |        |
| Focus Filter in Packages Section | `Settings View: Uninstall Packages`          |        |
| Themes Section                   | `Settings View: View Installed Themes`       |        |
| Focus Filter in Themes Section   | `Settings View: Change Themes`               |        |
|                                  | `Settings View: Uninstall Themes`            |        |
| Updates Section                  | `Settings View: Check For Package Updates`   |        |
| Install Section                  | `Settings View: Install Packages And Themes` |        |

### Snippets

| Name               | Command                           |
| ------------------ | --------------------------------- |
| Open Your Snippets | `Application: Open Your Snippets` |

### Tree View

| Name                     | Command                               | Hotkey | Note                                   |
| ------------------------ | ------------------------------------- | ------ | -------------------------------------- |
| Toggle Ignored Names     | `Tree View: Toggle Ignored Names`     |        |                                        |
| Toggle VCS Ignored Files | `Tree View: Toggle VCS Ignored Files` | `I`    | Respects .gitignore. Hotkey contextual |

## UI

### Pages

| Name                  | Command                         | Hotkey | Note                     |
| --------------------- | ------------------------------- | ------ | ------------------------ |
| Preferences           | `Application: Show Preferences` | `⌘ ,`  |                          |
|                       | `Application: Show Preferences` |        |                          |
| Welcome               | `Welcome: Show`                 |        | Opens both welcome pages |
| About                 | `Application: About`            |        |                          |
| Incompatible Packages | `Incompatible Packages: View`   |        |                          |
| Timecop               | `Timecop: View`                 |        |                          |

#### Markdown Preview

| Name                                            | Command                                            | Hotkey |
| ----------------------------------------------- | -------------------------------------------------- | ------ |
| Invert Confirm           | Fuzzy Finder: Invert Confirm             | `⇧ ↵`          |                                      |
| Toggle Buffer Finder     | `Fuzzy Finder: Toggle Buffer Finder`     | `⌘ B`          | Select Open File.                    |
| Toggle File Finder       | `Fuzzy Finder: Toggle File Finder`       | `⌘ P` \| `⌘ T` | Select Project File.                 |
| Toggle Git Status Finder | `Fuzzy Finder: Toggle Git Status Finder` | `⇧⌘ B`         | Select Modified and Untracked Files. |

### Palettes

#### Command Palette

| Name                   | Command                                 | Hotkey |
| ---------------------- | --------------------------------------- | ------ |
| Toggle Command Palette | `Command Palette: Toggle`               | `⇧⌘ P` |
| Show Hidden Commands   | `Command Palette: Show Hidden Commands` |        |

#### Fuzzy Finder

| Name                     | Command                                  | Hotkey | Note                                |
| ------------------------ | ---------------------------------------- | ------ | ----------------------------------- |
| Toggle Buffer Finder     | `Fuzzy Finder: Toggle Buffer Finder`     | `⌘ B`          | Select Open File.                    |
| Toggle File Finder       | `Fuzzy Finder: Toggle File Finder`       | `⌘ P` \| `⌘ T` | Select Project File.                 |
| Toggle Git Status Finder | `Fuzzy Finder: Toggle Git Status Finder` | `⇧⌘ B`         | Select Modified and Untracked Files. |

#### Bookmarks

| Name             | Command               | Hotkey |
| ---------------- | --------------------- | ------ |
| Toggle Bookmarks | `Bookmarks: View All` | `⌘ F2` |

#### Go To Line

| Name              | Command              | Hotkey |
| ----------------- | -------------------- | ------ |
| Toggle Go To Line | `Go To Line: Toggle` | `^ G`  |

#### Grammar Selector

| Name                    | Command                  | Hotkey | Note                                |
| ----------------------- | ------------------------ | ------ | ----------------------------------- |
| Toggle Grammar Selector | `Grammar Selector: Show` | `^⇧ L` | Select language or syntax for file. |

#### Git Diff

| Name             | Command                      | Hotkey      |
| ---------------- | ---------------------------- | ----------- |
| Toggle Diff List | `Git Diff: Toggle Diff List` | `⌥ G` + `D` |

#### Line Ending Selector

| Name                        | Command                      |
| --------------------------- | ---------------------------- |
| Toggle Line Ending Selector | `Line Ending Selector: Show` |

#### Snippets

| Name                      | Command               |
| ------------------------- | --------------------- |
| Toggle Available Snippets | `Snippets: Available` |

#### Symbols

| Name                   | Command                                | Hotkey |
| ---------------------- | -------------------------------------- | ---- |
| Toggle File Symbols     | `Symbols View: Toggle File Symbols`     | `⌘ R`  |
| Toggle Project Symbols  | `Symbols View: Toggle Project Symbols`  | `⇧⌘ R` |

### Panels and Docks

| Name               | Command                      |
| ------------------ | ---------------------------- |
| Toggle Left Dock   | `Window: Toggle Left Dock`   |
| Toggle Bottom Dock | `Window: Toggle Bottom Dock` |
| Toggle Right Dock  | `Window: Toggle Right Dock`  |

#### Find and Replace

| Name                    | Command                          | Hotkey               | Note                     |
| ----------------------- | -------------------------------- | ------------------------ | ------------------------ |
| Toggle Find and Replace | `Find And Replace: Toggle`       |                          |                          |
| Show Find and Replace   | `Find And Replace: Show`         | `⌘ F` | Focuses on Find field    |
| Show Replace            | `Find And Replace: Show Replace` | `⌥⌘ F` | Focuses on Replace field |

##### Find in Project

| Name                   | Command                | Hotkey |
| ---------------------- | ---------------------- | ------ |
| Toggle Find in Project | `Project Find: Toggle` |        |
| Show Find in Project   | `Project Find: Show`   | `⇧⌘ F` |

#### Key Binding Resolver

| Name                        | Command                        | Hotkey |
| --------------------------- | ------------------------------ | ------ |
| Toggle Key Binding Resolver | `Key Binding Resolver: Toggle` | `⌘ .`  |

#### Notifications

| Name                     | Command                     |
| ------------------------ | --------------------------- |
| Toggle Notifications Log | `Notifications: Toggle Log` |

#### Source Control

| Name                    | Command                           | Hotkey |
| ----------------------- | --------------------------------- | ------ |
| Toggle Git Tab                        | `GitHub: Toggle Git Tab`                        | `^⇧ 9`         |
| Toggle GitHub Tab                     | `GitHub: Toggle GitHub Tab`                     | `^⇧ 8`         |
| Toggle Git Tab Focus                  | `GitHub: Toggle Git Tab Focus`                  | `^ 9`          |
| Toggle GitHub Tab Focus               | `GitHub: Toggle GitHub Tab Focus`               | `^ 8`          |
| Activate Next List      | `GitHub: Activate Next List`      | `⇥` |
| Activate Previous List  | `GitHub: Activate Previous List`  | `⇧ ⇥` |
| Close All Diff Views    | `GitHub: Close All Diff Views`    |        |
| Close Empty Diff Views  | `GitHub: Close Empty Diff Views`  |        |

#### Status Bar

| Name              | Command              |
| ----------------- | -------------------- |
| Toggle Status Bar | `Status Bar: Toggle` |

#### Tree View

| Name                   | Command                   | Hotkey |
| ---------------------- | ------------------------- | ---- |
| Toggle Tree View                    | `Tree View: Toggle`                             | `⌘ \` \| `⌘ K` + `⌘ B`       |
| Toggle Tree View Focus              | `Tree View: Toggle Focus`                       | `^ 0`                        |
| Show Tree View         | `Tree View: Show`         |      |
| Unfocus Tree View      | `Tree View: Unfocus`      | `⎋` |

### Panes

| Name                             | Command                                  | Hotkey                                      |
| -------------------------------- | ---------------------------------------- | ------------------------------------------- |
| Show Next Item                   | `Pane: Show Next Item`                   | `⌥⌘ →` \| `⇧⌘ }` \| `^ ⇟` (Pagedown)        |
| Show Previous Item               | `Pane: Show Previous Item`               | `⌥⌘ ←` \| `⇧⌘ {` \| `^ ⇞` (Pageup)          |
| Show Item # (1-9)                | `Pane: Show Item #(1-9)`                 | `⌘ #(1-9)`                                  |
| Show Next Recently Used Item     | `Pane: Show Next Recently Used Item`     | `^ ⇥`                                       |
| Show Previous Recently Used Item | `Pane: Show Previous Recently Used Item` | `^⇧ ⇥`                                      |
| Save Items                       | `Pane: Save Items`                       |                                             |
| Close                            | `Pane: Close`                            | `⌘ K` + `⌘ W`                               |
| Close Other Items                | `Pane: Close Other Items`                | `⌘ K` + `⌥⌘ W`                              |
| Reopen Closed Item               | `Pane: Reopen Closed Item`               | `⇧⌘ T`                                      |
| Move Active Item to Top of Stack | `Pane: Move Active Item To Top Of Stack` | `^ ⇥` + `Release ^` \| `^⇧ ⇥` + `Release ^` |
| Increase Size                    | `Pane: Increase Size`                    | `⌥⌘ =`                                      |
| Decrease Size                    | `Pane: Decrease Size`                    | `⌥⌘ -`                                      |

#### Copy Items

| Name                              | Command                                     |
| --------------------------------- | ------------------------------------------- |
| Copy Active Item to Pane Above    | `Window: Copy Active Item To Pane Above`    |
| Copy Active Item to Pane on Right | `Window: Copy Active Item To Pane On Right` |
| Copy Active Item to Pane Below    | `Window: Copy Active Item To Pane Below`    |
| Copy Active Item to Pane on Left  | `Window: Copy Active Item To Pane On Left`  |

#### Focus

| Name                | Command                       | Hotkey        |
| ------------------- | ----------------------------- | ------------- |
| Focus Next Pane     | `Window: Focus Next Pane`     | `⌘ K` + `⌘ N` |
| Focus Previous Pane | `Window: Focus Previous Pane` | `⌘ K` + `⌘ P` |
| Focus Pane Above    | `Window: Focus Pane Above`    | `⌘ K` + `⌘ ↑` |
| Focus Pane on Left  | `Window: Focus Pane On Right` | `⌘ K` + `⌘ →` |
| Focus Pane Below    | `Window: Focus Pane Below`    | `⌘ K` + `⌘ ↓` |
| Focus Pane on Right | `Window: Focus Pane On Left`  | `⌘ K` + `⌘ ←` |

#### Move Items

| Name | Command | Hotkey |
| ---- | ------- | ---- |
| Move Item Left                     | `Pane: Move Item Left`                    | `^⇧ ←` |
| Move Item Right                    | `Pane: Move Item Right`                   | `^⇧ →` |
| Move Active Item to Panel Above    | `Window: Move Active Item To Pane Above`  |      |
| Move Active Item to Panel on Right | `Window: Move Active Item To Pane On Right` |      |
| Move Active Item to Panel Below    | `Window: Move Active Item To Pane Below`  |      |
| Move Active Item to Panel on Left  | `Window: Move Active Item To Pane On Left` |      |

#### Split Panes

| Name                             | Command                                  | Hotkey      |
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

| Name                | Command                     | Note                                    |
| ------------------- | --------------------------- | --------------------------------------- |
| Keep Pending Tab    | `Tabs: Keep Pending Tab`    | Turns a previewed tab into an open one. |
| Close Tab           | `Tabs: Close Tab`           |                                         |
| Close Tabs to Left  | `Tabs: Close Tabs To Left`  |                                         |
| Close Tabs to Right | `Tabs: Close Tabs To Right` |                                         |
| Close Saved Tabs    | `Tabs: Close Saved Tabs`    |                                         |
| Close Other Tabs    | `Tabs: Close All Tabs`      |                                         |
| Close All Tabs      | `Tabs: Close All Tabs`      |                                         |
| Split Up            | `Tabs: Split Up`            |                                         |
| Split Right         | `Tabs: Split Right`         |                                         |
| Split Down          | `Tabs: Split Down`          |                                         |
| Split Left          | `Tabs: Split Left`          |                                         |
| Open in New Window  | `Tabs: Open In New Window`  |                                         |

### Window

| Name                       | Command                                   | Hotkey  |
| -------------------------- | ----------------------------------------- | ------- |
| New Window                 | `Application: New Window`                 | `⇧⌘ N`  |
| Full Screen                | `Window: Toggle Full Screen`              | `^⌘ F`  |
| Zoom                       | `Application: Zoom`                       | `^⌥⌘ M` |
| Hide                       | `Application: Hide`                       | `⌘ H`   |
| Hide Other Applications    | `Application: Hide Other Applications`    | `⌥⌘ H`  |
| Unhide All Applications    | `Application: Unhide All Applications`    |         |
| Minimize                   | `Application: Minimize`                   | `⌘ M`   |
| Close                      | `Window: Close`                           | `⇧⌘ W`  |
| Bring All Windows to Front | `Application: Bring All Windows to Front` |         |
| Toggle Dev Tools           | `Window: Toggle Dev Tools`                | `⌥⌘ I`  |
| Reload Window              | `Window: Reload`                          | `^⌥⌘ L` |

---

# Packages

## Code

### Duplicate Line or Selection

[Atom Packages](https://atom.io/packages/duplicate-line-or-selection) | [Repo](https://github.com/nick/duplicate-line-or-selection)

> Sublime style duplication.

| Name      | Hotkey           | Note |
| --------- | ---------------- | ---- |
| Duplicate | `^⇧ D` or `⇧⌘ D` |      |

| Name      | Command                                  | Note |
| --------- | ---------------------------------------- | ---- |
| Duplicate | `Duplicate Line or Selection: Duplicate` |      |

### EditorConfig

[Atom Packages](https://atom.io/packages/editorconfig) | [Repo](https://github.com/sindresorhus/atom-editorconfig)

> Helps developers maintain consistent coding styles between different editors

#### Supported properties

- `root`
- `indent_style`
- `indent_size` / `tab_width` *(`indent_size` takes precedence over `tab_width`)*
- `charset` *(supported values: `latin1`, `utf-8`, `utf-16be`, `utf-16le`)*
- `end_of_line` *(supported values: `lf`, `crlf`)*
- `trim_trailing_whitespace` *(supported values: `true`, `false`)*
- `insert_final_newline` *(supported values: `true`, `false`; Setting this to `false` strips final newlines)*
- `max_line_length`

| Name            | Command                         | Note                                                         |
| --------------- | ------------------------------- | ------------------------------------------------------------ |
| Fix File        | `EditorConfig: Fix File`        | Fixes `indent_style` and `end_of_line` issues for the current editor. |
| Show State      | `EditorConfig: Show State`      | Shows the current state of EditorConfig for your current editor. |
| Generate Config | `EditorConfig: Generate Config` | Generates an initial `.editorconfig` for your project.       |

### Tab Control

[Atom Packages](https://atom.io/packages/tab-control) | [Repo](https://github.com/lexicalunit/tab-control)

> Control and view status of indentation settings.

I don't switch my settings often enough to really need the command but I do like seeing the current setting in the status bar so I know what a file I didn't create is set to.

| Name | Command             | Note |
| ---- | ------------------- | ---- |
| Show | `Tab Control: Show` |      |

### Toggle Quotes

[Atom Packages](https://atom.io/packages/toggle-quotes) | [Repo](https://github.com/atom/toggle-quotes)

> Quickly toggle between single and double quotes

| Name   | Hotkey | Note |
| ------ | ------ | ---- |
| Toggle | `⌘⇧ '` |      |

| Name   | Command                 | Note |
| ------ | ----------------------- | ---- |
| Toggle | `Toggle Quotes: Toggle` |      |

---

## Files & Project

### Advanced Open File

[Atom Packages](https://atom.io/packages/advanced-open-file) | [Repo](https://github.com/Osmose/advanced-open-file)

> Open and create files and directories easily. Type in a path (with autocomplete) and view directory contents.

| Name   | Hotkey | Note                                            |
| ------ | ------ | ----------------------------------------------- |
| Toggle | `⌥⌘ O` | Opens interface for opening and creating files. |

| Name   | Command                      | Note                                            |
| ------ | ---------------------------- | ----------------------------------------------- |
| Toggle | `Advanced Open File: Toggle` | Opens interface for opening and creating files. |

### File Bookmark

[Atom Packages](https://atom.io/packages/file-bookmark) | [Repo](https://github.com/akalajzi/atom-file-bookmark)

> Bookmark files in your project for quick access

| Name            | Hotkey | Note |
| --------------- | ------ | ---- |
| Toggle Bookmark | `⌘ ;`  |      |
| Toggle Panel    | `^⌘ :` |      |

| Name                  | Command                                | Note |
| --------------------- | -------------------------------------- | ---- |
| Add                   | `File Bookmark: Add`                   |      |
| Remove                | `File Bookmark: Remove`                |      |
| Toggle Bookmark       | `File Bookmark: Toggle Bookmark`       |      |
| Toggle Panel          | `File Bookmark: Toggle Panel`          |      |
| Toggle Shortcut Icons | `File Bookmark: Toggle Shortcut Icons` |      |

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

| Name   | Hotkey           | Note |
| ------ | ---------------- | ---- |
| Toggle | `⌘ N` or ` ⌘⌥ N` |      |

| Name   | Command                 | Note |
| ------ | ----------------------- | ---- |
| Toggle | `New File Plus: Toggle` |      |

### Open Recent

[Atom Packages](https://atom.io/packages/open-recent) | [Repo](https://github.com/Zren/atom-open-recent)

> Open recent files in the current window, and recent folders (optionally) in a new window.

| Name        | Command                            | Note |
| ----------- | ---------------------------------- | ---- |
| Open Recent | `Open Recent: *File or Directory*` |      |

### Project Manager

[Atom Packages](https://atom.io/packages/project-manager) | [Repo](https://github.com/danielbrodin/atom-project-manager)

> Project Manager for easy access and switching between projects in Atom.

#### Project Settings

| setting    | Type      | Description                                                  | Default                |
| ---------- | --------- | ------------------------------------------------------------ | ---------------------- |
| `title`    | `string`  | Projects title. Used in the projects list                    | `''`                   |
| `paths`    | `array`   | The folders that will open in the tree view. First path is the main one that counts as the project. | `[]`                   |
| `settings` | `Object`  | Enables you to set project specific settings. Everything that goes in the `config.cson` file can go here. It also supports scoped settings. | `{}`                   |
| `icon`     | `string`  | Icon that shows in the projects list. It's class-based so can either be a class already provided by Atom like `icon-squirrel` or a class of your own. You can find a list of all icons on [octicons.github.com](https://octicons.github.com/). | `'icon-chevron-right'` |
| `devMode`  | `boolean` | `true` if project should open in dev mode. [Look here](https://atom.io/docs/api/v1.11.2/AtomEnvironment#instance-open) for more info. | `false`                |
| `group`    | `string`  | Adds a group to the projects list that can be used to group and filter projects | `null`                 |
| `template` | `string`  | If you add a project in the `projects.cson` file without `paths` it will count as a template. This way you can easily share settings between projects | `null`                 |

| Name          | Hotkey | Note |
| ------------- | ------ | ---- |
| List Projects | `^⌘ P` |      |

| Name            | Command                            | Note                                                         |
| --------------- | ---------------------------------- | ------------------------------------------------------------ |
| List Projects   | `Project Manager: List Projects`   | Projects can be filtered by `title`, `group` and `template` by typing `group: atom` which would give all projects with the `atom` group. |
| Edit Project    | `Project Manager: Edit Project`    | Open a page where you can edit the current project. It currently only supports certain fields. |
| Save Project    | `Project Manager: Save Project`    | Write the title you want to save the project as.             |
| Edit Projects   | `Project Manager: Edit Projects`   | All projects are saved in a `.cson` file which you can easily reach by searching for `Project Manager: Edit Projects` in the Command Palette. |
| Update Projects | `Project Manager: Update Projects` |                                                              |

### Promote Folder to Project

[Atom Packages](https://atom.io/packages/promote-folder-to-project) | [Repo](https://github.com/forivall/atom-promote-folder-to-project)

> Add folders to your current project by right clicking on them in the tree view

| Name               | Command                                         | Note |
| ------------------ | ----------------------------------------------- | ---- |
| Add Project Folder | `Promote Folder To Project: Add Project Folder` |      |

### Prompt Big File

[Atom Packages](https://atom.io/packages/prompt-big-file) | [Repo](https://github.com/ajuste/atom-prompt-big-file)

> Avoid opening big files by accident which might cause Atom to stop responding

The default file threshold is 1Mb but can be changed.

### Set Syntax

[Atom Packages](https://atom.io/packages/set-syntax) | [Repo](https://atom.io/packages/set-syntax)

> Creates easy Command Palette commands for setting the syntax of the current file

| Name            | Command                     | Note |
| --------------- | --------------------------- | ---- |
| \*Syntax Name\* | `Set Syntax: *Syntax Name*` |      |

---

## Language Specific

### Property List (PLIST)

#### Property List Converter

[Atom Packages](https://atom.io/packages/plist-converter) | [Repo](https://github.com/danielbayley/atom-plist-converter)

> Automatically convert binary `.plist` files on macOS.

### Regex

#### Language Regexp

[Atom Packages](https://atom.io/packages/language-regexp) | [Repo](https://github.com/Alhadis/language-regexp)

> Bleeding edge, engine-agnostic highlighting for regular expression data.

### Regex Railroad Diagram

[Atom Packages](https://atom.io/packages/regex-railroad-diagram) | [Repo](https://github.com/klorenz/atom-regex-railroad-diagrams)

> Display railroad diagram of regex under cursor.

| Name | Hotkey        | Note |
| ---- | ------------- | ---- |
| Show | `⌘ R` + `⌘ R` |      |

| Name    | Command                           | Note |
| ------- | --------------------------------- | ---- |
| Show    | `Regex Railroad Diagram: Show`    |      |
| Enable  | `Regex Railroad Diagram: Enable`  |      |
| Disable | `Regex Railroad Diagram: Disable` |      |

---

## Package Management, Keybindings & Settings

### Auto-Update-Packages

[Atom Packages](https://atom.io/packages/auto-update-packages) | [Repo](https://github.com/yujinakayama/atom-auto-update-packages)

> Keep your Atom packages up to date.

Auto updates Atom packages every six hours or by a set interval.

| Name       | Command                            | Note |
| ---------- | ---------------------------------- | ---- |
| Update Now | `Auto Update Packages: Update Now` |      |

### Editor Settings

[Atom Packages](https://atom.io/packages/editor-settings) | [Repo](https://github.com/nirix/atom-editor-settings)

> Editor settings per-language, extension and directory.

### Keybinding Cheatsheet

[Atom Packages](https://atom.io/packages/keybinding-cheatsheet) | [Repo](https://github.com/jkasky/atom-keybinding-cheatsheet)

> Quickly view and filter atom keybindings.

| Name   | Hotkey | Note |
| ------ | ------ | ---- |
| Toggle | `^⌥ /` |      |

| Name   | Command                         | Note |
| ------ | ------------------------------- | ---- |
| Toggle | `Keybinding Cheatsheet: Toggle` |      |

### Sync Settings

[Atom Packages](https://atom.io/packages/sync-settings) | [Repo](https://github.com/atom-community/sync-settings)

> Synchronize package settings, keymap and installed packages

This package uses a GitHub Gist to sync your settings and requires a Personal Access Token for GitHub and a Gist ID to use.

| Name         | Command                       | Note                                                |
| ------------ | ----------------------------- | --------------------------------------------------- |
| Fork         | `Sync Settings: Fork`         | Fork existing settings from a different GitHub user |
| Backup       | `Sync Settings: Backup`       | Backup all settings                                 |
| Restore      | `Sync Settings: Restore`      | Restore all settings                                |
| View Backup  | `Sync Settings: View Backup`  | View your online backup                             |
| Check Backup | `Sync Settings: Check Backup` | Check the latest backup is applied                  |

---

## Reference

### Dash

[Atom Packages](https://atom.io/packages/dash) | [Repo](https://github.com/blakeembrey/atom-dash)

> Dash documentation integration with Atom

| Name                | Hotkey             | Note                                                        |
| ------------------- | ------------------ | ----------------------------------------------------------- |
| Shortcut            | `^ H`              | This uses a scoped search based on the filename and syntax. |
| Shortcut Alt        | ` ^⌥⇧ H` or `^⌥ H` | Search all documentation across grammars.                   |
| Shortcut Background | `^⇧ H`             | Same as shortcut but in the background.                     |

| Name                    | Command                         | Note                                                         |
| ----------------------- | ------------------------------- | ------------------------------------------------------------ |
| Shortcut                | `Dash: Shortcut`                | This uses a scoped search based on the filename and syntax.  |
| Shortcut Alt            | `Dash: Shortcut Alt`            | Search all documentation across grammars.                    |
| Context Menu            | `Dash: Context Menu`            | Seems to be same as shortcut, there is a right click menu option. |
| Shortcut Background     | `Dash: Shortcut Background`     | Same as shortcut but in the background.                      |
| Shortcut Alt Background | `Dash: Shortcut Alt Background` | Same as shortcut alt but in the background.                  |

---

## Scripts & Terminal

### Project Shell Env

[Atom Packages](https://atom.io/packages/000-project-shell-env) | [Repo](https://github.com/ddiachkov/atom-project-shell-env)

> Atom package to load shell env variables from project directory

| Name  | Command                    | Note |
| ----- | -------------------------- | ---- |
| Load  | `Project Shell Env: Load`  |      |
| Reset | `Project Shell Env: Reset` |      |

---

## Snippets

### Atomizr

[Atom Packages](https://atom.io/packages/atomizr) | [Repo](https://github.com/idleberg/atom-atomizr)

> Converts snippets for Atom, Sublime Text, TextMate, and Visual Studio Code

| Name                               | Hotkey        | Note |
| ---------------------------------- | ------------- | ---- |
| Toggle Atom Format                 | `^ A` + `^ A` |      |
| Atom to Sublime Text               | `^ A` + `^ S` |      |
| Atom to TextMate                   | `^ A` + `^ T` |      |
| Atom to Visual Studio Code         | `^ A` + `^ V` |      |
| Automatic Conversion               | `^ C` + `^ C` |      |
| Sublime Text to Atom               | `^ S` + `^ A` |      |
| Sublime Subformat                  | `^ S` + `^ S` |      |
| Sublime Text to Textmate           | `^ S` + `^ T` |      |
| Sublime Text to Visual Studio Code | `^ A` + `^ V` |      |
| TextMate to Atom                   | `^ T` + `^ A` |      |
| Textmate to Sublime Text           | `^ T` + `^ S` |      |
| Textmate to Visual Studio Code     | `^ T` + `^ V` |      |
| Visual Studio Code to Atom         | `^ V` + `^ A` |      |
| Visual Studio Code to Sublime Text | `^ V` + `^ S` |      |
| Visual Studio Code to Textmate     | `^ V` + `^ T` |      |

| Name                               | Command                                               | Note |
| ---------------------------------- | ----------------------------------------------------- | ---- |
| Toggle Atom Format                 | `Atomizr: Toggle Atom Format`                         |      |
| Automatic Conversion               | `Atomizr: Automatic Conversion`                       |      |
| Sublime Subformat                  | `Atomizr: Sublime Subformat`                          |      |
| Atom to Sublime Text               | `Atomizr: Convert Atom to Sublime Text`               |      |
| Atom to TextMate                   | `Atomizr: Convert Atom to Textmate`                   |      |
| Atom to Visual Studio Code         | `Atomizr: Convert Atom to Visual Studio Code`         |      |
| Sublime Text to Atom               | `Atomizr: Convert Sublime Text to Atom`               |      |
| Sublime Text to Textmate           | `Atomizr: Convert Sublime Text to Textmate`           |      |
| Sublime Text to Visual Studio Code | `Atomizr: Convert Sublime Text to Visual Studio Code` |      |
| TextMate to Atom                   | `Atomizr: Convert Textmate to Atom`                   |      |
| Textmate to Sublime Text           | `Atomizr: Convert Textmate to Sublime Text`           |      |
| Textmate to Visual Studio Code     | `Atomizr: Convert Textmate to Visual Studio Code`     |      |
| Visual Studio Code to Atom         | `Atomizr: Convert Visual Studio Code to Atom`         |      |
| Visual Studio Code to Sublime Text | `Atomizr: Convert Visual Studio Code to Sublime Text` |      |
| Visual Studio Code to Textmate     | `Atomizr: Convert Visual Studio Code to Textmate`     |      |
| Open Package Settings              | `Atomizr: Open Package Settings`                      |      |
---

## Source Control

### Open Project in Tower

[Atom Packages](https://atom.io/packages/open-project-in-tower) | [Repo](https://github.com/jwohlfeil/atom-open-project-in-tower)

> Open current project in Tower

| Name | Hotkey | Note |
| ---- | ------ | ---- |
| Open | `^⌥ R` |      |

| Name | Command                       | Note |
| ---- | ----------------------------- | ---- |
| Open | `Open Project In Tower: Open` |      |

---

## Text Editor

### Cursor History

[Atom Packages](https://atom.io/packages/cursor-history) | [Repo](https://atom.io/packages/cursor-history)

> Cursor position history manager

| Name               | Hotkey | Note                                                   |
| ------------------ | ------ | ------------------------------------------------------ |
| Next               | `^ -`  | Go to next point in history.                           |
| Prev               | `^ =`  | Go to previous point in history.                       |
| Next Within Editor | `^⌘ -` | Go to next point in history within current editor.     |
| Prev Within Editor | `^⌘ =` | Go to previous point in history within current editor. |

| Name               | Command                              | Note                                                   |
| ------------------ | ------------------------------------ | ------------------------------------------------------ |
| Next               | `Cursor History: Next`               | Go to next point in history.                           |
| Prev               | `Cursor History: Prev`               | Go to previous point in history.                       |
| Next Within Editor | `Cursor History: Next Within Editor` | Go to next point in history within current editor.     |
| Prev Within Editor | `Cursor History: Prev Within Editor` | Go to previous point in history within current editor. |
| Clear              | `Cursor History: Clear`              | Clear history                                          |

### Highlight Line

[Atom Packages](https://atom.io/packages/highlight-line) | [Repo](https://github.com/richrace/highlight-line)

> Highlights the current line in the editor

| Name                            | Hotkey  | Note |
| ------------------------------- | ------- | ---- |
| Toggle Underline                | `⇧⌘ U`  |      |
| Toggle Background               | `⌥⇧⌘ U` |      |
| Toggle Selection Borders        | `⇧⌘ H`  |      |
| Toggle Hide Highlight on Select | `⌥⇧⌘ H` |      |

| Name                            | Command                                           | Note |
| ------------------------------- | ------------------------------------------------- | ---- |
| Toggle Underline                | `Highlight Line: Toggle Underline`                |      |
| Toggle Background               | `Highlight Line: Toggle Background`               |      |
| Toggle Selection Borders        | `Highlight Line: Toggle Selection Borders`        |      |
| Toggle Hide Highlight on Select | `Highlight Line: Toggle Hide Highlight On Select` |      |

### Highlight Selected

[Atom Packages](https://atom.io/packages/highlight-selected) | [Repo](https://github.com/richrace/highlight-selected)

> Highlights the current word selected when double clicking

| Name   | Hotkey | Note |
| ------ | ------ | ---- |
| Toggle | `^⌘ H` |      |

| Name   | Command                      | Note |
| ------ | ---------------------------- | ---- |
| Toggle | `Highlight Selected: Toggle` |      |

### Indent Guide Improved

[Atom Packages](Highlight Selected: Toggle) | [Repo](https://github.com/harai/indent-guide-improved)

> This draws indent guide more correctly and understandably.

### Jumpy

[Atom Packages](https://atom.io/packages/jumpy) | [Repo](https://github.com/DavidLGoldberg/jumpy)

> An Atom package that creates dynamic hotkeys to jump around files across visible panes.

| Name   | Hotkey                     | Note |
| ------ | -------------------------- | ---- |
| Toggle | `⇧ ↩`                      |      |
| Reset  | `⌫`                        |      |
| Clear  | `↩`, `⎋`, `⇧ ↩` or `space` |      |

| Name   | Command         | Note |
| ------ | --------------- | ---- |
| Toggle | `Jumpy: Toggle` |      |
| Reset  | `Jumpy: Reset`  |      |
| Clear  | `Jumpy: Clear`  |      |

### Pigmets

[Atom Packages](https://atom.io/packages/pigments) | [Repo](https://github.com/abe33/atom-pigments)

> A package to display colors in project and files.

| Name            | Command                      | Note                                                   |
| --------------- | ---------------------------- | ------------------------------------------------------ |
| Show Palette    | `Pigments: Show Palette`     | Shows a global palette for the project                 |
| Find Colors     | `Pigments: Find Colors`      | Search for all of the colors in the project            |
| Convert To \*   | `Pigments: Convert To *`     | Converts color to Hex, HSL/HSLA and RGB/RGBA           |
| Copy As \*      | `Pigments: Copy as *`        | Copy color as Hex, HSL/HSLA and RGB/RGBA               |
| Project Setting | `Pigments: Project-Settings` | Open project specific settings                         |
| Reload          | `Pigments: Reload`           | Force reload all variables for the project             |
| Report          | `Pigments: Report`           | Generates a JSON array of information for a bug report |

### Sublime Style Column Selection

[Atom Packages](https://atom.io/packages/Sublime-Style-Column-Selection) | [Repo](https://github.com/bigfive/atom-sublime-select)

> Enable Sublime style 'Column Selection'. Just hold 'alt' while you select, or select using your middle mouse button. Also similar to Texmate's 'Multiple Carets', or BBEdit's 'Block Select'

| Name          | Hotkey             | Note |
| ------------- | ------------------ | ---- |
| Column Select | `⌥` + `Left Click` |      |

---

## Theme

### File Icons

[Atom Packages](https://atom.io/packages/file-icons) | [Repo](https://github.com/file-icons/atom)

> Assign file extension icons and colours for improved visual grepping

---

## Tracking

### Editor Stats

[Atom Packages](https://atom.io/packages/editor-stats) | [Repo](https://github.com/atom/editor-stats)

> Display a graph of keyboard and mouse usage for the last 6 hours.

| Name   | Command                | Note |
| ------ | ---------------------- | ---- |
| Toggle | `Editor Stats: Toggle` |      |

### WakaTime

[Atom Packages](https://atom.io/packages/wakatime) | [Repo](https://github.com/wakatime/atom-wakatime)

> Fitbit for programmers. Get automated metrics and insights about your programming.

---

## UI

### Expose

[Atom Packages](https://atom.io/packages/expose) | [Repo](https://github.com/mrodalgaard/atom-expose)

> Quick tab overview of open files

| Name          | Hotkey | Note |
| ------------- | ------ | ---- |
| Toggle        | `⌘⇧ E` |      |
| Next Item     | `⇥`    |      |
| Previous Item | `⇧ ⇥`  |      |

| Name   | Command          | Note |
| ------ | ---------------- | ---- |
| Toggle | `Expose: Toggle` |      |

### Maximize Panes

[Atom Packages](https://atom.io/packages/maximize-panes) | [Repo](https://github.com/santip/maximize-panes)

> Maximize panes to occupy the entire window without closing other panes

| Name     | Hotkey | Note |
| -------- | ------ | ---- |
| Maximize | `⌘⇧ ↩` |      |

| Name     | Command                    | Note |
| -------- | -------------------------- | ---- |
| Maximize | `Maximize Panes: Maximize` |      |

### Menu Manager

[Atom Packages](https://atom.io/packages/menu-manager) | [Repo](https://github.com/jerone/menu-manager)

> Menu Manager shows main menu items and all context menu items from Atom.

| Name | Command              | Note |
| ---- | -------------------- | ---- |
| Show | `Menu Manager: Show` |      |

### Minimap

[Atom Packages](https://atom.io/packages/minimap) | [Repo](https://github.com/atom-minimap/minimap)

> A preview of the full source code.

| Name                       | Command                               | Note                            |
| -------------------------- | ------------------------------------- | ------------------------------- |
| Toggle                     | `Minimap: Toggle`                     |                                 |
| Generate Babel Plugin      | `Minimap: Generate Babel Plugin`      | For developing a minimap plugin |
| Generate Coffee Plugin     | `Minimap: Generate Coffee Plugin`     | For developing a minimap plugin |
| Generate Javascript Plugin | `Minimap: Generate Javascript Plugin` | For developing a minimap plugin |

### Pinned Tabs

[Atom Packages](https://atom.io/packages/pinned-tabs) | [Repo](https://github.com/ericcornelissen/pinned-tabs-for-atom)

> An Atom package that allows you to pin tabs

| Name       | Hotkey | Note |
| ---------- | ------ | ---- |
| Pin Active | `^⌥ P` |      |

| Name           | Command                       | Note |
| -------------- | ----------------------------- | ---- |
| Pin Active     | `Pinned Tabs: Pin Active`     |      |
| Close Unpinned | `Pinned Tabs: Close Unpinned` |      |

### Rename Tabs

[Atom Packages](https://atom.io/packages/rename-tabs) | [Repo](https://github.com/jprichardson/atom-rename-tabs)

> Rename tabs titles with previous directory. Consistent with Sublime Text Editor behavior.

> Renames your Atom Text Editor tab titles to more useful names if there are many instances of the same file name open. This is consistent with Sublime Text editor tab title behavior.
>
> Atom's tab naming isn't very helpful if there are multiple files with the same name open. This package is useful if you write Node.js app with a lot of files named `index.js`. Atom would title the tabs `index.js - /my/project...`. That's not very helpful. Assuming you have two files: `/my/project/foo/index.js` and`/my/project/bar/index.js` the tabs to `index.js - foo` and `index.js - bar` respectively.
>
> To be clear, this isn't only for Node.js developers. This is for those who like Sublime Text editor's tab title convention.

### Tab Title

[Atom Packages](https://atom.io/packages/tab-title) | [Repo](https://github.com/erikjansson/atom-tab-title)

> Give your unsaved tabs better names. Because "Untitled" is about as useful as dinosaur repellent.

> The behavior is heavily inspired from Sublime Text.

Basically just mirrors the beginning of the text in the editor until you give it a real filename.

### Tool Bar

[Atom Packages](https://atom.io/packages/tool-bar) | [Repo](https://github.com/suda/tool-bar)

> Package providing customisable tool bar

| Name   | Hotkey | Note |
| ------ | ------ | ---- |
| Toggle | `^⌥ T` |      |

| Name            | Command                     | Note |
| --------------- | --------------------------- | ---- |
| Toggle          | `Tool Bar: Toggle`          |      |
| Position Top    | `Tool Bar: Position Top`    |      |
| Position Left   | `Tool Bar: Position Left`   |      |
| Position Right  | `Tool Bar: Position Right`  |      |
| Position Bottom | `Tool Bar: Position Bottom` |      |

### Toolbar Almighty

[Atom Packages](https://atom.io/packages/tool-bar-almighty) | [Repo](https://github.com/varemenos/atom-toolbar-almighty)

> A tool-bar plugin that adds an 'almighty toolbar' with many commonly used actions

I've used this to customize the toolbar pretty heavily, it works better than customizing the Tool Bar package directly.

### Tree View Filter

[Atom Packages](https://atom.io/packages/tree-view-filter) | [Repo](https://github.com/monsterkodi/tree-view-filter)

> Limits files in the tree-view to those matching certain patterns

> Press `ctrl-alt-shift-f` or invoke `Tree View Filter:Activate` to focus the filter editor, enter your pattern and press `enter`/`return` to confirm.
>
> The filter shows only files that match the provided pattern(s): e.g. `md coffee` shows all files that have *md* or *coffee* in their filename.
>
> You can reverse the search by prepending an exclamation mark: e.g. `!*.md !.*` hides all *markdown* and *dotfiles*.
>
> Note that the `Fuzzy search` option only works in the first case.
>
> To restore the tree view to its unfiltered state:
> either press `escape` when the filter has focus or click on the `(x)` button to the right.

| Name     | Hotkey  | Note |
| -------- | ------- | ---- |
| Activate | `^⌥⇧ F` |      |
| Toggle   | `⌥⇧⌘ F` |      |

| Name     | Command                      | Note |
| -------- | ---------------------------- | ---- |
| Activate | `Tree View Filter: Activate` |      |
| Toggle   | `Tree View Filter: Toggle`   |      |

---

# Command Line

## Launching Atom

> Another way to open a file in Atom is from the command line using the `atom` command. […]
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

[Atom Flight Manual: Atom Basics - Opening a File](http://flight-manual.atom.io/getting-started/sections/atom-basics/#opening-a-file)

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

[Atom Flight Manual: Atom Packages - Command Line](https://flight-manual.atom.io/using-atom/sections/atom-packages/#command-line)

Commands:

| Command                    | Aliases                               | Note                                                         |
| -------------------------- | ------------------------------------- | ------------------------------------------------------------ |
| `apm clean`                |                                       | Deletes all packages in the `node_modules` folder that are not referenced as a dependency in the package.json file. |
| `apm config`               |                                       | Pass-through to `npm config`: Manage the npm configuration files. [Pull Request](https://github.com/atom/apm/pull/258) |
| `apm dedupe`               |                                       | Reduce duplication in the `node_modules` folder in the current directory. |
| `apm develop`              | `dev`                                 | Clone the given package's Git repository to the directory specified, install its dependencies, and link it for development to `~/.atom/dev/packages/<package_name>`. |
| `apm disable`              |                                       | Disables the named package(s).                               |
| `apm docs`                 | `open`                                | Open a package's homepage in the default browser.            |
| `apm enable`               |                                       | Enables the named package(s).                                |
| `apm init`                 |                                       | Generates code scaffolding for either a theme or package depending on the option selected. |
| `apm install`              | `i`                                   | Install the given Atom package to `~/.atom/packages/<package_name>`. |
| `apm link`                 | `ln`                                  | Create a symlink for the package in `~/.atom/packages`. The package in the current working directory is linked if no path is given. |
| `apm links`                | `linked`, `lns`                       | List all of the symlinked atom packages in `~/.atom/packages` and `~/.atom/dev/packages`. |
| `apm list`                 | `ls`                                  | List all the installed packages and also the packages bundled with Atom. |
| `apm login`                |                                       | Enter your Atom.io API token and save it to the keychain. This token will be used to identify you when publishing packages to atom.io. |
| `apm publish`              |                                       | Publish a new version of the package in the current working directory. |
| `apm rebuild`              |                                       | Rebuild the given modules currently installed in the node_modules folder |
| `apm rebuild-module-cache` |                                       | Rebuild the module cache for all the packages installed to `~/.atom/packages` |
| `apm search`               |                                       | Search for Atom packages/themes on the atom.io registry.     |
| `apm star`                 |                                       | Star the given packages on https://atom.io                   |
| `apm stars`                | `starred`                             | List or install starred Atom packages and themes.            |
| `apm test`                 |                                       | Runs the package's tests contained within the spec directory (relative to the current working directory). |
| `apm uninstall`            | `deinstall`, `delete`, `remove`, `rm` | Delete the installed package(s) from the `~/.atom/packages` directory. |
| `apm unlink`               |                                       | Delete the symlink in `~/.atom/packages` for the package. The package in the current working directory is unlinked if no path is given. |
| `apm unpublish`            |                                       | Remove a published package or package version from the atom.io registry. |
| `apm unstar`               |                                       | Unstar the given packages on https://atom.io                 |
| `apm upgrade`              | `outdated`, `update`                  | Upgrade out of date packages installed to `~/.atom/packages` |
| `apm view`                 | `show`                                | View information about a package/theme in the atom.io registry. |

For usage and further information use `apm help *command*`.

---

## Dev Mode

From the [Atom Flight Manual](http://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/#creating-a-syntax-theme)

> **Tip:** You can avoid reloading to see changes you make by opening an Atom window in Dev Mode. To open a Dev Mode Atom window run `atom --dev .` in the terminal, or use the *View > Developer > Open in Dev Mode* menu. When you edit your theme, changes will instantly be reflected!

```shell
atom --dev .
```

## Safe Mode

From the [Atom Flight Manual](http://flight-manual.atom.io/hacking-atom/sections/debugging/#using-safe-mode)

> A large part of Atom's functionality comes from packages you can install. Atom will also execute the code in your [init script](http://flight-manual.atom.io/hacking-atom/sections/the-init-file) on startup. In some cases, these packages and the code in the init script might be causing unexpected behavior, problems, or performance issues.

To diagnose the problems you can start Atom in Safe Mode from command line:

```shell
atom --safe
```

> This starts Atom, but does not load packages from `~/.atom/packages` or `~/.atom/dev/packages` and disables loading of your init script. If you can no longer reproduce the problem in safe mode, it's likely it was caused by one of the packages or the init script.

## Profiling Startup Performance

From the [Atom Flight Manual](atom --profile-startup .)

> If the time for loading the window looks high, you can create a CPU profile for that period using the `--profile-startup` command line flag when starting Atom:

```shell
atom --profile-startup .
```

## Clearing Save State

From the [Atom Flight Manual](http://flight-manual.atom.io/hacking-atom/sections/debugging/#clearing-saved-state)

> Atom saves a number of things about your environment when you exit in order to restore Atom to the same configuration when you next launch the program. In some cases the state that gets saved can be something undesirable that prevents Atom from working properly. In these cases, you may want to clear the state that Atom has saved.

Use the following command to clear Atom's saved state:

`````bash
atom --clear-window-state
`````
