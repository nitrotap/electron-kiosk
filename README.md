# electron-kiosk

## Description

A simple electron app for linux, macos, and windows that wraps threejs.
<br />
![badmath](https://img.shields.io/github/languages/top/nitrotap/electron-kiosk)
![badmath](https://img.shields.io/github/issues/nitrotap/electron-kiosk)
![badmath](https://img.shields.io/github/forks/nitrotap/electron-kiosk)  
![badmath](https://img.shields.io/github/stars/nitrotap/electron-kiosk)

## Table of Contents

- [Installation](#Installation)
- [Usage](#Usage)
- [Questions](#Questions)
- [License](#License)

## Installation

The app uses node package manager. Install the app with `npm i`.

## Usage

After installing the app, run the following series of commands to build a local version. New models should be placed in the /public/models folder in their own folder. The scenes are in /components. To add a new scene, update the CustomScene.tsx file variable modelFile with the .gltf file. Comment out any scenes you don't want to use by removing the button and activeScene in Home.tsx.

### Commands for ionic electron

`ionic build`

`npx cap add electron`

`npx cap copy`

`npm run electron`

`npm -i --save-dev @electron-forge/cli`

`npx electron-forge import`

`npm run make`

## Questions

Please reach out to me on [GitHub](https://github.com/nitrotap) or by email at kartikinpublic@gmail.com for any additional questions.

## License

None
