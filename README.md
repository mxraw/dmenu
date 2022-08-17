# dmenu

This version of dmenu is inspired by [Luke Smith's version](https://github.com/lukesmithxyz/dmenu.git). and tries to track changes in that repository.

However, there are a couple of noteworthy differences.

- This version is based on [upstream by suckless](https://tools.suckless.org/dmenu) and prioritizes tracking new updates from there.
- This version installs to $HOME instead of /usr.
- This version has the same patches applied to them as Luke's version, but they are tracked in separate branches and have been changed to ease patch management. Those are:
	- [alpha](https://tools.suckless.org/dmenu/patches/alpha/)
	- [mouse-support](https://tools.suckless.org/dmenu/patches/mouse-support/)
	- [password](https://tools.suckless.org/dmenu/patches/password/)
	- [reject-no-match](https://tools.suckless.org/dmenu/patches/reject-no-match/)
	- [xresources](https://tools.suckless.org/dmenu/patches/xresources/) (heavily refactored)