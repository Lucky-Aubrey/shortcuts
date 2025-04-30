# Terminal & Ubuntu Shortcuts with fzf Plugin

A quick personal reference for useful terminal and Ubuntu shortcuts

---

## 🔍 Terminal with `fzf` Plugin

| Hotkey/Combo                          | Description                         | Notes                                |
|--------------------------------------|-------------------------------------|--------------------------------------|
| `cd $(find * -type d -print \| fzf)` | `cd` to output of `fzf`             |                                      |
| `vi $(fzf)`                           | Open a file with `vi` through `fzf` |                                      |
| `history`                             | History of commands                 |                                      |

---

## 🐧 Ubuntu Shortcuts

| Hotkey/Combo                          | Description                             | Notes                                        |
|--------------------------------------|-----------------------------------------|----------------------------------------------|
| `gnome-control-center sound`         | Open audio settings in Ubuntu           |                                              |
| `xdg-open .`                          | Open current directory in file explorer |                                              |
| `pwd \| xclip -selection clipboard`  | Copy current path to clipboard          | `sudo apt-get install xclip` may be required |

---

##  Vim Tricks

| Hotkey/Combo                          | Description                             | Notes                                        |
|--------------------------------------|-----------------------------------------|----------------------------------------------|
| `:g/^match/yank A`         | Run global command to yank any line that matches ^match and put in register a           | Register needs to be reset                     |
| `:let @a=""`         | Reset register           |                                              |
| `\(pattern\)\@!`         | Negative look-ahead assertion           |                                              |

---

## 📝 Context-specific Shortcuts

*(This section is reserved for context-specific hotkeys and combos. Fill it out as needed.)*

| Hotkey/Combo | Description | Notes |
|--------------|-------------|-------|
|              |             |       |

---

