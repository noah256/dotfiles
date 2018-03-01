# My Dotfiles

## Installing

```bash
git clone git@github.com:noahsilas/dotfiles.git
cd ./dotfiles
./linkup

vim -c PlugInstall

# compile Command-T
cd ~/.vim/plugged/Command-T/ruby/command-t/ext/command-t
ruby extconf.rb
make
```

## Other Important elements
- Install the iTerm colorscheme (or Vim will look very jank):
  https://github.com/chriskempson/base16-iterm2
- Install a Powerline patched font (and tell iTerm to use it):
  https://github.com/powerline/fonts
  I'm partial to Inconsolata-dz.
