# Guide on how to use dotfiles

1. Install the program(s) you want to configure, ex i3
2. Clone this repo to $HOME
3. Use stow to link dotfiles.
    * Delete ~/.config/x (where x is one of the folders, ex 'i3')
    * Inside dotfiles use `stow -S x` 
        * `stow -S i3` for only the i3-config
        * `stow -S */` for all configs
    * installed (stowed) dotfiles/x content is now mirrored in $HOME, edits in both places will have same effect.
