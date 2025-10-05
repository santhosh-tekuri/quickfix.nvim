<img width="4112" height="616" alt="image" src="https://github.com/user-attachments/assets/8cba8e8c-7402-4934-9640-6e37bd4b775c" />

- column range is is highlighted in `qfMatch` highlight group
- supports multiple column ranges. for example in above screenshot, in second items `true` is highlighted twice

## Plugin ID

```text
santhosh-tekuri/quickfix.nvim
https://github.com/santhosh-tekuri/quickfix.nvim
```

## Configuration

there is no `setup` function

```lua
vim.o.quickfixtextfunc = require("quickfix").quickfixtextfunc
```

the following changes are also done:

- `q` quits quickfix window
- `o` changes current quickfix item and closes quickfix list
- `d` `x_d` deleted current/selected items from quickfix list
- relative number, signcolumn turned off

if you dont want the above changes then you can do `vim.cmd("autocmd!  QFTweaks")`
