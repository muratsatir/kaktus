## kaktüs

A new minimalistic web browser. It's currently usable, [and there is a lot to do](#roadmap).

Screenshots: [Simple View](https://cldup.com/6jOWAjYdpo.png) | [Tabbing](https://cldup.com/wDadS2XGrb.gif) | [Private Mode for Sites](https://cldup.com/qsYAu0F-ja.png)

Index
* [Download](#download)
* [Keyboard Shortcuts](#keyboard-shortcuts)
* [Roadmap](#roadmap)
* [Call for Designers](#call-for-designers)
* [Development](#development)

![](https://cldup.com/6jOWAjYdpo.png)

## Download

* [OSX](https://www.dropbox.com/s/tpiffhx45v856sl/Kakt%C3%BCs-darwin-x64.zip?dl=0)

#### Keyboard Shortcuts:
* Command+T: New Tab
* Control+Space: Open Menu
* Command+O: Focus Mode
* Shift+Command+F: Full Screen
* Shift+Command+N: Open New Window with Privacy Mode
* Command+F: Find in the page
* Command+W: Close Tab

## How It Works

* [Tabbing]()

## Roadmap

Features planned:
* Improved privacy mode that can be enabled for domain names (e.g Google)
* Auto-search: automatically bringing results from search engines -in privacy mode- to the menu, so user doesn't have to open them.
* Split browsing and follow-mode

Known issues:
* Multiple windows share same tabbing session.
* There is bugs with tabbing behavior.
* Back/forward buttons should update immediately after url changes
* The tabbing menu doesn't make it clear between history and tab items

Missing:
* Context menu
* Download manager
* PDF Preview

Improvements:
* Making search better (it currently can only match word-by-word)
* Showing screenshot on the tabbing menu (saving it to DB may be?)
* Saving and recovering screen size & positions

Windows & Linux:
* They don't look as nice as OSX builds do. Visual improvements are needed for both.

## Call For Designers 

Kaktüs needs a lot of help on design. Here is what's missing;

* **Logo:** Current logo is something I had to pick up from Dribble (with the permission of the designer) and it's temporary.
* **Icons:** Kaktüs needs an icon set to interact with user better/
* **Ideas:** Kaktüs needs your ideas on how to improve tabbing and search.

## Development

#### Building From Source

Install all dependencies:

```bash
npm install
```

And get the build out for your target platform. Available platforms are:

* osx
* win
* linux

So, I usually run;

```
make osx
```

Command to get my build for OSX.

#### Making Changes
Kaktüs is built with [choo](https://github.com/yoshuawuyts/choo) and [electron](https://github.com/electron/electron). Here is the commands I run to start the development:

```bash
$ make watch-css
$ make dev
$ make start
```

## Logo

I'm temporarily using [a cactus image I found on Dribble](https://dribbble.com/shots/1842263-Cactus) as a logo.
