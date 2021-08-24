# Wagyu Key Gen
Wagyu Key Gen is a GUI application providing functionality to the [eth2.0-deposit-cli](https://github.com/ethereum/eth2.0-deposit-cli).

## Setup
Wagyu Key Gen is a React app running in Electron.  See `src/electron/` for the simple electron app and `src/react/` for where the magic happens.

Start by cloning this repo amd entering the directory.  Then run the following:
 - `yarn install`
 - `yarn build`
   - `yarn build:watch` (will reload build on changes)
   - _In order to get them to show in the app press `ctrl+r` or `cmd+r` once the app is started._
 - `yarn start`

## Installing Yarn on Ubuntu
Run the following commands:
- 'sudo apt update'
- 'sudo apt remove cmdtest yarn'
- 'sudo apt install npm'
- 'sudo npm install -g yarn'

## Design
Current designs: https://www.figma.com/file/jcF78fVjndvM2hOPvifl0N/Wagyu-Key?node-id=1%3A4

## Support
Reach out to the EthStaker community:
 - on [discord](https://invite.gg/ethstaker)
 - on [reddit](https://www.reddit.com/r/ethstaker/)

## License
[GPL](LICENSE)
