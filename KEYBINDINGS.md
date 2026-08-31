# Neovim Keybindings Reference

> Leader key is `<Space>`

---

## Navigation

| Key | Mode | Action |
|-----|------|--------|
| `<M-h>` | Normal/Terminal | Move to left window |
| `<M-j>` | Normal/Terminal | Move to lower window |
| `<M-k>` | Normal/Terminal | Move to upper window |
| `<M-l>` | Normal/Terminal | Move to right window |
| `<M-Tab>` | Normal | Toggle between last two files |
| `<S-h>` | Normal/Visual/Op | Jump to start of line |
| `<S-l>` | Normal/Visual/Op | Jump to end of line |
| `j` / `k` | Normal/Visual | Move down/up (respects line wrap) |

---

## Search

| Key | Mode | Action |
|-----|------|--------|
| `n` | Normal | Next search result (centers screen) |
| `N` | Normal | Previous search result (centers screen) |
| `*` | Normal | Search word under cursor (centers screen) |
| `#` | Normal | Search word backward (centers screen) |
| `g*` | Normal | Search word under cursor (loose match) |
| `g#` | Normal | Search word backward (loose match) |
| `<leader>h` | Normal | Clear search highlight |

---

## Editing

| Key | Mode | Action |
|-----|------|--------|
| `<` | Visual | Decrease indent (keeps selection) |
| `>` | Visual | Increase indent (keeps selection) |
| `p` | Visual | Paste without overwriting register |
| `<leader>/` | Normal/Visual | Toggle comment |
| `<leader>w` | Normal | Toggle line wrapping |

---

## File Explorer

| Key | Mode | Action |
|-----|------|--------|
| `<leader>e` | Normal | Toggle file explorer (NvimTree) |
| `-` | Normal | Open parent directory (Oil, floating) |

---

## Find (Telescope)

| Key | Mode | Action |
|-----|------|--------|
| `<leader>ff` | Normal | Find files |
| `<leader>ft` | Normal | Live grep (search text) |
| `<leader>fr` | Normal | Recent files |
| `<leader>fb` | Normal | Git branches |
| `<leader>fc` | Normal | Select colorscheme |
| `<leader>fp` | Normal | Find projects |
| `<leader>fh` | Normal | Search help tags |
| `<leader>fl` | Normal | Resume last search |
| `<leader>bb` | Normal | Find open buffers |

### Inside Telescope picker

| Key | Mode | Action |
|-----|------|--------|
| `<C-j>` / `<C-k>` | Insert | Move between results |
| `<C-n>` / `<C-p>` | Insert | Browse history |
| `<Esc>` / `q` | Normal | Close picker |
| `<C-d>` / `dd` | Insert/Normal | Delete buffer (buffers picker) |

---

## Harpoon (Quick File Marks)

| Key | Mode | Action |
|-----|------|--------|
| `<leader>a` | Normal | Mark current file |
| `<Tab>` | Normal | Toggle Harpoon quick menu |

---

## LSP

| Key | Mode | Action |
|-----|------|--------|
| `gd` | Normal | Go to definition |
| `gD` | Normal | Go to declaration |
| `gI` | Normal | Go to implementation |
| `gr` | Normal | Find references |
| `K` | Normal | Hover documentation |
| `gl` | Normal | Show diagnostic float |
| `<leader>la` | Normal | Code action |
| `<leader>lf` | Normal | Format buffer |
| `<leader>lr` | Normal | Rename symbol |
| `<leader>lh` | Normal | Toggle inlay hints |
| `<leader>li` | Normal | Show LSP info |
| `<leader>lj` | Normal | Go to next diagnostic |
| `<leader>lk` | Normal | Go to previous diagnostic |
| `<leader>ll` | Normal | Run CodeLens action |
| `<leader>lq` | Normal | Show diagnostics in quickfix |
| `<leader>laa` | Visual | Code action (selection) |

---

## Completion (cmp)

| Key | Mode | Action |
|-----|------|--------|
| `<C-j>` / `<Down>` | Insert | Next completion item |
| `<C-k>` / `<Up>` | Insert | Previous completion item |
| `<C-b>` | Insert | Scroll docs backward |
| `<C-f>` | Insert | Scroll docs forward |
| `<C-Space>` | Insert | Trigger completion |
| `<C-e>` | Insert | Abort/close completion |
| `<CR>` | Insert | Confirm selection |
| `<Tab>` / `<S-Tab>` | Insert/Snippet | Next/previous snippet jump |

---

## Git

| Key | Mode | Action |
|-----|------|--------|
| `<leader>gg` | Normal | Open Neogit |
| `<leader>gj` | Normal | Next hunk |
| `<leader>gk` | Normal | Previous hunk |
| `<leader>gp` | Normal | Preview hunk |
| `<leader>gr` | Normal | Reset hunk |
| `<leader>gR` | Normal | Reset buffer |
| `<leader>gs` | Normal | Stage hunk |
| `<leader>gu` | Normal | Undo stage hunk |
| `<leader>gl` | Normal | Blame line |
| `<leader>gd` | Normal | Git diff (HEAD) |
| `<leader>gy` | Normal | Copy git link |
| `<leader>gY` | Normal | Copy git link with blame |

---

## Testing (Neotest)

| Key | Mode | Action |
|-----|------|--------|
| `<leader>tt` | Normal | Run nearest test |
| `<leader>tf` | Normal | Run test file |
| `<leader>td` | Normal | Debug test (DAP) |
| `<leader>ts` | Normal | Stop test |
| `<leader>ta` | Normal | Attach to test |

---

## Terminal (Toggleterm)

| Key | Mode | Action |
|-----|------|--------|
| `<M-1>` | Normal/Terminal | Toggle horizontal terminal |
| `<M-2>` | Normal/Terminal | Toggle vertical terminal |
| `<M-3>` | Normal/Terminal | Toggle floating terminal |
| `<leader>;` | Normal | Open new terminal |
| `<C-;>` | Terminal | Exit terminal mode |

---

## Code Folding (UFO)

| Key | Mode | Action |
|-----|------|--------|
| `zR` | Normal | Open all folds |
| `zM` | Normal | Close all folds |
| `zr` | Normal | Open folds (one level) |
| `zm` | Normal | Close folds (one level) |
| `K` | Normal | Peek fold (or hover if not folded) |

---

## Symbol Navigation (Navbuddy)

| Key | Mode | Action |
|-----|------|--------|
| `<leader>o` | Normal | Open Navbuddy |
| `<M-s>` / `<M-o>` | Normal | Open Navbuddy (fullscreen) |

---

## Copilot

| Key | Mode | Action |
|-----|------|--------|
| `<C-l>` | Insert | Accept suggestion |
| `<C-j>` | Insert | Next suggestion |
| `<C-k>` | Insert | Previous suggestion |
| `<C-h>` | Insert | Dismiss suggestion |
| `<C-s>` | Normal | Toggle auto-trigger |
| `<M-CR>` | Normal | Open Copilot panel |
| `r` | Panel | Refresh suggestions |

---

## Tabs

| Key | Mode | Action |
|-----|------|--------|
| `<leader>an` | Normal | New empty tab |
| `<leader>aN` | Normal | New tab with current file |
| `<leader>ah` | Normal | Move tab left |
| `<leader>al` | Normal | Move tab right |
| `<leader>ao` | Normal | Close other tabs |

---

## Misc

| Key | Mode | Action |
|-----|------|--------|
| `<leader>v` | Normal | Vertical split |
| `<leader>q` | Normal | Quit (with confirmation) |
| `<leader>y` | Normal | Cellular Automaton effect (fun!) |
| `<c-p>` | Normal | Open projects finder |
