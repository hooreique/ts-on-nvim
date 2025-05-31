```lua
-- Using github:neovim/nvim-lspconfig
if vim.fn.executable 'typescript-language-server' == 1 then
  vim.lsp.config('ts_ls', {})
  vim.lsp.enable 'ts_ls'
end
```
