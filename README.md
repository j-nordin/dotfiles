# Guide on how to use dotfiles

1. Install the program(s) you want to configure, ex i3
2. Clone this repo to $HOME
3. Use stow to link dotfiles.
    * Delete ~/.config/x (where x is one of the folders, ex 'i3')
    * Inside dotfiles use `stow -S x` (ex `stow -S i3` or `stow -S /*` for all folders and `stow -S /` for the zsh-config)
    * dotfiles/x content is now mirrored in .config, edits in both places will have same effect.
