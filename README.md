# vim-commands
A helpful list of commands for faster work with vim.

#### Movement and navigation


| Command                                  | Key              |
| -----------------------------------------| :-:              |
| Move left                                | `h`              |
| Move right                               | `j`              |
| Move up                                  | `k`              |
| Move down                                | `l`              |
| Move one word to the right               | `w`              |
| Move one word back to the left           | `b`              |
| Move to a specific line                  | `#G / #gg / 55G` |
| Move half page up                        | `ctrl + u`       |
| Move half page down                      | `ctrl + d`       |
| Move to the end of the row               | `$`              |
| Move to previous buffer                  | `:bp`            |
| Go to file under the curosr              | `gf`             |
| Go to older cursor position in jump list | `ctr + O`        |

#### Searching

| Command                 | Key |
| ----------------------- | :-: |
| Search                  | `/` |
| Searching and show next | `n` |

#### Basics

| Command                               |      Key      |
| ------------------------------------- | :-----------: |
| Insert mode (before the cursor)       |      `i`      |
| Insert/Append mode (after the cursor) |      `a`      |
| Change word                           |     `cw`      |
| Change inner ("/</{)                  |     `ci"`     |
| Undo last change                      |      `u`      |
| Find &replace                         | `:%s/foo/bar` |
| Exit insert mode                      |     `Esc`     |
| Save the file                         |  `Esc + :w`   |
| Save & close the file                 |  `Esc + :x`   |
| Go back                               |     `:eX`     |
| Quit                                  |  `Esc + :q`   |


#### Copy, paste, delete

| Command                                                | Key   |
| ------------------------------------------------------ | :---: |
| Copy single line                                       | `yy`  |
| Paste single line                                      | `p`   |
| Delete single line                                     | `dd`  |
| Delete all text the cursor moves over with a w command | `dw`  |
| Delete a word                                          | `daw` |
| Delete a sentence                                      | `das` |     
