# cutefetch
Cute little sysinfo fetch script for use in screenshots.

A "fork" of [elenapan](https://github.com/elenapan)'s [bunnyfetch](https://github.com/elenapan/dotfiles/blob/master/bin/bunnyfetch) script.

PS: I don't know how to fork single scripts from larger repos.

### Dependencies
- A terminal emulator with good font support, especially multiple fallback fonts. I use kitty.
- Typicons ([typicons-git](http://aur.archlinux.org/packages/ttf-typicons) in AUR, [website](https://www.s-ings.com/typicons/))

### Install
- Click the "Download script" button and save it somewhere on your `$PATH` (I use `$HOME/.local/bin/`).
- Make it executable by running `chmod a+x ./cutefetch` in the directory it is located.

### Usage
After installing, run `cutefetch` in the terminal.

Command line arguments can be passed to specify the animal and eye style.
- Valid animal arguments: kitty, k, bunny, b
- Valid eye styles: integers from 0 to 13

Examples: `cutefetch kitty 6`, `cutefetch k 6`, `cutefetch` prints the default kitty.
`cutefetch bunny 0`, `cutefetch b 0`, `cutefetch b`, etc. prints a bunny.

`cutefetch $(printf 'kitty\nbunny' | shuf -n 1) $(shuf -i 1-13 -n 1)` prints a random animal with random face. Add this to your `.zshrc`, `.bashrc`, `config.fish`, etc. to spice up your shell. :3

*this wonderful idea of randomizing the animal and face was contributed by [Westofer](https://github.com/westofer)*

PS: You can pass an eye style without an animal argument to print a kitty with that eye style.

### Screenshots

![desktop](https://imgur.com/tX8Fqt4.png)

### Links:
- [original script](https://github.com/elenapan/dotfiles/blob/master/bin/bunnyfetch)
- [author's repo](https://github.com/elenapan/dotfiles/)
