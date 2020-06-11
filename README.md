# mpv config

[![release badge]][release]

## Usage

Requires the following font to be installed on the system: `Alte Haas Grotesk Regular`

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
[release badge]:https://flat.badgen.net/github/release/wopian/mpv-config
