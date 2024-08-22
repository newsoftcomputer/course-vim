
# ADD ESTRAS

  - 


## Languages

  1. In to Lazy vim with Lazy Vim instaled

  2. Go to Config

  3. Go to lua/config/lazy.lua


    require("lazy").setup({
      spec = {
        { "LazyVim/LazyVim", import = "lazyvim.plugins" },
        
        // ADD HERE
        { import = "lazyvim.plugins.extras.lang.rust" },
        
      { import = "plugins" },
      },
    })
