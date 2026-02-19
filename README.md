# Terminal & Ubuntu Shortcuts with fzf Plugin

A quick personal reference for useful terminal and Ubuntu shortcuts

---

## 🐧 Ubuntu Shortcuts

| Hotkey/Combo                          | Description                             | Notes                                        |
|--------------------------------------|-----------------------------------------|----------------------------------------------|
| `cd $(find * -type d -print \| fzf)` | `cd` to output of `fzf`             |                                      |
| `vi $(fzf)`                           | Open a file with `vi` through `fzf` |                                      |
| `history`                             | History of commands                 |                                      |
| `gnome-control-center sound`         | Open audio settings in Ubuntu           |                                              |
| `pwd \| xclip -selection clipboard`  | Copy current path to clipboard          | `sudo apt-get install xclip` may be required |
| `copypath`                           | Copy current path to clipboard          | `sudo apt-get install copypath` may be required |
| `less *file*`| View file in scrollable way| alternatively use `more`|
| `bat *file*`| better `cat`|  |
| `fd`| better `find`| use `-type d` or `f` for directory or file  |
| `ripgrep`| better `find`|  |
| `fzf --preview "*tool* {}"`| nice preview e.g. use `cat\|ls\|*others*`|  |
| `z *directory*`| better `cd` to directory| need zoxide  |
| `tldr *tool*`| better `man` | need to install  |
| `dust`| better `du` | need to install |
| `cd $(ls -t */ \| head -n1)`| cd to last created dictionary |  |

---

## (N)Vim Tricks

| Hotkey/Combo                          | Description                             | Notes                                        |
|--------------------------------------|-----------------------------------------|----------------------------------------------|
| `:g/^match/yank A`         | Run global command to yank any line that matches ^match and put in register a           | Register needs to be reset                     |
| `:let @a=""`         | Reset register           |                                              |
| `\(pattern\)\@!`         | Negative look-ahead assertion           |                                              |
|`\<Leader\>sg, \<C-q\>, :cdo %s/*oldpattern*/*newpattern*/gc `| Search lines by grep in whole directory, then replace|                                              |
|` :let @*=@% `| Copy path of current file to clipboard |                                              |
|` /*pattern*, \<Shift\>n, cgn, *new_pattern*, \<Esc\> `| replace pattern |                                              |
|` \<C-^\> `| Switch to last visited buffer|                                              |
|` qa *macro* q, :new, :put a, *edit macro*, "ayy `| edit macro |                                              |
|`3gcc` and `gcap`| comment with movement | nvim plugin                                              |
|`:ls, :b 0, :b 1`| switch between buffer 0 and 1 | built in vim feature                                              |
|`ZZ`| save and quit nvim / vim|           |
|`cib`| change anything between \{...\}, \[...\] or \(...\)| nvim only?           |
|`\<C-v\>, *movement*, I`  | edit beginning al marked lines|           |
|`gv, $, A`| reselect last highlighted text and append to end of lines|           |
|`g~*motion*`| capitalize multiple characters |           |
|`gg,=G`| Re-indent whole file |           |
|`\<C-z\>, fg`| put vim to background and re-enter| (I believe vim only?)           |
|`:mksession *name*.vim, wq,:source *name*.vim`| save and open session ||
|`gx`| open url under cursor| https://github.com/Lucky-Aubrey |
|`gf`| open file under cursor| ~/.config/wezterm/wezterm.lua |
|`m*UPPERCASELETTER*`| set mark which works between file |  |
|`gJ`| Join two lines without space between lines |  |
|<C-w>| Delete word in insert mode |  |
|<C-u>| Delete line in insert mode |  |
|<C-h>| Delete character in insert mode |  |
| g~ | Swap case |  |
| gu | Make lowercase |  |
| gU | Make lowercase |  |
| :6t. | Copy line 6 to just below the current line |  |
| :t6 | Copy current to just below just below line 6 |  |
| :t. | Duplicate current line |  |
| :t$ | Copy current line to the end of the file |  |
| :'<,'>t0 | Copy visually selected lines to the start of the file |  |
| :'<,'>m$ | Move visually selected lines to the end of the file |  |
| :'<,'>m$ | Move visually selected lines to the end of the file |  |
| :'<,'>normal . | For each line in the visual selection, execute the Normal mode . command |  |
| :'<,'>normal @q | For each line in the visual selection, execute macro q |  |

---

## 📝 Context-specific Shortcuts

*(This section is reserved for context-specific hotkeys and combos. Fill it out as needed.)*

| Hotkey/Combo | Description | Notes |
|--------------|-------------|-------|
|              |             |       |

---

