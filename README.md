# Rope.nvim

Simple lua and python wrapper around the rope python library


```lua
{ "niilohlin/rope",
  config = function()
    local null_ls = require("null-ls")
    local rope = require("rope")
    null_ls.register(rope.auto_import)
    null_ls.register(rope.completion)
  end,
}
```
