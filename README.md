<img width="4112" height="616" alt="image" src="https://github.com/user-attachments/assets/8cba8e8c-7402-4934-9640-6e37bd4b775c" />

- column range is is highlighted in `qfMatch` highlight group
- supports multiple column ranges. for example in above screenshot, in second items `true` is highlighted twice
- `q` quits quickfix window
- relative number, signcolumn turned off

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
