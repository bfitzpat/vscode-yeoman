# vscode-yeoman [![GitHub tag](https://img.shields.io/github/tag/camel-tooling/vscode-yeoman.svg?style=plastic)]() [![Build Status](https://circleci.com/gh/redhat-developer/vscode-yeoman.svg?branch=master)](https://circleci.com/gh/redhat-developer/vscode-yeoman) [![License](https://img.shields.io/badge/license-MIT-green.svg)]()

> Scaffold projects using [Yeoman](http://yeoman.io/).

This project is forked from the https://github.com/SamVerschueren/vscode-yo project upstream.

## Usage

Inside VS Code, press  `F1` or `Ctrl+Shift+P` to bring up the Command Palette, and type `Generate Yeoman` or just `Yo` and hit Enter. Other option is to execute `Generate Yeoman` from any folder context menu. You will be presented with a list of Yeoman generators that are installed and available for use. Once you select a generator, answer each of the questions it prompts for to complete the process.

![](https://github.com/bfitzpat/vscode-yo/raw/master/media/yo.gif)

### Sub-Generator

The plugin also supports sub-generators. If a plugin has multiple generators, a list with all the available
generators will pop-up. The default generator is marked by a ★.

![](https://github.com/bfitzpat/vscode-yo/raw/master/media/sub-generator.gif)

### Pre-requirements
* [Node.js](https://nodejs.org)
* [npm](https://www.npmjs.com) 
* [Yeoman](http://yeoman.io)
* A [Yeoman generator](http://yeoman.io/generators/) of choice

### The Future

There are several places we would like to improve this Yeoman extension going forward, including improving validation in the Command Palette input box, and potentially installing new Yeoman generators directly. However, we see a working extension as the first step! 

If you like this tool, be sure to let us know! We’d love to hear what features you might want to see next as we continue to expand its capabilities.

## License

MIT © [Sam Verschueren](http://github.com/SamVerschueren) for initial code at https://github.com/SamVerschueren/vscode-yo

MIT © [bfitzpat](http://github.com/bfitzpat)
