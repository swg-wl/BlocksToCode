## About The Project

Simple visual code generator created with Google Blockly.


### Built With

* [Angular](https://angular.io/)
* [Blockly](https://developers.google.com/blockly)
* [Electron](https://www.electronjs.org/)

## Getting Started

### Prerequisites

* Clone the repo
   ```sh
   git clone https://github.com/swg-wl/BlocksToCode.git
   ```
* Install NPM packages
   ```sh
   npm install
   ```

### Run

* Web
   ```sh
   ng serve
   ```
* Electron
   ```sh
   npm run electron
   ```

### Build electron package

* Windows
  ```sh
  npm exec electron-packager ./dist  --platform=win32`
  ```
* MacOs
  ```sh
  npm exec electron-packager ./dist  --platform=darwin`
  ```
