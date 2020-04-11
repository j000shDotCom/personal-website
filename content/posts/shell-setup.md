---
title: "Dev Environment Setup"
date: 2020-04-09T14:20:00-08:00
draft: true
---

Finally getting around to setting up [my dotfiles](https://github.com/josh-dot-com/dotfiles) and really learning how to use vim, zsh, stow, and all the tools. Going to jot down some notes for reference.

Also, I must shamefully point out that I wrote this in VS Code with the really handy markdown viewer! Maybe this could be a good first dive into editing with emacs! ... soon™️

### Zsh

Not sure I have any concrete understanding yet. Just consumed some learnings about different popular options and stuff from a [comparison of ZSH frameworks](https://gist.github.com/laggardkernel/4a4c4986ccdcaf47b91e8227f9868ded) and /r/unixporn mod [xero](https://github.com/xero/dotfiles/tree/master/zsh). I settled on [zinit](https://github.com/zdharma/zinit) (formerly zplugin) and will try to learn more about how plugin managers work.

### Git and SSH configs

Finally got around to setting up a USABLE `.gitconfig` `.ssh/config`. I always want to have multiple identity files (for personal, work, and student use), but never spent time looking into how to go about it. You can find them in [my dotfiles](https://github.com/josh-dot-com/dotfiles) repo.

### Stow

Seeing that GNU stow seems recommended by my buddy Girdler and xero, so I figure I'll give it a shot.

``` bash
stow -d Repos/dotfiles -t . git ssh zsh
```

[Straightforward example](https://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html) of how to use stow

### Vim

Considering paying for a 6-month [Vim Adventures](https://vim-adventures.com) license

Reddit also mentions the following:

- [PacVim](https://github.com/jmoon018/PacVim)
- [VimGolf](https://vimgolf.com/)
- [Onramp to Vim](https://thoughtbot.com/upcase/onramp-to-vim) if you like videos
- `vimtutor`, of course

### Emacs

Also, Girdler has been a strong advocate for [Doom Emacs](https://github.com/hlissner/doom-emacs) and helped me get it set up on my machines.

### Screen

TBD

### Tmux

TBD

### MacOS software

Much like everything there a plethora of terminal options. I don't have as much experience to weigh the pros and cons, but here are some options.

#### Terminal Emulators

- [Alacritty](https://github.com/alacritty/alacritty) - cross-platform, GPU-accelerated terminal emulator
- [iTerm2](https://iterm2.com/) - tabs and windows?

#### Text Editors / Operating Systems

- [spacemacs](https://www.spacemacs.org/) - supposedly emacs AND vim!
- [NeoVim](https://neovim.io/)
- [VS Code](https://code.visualstudio.com/)
