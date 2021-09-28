# Installing Emacs
I use emacs with the native-comp feature. To get that you can either download the tarballs from [here](https://github.com/jimeh/emacs-builds) or build it [by following the instructions over here](https://github.com/jimeh/build-emacs-for-macos).

# JetBrains mono font
The JetBrains Mono font can be [downloaded from here](https://www.jetbrains.com/lp/mono/).

# Installing Doom Emacs
To setup doom emacs follow the instructions [in the repository](https://github.com/hlissner/doom-emacs#install)
If your emacs installation has native compilation support then setting up doom emacs will take some time.

# Configuring Doom Emacs
Doom emacs creates its own directory at `~/.doom.d/` where your custom configuration resides. You can clone this repository to that location and run `doom sync`.
When you open emacs the initial load can take some time. Consecutive loads will be faster.

> Any changes to the package list in `~/.doom.d/init.el` requires that you run `doom sync`

# Clojure LSP
When you open a clojure project for the first time emacs will prompt you for installing the lsp server. This can take some time or fail depending on your network.
For configuring your lsp setup for clojure you can [follow this guide here](https://emacs-lsp.github.io/lsp-mode/tutorials/clojure-guide/).

# Pending items
* [Setting up dap for clojurescript](https://emacs-lsp.github.io/lsp-mode/tutorials/debugging-clojure-script/)
