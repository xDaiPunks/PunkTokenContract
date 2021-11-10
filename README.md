# Punk Token
The Punk token ($PUNK) is the token of the xDaiPunks community. $PUNK is an ERC20 token that lives on the Mainnet of Ethereum, bridged to xDai.

The token is will be used as the governance and utility token for the upcoming NFT marketplace "NiftyFair".

The total supply of the token is 200.000.000
 - 50.000.000 will be transferred to the IBCO contract
 - 100.000.000 will be transferred to the vesting contract 

## Truffle
The token has been created using Truffle and OpenZeppelin 

### Deploying the token on a local environment
Install truffle and ganache-cli globally:
```sh
npm i truffle -g && npm i ganache-cli -g
```

Install dependencies

```sh
npm i 
```

Run truffle commands for example

```sh
ganache-cli

truffle build

truffle deploy
```

## Remix
To interact with this contract using Remix IDE (https://remix.ethereum.org/) using your local file system, you can install the remixd package.

```sh
npm install -g @remix-project/remixd
```

After install you can start remixd by issuing the followinng command:

```sh
remixd -s ~/YOUR-CONTRACT-DIRECTORY --remix-ide https://remix.ethereum.org/

```
Then in the Remix IDE choose 'localhost' as workspace and connect. You can also use your local ganache instance with Remix IDE. To do so, select 'Web3 Provider' for the environment. Make sure to have ganache-cli running 





