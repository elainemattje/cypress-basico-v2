# cypress-basico-v2
main

Sample project to learn about basic cypress, where we have a form and we need to test the functionalities.

## Pre-requirements
It is required to have Node.js, Cypress and VsCode and npm installed to run this project.

I used versions `v18.15.0` of Node.js, npm `v9.5.0`, cypress v9.5.0. I suggest you use the same or later versions.

## Installation
Run `npm install` (or `npm i` for the short version) to install the dev dependencies.

## Tests

You can run the tests simulating a desktop or mobile viewport.

### Desktop
Run `npm test` (or npm t for the short version) to run the test in headless mode on a desktop viewport.

Or, run `npm run cy:open` to open Cypress in interactive mode on a desktop viewport.

### Mobile
Run `npm run test:mobile` to run the test in headless mode on a mobile viewport.

Or, run `npm run cy:open:mobile` to open Cypress in interactive mode.