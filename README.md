# Overview
This plugin wraps cheat.sh in a telescope picker, allowing you to recursively search through cheat.sh entries and them open them in local buffers. 
The plugin caches responses from cheat.sh to your local filesystem to make frequent sheets load faster.

Default keymap is `<leader>sc` for [S]earch [C]heat.

# Installation

## Lazy
```lua
return {
  '13janderson/chtsht.nvim',
  dependencies = {
    'nvim-telescope/telescope.nvim',
  },
  -- Optional keymap to use, default is <leader>sc for [S]earch [C]heat
  config = function()
    require('chtsht').setup '<leader>sc'
  end,
}
```
