# filepaths_ls.nvim

In-process filepath completion for Neovim's built-in LSP client.

## Features

- **Buffer-relative** by default with `./` and `../`
- **Absolute, `~/`, and `$VAR/` paths** expansion
- **Responsive scanning** batches large directories to reduce UI hitching
- **Preview on select**
    - Absolute files path
    - File size
    - Binary file detection
    - Symlink target and broken symlink detection
    - Content preview

## When To Use It

Use this if you want filepath completion through Neovim's built-in LSP completion or [`mini.completion`](https://github.com/nvim-mini/mini.nvim).

> [!WARNING]
> If you use [`blink.cmp`](https://github.com/Saghen/blink.cmp) or [`nvim-cmp`](https://github.com/hrsh7th/nvim-cmp) with [`cmp-path`](https://github.com/hrsh7th/cmp-path), you do not need this LS

## Requirements

- Neovim 0.11+

## Installation

With `vim.pack` in Neovim 0.12+

```lua
vim.pack.add({
    'https://github.com/antonk52/filepaths_ls.nvim',
})
```

With [`lazy.nvim`](https://github.com/folke/lazy.nvim)

```lua
{
    'antonk52/filepaths_ls.nvim',
}
```

## Usage

```lua
vim.lsp.enable('filepaths_ls')
```

Completion starts when the token already looks like a path, for example `./`, `../`, `~/`, `/`, or `$VAR/`.

## Configuration

Omit this if the defaults already work for you.

```lua
vim.lsp.config('filepaths_ls', {
    settings = {
        ---Sort directories first or keep the system order.
        ---@type 'dir_first' | 'system'
        sort = 'dir_first',

        ---Show directories as `foo/` in the completion menu.
        ---@type boolean
        label_dir_trailing_slash = true,

        ---Insert `foo/` instead of `foo` when accepting a directory.
        ---@type boolean
        insert_dir_trailing_slash = false,

        ---Show symlinks as `foo@` in the completion menu.
        ---@type boolean
        label_symlink_trailing_at = true,

        ---Positive cap for completion items returned from one directory scan.
        ---@type integer
        max_items = 1000,
    },
})
```
