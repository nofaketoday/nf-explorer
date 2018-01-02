# nf-explorer

This Blockchain explorer is built with NodeJS, Express and Parity without any dependency on NFC'S infrastructure.

If you would like to take a look at the demo, please inform us.

## Current Features
* Support producers, merchants (logistic, bank, custom, retailers) and end consumers
* Browse transactions and accounts
* Named accounts
* Event log browser
* Supports Transfer and Approval events
* Live Backend Node status display
* Support for all [Bootswatch](https://bootswatch.com/) skins
* Accounts enumeration
* Supports IPC and HTTP backend connections
* Responsive layout

## Getting started
Supported Ethereum backend nodes: Parity, Geth (untested)

1. Setup a nodejs & npm environment
2. Install the latest version of the Parity Ethereum client
3. Start parity using the following options: `parity --warp`
4. Clone this repository to your local machine
5. Install all dependencies: `npm install`
6. Rename `config.js.example` into `config.js` and adjust the file to your local environment & token
7. Start the explorer: `npm start`
8. Browse to `http://localhost:3000`

The data initialization may take up to 30 minutes.
