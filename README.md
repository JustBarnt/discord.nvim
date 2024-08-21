# discord.nvim

## Installation

Lazy: 

```lua
{
    'justbarnt/discord.nvim',
    config = function()
        local discord = require('discord')

        discord.setup()
    end
}
```

This plugin requires the [rpc server](https://github.com/lpturmel/nvim-discord)
