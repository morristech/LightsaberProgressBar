<h1 align="center">
  <img src="https://raw.githubusercontent.com/brkckr/LightsaberProgressBar/master/art/logo.png" alt="LightsaberProgressBar" width="200">
  <br>
  LightsaberProgressBar
  <br>
</h1>

<h4 align="center">A harmless progress bar that looks like a lightsaber. :rocket: :star: .</h4>

<p align="center">
  <a href="#summary">Summary</a> •
  <a href="#how-to-use">How To Use?</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://raw.githubusercontent.com/amitmerchant1990/electron-markdownify/master/img/markdownify.gif)

## Summary

* LivePreview - Make changes, See changes
  - Instantly see what your Markdown documents look like in HTML as you create them.
* Sync Scrolling
  - While you type, LivePreview will automatically scroll to the current location you're editing.
* GitHub Flavored Markdown  
* Syntax highlighting
* [KaTeX](https://khan.github.io/KaTeX/) Support
* Dark/Light mode
* Toolbar for basic Markdown formatting
* Supports multiple cursors
* Save the Markdown preview as PDF
* Emoji support in preview :tada:
* App will keep alive in tray for quick usage
* Full screen mode
  - Write distraction free.
* Cross platform
  - Windows, Mac and Linux ready.

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/amitmerchant1990/electron-markdownify

# Go into the repository
$ cd electron-markdownify

# Install dependencies
$ npm install

# Run the app
$ npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## 🤖 Interactive vs. non-interactive mode

By default, release-it is interactive and allows you to confirm each task before execution:

<img src="./assets/release-it.png?raw=true" height="148">

On a Continuous Integration (CI) environment, or by using the `-n` option, this is fully automated. No prompts are shown and the configured tasks will be executed. This is demonstrated in the first animation above. An overview of the default tasks:

Task | Option | Default | Prompt | Default
:--|:--|:-:|:--|:-:
Ready (confirm version) | N/A | N/A | - | `Y`
Show staged files | N/A | N/A | `prompt.src.status` | `N`
Git commit | `src.commit` | `true` | `prompt.src.commit` | `Y`
Git push | `src.push` | `true` | `prompt.src.push` | `Y`
Git tag | `src.tag` | `true` | `prompt.src.tag` | `Y`
GitHub release | `github.release` | `false` | `prompt.src.release` | `Y`
npm publish | `npm.publish` | `true` | `prompt.src.publish` | `Y`

The left columns are default options in non-interactive (or CI) mode.

The `prompt.*` options on the right in the table are used for the default answers in interactive mode. You can still change the answer to either `Y` or `N` as the questions show up (or cancel the process with `Ctrl-c`).

Also, if e.g. `npm.publish` is `false`, the related prompt (`prompt.src.publish`) will not be shown (regardless of its default answer).

## Credits

This software uses code from several open source packages.

- [Electron](http://electron.atom.io/)
- [Node.js](https://nodejs.org/)
- [Marked - a markdown parser](https://github.com/chjj/marked)
- [showdown](http://showdownjs.github.io/showdown/)
- [CodeMirror](http://codemirror.net/)
- Emojis are taken from [here](https://github.com/arvida/emoji-cheat-sheet.com)
- [highlight.js](https://highlightjs.org/)

## License

MIT
