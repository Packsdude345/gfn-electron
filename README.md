[![Donate](https://img.shields.io/badge/-%E2%99%A5%20Donate-%23ff69b4)](https://hmlendea.go.ro/fund.html) [![Build Status](https://github.com/hmlendea/gfn-electron/actions/workflows/node.js.yml/badge.svg)](https://github.com/hmlendea/gfn-electron/actions/workflows/node.js.yml) [![Latest GitHub release](https://img.shields.io/github/v/release/hmlendea/gfn-electron)](https://github.com/hmlendea/gfn-electron/releases/latest)

# About

GeForce NOW application written in Electron, wrapping around the GFN web browser implementation.

# Installation

[![Get it from the AUR](https://raw.githubusercontent.com/hmlendea/readme-assets/master/badges/stores/aur.png)](https://aur.archlinux.org/packages/geforcenow-electron/) [![Get it from FlatHub](https://raw.githubusercontent.com/hmlendea/readme-assets/master/badges/stores/flathub.png)](https://flathub.org/apps/details/io.github.hmlendea.geforcenow-electron) [![Get it from the Snap Store](https://raw.githubusercontent.com/snapcore/snap-store-badges/master/EN/%5BEN%5D-snap-store-white.png)](https://snapcraft.io/geforcenow-electron)

## Manual Installation

 - Go to the [latest release](https://github.com/hmlendea/gfn-electron/releases/latest).
 - Download the specific file that best fits your disto.

# Usage

If you've installed it through your package manager, then it should already contain a launcher for it. Otherwise, run the `geforcenow` binary.

## Keyboard shortcuts

 - **Super + F**: Toggles the fullscreen mode
 - **Super + M**: Toggles the microphone

# Building from source

## Requirements

You will need to install [npm](https://www.npmjs.com/), the Node.js package manager. On most distributions, the package is simply called `npm`.

## Cloning the source code

Once you have npm, clone the wrapper to a convenient location:

```bash
git clone https://github.com/hmlendea/gfn-electron.git
```

## Building

```bash
npm install
npm start
```

On subsequent runs, `npm start` will be all that's required.

## Updating the source code

Simply pull the latest version of master and install any changed dependencies:

```bash
git checkout master
git pull
npm install
```

# Links
 - [GeForce NOW](https://nvidia.com/en-eu/geforce-now)
 - [FlatHub release](https://flathub.org/apps/details/io.github.hmlendea.geforcenow-electron)
 - [FlatHub repository](https://github.com/flathub/io.github.hmlendea.geforcenow-electron)
