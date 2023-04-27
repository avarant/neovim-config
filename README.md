# neovim-config
My neovim configuration. Adapted from https://github.com/josean-dev/dev-environment-files

to install neovim on macOS

```bash
brew install neovim
```

to install neovim on Ubuntu

```bash
sudo apt-get install nvim
```

to install a [python language server](https://github.com/neovim/nvim-lspconfig#quickstart)

```bash
npm i -g tree-sitter cli
```

## Keymaps

| Keymap                | Function                                                                                     |
| --------------------- | -------------------------------------------------------------------------------------------- |
| jk                    | Esc                                                                                          |
| leader nh             | clear search highlights                                                                      |
| x                     | delete single char without copying into register                                             |
| leader +              | increment                                                                                    |
| leader -              | decrement                                                                                    |
| leader sv             | split vertically                                                                             |
| leader sh             | split horizontally                                                                           |
| leader sx             | close split                                                                                  |
| leader se             | make split windows equal width & height                                                      |
| leader to             | new tab                                                                                      |
| leader tx             | close tab                                                                                    |
| leader tn             | next tab                                                                                     |
| leader tp             | previous tab                                                                                 |
| :s/pattern/replace/g  | Substitute “pattern” by “replace” on the current line.                                       |
| :%s/pattern/replace/g | Substitute “pattern” by “replace” in the current file.                                       |
| ys motion char        | add char before and after motion                                                             |
| ds char               | remove char before and after motion                                                          |
| cs char               | replace char before and after motion                                                         |
| y motion              | yank                                                                                         |
| gr motion             | replace motion with clipboard                                                                |
| gc motion             | toggle comment out motion                                                                    |
| :NvimTreeToggle       | toggle file explorer sidebar                                                                 |
| leader e              | toggle file explorer sidebar                                                                 |
| leader ff             | Find files within directory                                                                  |
| Ctrl k                | Move up filefinder                                                                           |
| Ctrl j                | Move down filefinder                                                                         |
| Ctrl q                |                                                                                              |
| leader fs             | find string in current working directory as you type                                         |
| leader fc             | find string under cursor in current working directory                                        |
| leader fb             | list open buffers in current neovim instance                                                 |
| leader fh             | list available help tags                                                                     |
| leader gc             | list all git commits (use <cr> to checkout) ["gc" for git commits]                           |
| leader gfc            | list git commits for current file/buffer (use <cr> to checkout) ["gfc" for git file commits] |
| leader gb             | list git branches (use <cr> to checkout) ["gb" for git branch]                               |
| leader gs             | list current changes per file with diff preview ["gs" for git status]                        |
| m char                | set mark at location                                                                         |
| ` char                | go to mark location                                                                          |
| ' char                | go to the beginning of the line containing the char mark                                     |
| y ` mark              | yank from current cursor location to mark location                                           |
