# Tiny tweaks to luan's vim configs

Right now, this just makes doing git rebases very slightly nicer.

1. Install [this](https://github.com/luan/vimfiles)
1. `git clone https://github.com/totherme/vimtweaks.git`
1. `cd vimtweaks`
1. ```ln -s `pwd`/gds.vim ~/.vimrc.local```

Now when you're doing a `git rebase -i` you should be able to use `<C-j>` and
`<C-k>` to re-order commits, and `p`,`r`,`e`,`s`,`f`,`x` to pick, reword, edit,
squash, fixup, and exec the commit on the current line.
