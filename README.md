# dotfiles

My dot files. Based on [The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles). Uses names `.dotfiles` and `dotfiles` instead of `.cfg` and `config`.

### Installation

By running [installation script](https://gist.github.com/vhenzl/d430f5e3387177fb22e9234438fc33d1):

```
curl -sS https://gist.githubusercontent.com/vhenzl/d430f5e3387177fb22e9234438fc33d1/raw/0591a3573563960599eaa4e5a2ee7680ff585771/dotfiles | bash
```

### Local configs

It may be necessary to adjust Git configuration (like `core.autocrlf`) on different machines. The main `.gitconfig` [includes](https://git-scm.com/docs/git-config#_includes) `~/.gitconfig.local` which can be created locally to tweek Git config as needed.
