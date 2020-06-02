# Neovim-config
This is my neovim config

## Bindings
Modes | Keys | Actionj
------------ | ------------ | -------------
insert, terminal insert | <kbd>j</kbd> <kbd>j</kbd> | Enter normal mode
normal | <kbd>Ctrl</kbd> <kbd>n</kbd> | Toggle NERDTREE file explorer
normal | <kbd>SPC</kbd> <kbd>t</kbd> | Opens a terminal at the bottom of the screen
normal | <kbd>SPC</kbd> + <kbd>v</kbd> <kbd>t</kbd> | Opens a terminal at the right of the screen
normal | <kbd>Tab</kbd> | Cycle tabs in right direction
normal | <kbd>Shift</kbd> + <kbd>Tab</kbd> | Cycle tabs in left direction
insert | <kbd>Tab</kbd> | If completion pop up open then cycle down the pop up else inserts a tab
insert | <kbd>Shift</kbd> + <kbd>Tab</kbd> | If completion pop up open then cycle up the pop up
normal | <kbd>n</kbd> <kbd>p</kbd> | paste on next line
normal | <kbd>Ctrl</kbd> + (<kbd>h</kbd> or <kbd>j</kbd> or <kbd>k</kbd> or <kbd>l</kbd>) | Change window left, down, up, right respectively.
normal | <kbd>,</kbd> <kbd>g</kbd> <kbd>a</kbd> | git add (Stage changes for commit)
normal | <kbd>,</kbd> <kbd>g</kbd> <kbd>c</kbd> | git commit (Commit added changes)
normal | <kbd>,</kbd> <kbd>g</kbd> <kbd>s</kbd> <kbd>h</kbd> | git push (Push committed changes)
normal | <kbd>,</kbd> <kbd>g</kbd> <kbd>l</kbd> <kbd>l</kbd> | git pull (Pull changes from upstream branch)
normal | <kbd>,</kbd> <kbd>g</kbd> <kbd>d</kbd> | git diff (See unstaged changes)
normal | <kbd>,</kbd> <kbd>g</kbd> <kbd>b</kbd> | git blame (See who changed what)
normal | <kbd>,</kbd> <kbd>h</kbd> | open nvim in horizontal split 
normal | <kbd>,</kbd> <kbd>v</kbd> | open nvim in vertical split
normal | <kbd>,</kbd> <kbd>s</kbd> <kbd>o</kbd> | Open a session
normal | <kbd>,</kbd> <kbd>s</kbd> <kbd>s</kbd> | Save a session
normal | <kbd>,</kbd> <kbd>s</kbd> <kbd>d</kbd> | Delete a session
normal | <kbd>,</kbd> <kbd>s</kbd> <kbd>c</kbd> | Close a session

These are commonly used commands. You can can look at init.vim file for more commands 
