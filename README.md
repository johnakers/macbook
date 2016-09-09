# macbook
How I setup my 13" MacBook Air

This isn't 100% the order of this as I'm doing this after setup, but its more or less it. This doesn't take too long to get up and running for Ruby development. I'm adding things as I go, where relevant.

- [Chrome](https://www.google.com/chrome/browser/desktop/index.html)<br>
    -- Sign In + Gmail
- [Spectacle](https://www.spectacleapp.com/)
- [iTerm2](https://www.iterm2.com/)<br>
    -- Change font to `Source Code Pro` via `Preferences -> Profiles -> Text` (download link in #8)
- [Caffiene](https://itunes.apple.com/us/app/caffeine/id411246225?mt=12)
- [Homebrew](http://brew.sh/) (note: this requires Xcode)
- [git](https://git-scm.com/book/en/v1/Getting-Started-Installing-Git#Installing-on-Mac) via Homebrew
- [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) (requires git)<br>
    -- set theme to [steef](https://github.com/robbyrussell/oh-my-zsh/wiki/themes#steeef)
- [Sublime Text](https://www.sublimetext.com/) (note: I bought a license a long time ago)<br>
    -- [Set up 'subl' command](http://stackoverflow.com/questions/11889484/command-subl-from-terminal-dont-work/16390622#16390622)<br>
    -- [Dark Room theme via ColorSublime](http://colorsublime.com/?q=dark+room)<br>
    -- [Adobe's Source Code Pro font](https://github.com/adobe-fonts/source-code-pro)<br>
    -- Below goes in `Preferences -> User`
```JS
// Preferences
{
	"color_scheme": "Cache/ColorSublime/DarkRoomNormal.tmTheme",
	"font_face": "Source Code Pro",
	"font_size": 12,
	"ignored_packages":
	[
		"Vintage"
	],
	"rulers":
	[
		110
	],
	"save_on_focus_lost": true,
	"show_full_path": true,
	"tab_size": 2,
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true
}
```
- [rbenv](https://github.com/rbenv/rbenv#homebrew-on-mac-os-x) via Homebrew<br>
    -- ensure your `PATH` is correct!<br>
    -- for now, global Ruby version set to 2.2.1
- [install bundler](http://bundler.io/)
- [Slack App](https://itunes.apple.com/us/app/slack/id803453959?mt=12)
- [Node Version Manager](https://github.com/creationix/nvm) via Homebrew<br>
    -- [Add `source $(brew --prefix nvm)/nvm.sh` & `export NVM_DIR=~/.nvm` to your `.zshrc`](http://stackoverflow.com/a/27652360)
- [NPM](https://www.npmjs.com/) via Homebrew
- [`tree`](http://mama.indstate.edu/users/ice/tree/) via Homebrew
- [PostgreSQL](https://www.postgresql.org/) via Homebrew<br>
    -- Note: your DB will be stopped and started via `brew services start/stop postgresql`
- ~~[LÖVE2D](https://love2d.org/)~~
- ~~[asciinema](https://asciinema.org/) via Homebrew~~
- [Giphy Capture](https://itunes.apple.com/us/app/giphy-capture.-the-gif-maker/id668208984?mt=12)
- [Unity](https://unity3d.com)
- [Aseprite](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwj52cDc4bnOAhVI7WMKHbpZCYgQFggeMAA&url=http%3A%2F%2Fwww.aseprite.org%2F&usg=AFQjCNExMdw-b8GLabpEFBiXLpoyGwyYYA&sig2=gK5bF6Zz-Dovydh9QbXrQw)
- ~~[Fusion360](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwj7vuDi4bnOAhVG5WMKHVuABBkQFggvMAA&url=http%3A%2F%2Fwww.autodesk.com%2Fproducts%2Ffusion-360%2Foverview&usg=AFQjCNFmAFML64--aKSkOtGMgxIiCatdgw&sig2=ZBSbg_wbXjV8XgbqKhJApA)~~
- [Heroku Toolbelt](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwiyiazr4bnOAhUL7mMKHeE-BoEQFggvMAA&url=https%3A%2F%2Ftoolbelt.heroku.com%2F&usg=AFQjCNHcfl5kmTpnA5VOL769KH15iDN_Ug&sig2=dORhDHopkW4mRMA2ieTjYQ)
