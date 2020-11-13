## How to use

You need of **NodeJS 12 LTS** and **NPM** installed, but you can use **Yarn** instead NPM.

On Windows, run these commands on CMD:

    git clone https://www.github.com/Maickonn/react-electron.git react-electron
    cd react-electron
    rmdir /Q /S .git
    npm install

On Linux or MacOS, run these commands on Terminal:

    git clone https://www.github.com/Maickonn/react-electron.git react-electron
    cd react-electron
    rm -r .git
    npm install

## How to run
To run on development mode, run:

    npm run electron-dev


## How to build
Windows:

    npm run electron-compile-windows

Linux:

    npm run electron-compile-linux

MacOS:

    npm run electron-compile-macos

The files will be generated on **dist** folder.

**PS: On build version, the electron.js will be obfuscated to prevent reverse engineering.**