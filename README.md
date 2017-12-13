# macbook
How I setup my 13" MacBook Air

- [ ] [Chrome](https://www.google.com/chrome/browser/desktop/index.html)
- [ ] [Spectacle](https://www.spectacleapp.com/)
- [ ] [Adobe's Source Code Pro font](https://github.com/adobe-fonts/source-code-pro)
- [ ] [iTerm2](https://www.iterm2.com/)<br>
- Change font to `Source Code Pro` via `Preferences -> Profiles -> Text`
- Set up escape character for moving between words https://coderwall.com/p/h6yfda/use-and-to-jump-forwards-backwards-words-in-iterm-2-on-os-x
- [ ] [Caffiene](https://itunes.apple.com/us/app/caffeine/id411246225?mt=12)
- [ ] [Homebrew](http://brew.sh/) (note: this requires Xcode)
- [ ] [git](https://git-scm.com/book/en/v1/Getting-Started-Installing-Git#Installing-on-Mac) via Homebrew
- [ ] [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) (requires git)
- set theme to [steef](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#steeef)
- [ ] [Sublime Text](https://www.sublimetext.com/) (note: I bought a license a long time ago)
- [Set up 'subl' command](http://stackoverflow.com/questions/11889484/command-subl-from-terminal-dont-work/16390622#16390622)
- Boxy Monokai Theme, via Package Control<br>
- GitGutter Package, via Package Control<br>
- Bracket Highlighter Package, via Package Control<br>
- Git, via Package Control<br>
- Below goes in `Preferences -> User`, not 100% up to date but configurable
```JS
{
	"color_scheme": "Packages/Boxy Theme/schemes/Boxy Monokai.tmTheme",
	"font_face": "Source Code Pro",
	"font_size": 11,
	"ignored_packages":
	[
		"Vintage"
	],
	"line_padding_top": 3,
	"rulers":
	[
		110
	],
	"save_on_focus_lost": true,
	"show_full_path": true,
	"tab_size": 2,
	"theme": "Boxy Monokai.sublime-theme",
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true,
	"word_wrap": "false"
}
```

- [ ] [rbenv](https://github.com/rbenv/rbenv#homebrew-on-mac-os-x) via Homebrew<br>
- ensure your `PATH` is correct!
- [ ] install [bundler](http://bundler.io/)
- [ ] [Slack App](https://itunes.apple.com/us/app/slack/id803453959?mt=12)
- [ ] [Node Version Manager](https://github.com/creationix/nvm) via Homebrew<br>
- [Add `source $(brew --prefix nvm)/nvm.sh` & `export NVM_DIR=~/.nvm` to your `.zshrc`](http://stackoverflow.com/a/27652360)
- [ ] [NPM](https://www.npmjs.com/) via Homebrew
- [ ] [`tree`](http://mama.indstate.edu/users/ice/tree/) via Homebrew
- [ ] [PostgreSQL](https://www.postgresql.org/) via Homebrew<br>
- Note: your DB will be stopped and started via `brew services start/stop postgresql`
- [ ] [asciinema](https://asciinema.org/)
- [ ] [Giphy Capture](https://itunes.apple.com/us/app/giphy-capture.-the-gif-maker/id668208984?mt=12)
- [ ] [Heroku Toolbelt](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwiyiazr4bnOAhUL7mMKHeE-BoEQFggvMAA&url=https%3A%2F%2Ftoolbelt.heroku.com%2F&usg=AFQjCNHcfl5kmTpnA5VOL769KH15iDN_Ug&sig2=dORhDHopkW4mRMA2ieTjYQ)
- [ ] [vim-plug](https://github.com/junegunn/vim-plug)
- `.vimrc`
```vim
" vim-plug
" :: on new .vimrc, run PlugUpdate
" :: https://github.com/junegunn/vim-plug
call plug#begin('~/.vim/plugged')

Plug 'skielbasa/vim-material-monokai'
Plug 'vim-airline/vim-airline'

call plug#end()

" config
syntax on
set number
set background=dark
colorscheme material-monokai

" material monokai
let g:materialmonokai_italic=1
let g:airline_theme='materialmonokai'
```
- [ ] [1Password for Mac](https://1password.com/downloads/)
- [ ] [OBS](https://obsproject.com/)
