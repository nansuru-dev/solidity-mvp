# Solidity MVP

### Dependencies

compiler:&ensp;solc<br>
testing framewark:&ensp;mocha<br>
local-provider:&ensp;ganache-cli<br>
main(or test)-provider:&ensp;@truffle/hdwallet-provider<br>
Web3 instance:&ensp;web3<br>

### Development Flow

1. write code
2. compile
3. deploy to local test network and test
4. deploy to mainnet(or testnet)

### Edit package.json For Test Command

```
"scripts": {
    "test": "mocha"
},
```
