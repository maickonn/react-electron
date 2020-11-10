## How to use
Clone this repo with:

    git clone https://www.github.com/Maickonn/react-electron.git react-electron
Go to react-electron directory:

    cd react-electron
Run:

    yarn
or

    npm install

## How to run
To run on development mode, run:

    yarn electron-dev

or

    npm electron-dev

## How to build
Windows:

    yarn electron-compile-windows

Linux:

    yarn electron-compile-linux

MacOS:

    yarn electron-compile-macos

The files will be generated on **dist** folder.

**PS: On build version, the electron.js will be obfuscated to prevent reverse engineering.**