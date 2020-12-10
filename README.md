# clipboard
A simple clipboard tool:
```
$ clipboard --help
Usage: clipboard [-f|--force] [-h|--help]

EXAMPLES

Copy STDIN:
  echo 'Hello, world!' | clipboard

Paste to STDOUT:
  clipboard

Paste image to file:
  clipboard > foo.png
```


# Prerequisites
You'll need bash and [xclip](https://sourceforge.net/projects/xclip/).

Ubuntu:
```
sudo apt-get install xclip
```

Arch:
```
sudo pacman -S xclip
```


# Installation
Put [clipboard](clipboard) on your `PATH`, e.g.
```
wget \
  https://raw.githubusercontent.com/felixhummel/clipboard/master/clipboard \
  -O ~/.local/bin/clipboard
chmod +x ~/.local/bin/clipboard
```


# Development
Clone this and put [clipboard](clipboard) on your `PATH`, e.g.
```
git clone https://github.com/felixhummel/clipboard.git
cd clipboard
ln -s $PWD/clipboard ~/.local/bin/clipboard
hash clipboard
```
