# Guide on how to use dotfiles

1. Install i3-gaps, nitrogen, polybar, stow, neovim, rofi and picom with your package manager.
2. Clone this repo to $HOME
3. Use stow to link dotfiles.
    * Delete ~/.config/x (where x is one of the folders)
    * Inside .dotfiles use stow -S x
    * .dotfiles/x content is now mirrored in .config, edits in both places will have same effect.
