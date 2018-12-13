# OSX Custom Setup
Currently curated for an **OSX 10.14.1 Mojave** fresh install

## Why?

I'm lazy and tend to be very picky on what (and how) to install things on my OS. Automating the process seems a good way to keep things under control and learn some new things..

I'll try to maintain this as:
- A step by step guide after a fresh install
- My research into osx hidden settings (and useful configs)
 

## Use:
After a fresh install of macOS:

1. Check for Updates:
![Software Update](http://f.cl.ly/items/0O0p1b081B2I421r2z2y/Screen%20Shot%202013-11-23%20at%201.27.56%20PM.png)

or

`softwareupdate -ia`

2. Install x-code command tools

`xcode-select --install`

After making sure everything is up to date, just download and run `setup.sh` 

```bash
curl -O https://raw.githubusercontent.com/enblanco/osx-setup/master/setup.sh
chmod +x setup.sh
./setup.sh
````


## References

- https://dotfiles.github.io


## Inspiration

- https://github.com/mathiasbynens/dotfiles/blob/master/.osx
- https://github.com/madsgraphics/osx-clean-install
- https://github.com/webpro/dotfiles


