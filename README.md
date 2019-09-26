# javascript-code-protection-example
An example of JavaScript code protection.

## Introduction
This repository contains an example of JavaScript code protection using javascript-obfuscator, bytenode and node-packer.

## For Local Development
- Clone this repo and change directory to it.
- Install the dependencies using `npm install`.
- Make sure you have installed node-packer: https://github.com/pmq20/node-packer OR https://github.com/slee047/node-packer (For releases after Node.js 8.3.0)

## Command Usage
- `npm run obfuscate`: obfuscate the `index.js` to `index-obfuscated.js`
- `npm run bytenode`: compile the `index-obfuscated.js` to `index-obfuscated.jsc`
- `npm run bytenode:run`: run the `index-obfuscated.jsc`
- `npm run nodec`: package your Node.js project
- `npm run build`: package your Node.js project into an executable that is obfuscated and Compiled
