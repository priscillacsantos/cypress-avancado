# Automated Testing with Cypress - Advanced

Sample project.


## Pre-requirements

It is required to have Node.js and npm installed to run this project.

I used versions  `v16.13.2` and `8.19.4` of Node.js and npm, respectively. I suggest you use the same or later versions.

For git, I'm using version: `2.45.1`.



## Installation

Run `npm install` (or npm i for the short version) to install the dev dependencies.
The project's dependencies are already in package.json, so when executing the `npm install` command, it will download cypress, cypress-localstorage-commands, faker, and standardjs. All of them were used in this project.

  >cypress-localstorage-commands was used to access the browser's localStorage during some of the tests;

  >The faker was used in one of the tests to generate random data;

  >And standardjs was used to follow a standard coding style (such as using single quotes instead of double quotes, 2-space indentation, end of line without semicolons, etc).


## Tests

Run `npm run test` (or `npm t` for the short version) to run the test in headless mode.

Or, run `npm run cy:open` to open Cypress in interactive mode.



## Support this project
--