![Playbox logo](https://raw.githubusercontent.com/cjdenio/playbox/master/img/logo_dark_small.png)
# Playbox

[![Travis (.org)](https://img.shields.io/travis/cjdenio/playbox.svg)](https://travis-ci.org/cjdenio/playbox)
[![GitHub All Releases](https://img.shields.io/github/downloads/cjdenio/playbox/total.svg)](https://github.com/cjdenio/playbox/releases)
[![GitHub issues](https://img.shields.io/github/issues/cjdenio/playbox.svg)](https://github.com/cjdenio/playbox/issues)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/cjdenio/playbox.svg?label=version)](https://github.com/cjdenio/playbox/releases/latest)
[![GitHub](https://img.shields.io/github/license/cjdenio/playbox.svg)](https://github.com/cjdenio/playbox/blob/master/LICENSE)

Playbox is a system for playing back audio during live productions.

### Features
- Super simple interface
- Cues can be any color
- Stage display allows performers to see playing cue
- It's **free**, so what more can you ask for?
- Did I mention it's **cross-platform** too? It works on Windows, MacOS, and pretty much any Linux distribution.
- And it's **open-source**, so you aspiring developers can play around with it.
- It has a *sweet* logo

## Get Playbox

Convinced yet? You can download Playbox over at yonder [Releases](https://github.com/cjdenio/playbox/releases/latest) page. 

## Build it

Playbox was built in Javascript with Electron. Here's how to build it yourself.
1. Install Node.js and Git (Git is optional)
2. Run `node -v` and `npm -v` in your terminal to ensure that you have both Node.js and NPM installed.
    * A little note, NPM is installed with Node.js. Don't worry about installing it.
3. If you have Git installed, run `git clone https://github.com/cjdenio/playbox.git`.
Otherwise, just download the repository.
4. In your terminal, `cd` to the Playbox directory (`Playbox-master` if you downloaded it from GitHub)
5. Run `npm install` to install Electron and other required goodies
6. Finally, run `npm start` to run Playbox.

## Package it

1. To create an installer, first install `electron-builder` with `npm install electron-builder -g`. The `-g` is necessary.
2. `cd` into the Playbox directory.
3. Run the `build` command in your terminal with either `-w` `-m` or `-l` to build for Windows, MacOS, or Linux. Example: `build -w` to build for Windows.
4. Your installer has now been created in the `dist/` directory.
