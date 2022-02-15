# VS Code Cheat Sheet

## 前言

本篇 cheat sheet 不包括一些常见操作，例如 save, undo, redo, copy (yank), paste, ⌘ `p` (double `shift` )等等。

我是看完 ipads 和 MIT 的 vim tutorial 后，意识到 vim 并非狭义上的一种 IDE，而是广义上的一种思想。因此在 VS Code 中也可以找到其对应的快捷操作。

⚠️注意：我使用了 IntelliJ IDEA Keybindings 插件，因为我是从 webstorm 转入的 VS Code。而我会混用 VS Code 的 default 快捷键、Extension 的快捷键以及我自定义的快捷键，一切都是单纯依靠肌肉记忆。因此本篇 cheat sheet 并不具备参考意义。但是从思想上来说，可以参考本篇写出自己的 cheat sheet（Preferences -> Keyboard Shortcuts）。

## 光标移动

|         Command          | Keybinding  |      Command       | Keybinding |
| :----------------------: | :---------: | :----------------: | :--------: |
|    Insert Line Above     | ⌥ ⌘ `Enter` | Insert Line Below  | ⇧ `Enter`  |
|      cursorWordLeft      |    ⌥  ←     | cursorWordEndRight |    ⌥  →    |
|    cursorWordPartLeft    |    ⌃⌥  ←    | cursorWordPartLeft |   ⌃⌥  →    |
|      Go to Bracket       |   ⇧ ⌘ `\`   |                    |            |
| Go to Last Edit Location | ⌘ `k` ⌘ `q` |                    |            |

## 选中

|             Command              | Keybinding |               Command                | Keybinding |
| :------------------------------: | :--------: | :----------------------------------: | :--------: |
|        Select to Bracket         | ⇧ ⌘ ⌥  `\` |                                      |            |
| Add Selection To Next Find Match |   ⌃ `g`    | Select All Occurrences of Find Match |  ⌃ ⌘ `g`   |
|         Expand Selection         |    ⌥ ↑     |           Shrink Selection           |    ⌥ ↓     |

|             Command              | Keybinding |               Command                |        Keybinding        |
| :------------------------------: | :--------: | :----------------------------------: | :----------------------: |
| Add Selection To Next Find Match | `Alt` `j`  | Select All Occurrences of Find Match | `Ctrl` `Shift` `Alt` `j` |
|         Expand Selection         | `Ctrl` `w` |           Shrink Selection           |    `Ctrl` `Shift` `w`    |

## 复制

|    Command     | Keybinding | Command | Keybinding |
| :------------: | :--------: | :-----: | :--------: |
| Copy Line Down |   ⌘ `d`    |         |            |

## 移动

|   Command    | Keybinding |    Command     | Keybinding |
| :----------: | :--------: | :------------: | :--------: |
| Move Line Up |   ⇧ ⌥ ↑    | Move Line Down |   ⇧ ⌥ ↓    |

## 删除

|      Command       |   Keybinding    |       Command       |  Keybinding  |
| :----------------: | :-------------: | :-----------------: | :----------: |
|   deleteWordLeft   |  ⌥ `Backspace`  |   deleteWordRight   |  ⌥ `Delete`  |
| deleteWordPartLeft | ⌃ ⌥ `Backspace` | deleteWordPartRight | ⌃ ⌥ `Delete` |
|  Delete All Right  |      ⌃ `k`      |                     |              |
|    Delete Line     |  ⌘ `Backspace`  |                     |              |

## 查看

|   Command    |   Keybinding   | Command | Keybinding |
| :----------: | :------------: | :-----: | :--------: |
| Fold All | ⌘ `k`  ⌘ `0` | Unfold All | ⌘ `k` ⌘ `j` |
| Fold | ⌘ `-` |   Unfold   | ⌘ `=` |
| Fold Level `Number` | ⌘ `k` ⌘ `number` |            |  |

## 符号标识

| symbol |  keybord   | symbol |   keybord   |
| :----: | :--------: | :----: | :---------: |
|   ⌘    |  Command   |   ⌃    |   Control   |
|   ⌥    |   Option   |   ⇧    |    Shift    |
|   ↑    |  Up Arrow  |   ↓    | Down Arrow  |
|   ←    | Left Arrow |   →    | Right Arrow |
|   ⇪    | Caps Lock  |        |             |

