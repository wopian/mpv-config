# mpv config

[![release badge]][release]
[![donate badge]][donate]

## Usage

### Windows

#### Install

```console
cd $HOME/AppData/Roaming/mpv
git init .
git remote add -t \* -f origin https://github.com/wopian/mpv-config
git checkout master
```

#### Update

```console
git -C $HOME/AppData/Roaming/mpv pull
```

### BSD, Linux & MacOS

#### Install

```console
cd ~/.config/mpv
git init .
git remote add -t \* -f origin https://github.com/wopian/mpv-config
git checkout master
```

#### Update

```console
git -C ~/.config/mpv pull
```

## Example

[diff.pics comparison](http://diff.pics/UasGxbWi3k4W/1)

### Config

![](https://i.imgur.com/qamsvtC.jpg)

### Default (0.24.0)

![](https://i.imgur.com/UTUPumd.jpg)

[release]:https://github.com/wopian/mpv-config/releases
[release badge]:https://img.shields.io/github/release/wopian/mpv-config.svg?style=flat-square

[donate]:https://paypal.me/wopian
[donate badge]:https://img.shields.io/badge/support%20me%20on-paypal.me-ff69b4.svg?style=flat-square
