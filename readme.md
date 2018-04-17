# Basic SCSS Compiler

Listed below are instructions for compiling *```.scss```* files into *```.css```* files. In this example, we will compile the *```bootstrap.scss```* file to the *```bootstrap.css```* file. The newly compiled CSS file will only include the 'form' styling specified in the *```bootstrap.scss```* file (ex: *```@import "forms"```*)

## Libraries

 - Node.js
 - node-sass

## Installation Instructions

 - Download & install [Node.js](https://nodejs.org/en/download/)
 - Install node-sass via Command Line: *```npm install -g node-sass```*

## Compiler Instructions

 - How to Start a SCSS File Watcher:
   - Open command line
   - Run: *```npm run scss```*

 - How to Manually Compile SCSS to CSS:
   - Open command line
   - Run: *```node-sass bootstrap.scss bootstrap.css```*

 - How to Quickly Watch SCSS folder:
   - Open File Explorer
   - Open the *```"watch.bat"```* file inside the root folder

 - How to Quickly Compile SCSS to CSS folder:
   - Open File Explorer
   - Open the *```"compile.bat"```* file inside the root folder
