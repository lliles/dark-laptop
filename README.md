# About #

This is a port of the original dark-laptop color theme by Laurent
Michel to Emacs 24.

# Installation #

Download `dark-laptop-theme.el` to a folder in your Emacs config
directory such as `~/.emacs.d/themes/`. 

Add this folder to the custom theme load path by placing the following
in your `init.el`:

`(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")`

Now you can load the theme with the interactive function `load-theme`
with:

`M-x load-theme dark-laptop`

Or you can place the following in your `init.el` to have it loaded at
startup:

`(load-theme 'dark-laptop)`

# Bugs & Improvements #

This is mostly a straight port of the original dark-laptop theme, so
it lacks faces for some of the more recent Emacs features and
packages. Bug fixes and improvements in the form of pull requests are
welcomed.

