# macbook
How I setup my 13" MacBook Air

This isn't 100% the order of this as I'm doing this after setup, but its more or less it. This doesn't take too long to get up and running for Ruby development. I'm adding things as I go, where relevant.

1.  [Chrome](https://www.google.com/chrome/browser/desktop/index.html)<br>
    -- Sign In + Gmail
2.  [Spectacle](https://www.spectacleapp.com/)
3.  [iTerm2](https://www.iterm2.com/)
4.  [Caffiene](https://itunes.apple.com/us/app/caffeine/id411246225?mt=12)
5.  [Homebrew](http://brew.sh/) (note: this requires Xcode)
6.  [git](https://git-scm.com/book/en/v1/Getting-Started-Installing-Git#Installing-on-Mac) via Homebrew
7.  [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) (requires git)<br>
    -- set theme to [steef](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#steeef)
8.  [Sublime Text](https://www.sublimetext.com/) (note: I bought a license a long time ago)<br>
    -- [Set up 'subl' command](http://stackoverflow.com/questions/11889484/command-subl-from-terminal-dont-work/16390622#16390622)<br>
    -- [Tomorrow Night Eighties theme via ColorSublime](http://colorsublime.com/?q=tomorrow+night+eighties)<br>
    -- [Adobe's Source Code Pro font](https://github.com/adobe-fonts/source-code-pro)
9.  [rbenv](https://github.com/rbenv/rbenv#homebrew-on-mac-os-x) via Homebrew<br>
    -- ensure your `PATH` is correct!<br>
    -- for now, global Ruby version set to 2.2.1
10. [install bundler](http://bundler.io/)
11. [Slack App](https://itunes.apple.com/us/app/slack/id803453959?mt=12)
12. [Node Version Manager](https://github.com/creationix/nvm) via Homebrew<br>
    -- [Add `source $(brew --prefix nvm)/nvm.sh` & `export NVM_DIR=~/.nvm` to your `.zshrc`](http://stackoverflow.com/a/27652360)
13. [NPM](https://www.npmjs.com/) via Homebrew
14. [`tree`](http://mama.indstate.edu/users/ice/tree/) via Homebrew
15. [PostgreSQL](https://www.postgresql.org/) via Homebrew<br>
    -- Note: your DB will be stopped and started via `brew services start/stop postgresql`
16. [LÖVE2D](https://love2d.org/)
17. [asciinema](https://asciinema.org/) via Homebrew
18. [Giphy Capture](https://itunes.apple.com/us/app/giphy-capture.-the-gif-maker/id668208984?mt=12)
