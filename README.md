# Vish

> A simple NeoVim plugin manager for fish

Install, uninstall and update plugins using fish. A simple wrapper around the vim `:pack` functionality.

## Installation

It's recommended that you install using [fisher](https://github.com/jorgebucaran/fisher)

**Requirements**

- [fish](http://fishshell.com)
- [neovim](https://neovim.io)
- [git](https://git-scm.com)

```console
fisher add lkemitchll/vish
vish init
```

## Usage

### Installing a plugin

Install a plugin with the `install` (or `i`) command:

```console
vish install tpope/vim-fugitive
```

### Uninstalling a plugin

Uninstall a plugin with the `uninstall` (or `u`) command:

```console
vish uninstall vim-fugitive
```

### Update all plugins

Update all installed plugins with the `update` command:

```console
vish update
```

### List/search plugins

List all installed plugins with the `list` (or `ls`) command:

```console
vish list
```

```console
vish list fugitive
```

### License

[MIT](LICENSE.md)
