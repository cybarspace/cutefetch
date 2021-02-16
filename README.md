# cutefetch
Cute little sysinfo fetch script for use in screenshots.

## PS: This is the branch where I run my experiments. Use at your own risk. (not that I'd take any liability if you use the main branch)

A "fork" of [elenapan](https://github.com/elenapan)'s [bunnyfetch](https://github.com/elenapan/dotfiles/blob/master/bin/bunnyfetch) script.

PS: I don't know how to fork single scripts from larger repos.

### Install
- Place the fetch script somewhere on your `$PATH` (I use `$HOME/.local/bin/`)
- Make it executable by running `chmod a+x ./cutefetch` in the directory it is located

### Usage
After installation, run `cutefetch` in the terminal.

Command line arguments can be passed to specify the animal and eye style.
- Valid animal arguments: kitty, k, bunny, b
- Valid eye styles: integers from 0 to 13

Examples: `cutefetch kitty 6`, `cutefetch k 6`, `cutefetch` prints the default kitty.
`cutefetch bunny 0`, `cutefetch b 0`, `cutefetch b`, etc. prints a bunny.

PS: You can pass an eye style without an animal argument to print a kitty with that eye style.

### Screenshots

![desktop](https://imgur.com/tX8Fqt4.png)

### Links:
- [original script](https://github.com/elenapan/dotfiles/blob/master/bin/bunnyfetch)
- [author's repo](https://github.com/elenapan/dotfiles/)
