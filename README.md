# The Boydrice (my dotfiles)

These are the dotfiles deployed by [DFI](https://github.com/tiesinto/dfi).

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- nsxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/lukesmithxyz/dwm) (window manager)
- [dwmblocks](https://github.com/lukesmithxyz/dwmblocks) (statusbar)
- [st](https://github.com/lukesmithxyz/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [DFI](https://github.com/tiesinto/dfi) to autoinstall everything:

```
curl -LO https://github.com/tiesinto/dfi/blob/master/static/larbs.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/tiesinto/dfi/blob/master/static/progs.csv).

## Default Desktop Artwork

My favorite Yume 2kki wallpaper, *No.01* by FOUNCID (wallpaper №15) ([pixiv](https://www.pixiv.net/users/796402))

##
![screenshot](./boyd.webp)
