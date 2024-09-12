# My Neovim Configuration

This is my way of using [Neovim](https://github.com/neovim/neovim), I use [LazyVim](https://github.com/LazyVim/LazyVim) as a starter.

## Requirements

- GUI Terminal, I use [iTerm2](https://github.com/gnachman/iTerm2) but might migrate to [WezTerm](https://github.com/wez/wezterm)
- [LazyGit](https://github.com/jesseduffield/lazygit) installed, `brew install lazygit`
- [Nerdfont](https://www.nerdfonts.com/font-downloads) installed, I use [Fira Code](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/FiraCode.zip)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim) needs [FD](https://github.com/sharkdp/fd) and [RipGrep](https://github.com/BurntSushi/ripgrep) installed, both can be installed by `brew`
- `Rust` and `Node` installed, for Rust `brew install rust`, for Node I use `nvm` and need to run `nvm alias default node`

## Helpful Links

- <https://stackoverflow.com/questions/9164405/vim-surround-inserts-extra-space-around-the-word>
- <https://www.reddit.com/r/neovim/comments/13pr3nn/how_to_switch_focus_between_the_terminal_buffer>
- <https://vi.stackexchange.com/questions/39247/how-to-integrate-an-own-vim-color-scheme-into-neovim>

## Customization

- disabled nvim-cmp in `disabled.lua`
- using theme `dracula_pro_van_helsing` in `colorscheme.lua`, this is custom and needs local `colors` & `autoload` folders

## Improvements

- default to `catppuccin` colorscheme when `dracula_pro` folder is not present
- bring in overseer to run tasks
- install `neotests` for `golang` tests
- test `debugging`
- disable arrow keys to get used to h, j, k, l
