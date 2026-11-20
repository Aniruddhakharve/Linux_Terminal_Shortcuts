# Linux Terminal Shortcuts Cheat Sheet (Bash / Zsh Emacs Mode)

## Cursor Navigation

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + A` or `Home` | Jump to the **first character** of the line |
| `Ctrl + E` or `End` | Jump to the **last character** of the line |
| `Alt + B` or `Ctrl + Left` | Move backward **one word** |
| `Alt + F` or `Ctrl + Right` | Move forward **one word** |
| `Ctrl + B` or `Left` | Move backward **one character** |
| `Ctrl + F` or `Right` | Move forward **one character** |
| `Ctrl + ]` + `<char>` | Jump forward to the next occurrence of `<char>` |
| `Alt + Ctrl + ]` + `<char>` | Jump backward to the previous occurrence of `<char>` |
| `Ctrl + XX` | Toggle cursor between the start of the line and current position |

## Cutting, Deleting & Pasting (Yank)

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + U` | Cut everything **before** the cursor to the start of the line |
| `Ctrl + K` | Cut everything **after** the cursor to the end of the line |
| `Ctrl + W` | Cut the **word before** the cursor (up to whitespace) |
| `Alt + Backspace` | Cut the **word before** the cursor (stops at slashes/punctuation) |
| `Alt + D` | Cut the **word after** the cursor |
| `Ctrl + D` | Delete the character **under** the cursor (exits shell if line is empty) |
| `Ctrl + H` | Delete the character **before** the cursor (same as Backspace) |
| `Ctrl + Y` | **Paste** (yank) the last text you cut |
| `Alt + Y` | Cycle through previously cut items (use immediately after `Ctrl + Y`) |

## Editing & Case Manipulation

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + _` or `Ctrl + X` then `Ctrl + U` | **Undo** the last edit |
| `Ctrl + T` | Swap (transpose) the character under the cursor with the one before it |
| `Alt + T` | Swap the current word with the previous word |
| `Alt + U` | Convert word after cursor to **UPPERCASE** |
| `Alt + L` | Convert word after cursor to **lowercase** |
| `Alt + C` | **Capitalize** the first letter of the word after cursor |

## Command History

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + R` | **Reverse search** command history (press `Ctrl + R` again to cycle matches) |
| `Ctrl + G` | Exit history search without running a command |
| `Ctrl + P` or `Up` | Previous command in history |
| `Ctrl + N` or `Down` | Next command in history |
| `Alt + .` or `Esc + .` | Insert the **last argument** of the previous command |

## Process & Screen Control

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + C` | **Terminate** (SIGINT) the currently running command |
| `Ctrl + Z` | **Suspend** (SIGTSTP) the current process to the background (resume with `fg`) |
| `Ctrl + D` | Send EOF / **Exit** the current shell session |
| `Ctrl + L` | **Clear** the terminal screen (keeps current typed command intact) |
| `Ctrl + S` | Pause terminal screen output |
| `Ctrl + Q` | Resume terminal screen output |
| `Tab` | **Autocomplete** file, folder, or command name (press twice to list all) |
