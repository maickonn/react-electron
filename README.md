## How to use

You need of **NodeJS 12 LTS** and **Yarn** installed, but you can use **NPM** instead Yarn.

On Windows, run these commands on CMD:

    git clone https://www.github.com/Maickonn/react-electron.git react-electron
    cd react-electron
    rmdir /Q /S .git
    yarn

On Linux or MacOS, run these commands on Terminal:

    git clone https://www.github.com/Maickonn/react-electron.git react-electron
    cd react-electron
    rm -r .git
    yarn

## How to run
To run on development mode, run:

    yarn electron-dev


## How to build
Windows:

    yarn electron-compile-windows

Linux:

    yarn electron-compile-linux

MacOS:

    yarn electron-compile-macos

The files will be generated on **dist** folder.

**PS: On build version, the electron.js will be obfuscated to prevent reverse engineering.**