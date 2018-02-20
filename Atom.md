 title: Atom Cheatsheet

# Atom Commands

---

#  Commands

## Actions

| Name           | Command                | Note |
| -------------- | ---------------------- | ---- |
| Confirm        | `Core: Confirm`        |      |
| Cancel         | `Core: Cancel`         |      |
| Focus Next     | `Core: Focus Next`     |      |
| Focus Previous | `Core: Focus Previous` |      |
| Delete         | `Core: Delete`         |      |
| Close          | `Core: Close`          |      |
| Undo           | `Core: Undo`           |      |
| Redo           | `Core: Redo`           |      |
| Unfocus Panels | `Tool Panel: Unfocus`  |      |

### Application

| Name                   | Command                          | Note                                       |
| ---------------------- | -------------------------------- | ------------------------------------------ |
| Quit                   | `Application: Quit`              |                                            |
| Install Update         | `Application: Install Update`    |                                            |
| Install Shell Commands | `Window: Install Shell Commands` |                                            |
| Open License           | `Application: Open License`      | Opens Atom's application license in a file |

### Bookmarks

| Name                         | Command                                  | Note |
| ---------------------------- | ---------------------------------------- | ---- |
| Toggle Bookmark              | `Bookmarks: Toggle Bookmark`             |      |
| Jump to Next Bookmark        | `Bookmarks: Jump to Next Bookmark`       |      |
| Jump to Previous Bookmark    | `Bookmarks: Jump to Previous Bookmark`   |      |
| Select to Next Bookmark      | `Bookmarks: Select to Next Bookmark`     |      |
| Select to Previous Bookmarks | `Bookmarks: Select to Previous Bookmark` |      |
| Clear Bookmarks              | `Bookmarks: Clear Bookmarks`             |      |
| View All                     | `Bookmarks: View All`                    |      |

### Browser

| Name  | Command              | Note       |
| ----- | -------------------- | ---------- |
| Open Link | `Link: Open` | Opens http(s) links under cursor |
| View Release Notes | `About: View Release Notes` |                                              |
### Clipboard

| Name                       | Command                              | Note                                                         |
| -------------------------- | ------------------------------------ | ------------------------------------------------------------ |
| Copy                       | `Core: Copy`                         |                                                              |
| Cut                        | `Core: Cut`                          |                                                              |
| Paste                      | `Core: Paste`                        |                                                              |
| Copy Selection             | `Editor: Copy Selection`             | Redundant copy command for selection                         |
| Cut to End of Line         | `Editor: Cut To End Of Line`         |                                                              |
| Cut to End of Buffer Line  | `Editor: Cut To End Of Buffer Line`  | If code is selected cut selection, otherwise, cut from cursor to the end of the line. |
| Paste Without Reformatting | `Editor: Paste Without Reformatting` |                                                              |

#### Paths

| Name              | Command                     | Note                                              |
| ----------------- | --------------------------- | ------------------------------------------------- |
| Copy Path         | `Editor: Copy Path`         | Copy current file's absolute path                 |
| Copy Project Path | `Editor: Copy Project Path` | Copy current file's path relative to project root |

### Developer

| Name | Command | Note |
| ---- | ------- | ---- |
| Reload Window | `Window: Toggle Dev Tools` |  |
| Toggle Dev Tools | `Window: Toggle Dev Tools` |  |
| Log (Display) Cursor Scope | `Editor: Log Cursor Scope` | |
| Log Deprecation Warnings | `Window: Log Deprecation Warnings` |  |
| Styleguide | `Styleguide: Show` | Exercises all UI components and acts as a styleguide. |
| Timecop | `Timecop: View` |  |
| Generate Package | `Package Generator: Generate Package` | |
| Generate Language Package | `Package Generator: Generate Language Package` | |
| Generate Syntax Theme | `Package Generator: Generate Syntax Theme` | |
| Update Package Dependencies | `Update Package Dependencies: Update` | |
| Incompatible Packages | `Incompatible Packages: View` | |
| Run Benchmarks | `Window: Run Benchmarks` |  |
| Run Package Specs | `Window: Run Package Specs` |  |
| Clear Update State | `About: Clear Update State` | [Info](https://github.com/atom/about/pull/66) |
| Show Waterfall Diagnostics | `GitHub: Show Waterfall Diagnostics` |  |

### Editor

#### Casing

| Name       | Command              | Note |
| ---------- | -------------------- | ---- |
| Lower Case | `Editor: Lower Case` |      |
| Upper Case | `Editor: Upper Case` |      |

#### Deletion

##### Delete by Subword

| Name                           | Command                                  | Note |
| ------------------------------ | ---------------------------------------- | ---- |
| Delete to Beginning of Subword | `Editor: Delete To Beginning Of Subword` |      |
| Delete to End of Subword       | `Editor: Delete To End Of Subword`       |      |

##### Delete by Word

| Name                             | Command                                    | Note |
| -------------------------------- | ------------------------------------------ | ---- |
| Delete to Beginning of Word      | `Editor: Delete To Beginning Of Word`      |      |
| Delete to End of Word            | `Editor: Delete To End Of Word`            |      |
| Delete to Next Word Boundary     | `Editor: Delete To Next Word Boundary`     |      |
| Delete to Previous Word Boundary | `Editor: Delete To Previous Word Boundary` |      |

##### Delete by Line

| Name                        | Command                               | Note |
| --------------------------- | ------------------------------------- | ---- |
| Delete Line                 | `Editor: Delete Line`                 |      |
| Delete to Beginning of Line | `Editor: Delete To Beginning Of Line` |      |
| Delete to End of Line       | `Editor: Delete To End Of Line`       |      |

#### Folding

| Name                         | Command                               | Note |
| ---------------------------- | ------------------------------------- | ---- |
| Fold Current Row             | `Editor: Fold Current Row`            |      |
| Unfold Current Row           | `Editor: Unfold Current Row`          |      |
| Fold Selection               | `Editor: Fold Selection`              |      |
| Fold All                     | `Editor: Fold All`                    |      |
| Unfold All                   | `Editor: Unfold All`                  |      |
| Fold at Indent Level # (1-9) | `Editor: Fold At Indent Level #(1-9)` |      |

#### Formatting

| Name     | Command                      | Note                                                         |
| -------- | ---------------------------- | ------------------------------------------------------------ |
| Autoflow | `Autoflow: Reflow Selection` | Hard wraps at no more than preferred line length (80 characters by default). [Info](https://atom.io/packages/autoflow) |

#### Indentation

| Name                  | Command                         | Note |
| --------------------- | ------------------------------- | ---- |
| Indent                | `Editor: Indent`                |      |
| Indent Selected Rows  | `Editor: Indent Selected Rows`  |      |
| Outdent Selected Rows | `Editor: Outdent Selected Rows` |      |

#### Line Manipulation

| Name            | Command                               | Note |
| --------------- | ------------------------------------- | ---- |
| Newline         | `Editor: Newline`                     |      |
| Newline Above   | `Editor: Newline`                     |      |
| Newline Below   | `Editor: Newline Below`               |      |
| Duplicate Lines | `Editor: Duplicate Lines`             |      |
| Join Lines      | `Editor: Join Lines`                  |      |
| Split           | `Editor: Split Selections Into Lines` |      |
| Comment Line    | `Editor: Toggle Line Comments`        |      |

#### Move Text

##### Move by Character

| Name                 | Command                        | Note                                                         |
| -------------------- | ------------------------------ | ------------------------------------------------------------ |
| Move Selection Left  | `Editor: Move Selection Left`  |                                                              |
| Move Selection Right | `Editor: Move Selection Right` |                                                              |
| Transpose            | `Editor: Transpose`            | Switches character on left of cursor with that on right or reverses text if selection. |

##### Move by Line

| Name           | Command                  | Note |
| -------------- | ------------------------ | ---- |
| Move Line Up   | `Editor: Move Line Up`   |      |
| Move Line Down | `Editor: Move Line Down` |      |

#### Navigation

| Name             | Command                    | Note |
| ---------------- | -------------------------- | ---- |
| Move Up          | `Core: Move Up`            |      |
| Move Right       | `Core: Move Right`         |      |
| Move Down        | `Core: Move Down`          |      |
| Move Left        | `Core: Move Left`          |      |
| Scroll to Cursor | `Editor: Scroll To Cursor` |      |

##### Move by Subword

| Name                              | Command                                     | Note |
| --------------------------------- | ------------------------------------------- | ---- |
| Move to Previous Subword Boundary | `Editor: Move To Previous Subword Boundary` |      |
| Move to Next Subword Boundary     | `Editor: Move To Next Subword Boundary`     |      |

##### Move by Word

| Name                           | Command                                  | Note |
| ------------------------------ | ---------------------------------------- | ---- |
| Move to Beginning of Word      | `Editor: Move To Beginning Of Word`      |      |
| Move to End of Word            | `Editor: Move To End Of Word`            |      |
| Move to Previous Word Boundary | `Editor: Move To Previous Word Boundary` |      |
| Move to Next Word Boundary     | `Editor: Move To Next Word Boundary`     |      |
| Move to Beginning of Next Word | `Editor: Move To Beginning Of Next Word` |      |

##### Move by Line

| Name                             | Command                                    | Note             |
| -------------------------------- | ------------------------------------------ | ---------------- |
| Move to First Character of Line  | `Editor: Move To First Character Of Line`  | After whitespace |
| Move to Beginning of Line        | `Editor: Move To Beginning Of Line`        |                  |
| Move to End of Line              | `Editor: Move To End Of Line`              |                  |
| Move to Beginning of Screen Line | `Editor: Move To Beginning Of Screen Line` |                  |
| Move to End of Screen Line       | `Editor: Move To End Of Screen Line`       |                  |
| Go To Line                       | `Go To Line: Toggle`                       |                  |

##### Move by Paragraph

| Name                                    | Command                                           | Note |
| --------------------------------------- | ------------------------------------------------- | ---- |
| Move to Beginning of Previous Paragraph | `Editor: Move To Beginning Of Previous Paragraph` |      |
| Move to Beginning of Next Paragraph     | `Editor: Move To Beginning Of Next Paragraph`     |      |

##### Move by Screen

| Name      | Command           | Note |
| --------- | ----------------- | ---- |
| Page Up   | `Core: Page Down` |      |
| Page Down | `Core: Page Up`   |      |

##### Move by File

| Name           | Command                | Note |
| -------------- | ---------------------- | ---- |
| Move to Top    | `Core: Move To Bottom` |      |
| Move to Bottom | `Core: Move To Bottom` |      |

#### Selection

| Name                       | Command                            | Note                                                         |
| -------------------------- | ---------------------------------- | ------------------------------------------------------------ |
| Consolidate Selections     | `Editor: Consolidate Selections`   | Reduce multiple selections to the least recently added selection. |

##### Select by Context

| Name | Command | Note |
| ---- | ------- | ---- |
| Select Larger Syntax Node  | `Editor: Select Larger Syntax Node` | Only works with limited grammars for now...                  |
| Select Smaller Syntax Node | `Editor: Select Smaller Syntax Node` | ...more information [here](http://blog.atom.io/2018/02/13/atom-1-24.html). |

##### Select by Character

| Name         | Command              | Note |
| ------------ | -------------------- | ---- |
| Select Left  | `Core: Select Left`  |      |
| Select Right | `Core: Select Right` |      |

##### Select by Subword

| Name                                | Command                                       | Note |
| ----------------------------------- | --------------------------------------------- | ---- |
| Select to Next Subword Boundary     | `Editor: Select To Next Subword Boundary`     |      |
| Select to Previous Subword Boundary | `Editor: Select To Previous Subword Boundary` |      |

##### Select by Word

| Name                             | Command                                    | Note |
| -------------------------------- | ------------------------------------------ | ---- |
| Select Word                      | `Editor: Select Word`                      |      |
| Select to Beginning of Word      | `Editor: Select To Beginning Of Word`      |      |
| Select to End of Word            | `Editor: Select To End Of Word`            |      |
| Select to Previous Word Boundary | `Editor: Select To Previous Word Boundary` |      |
| Select to Next Word Boundary     | `Editor: Select To Next Word Boundary`     |      |
| Select to Beginning of Next Word | `Editor: Select To Beginning Of Next Word` |      |

##### Select by Line

| Name                              | Command                                     | Note                                                  |
| --------------------------------- | ------------------------------------------- | ----------------------------------------------------- |
| Select Line                       | `Editor: Select Line`                       |                                                       |
| Select to First Character of Line | `Editor: Select to First Character of Line` | After whitespace                                      |
| Select to Beginning of Line       | `Editor: Select To Beginning Of Line`       |                                                       |
| Select to End of Line             | `Editor: Select To End Of Line`             |                                                       |
| Select Up                         | `Core: Select Up`                           |                                                       |
| Select Down                       | `Core: Select Down`                         |                                                       |
| Add Selection Above               | `Editor: Add Selection Above`               | Expands the current selection up one line by column   |
| Add Selection Below               | `Editor: Add Selection Below`               | Expands the current selection down one line by column |

##### Select by Paragraph

| Name                                      | Command                                             | Note |
| ----------------------------------------- | --------------------------------------------------- | ---- |
| Select to Beginning of Previous Paragraph | `Editor: Select To Beginning Of Previous Paragraph` |      |
| Select to Beginning of Next Paragraph     | `Editor: Select To Beginning Of Next Paragraph`     |      |

##### Select by Screen

| Name             | Command                  | Note |
| ---------------- | ------------------------ | ---- |
| Select Page Up   | `Core: Select Page Up`   |      |
| Select Page Down | `Core: Select Page Down` |      |

##### Select By File

| Name             | Command                  | Note |
| ---------------- | ------------------------ | ---- |
| Select All       | `Core: Select All`       |      |
| Select to Top    | `Core: Select To Bottom` |      |
| Select to Bottom | `Core: Select To Bottom` |      |

### Files

#### New

| Name     | Command                 | Note |
| -------- | ----------------------- | ---- |
| New File | `Application: New File` |      |

#### Open

| Name        | Command                    | Note |
| ----------- | -------------------------- | ---- |
| Open        | `Application: Open`        |      |
| Open File   | `Application: Open File`   |      |
| Open Folder | `Application: Open Folder` |      |
| Open Safe   | `Application: Open Safe`   |      |
| Open Dev    | `Application: Open Dev`    |      |

#### Save

| Name       | Command            | Note                                        |
| ---------- | ------------------ | ------------------------------------------- |
| Save       | `Core: Save`       |                                             |
| Save As    | `Core: Save As`    |                                             |
| Save All   | `Window: Save All` |                                             |
| Save Items | `Pane: Save Items` | This saves a pane, not a file specifically. |

#### Close

##### Panes

Note that these commands close panes, not files. Depending on your focus they may not close the file you're working on but not currently in focus.

| Name               | Command                    | Note |
| ------------------ | -------------------------- | ---- |
| Close              | `Pane: Close`              |      |
| Close Other Items  | `Pane: Close Other Items`  |      |
| Reopen Closed Item | `Pane: Reopen Closed Item` |      |

##### Tabs

| Name | Command | Note |
| ---- | ------- | ---- |
| Close Tab           | `Tabs: Close Tab`         |                                         |
| Close Tabs to Left  | `Tabs: Close Tabs To Left` |                                         |
| Close Tabs to Right | `Tabs: Close Tabs To Right` |                                         |
| Close Saved Tabs    | `Tabs: Close Saved Tabs`  |                                         |
| Close Other Tabs    | `Tabs: Close All Tabs`    |                                         |
| Close All Tabs      | `Tabs: Close All Tabs`    |                                         |

##### Window

| Name         | Command         | Note |
| ------------ | --------------- | ---- |
| Close Window | `Window: Close` |      |

#### File Properties

| Name                 | Command                                 | Note                                                     |
| -------------------- | --------------------------------------- | -------------------------------------------------------- |
| Grammar Selector     | `Grammar Selector: Show`                |                                                          |
| Select Encoding      | `Encoding Selector: Show`               |                                                          |
| Line Ending Selector | `Line Ending Selector: Show`            |                                                          |
| Convert To CRLF      | `Line Ending Selector: Convert To CRLF` |                                                          |
| Convert To LF        | `Line Ending Selector: Convert To LF`   |                                                          |
| Toggle Soft Tabs     | `Editor: Toggle Soft Tabs`              | This does not modify the file, just future tab behavior. |

#### Tree View

| Name                                | Command                                         | Note |
| ----------------------------------- | ----------------------------------------------- | ---- |
| Copy                                | `Tree View: Copy`                               |      |
| Cut                                 | `Tree View: Cut`                                |      |
| Paste                               | `Tree View: Paste`                              |      |
| Duplicate                           | `Tree View: Duplicate`                          |      |
| Rename                              | `Tree View: Rename`                             |      |
| Move                                | `Tree View: Move`                               |      |
| Add File                            | `Tree View: Add File`                           |      |
| Add Folder                          | `Tree View: Add Folder`                         |      |
| Remove                              | `Tree View: Remove`                             |      |
| Remove Project Folder               | `Tree View: Remove Project Folder`              |      |
| Expand Item                         | `Tree View: Expand Item`                        |      |
| Collapse Directory                  | `Tree View: Collapse Directory`                 |      |
| Recursively Expand Directory        | `Tree View: Recursive Collapse Directory`       |      |
| Recursively Collapse Directory      | `Tree View: Recursive Collapse Directory`       |      |
| Collapse All                        | `Tree View: Collapse All`                       |      |
| Reveal Active File                  | `Tree View: Reveal Active File`                 |      |
| Show Current File in File Manager   | `Tree View: Show Current File In File Manager`  |      |
| Show in File Manager                | `Tree View: Show In File Manager`               |      |
| Open Selected Entry                 | `Tree View: Open Selected Entry`                |      |
| Open Selected Entry Up              | `Tree View: Open Selected Entry Up`             |      |
| Open Selected Entry Right           | `Tree View: Open Selected Entry Right`          |      |
| Open Selected Entry Down            | `Tree View: Open Selected Entry Down`           |      |
| Open Selected Entry Left            | `Tree View: Open Selected Entry Left`           |      |
| Open Selected Entry in Pane # (1-9) | `Tree View: Open Selected Entry In Pane #(1-9)` |      |
| Open in New Window                  | `Tree View: Open In New Window`                 |      |
| Copy Full Path                      | `Tree View: Copy Full Path`                     |      |
| Copy Project Path                   | `Tree View: Copy Project Path`                  |      |
| Toggle Tree View                    | `Tree View: Toggle`                             |      |
| Toggle Tree View Focus              | `Tree View: Toggle Focus`                       |      |

### Find and Replace

| Name                    | Command                                           | Note |
| ----------------------- | ------------------------------------------------- | ---- |
| Find Selection          | `Find And Replace: Use Selection As Find Pattern` |      |
| Find Next               | `Find And Replace: Find Next`                     |      |
| Find Previous           | `Find And Replace: Find Previous`                 |      |
| Find Next Selected      | `Find And Replace: Find Next Selected`            |      |
| Find Previous Selected  | `Find And Replace: Find Previous Selected`        |      |
| Find All                | `Find And Replace: Find All`                      |      |
| Replace Next            | `Find And Replace: Replace Next`                  |      |
| Replace All             | `Find And Replace: Replace All`                   |      |
| Select Next             | `Find And Replace: Select Next`                   |      |
| Select All              | `Find And Replace: Select All`                    |      |
| Clear History           | `Find And Replace: Clear History`                 |      |
| Toggle Find and Replace | `Find And Replace: Toggle`                        |      |

#### Find in Project

| Name                      | Command                                   | Note |
| ------------------------- | ----------------------------------------- | ---- |
| Find in Project           | `Project Find: Show`                      |      |
| Find in Current Directory | `Project Find: Show In Current Directory` |      |
| Toggle Find in Project    | `Project Find: Toggle`                    |      |

### Markdown Preview

| Name                           | Command                                            | Note |
| ------------------------------ | -------------------------------------------------- | ---- |
| Preview File                   | `Markdown Preview: Preview File`                   |      |
| Copy HTML                      | `Markdown Preview: Copy HTML`                      |      |
| Save as HTML                   | `Markdown Preview: Save As HTML`                   |      |
| Toggle                         | `Markdown Preview: Toggle`                         |      |
| Toggle Break On Single Newline | `Markdown Preview: Toggle Break On Single Newline` |      |
| Toggle GitHub Style            | `Markdown Preview: Toggle GitHub Style`            |      |

### Projects

| Name                  | Hotkey                             | Note                           |
| --------------------- | ---------------------------------- | ------------------------------ |
| Reopen Project | `Application: Reopen Project` |  |
| Add Project Folder | `Application: Add Project Folder` |      |
| Clear Project History | `Application: Clear Project History` | Clears the reopen project list |

### Simulate Keystrokes

| Name            | Command           | Note |
| --------------- | ----------------- | ---- |
| Backspace Key ⌫ | `Core: Backspace` |      |

### Snippets

| Name                      | Command                       | Note |
| ------------------------- | ----------------------------- | ---- |
| Expand Snippet            | `Snippets: Expand`            |      |
| Next Tab Stop             | `Previous Tab Stop`           |      |
| Previous Tab Stop         | `Snippets: Previous Tab Stop` |      |
| Toggle Available Snippets | `Snippets: Available`         |      |

### Source Control

| Name                                  | Command                                         | Note |
| ------------------------------------- | ----------------------------------------------- | ---- |
| Fetch                                 | `GitHub: Fetch`                                 |      |
| Pull                                  | `GitHub: Pull`                                  |      |
| Commit                                | `GitHub: Commit`                                |      |
| Push                                  | `GitHub: Push`                                  |      |
| Force Push                            | `GitHub: Force Push`                            |      |
| Clone                                 | `GitHub: Clone`                                 |      |
| Checkout Head Revision                | `Editor: Checkout Head Revision`                |      |
| Discard All Changes                   | `GitHub: Discard All Changes`                   |      |
| Undo Last Discard in Git Tab          | `GitHub: Undo Last Discard In Git Tab`          |      |
| Stage All Changes                     | `GitHub: Stage All Changes`                     |      |
| Unstage All Changes                   | `GitHub: Unstage All Changes`                   |      |
| Resolve File as Ours                  | `GitHub: Resolve File As Ours`                  |      |
| Resolve File as Theirs                | `GitHub: Resolve File As Theirs`                |      |
| Toggle Expanded Commit Message Editor | `GitHub: Toggle Expanded Commit Message Editor` |      |
| Toggle Git Tab                        | `GitHub: Toggle Git Tab`                        |      |
| Toggle GitHub Tab                     | `GitHub: Toggle GitHub Tab`                     |      |

#### Files

| Name                              | Command                                     | Note |
| --------------------------------- | ------------------------------------------- | ---- |
| Open File                         | `GitHub: Open File`                         |      |
| Show Diff View                    | `GitHub: Show Diff View`                    |      |
| Discard Changes in Selected Files | `GitHub: Discard Changes In Selected Files` |      |

#### GitHub

| Name                       | Command                              | Note                                 |
| -------------------------- | ------------------------------------ | ------------------------------------ |
| Open Issue or Pull Request | `GitHub: Open Issue Or Pull Request` | Pass it the URL for any issue or PR. |
| Logout                     | `GitHub: Logout`                     |                                      |

#### Git Diff

| Name                  | Command                           | Note |
| --------------------- | --------------------------------- | ---- |
| Move to Next Diff     | `Git Diff: Move To Next Diff`     |      |
| Move to Previous Diff | `Git Diff: Move To Previous Diff` |      |
| Toggle Diff List      | `Git Diff: Toggle Diff List`      |      |

#### Open on GitHub

| Name           | Command                          | Note |
| -------------- | -------------------------------- | ---- |
| File           | `Open On GitHub: File`           |      |
| File on Master | `Open On GitHub: File On Master` |      |
| Copy URL       | `Open On GitHub: Copy URL`       |      |
| Branch Compare | `Open On GitHub: Branch Compare` |      |
| Blame          | `Open On GitHub: Blame`          |      |
| History        | `Open On GitHub: File On Master` |      |
| Issues         | `Open On GitHub: Issues`         |      |
| Pull Requests  | `Open On GitHub: Pull Requests`  |      |
| Repository     | `Open On GitHub: Repository`     |      |

#### Staging

| Name                                   | Command                                          | Note |
| -------------------------------------- | ------------------------------------------------ | ---- |
| View Stage Changes for Current File    | `GitHub: View Staged Changes For Current File`   |      |
| View Unstaged Changes for Current File | `GitHub: View Unstaged Changes For Current File` |      |

### Spell Check

| Name                  | Command                            | Note |
| --------------------- | ---------------------------------- | ---- |
| Correct Misspelling   | `Spell Check: Correct Misspelling` |      |
| Toggle Spell Checking | `Spell Check: Toggle`              |      |

### Symbols

| Name                    | Command                                 | Note |
| ----------------------- | --------------------------------------- | ---- |
| Go To Declaration       | `Symbols View: Go To Declaration`       |      |
| Return From Declaration | `Symbols View: Return From Declaration` |      |
| Toggle File Symbols     | `Symbols View: Toggle File Symbols`     |      |
| Toggle Project Symbols  | `Symbols View: Toggle Project Symbols`  |      |

## Settings

### Configuration

| Name                  | Command                              | Note |
| --------------------- | ------------------------------------ | ---- |
| Open Your Config      | `Application: Open Your Config`      |      |
| Open Your Init Script | `Application: Open Your Init Script` |      |
| Open Your Keymap      | `Application: Open Your Keymap`      |      |
| Open Your Snippets    | `Application: Open Your Snippets`    |      |
| Open Your Stylesheet  | `Application: Open Your Stylesheet`  |      |

### Editor

| Name                          | Command                       | Note                                  |
| ----------------------------- | ----------------------------- | ------------------------------------- |
| Toggle Auto Indent            | `Editor: Auto Indent`         |                                       |
| Toggle Auto Indent for Window | `Window: Toggle Auto Indent`  |                                       |
| Toggle Soft Tabs              | `Editor: Toggle Soft Tabs`    |                                       |
| Toggle Invisibles             | `Window: Toggle Invisibles`   | Shows symbols representing whitespace |
| Toggle Indent Guide           | `Editor: Toggle Indent Guide` |                                       |
| Toggle Line Numbers           | `Editor: Toggle Line Numbers` |                                       |
| Toggle Soft Wrap              | `Editor: Toggle Soft Wrap`    |                                       |
| Toggle Spell Check            | `Spell Check: Toggle`         |                                       |
| Increase Font Size            | `Window: Increase Font Size`  |                                       |
| Decrease Font Size            | `Window: Decrease Font Size`  |                                       |
| Reset Font Size               | `Window: Reset Font Size`     |                                       |

### Keymap

| Name                 | Command                         | Note |
| -------------------- | ------------------------------- | ---- |
| Open Your Keymap     | `Application: Open Your Keymap` |      |
| Key Binding Resolver | `Key Binding Resolver: Toggle`  |      |

### Preferences

| Name                             | Command                                      | Note |
| -------------------------------- | -------------------------------------------- | ---- |
| Preferences                      | `Application: Show Preferences`              |      |
|                                  | `Application: Show Settings`                 |      |
|                                  | `Settings View: Open`                        |      |
| Core Section                     | `Settings View: Core`                        |      |
| Editor Section                   | `Settings View: Editor`                      |      |
| Keybindings Section              | `Settings View: Show Keybindings`            |      |
| Packages Section                 | `Settings View: View Installed Packages`     |      |
| Focus Filter in Packages Section | `Settings View: Uninstall Packages`          |      |
| Themes Section                   | `Settings View: View Installed Themes`       |      |
| Focus Filter in Themes Section   | `Settings View: Change Themes`               |      |
|                                  | `Settings View: Uninstall Themes`            |      |
| Updates Section                  | `Settings View: Check For Package Updates`   |      |
| Install Section                  | `Settings View: Install Packages And Themes` |      |

### Snippets

| Name               | Command                           | Note |
| ------------------ | --------------------------------- | ---- |
| Open Your Snippets | `Application: Open Your Snippets` |      |

### Tree View

| Name                     | Command                               | Note                |
| ------------------------ | ------------------------------------- | ------------------- |
| Toggle Ignored Names     | `Tree View: Toggle Ignored Names`     |                     |
| Toggle VCS Ignored Files | `Tree View: Toggle VCS Ignored Files` | Respects .gitignore |

## UI

### Pages

| Name                  | Command                         | Note                     |
| --------------------- | ------------------------------- | ------------------------ |
| Preferences           | `Application: Show Preferences` |                          |
|                       | `Application: Show Preferences` |                          |
| Welcome               | `Welcome: Show`                 | Opens both welcome pages |
| About                 | `Application: About`            |                          |
| Incompatible Packages | `Incompatible Packages: View`   |                          |
| Timecop               | `Timecop: View`                 |                          |

#### Markdown Preview

| Name                                            | Command                                            | Note |
| ----------------------------------------------- | -------------------------------------------------- | ---- |
| Toggle Markdown Preview                         | `Markdown Preview: Toggle`                         |      |
| Toggle Break on Single Newline Markdown Preview | `Markdown Preview: Toggle Break On Single Newline` |      |
| Toggle GitHub Style Markdown Preview            | `Markdown Preview: Toggle GitHub Style`            |      |

### Palettes

#### Command Palette

| Name                   | Command                                 | Note |
| ---------------------- | --------------------------------------- | ---- |
| Toggle Command Palette | `Command Palette: Toggle`               |      |
| Show Hidden Commands   | `Command Palette: Show Hidden Commands` |      |

#### Fuzzy Finder

| Name                     | Command                                  | Note                                |
| ------------------------ | ---------------------------------------- | ----------------------------------- |
| Toggle Buffer Finder     | `Fuzzy Finder: Toggle Buffer Finder`     | Select Open File                    |
| Toggle File Finder       | `Fuzzy Finder: Toggle File Finder`       | Select Project File                 |
| Toggle Git Status Finder | `Fuzzy Finder: Toggle Git Status Finder` | Select Modified and Untracked Files |

#### Bookmarks

| Name             | Command               | Note |
| ---------------- | --------------------- | ---- |
| Toggle Bookmarks | `Bookmarks: View All` |      |

#### Go To Line

| Name              | Command              | Note |
| ----------------- | -------------------- | ---- |
| Toggle Go To Line | `Go To Line: Toggle` |      |

#### Grammar Selector

| Name                    | Command                  | Note |
| ----------------------- | ------------------------ | ---- |
| Toggle Grammar Selector | `Grammar Selector: Show` |      |

#### Git Diff

| Name             | Command                      | Note |
| ---------------- | ---------------------------- | ---- |
| Toggle Diff List | `Git Diff: Toggle Diff List` |      |

#### Line Ending Selector

| Name                        | Command                      | Note |
| --------------------------- | ---------------------------- | ---- |
| Toggle Line Ending Selector | `Line Ending Selector: Show` |      |

#### Snippets

| Name                      | Command               | Note |
| ------------------------- | --------------------- | ---- |
| Toggle Available Snippets | `Snippets: Available` |      |

#### Symbols

| Name                   | Command                                | Note |
| ---------------------- | -------------------------------------- | ---- |
| Toggle File Symbols    | `Symbols View: Toggle File Symbols`    |      |
| Toggle Project Symbols | `Symbols View: Toggle Project Symbols` |      |

### Panels and Docks

| Name               | Command                      | Note |
| ------------------ | ---------------------------- | ---- |
| Toggle Left Dock   | `Window: Toggle Left Dock`   |      |
| Toggle Bottom Dock | `Window: Toggle Bottom Dock` |      |
| Toggle Right Dock  | `Window: Toggle Right Dock`  |      |

#### Find and Replace

| Name                    | Command                          | Note                     |
| ----------------------- | -------------------------------- | ------------------------ |
| Toggle Find and Replace | `Find And Replace: Toggle`       |                          |
| Show Find and Replace   | `Find And Replace: Show`         | Focuses on Find field    |
| Show Replace            | `Find And Replace: Show Replace` | Focuses on Replace field |
| Toggle Find in Project  | `Project Find: Toggle`           |                          |
| Show Find in Project    | `Project Find: Show`             |                          |

#### Key Binding Resolver

| Name                        | Command                        | Note |
| --------------------------- | ------------------------------ | ---- |
| Toggle Key Binding Resolver | `Key Binding Resolver: Toggle` |      |

#### Notifications

| Name                     | Command                     | Note |
| ------------------------ | --------------------------- | ---- |
| Toggle Notifications Log | `Notifications: Toggle Log` |      |

#### Source Control

| Name                    | Command                           | Note                                        |
| ----------------------- | --------------------------------- | ------------------------------------------- |
| Toggle Git Tab          | `GitHub: Toggle Git Tab`          |                                             |
| Toggle Git Tab Focus    | `GitHub: Toggle Git Tab Focus`    |                                             |
| Toggle GitHub Tab       | `GitHub: Toggle GitHub Tab`       |                                             |
| Toggle GitHub Tab Focus | `GitHub: Toggle GitHub Tab Focus` |                                             |
| Activate Next List      | `GitHub: Activate Next List`      | Switches focus between lists in the Git tab |
| Activate Previous List  | `GitHub: Activate Previous List`  | Switches focus between lists in the Git tab |
| Close All Diff Views    | `GitHub: Close All Diff Views`    | This doesn't seem to work right now         |
| Close Empty Diff Views  | `GitHub: Close Empty Diff Views`  |                                             |

#### Status Bar

| Name              | Command              | Note |
| ----------------- | -------------------- | ---- |
| Toggle Status Bar | `Status Bar: Toggle` |      |

#### Tree View

| Name                   | Command                   | Note |
| ---------------------- | ------------------------- | ---- |
| Toggle Tree View       | `Tree View: Toggle`       |      |
| Show Tree View         | `Tree View: Show`         |      |
| Toggle Tree View Focus | `Tree View: Toggle Focus` |      |
| Unfocus Tree View      | `Tree View: Unfocus`      |      |

### Panes

| Name                             | Command                                  | Note |
| -------------------------------- | ---------------------------------------- | ---- |
| Show Next Item                   | `Pane: Show Next Item`                   |      |
| Show Previous Item               | `Pane: Show Previous Item`               |      |
| Show Item # (1-9)                | `Pane: Show Item #(1-9)`                 |      |
| Show Next Recently Used Item     | `Pane: Show Next Recently Used Item`     |      |
| Show Previous Recently Used Item | `Pane: Show Previous Recently Used Item` |      |
| Save Items                       | `Pane: Save Items`                       |      |
| Close                            | `Pane: Close`                            |      |
| Close Other Items                | `Pane: Close Other Items`                |      |
| Reopen Closed Item               | `Pane: Reopen Closed Item`               |      |
| Move Active Item to Top of Stack | `Pane: Move Active Item To Top Of Stack` |      |
| Increase Size                    | `Pane: Decrease Size`                    |      |
| Decrease Size                    | `Pane: Decrease Size`                    |      |

#### Copy Items

| Name                              | Command                                     | Note |
| --------------------------------- | ------------------------------------------- | ---- |
| Copy Active Item to Pane Above    | `Window: Copy Active Item To Pane Above`    |      |
| Copy Active Item to Pane on Right | `Window: Copy Active Item To Pane On Right` |      |
| Copy Active Item to Pane Below    | `Window: Copy Active Item To Pane Below`    |      |
| Copy Active Item to Pane on Left  | `Window: Copy Active Item To Pane On Left`  |      |

#### Focus

| Name                | Command                       | Note |
| ------------------- | ----------------------------- | ---- |
| Focus Next Pane     | `Window: Focus Next Pane`     |      |
| Focus Previous Pane | `Window: Focus Previous Pane` |      |
| Focus Pane Above    | `Window: Focus Pane Above`    |      |
| Focus Pane on Right | `Window: Focus Pane On Left`  |      |
| Focus Pane Below    | `Window: Focus Pane Below`    |      |
| Focus Pane on Left  | `Window: Focus Pane On Right` |      |

#### Move Items

| Name | Command | Note |
| ---- | ------- | ---- |
| Move Item Left                     | `Pane: Move Item Left`                    |      |
| Move Item Right                    | `Pane: Move Item Right`                   |      |
| Move Active Item to Panel Above    | `Window: Move Active Item To Pane Above`  |      |
| Move Active Item to Panel on Right | `Window: Move Active Item To Pane On Right` |      |
| Move Active Item to Panel Below    | `Window: Move Active Item To Pane Below`  |      |
| Move Active Item to Panel on Left  | `Window: Move Active Item To Pane On Left` |      |

#### Split Panes

| Name                             | Command                                  | Note |
| -------------------------------- | ---------------------------------------- | ---- |
| Split Up                         | `Pane: Split Up`                         |      |
| Split Right                      | `Pane: Split Right`                      |      |
| Split Down                       | `Pane: Split Down`                       |      |
| Split Left                       | `Pane: Split Left`                       |      |
| Split Up and Copy Active Item    | `Pane: Split Up And Copy Active Item`    |      |
| Split Right and Copy Active Item | `Pane: Split Right And Copy Active Item` |      |
| Split Down and Copy Active Item  | `Pane: Split Down And Copy Active Item`  |      |
| Split Left and Copy Active Item  | `Pane: Split Left And Copy Active Item`  |      |
| Split Up and Move Active Item    | `Pane: Split Up And Move Active Item`    |      |
| Split Right and Move Active Item | `Pane: Split Right And Move Active Item` |      |
| Split Down and Move Active Item  | `Pane: Split Down And Move Active Item`  |      |
| Split Left and Move Active Item  | `Pane: Split Left And Move Active Item`  |      |

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

| Name                       | Command                                   | Note |
| -------------------------- | ----------------------------------------- | ---- |
| New Window                 | `Application: New Window`                 |      |
| Full Screen                | `Window: Toggle Full Screen`              |      |
| Zoom                       | `Application: Zoom`                       |      |
| Hide                       | `Application: Hide`                       |      |
| Hide Other Applications    | `Application: Hide Other Applications`    |      |
| Unhide All Applications    | `Application: Unhide All Applications`    |      |
| Minimize                   | `Application: Minimize`                   |      |
| Close                      | `Window: Close`                           |      |
| Bring All Windows to Front | `Application: Bring All Windows to Front` |      |
| Toggle Dev Tools           | `Window: Toggle Dev Tools`                |      |
| Reload Window              | `Window: Reload`                          |      |