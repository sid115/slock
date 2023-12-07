# My custom build of suckless's slock

[Suckless's slock](https://tools.suckless.org/slock/) for my personal machine.

## Installation

```
mkdir -p ~/.local/src
cd ~/.local/src
git clone https://github.com/sid115/slock.git
cd slock
```

Set `user` and `group` in `config.h`.

```
sudo make clean install
```

## Usage

Run `slock` to lock your screen and type your password to unlock it.
