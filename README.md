# GachaSploit
GachaSploit is a series of exploits developed by expl0itcha1nz for the game "Gacha Life" created by the mobile game company Lunime. These exploits can be utilized to generate gems and XP/levels in-game.

## Installation
You must have [Git](https://git-scm.com) installed in order to download and execute GachaSploit. To download GachaSploit, simply open your Linux terminal and execute:
```bash
git clone https://github.com/expl0itcha1nz/gachasploit
```
## Usage
**GachaSploit is currently only compatible with Linux. If you are on Windows or MacOS, please use the online demo.**

After using `git clone`, `cd` to `gachasploit` and type `make`. After this, you simply have to type `./gachasploit` and instructions will appear before you.

```bash
Usage: ./gachasploit [-h] [--gems GEMS] [--level LEVEL]

Required arguments:
 -g, --gems       | Generate this amount of gems
 -l, --level      | Generate this amount of levels

Optional arguments:
 -h,  --help      | Print usage
 -v,  --version   | Print version
 -cl, --changelog | Print changelog
```

As shown in the above instructional text, using `-g` and `-l` will allow you to generate gems and levels. For example, to generate a save transfer file with 1,000,000 gems and 150 levels, one would have to execute the following command:

```bash
./gachasploit -g 1000000 -l 150
```

## Limitations
The limit for the amount of gems you can generate in this program is 2,147,483,647 - which is the 32-bit integer limit. The limit for the amount of levels you can generate is 151. This program only works on Android on the latest version of Gacha Life.
