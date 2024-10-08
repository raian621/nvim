# Ryan's Neovim Config

Extends the configuration from thePrimeagen's [0 to LSP: Neovim RC from Scratch](https://www.youtube.com/watch?v=w7i4amO_zaE) video tutorial. I added code coverage, a couple extra language servers, and configured a gruvbox theme.

## Installation

After [installing Neovim](https://github.com/neovim/neovim/blob/master/INSTALL.md), clone this repository into your config folder:

### Linux

```sh
git clone git@github.com:raian621/nvim.git ~/.config/nvim
```

### Windows

```sh
git clone git@github.com:raian621/nvim.git ~/AppData/Local/nvim
```

then, in the cloned `nvim` directory, open `./lua/ryan/packer.lua` in Neovim and run the `so` command followed by the `PackerSync` command to download the plugins used in this Neovim config.

> [!important]
> Most of the default language servers in this config can be installed without extra dependencies, but `gopls` needs `go` to be installed before it will successfully download.
