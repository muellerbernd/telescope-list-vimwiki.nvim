# telescope-list-vimwiki.nvim
Telescope extension to list all configured vimwikis

### Requirements
- [neovim](https://github.com/neovim/neovim) (>= 0.5.0)
- [vimwiki](https://github.com/vimwiki/vimwiki)
- [nvim-telescope](https://github.com/nvim-telescope/telescope.nvim)

### Installation and Configuration

1. Install using your favorite plug-in manager (e.g. [packer](https://github.com/wbthomason/packer.nvim), [vim-plug](https://github.com/junegunn/vim-plug), etc.), Example with Packer:
```lua
    use "muellerbernd/telescope-list-vimwiki.nvim"
```

2. Configure [telescope](https://github.com/nvim-telescope/telescope.nvim)

3. Load extension:

```lua
require('telescope').load_extension('list_vimwikis')
```

### Usage

```
:Telescope list_vimwikis
```
