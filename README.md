# vim-bicep

A plugin for Microsoft's domain-specific language [Bicep][].

[Bicep]: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview

## Installation

With [Vim 8 packages](http://vimhelp.appspot.com/repeat.txt.html#packages):

```sh
git clone https://github.com/carlsmedstad/vim-bicep.git ~/.vim/pack/plugins/start/vim-bicep
```

With [vim-plug](https://github.com/junegunn/vim-plug):

```vim
call plug#begin()
Plug 'carlsmedstad/vim-bicep'
call plug#end()
```

With NeoVim and [packer-nvim](https://github.com/wbthomason/packer.nvim):

```lua
require("packer").startup(function()
  use("carlsmedstad/vim-bicep")
end)
```

## Credits

Inspiration taken from [vim-terraform][].

[vim-terraform]: https://github.com/hashivim/vim-terraform
