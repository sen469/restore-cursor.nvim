# restore-cursor.nvim

A small Neovim plugin to restore the last cursor position when reopening a file.

## Installation

### With lazy.nvim

```lua
{
  "sen46/restore-cursor.nvim",
  config = function()
    require("restore_cursor").setup()
  end,
}
