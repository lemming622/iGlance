# iGlance &ensp;&ensp;[![Build Status](https://travis-ci.org/iglance/iGlance.svg?branch=master)](https://travis-ci.org/iglance/iGlance) [![Github All Releases](https://img.shields.io/github/downloads/iglance/iGlance/latest/total.svg?colorB=orange)](https://github.com/iglance/iGlance/releases)
> macOS System Monitor for the Status Bar

## Introduction

iGlance is a small System Monitor that displays current stats about your Mac on the status bar. It is built to be highly customizable so that everyone can adjust it to his/her needs. A full list of all the features is below. If you encounter any bugs or have suggestions for new features, feel free to write them down in the Issues tab.

<img src="https://raw.githubusercontent.com/iglance/iGlance/master/gifs/iGlance1.gif" title="Status Bar" alt="Status Bar">
<img src="https://raw.githubusercontent.com/iglance/iGlance/master/gifs/iGlance3.gif" title="Status Bar Graphs" alt="Status Bar with graphs">

<img src="https://raw.githubusercontent.com/iglance/iGlance/master/gifs/iGlance2.gif" title="Status Bar" alt="Status Bar">

## Features

-   CPU Utilization
-   CPU Temperature
-   Memory Usage
-   Network Usage
-   Fan Speed
-   Low/High Battery Notification
-   Adjusts to Light & Dark mode

## Installation

There are two possible ways to install iGlance: 

1. Download the iGlance.dmg from https://github.com/iglance/iGlance/releases and manually move the app into the applications folder.
2. Install iGlance using [brew](https://brew.sh):

    `brew cask install iglance`
    
<b>INFO:</b> If you get a warning that iGlance can't be opened due to an unidentified developer you have to make sure that under "System Preferences" > "Security & Privacy" > "General" it is allowed to open apps from the "Mac App Store and identified developers". Then try to open iGlance and under "System Preferences" > "Security & Privacy" > "General" click on "Open Anyway". 

## Contribute

There are two ways you can contribute to this project:

1. You can star this repository and tell all your friends about our cool app ;)
2. You can work on one of the open issues. Please read our [Contribution Guide](https://github.com/iglance/iGlance/blob/master/.github/CONTRIBUTING.md) and our [Code of Conduct](https://github.com/iglance/iGlance/blob/master/.github/CODE_OF_CONDUCT.md) before you start.

## Credits
- <a href="https://github.com/beltex">beltex</a> - for providing the SMCKit and SystemKit Library
- <a href="https://github.com/m-oscartong">m-oscartong</a> and <a href="https://github.com/sindresorhus">sindresorhus</a> for providing the <a href="https://github.com/sindresorhus/create-dmg">create-dmg</a> script.
- And of course all the other <a href="https://github.com/iglance/iGlance/graphs/contributors">contributors</a>.

## License

This software is published under the <b>MIT License</b>.
