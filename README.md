# blade-lsp-mason

Custom [Mason](https://github.com/williamboman/mason.nvim) registry for [blade-lsp](https://github.com/gcavanunez/blade-lsp).

## Installation

Add this registry before the default Mason registry in your Neovim config:

```lua
require("mason").setup({
  registries = {
    "github:gcavanunez/blade-lsp-mason",
    "github:mason-org/mason-registry",
  },
})
```

Then run `:MasonUpdate` to refresh registries, followed by `:MasonInstall blade-lsp`.

## Packages

- **blade-lsp** — LSP for Laravel Blade templates
