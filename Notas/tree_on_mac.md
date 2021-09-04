A simple alias will allow you to view folder trees from the command line of Mac OS:

1.  Launch Terminal or iTerm if you haven’t done so already
2.  Open your .bashrc or .zshrc profile in your preferred text editor, we’re using nano because nano is easy:

`nano .zshrc`

4.  On a new line, paste the following alias:

`alias tree="find . -print | sed -e 's;[^/]*/;|____;g;s;____|; |;g'"`

6.  Hit Control+O and Control+X to save and exit out of nano (or quit from vim or emacs as usual), your tree command for printing directory trees is now ready to use

![View folder tree on Mac with tree alias ](https://cdn.osxdaily.com/wp-content/uploads/2016/09/view-folder-tree-mac-command-line-3-610x419.jpg)

Open a new Terminal or [reload your Terminal profile](https://osxdaily.com/2016/06/07/reload-bash_profile-zsh-profiles-command-line/) and you’re ready to use the new tree alias.